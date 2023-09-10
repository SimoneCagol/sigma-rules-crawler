# Sigma Rules Crawler
Within this project you will find the complete list of detection rules present within the Sigma Rule (https://github.com/SigmaHQ/sigma) project. The list is automatically updated several times a day.
The list can be useful for those who need to search for and activate the detection rules based on the technologies present within their infrastructure.

The project also performs a translation of the detection rules from the Sigma format to the Elastic Rule format. The rule thus translated, in ndjson format, can be imported directly from the Kibana GUI (Secuirty - Rules - Import rules).


###### The last rule was uploaded / updated on:
2023/09/09
###### The total of the rules present is:
2758
###### Below we show the number of rules present divided by categories:
- 1 application/django
- 5 application/jvm
- 1 application/nodejs
- 1 application/python
- 17 application/rpc_firewall
- 1 application/ruby
- 2 application/spring
- 1 application/sql
- 1 application/velocity
- 7 category/antivirus
- 1 category/database
- 32 cloud/aws
- 100 cloud/azure
- 15 cloud/azure/identity_protection
- 14 cloud/gcp
- 7 cloud/github
- 6 cloud/gworkspace
- 15 cloud/m365
- 15 cloud/okta
- 2 cloud/onelogin
- 3 compliance
- 49 linux/auditd
- 17 linux/builtin
- 1 linux/builtin/auth
- 1 linux/builtin/clamav
- 1 linux/builtin/cron
- 1 linux/builtin/guacamole
- 2 linux/builtin/sshd
- 1 linux/builtin/sudo
- 2 linux/builtin/syslog
- 1 linux/builtin/vsftpd
- 7 linux/file_event
- 3 linux/network_connection
- 100 linux/process_creation
- 2 macos/file_event
- 49 macos/process_creation
- 12 network/cisco/aaa
- 1 network/cisco/bgp
- 1 network/cisco/ldp
- 7 network/dns
- 2 network/firewall
- 1 network/huawei/bgp
- 1 network/juniper/bgp
- 21 network/zeek
- 2 web/product/apache
- 1 web/product/nginx
- 39 web/proxy_generic
- 12 web/webserver_generic
- 1 windows/builtin
- 2 windows/builtin/application/application_error
- 2 windows/builtin/application/esent
- 1 windows/builtin/application/microsoft-windows_audit_cve
- 1 windows/builtin/application/microsoft_windows_backup
- 1 windows/builtin/application/microsoft_windows_software_restriction_policies
- 1 windows/builtin/application/msexchange_control_panel
- 5 windows/builtin/application/msiinstaller
- 1 windows/builtin/application/msmq
- 6 windows/builtin/application/mssqlserver
- 1 windows/builtin/application/Other
- 1 windows/builtin/application/windows_error_reporting
- 1 windows/builtin/applocker
- 1 windows/builtin/appmodel_runtime
- 7 windows/builtin/appxdeployment_server
- 1 windows/builtin/appxpackaging_om
- 7 windows/builtin/bits_client
- 1 windows/builtin/capi2
- 1 windows/builtin/certificate_services_client_lifecycle_system
- 10 windows/builtin/code_integrity
- 1 windows/builtin/diagnosis/scripted
- 5 windows/builtin/dns_client
- 2 windows/builtin/dns_server
- 1 windows/builtin/dns_server_analytic
- 1 windows/builtin/driverframeworks
- 8 windows/builtin/firewall_as
- 1 windows/builtin/ldap
- 1 windows/builtin/lsa_server
- 8 windows/builtin/msexchange
- 3 windows/builtin/ntlm
- 1 windows/builtin/openssh
- 120 windows/builtin/security
- 18 windows/builtin/security/account_management
- 2 windows/builtin/security_mitigations
- 1 windows/builtin/servicebus
- 1 windows/builtin/shell_core
- 1 windows/builtin/smbclient/security
- 1 windows/builtin/system/application_popup
- 1 windows/builtin/system/lsasrv
- 2 windows/builtin/system/microsoft_windows_dhcp_server
- 1 windows/builtin/system/microsoft_windows_directory_services_sam
- 1 windows/builtin/system/microsoft_windows_distributed_com
- 2 windows/builtin/system/microsoft_windows_eventlog
- 1 windows/builtin/system/microsoft_windows_kerberos_key_distribution_center
- 2 windows/builtin/system/microsoft_windows_kernel_general
- 1 windows/builtin/system/microsoft_windows_ntfs
- 1 windows/builtin/system/microsoft_windows_user_profiles_service
- 1 windows/builtin/system/microsoft_windows_windows_update_client
- 2 windows/builtin/system/netlogon
- 1 windows/builtin/system/ntfs
- 48 windows/builtin/system/service_control_manager
- 1 windows/builtin/system/termdd
- 3 windows/builtin/taskscheduler
- 1 windows/builtin/terminalservices
- 12 windows/builtin/windefend
- 1 windows/builtin/wmi
- 12 windows/create_remote_thread
- 9 windows/create_stream_hash
- 13 windows/dns_query
- 16 windows/driver_load
- 4 windows/file/file_access
- 2 windows/file/file_change
- 12 windows/file/file_delete
- 149 windows/file/file_event
- 2 windows/file/file_rename
- 89 windows/image_load
- 43 windows/network_connection
- 17 windows/pipe_created
- 15 windows/powershell/powershell_classic
- 32 windows/powershell/powershell_module
- 163 windows/powershell/powershell_script
- 27 windows/process_access
- 1026 windows/process_creation
- 1 windows/raw_access_thread
- 9 windows/registry/registry_add
- 6 windows/registry/registry_delete
- 36 windows/registry/registry_event
- 171 windows/registry/registry_set
- 7 windows/sysmon
- 3 windows/wmi_event
