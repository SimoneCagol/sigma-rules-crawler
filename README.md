# Sigma Rules Crawler
Within this project you will find the complete list of detection rules present within the Sigma Rule (https://github.com/SigmaHQ/sigma) project. The list is automatically updated several times a day.
The list can be useful for those who need to search for and activate the detection rules based on the technologies present within their infrastructure.

The project also performs a translation of the detection rules from the Sigma format to the Elastic Rule format. The rule thus translated, in ndjson format, can be imported directly from the Kibana GUI (Secuirty - Rules - Import rules).


###### The last rule was uploaded / updated on:
2023/02/13
###### The total of the rules present is:
2671
###### Below we show the number of rules present divided by categories:
- 1 application/django
- 1 application/python
- 17 application/rpc_firewall
- 1 application/ruby
- 1 application/spring
- 1 application/sql
- 7 category/antivirus
- 1 category/database
- 37 cloud/aws
- 101 cloud/azure
- 14 cloud/gcp
- 7 cloud/github
- 6 cloud/gworkspace
- 15 cloud/m365
- 13 cloud/okta
- 2 cloud/onelogin
- 3 compliance
- 52 linux/auditd
- 18 linux/builtin
- 2 linux/builtin/auth
- 1 linux/builtin/clamav
- 1 linux/builtin/cron
- 1 linux/builtin/guacamole
- 2 linux/builtin/sshd
- 1 linux/builtin/sudo
- 2 linux/builtin/syslog
- 1 linux/builtin/vsftpd
- 5 linux/file_event
- 3 linux/network_connection
- 67 linux/process_creation
- 2 macos/file_event
- 37 macos/process_creation
- 12 network/cisco/aaa
- 1 network/cisco/bgp
- 1 network/cisco/ldp
- 12 network/dns
- 6 network/firewall
- 1 network/huawei/bgp
- 1 network/juniper/bgp
- 22 network/zeek
- 2 web/product/apache
- 1 web/product/modsecurity
- 37 web/proxy_generic
- 65 web/webserver_generic
- 1 windows/builtin
- 20 windows/builtin/application
- 1 windows/builtin/applocker
- 1 windows/builtin/appmodel_runtime
- 7 windows/builtin/appxdeployment_server
- 1 windows/builtin/appxpackaging_om
- 7 windows/builtin/bits_client
- 3 windows/builtin/code_integrity
- 1 windows/builtin/diagnosis/scripted
- 5 windows/builtin/dns_client
- 1 windows/builtin/dns_server
- 1 windows/builtin/dns_server_analytic
- 1 windows/builtin/driverframeworks
- 7 windows/builtin/firewall_as
- 1 windows/builtin/ldap
- 1 windows/builtin/lsa_server
- 8 windows/builtin/msexchange
- 3 windows/builtin/ntlm
- 1 windows/builtin/openssh
- 2 windows/builtin/printservice
- 152 windows/builtin/security
- 2 windows/builtin/security_mitigations
- 1 windows/builtin/servicebus
- 1 windows/builtin/shell_core
- 2 windows/builtin/smbclient
- 64 windows/builtin/system
- 4 windows/builtin/taskscheduler
- 1 windows/builtin/terminalservices
- 11 windows/builtin/windefend
- 1 windows/builtin/wmi
- 13 windows/create_remote_thread
- 7 windows/create_stream_hash
- 13 windows/dns_query
- 15 windows/driver_load
- 4 windows/file/file_access
- 2 windows/file/file_change
- 8 windows/file/file_delete
- 132 windows/file/file_event
- 2 windows/file/file_rename
- 62 windows/image_load
- 36 windows/network_connection
- 17 windows/pipe_created
- 15 windows/powershell/powershell_classic
- 32 windows/powershell/powershell_module
- 160 windows/powershell/powershell_script
- 27 windows/process_access
- 1019 windows/process_creation
- 1 windows/raw_access_thread
- 9 windows/registry/registry_add
- 6 windows/registry/registry_delete
- 36 windows/registry/registry_event
- 151 windows/registry/registry_set
- 5 windows/sysmon
- 3 windows/wmi_event
