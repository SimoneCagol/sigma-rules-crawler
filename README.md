# Sigma Rules Crawler
Within this project you will find the complete list of detection rules present within the Sigma Rule (https://github.com/SigmaHQ/sigma) project. The list is automatically updated several times a day.
The list can be useful for those who need to search for and activate the detection rules based on the technologies present within their infrastructure.

The project also performs a translation of the detection rules from the Sigma format to the Elastic Rule format. The rule thus translated, in ndjson format, can be imported directly from the Kibana GUI (Secuirty - Rules - Import rules).


###### The last rule was uploaded / updated on:
2025-04-12
###### The total of the rules present is:
2987
###### Below we show the number of rules present divided by categories:
- 1 application/django
- 5 application/jvm
- 15 application/kubernetes/audit
- 1 application/nodejs
- 18 application/opencanary
- 1 application/python
- 17 application/rpc_firewall
- 1 application/ruby
- 2 application/spring
- 1 application/sql
- 1 application/velocity
- 6 category/antivirus
- 1 category/database
- 46 cloud/aws/cloudtrail
- 43 cloud/azure/activity_logs
- 38 cloud/azure/audit_logs
- 19 cloud/azure/identity_protection
- 7 cloud/azure/privileged_identity_management
- 24 cloud/azure/signin_logs
- 14 cloud/bitbucket/audit
- 1 cloud/cisco/duo
- 16 cloud/gcp/audit
- 7 cloud/gcp/gworkspace
- 13 cloud/github
- 3 cloud/m365/audit
- 1 cloud/m365/exchange
- 1 cloud/m365/threat_detection
- 13 cloud/m365/threat_management
- 21 cloud/okta
- 2 cloud/onelogin
- 3 compliance
- 48 linux/auditd
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
- 5 linux/network_connection
- 113 linux/process_creation
- 2 macos/file_event
- 65 macos/process_creation
- 12 network/cisco/aaa
- 1 network/cisco/bgp
- 1 network/cisco/ldp
- 7 network/dns
- 1 network/firewall
- 1 network/huawei/bgp
- 1 network/juniper/bgp
- 22 network/zeek
- 2 web/product/apache
- 1 web/product/nginx
- 28 web/proxy_generic
- 13 web/webserver_generic
- 1 windows/builtin
- 2 windows/builtin/application/application_error
- 2 windows/builtin/application/esent
- 1 windows/builtin/application/microsoft-windows_audit_cve
- 1 windows/builtin/application/microsoft_windows_backup
- 1 windows/builtin/application/microsoft_windows_software_restriction_policies
- 4 windows/builtin/application/msiinstaller
- 7 windows/builtin/application/mssqlserver
- 1 windows/builtin/application/Other
- 2 windows/builtin/application/screenconnect
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
- 6 windows/builtin/dns_client
- 2 windows/builtin/dns_server
- 1 windows/builtin/driverframeworks
- 8 windows/builtin/firewall_as
- 4 windows/builtin/iis-configuration
- 1 windows/builtin/ldap
- 1 windows/builtin/lsa_server
- 7 windows/builtin/msexchange
- 3 windows/builtin/ntlm
- 1 windows/builtin/openssh
- 123 windows/builtin/security
- 17 windows/builtin/security/account_management
- 2 windows/builtin/security_mitigations
- 1 windows/builtin/security/object_access
- 1 windows/builtin/servicebus
- 1 windows/builtin/shell_core
- 1 windows/builtin/smbclient/security
- 1 windows/builtin/system/application_popup
- 1 windows/builtin/system/lsasrv
- 1 windows/builtin/system/microsoft_windows_certification_authority
- 2 windows/builtin/system/microsoft_windows_dhcp_server
- 1 windows/builtin/system/microsoft_windows_directory_services_sam
- 1 windows/builtin/system/microsoft_windows_distributed_com
- 2 windows/builtin/system/microsoft_windows_eventlog
- 3 windows/builtin/system/microsoft_windows_kerberos_key_distribution_center
- 1 windows/builtin/system/microsoft_windows_kernel_general
- 1 windows/builtin/system/microsoft_windows_ntfs
- 1 windows/builtin/system/microsoft_windows_user_profiles_service
- 1 windows/builtin/system/microsoft_windows_windows_update_client
- 2 windows/builtin/system/netlogon
- 1 windows/builtin/system/ntfs
- 45 windows/builtin/system/service_control_manager
- 1 windows/builtin/system/termdd
- 3 windows/builtin/taskscheduler
- 1 windows/builtin/terminalservices
- 16 windows/builtin/windefend
- 1 windows/builtin/wmi
- 12 windows/create_remote_thread
- 9 windows/create_stream_hash
- 18 windows/dns_query
- 10 windows/driver_load
- 6 windows/file/file_access
- 2 windows/file/file_change
- 13 windows/file/file_delete
- 156 windows/file/file_event
- 1 windows/file/file_executable_detected
- 1 windows/file/file_rename
- 95 windows/image_load
- 50 windows/network_connection
- 17 windows/pipe_created
- 13 windows/powershell/powershell_classic
- 33 windows/powershell/powershell_module
- 162 windows/powershell/powershell_script
- 21 windows/process_access
- 1103 windows/process_creation
- 1 windows/process_tampering
- 1 windows/raw_access_thread
- 8 windows/registry/registry_add
- 7 windows/registry/registry_delete
- 33 windows/registry/registry_event
- 188 windows/registry/registry_set
- 6 windows/sysmon
- 3 windows/wmi_event
