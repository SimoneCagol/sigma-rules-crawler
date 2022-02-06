# Sigma Rules Crawler
Within this project you will find the complete list of detection rules present within the Sigma Rule (https://github.com/SigmaHQ/sigma) project. The list is automatically updated several times a day.
The list can be useful for those who need to search for and activate the detection rules based on the technologies present within their infrastructure.

The project also performs a translation of the detection rules from the Sigma format to the Elastic Rule format. The rule thus translated, in ndjson format, can be imported directly from the Kibana GUI (Secuirty - Rules - Import rules).


###### The last rule was uploaded / updated on:
2022/02/06
###### The total of the rules present is:
1759
###### Below we show the number of rules present divided by categories:
- 6 application/antivirus
- 1 application/django
- 1 application/edr/windows
- 1 application/python
- 17 application/rpc_firewall
- 1 application/ruby
- 1 application/spring
- 1 application/sql
- 2 apt
- 30 cloud/aws
- 50 cloud/azure
- 14 cloud/gcp
- 6 cloud/gworkspace
- 12 cloud/m365
- 12 cloud/okta
- 2 cloud/onelogin
- 6 compliance
- 1 generic
- 47 linux/auditd
- 20 linux/builtin
- 2 linux/file_create
- 2 linux/macos/file_event
- 28 linux/macos/process_creation
- 1 linux/modsecurity
- 2 linux/network_connection
- 8 linux/other
- 25 linux/process_creation
- 16 network
- 12 network/cisco/aaa
- 21 network/zeek
- 31 proxy
- 51 web
- 1 windows/builtin
- 8 windows/builtin/application
- 1 windows/builtin/applocker
- 1 windows/builtin/code_integrity
- 2 windows/builtin/dns_server
- 1 windows/builtin/driverframeworks
- 1 windows/builtin/ldap
- 8 windows/builtin/msexchange
- 3 windows/builtin/ntlm
- 2 windows/builtin/printservice
- 136 windows/builtin/security
- 1 windows/builtin/servicebus
- 1 windows/builtin/smbclient
- 39 windows/builtin/system
- 1 windows/builtin/taskscheduler
- 8 windows/builtin/windefend
- 1 windows/builtin/wmi
- 7 windows/create_remote_thread
- 2 windows/create_stream_hash
- 10 windows/deprecated
- 8 windows/dns_query
- 6 windows/driver_load
- 5 windows/file_delete
- 71 windows/file_event
- 37 windows/image_load
- 22 windows/network_connection
- 13 windows/pipe_created
- 14 windows/powershell/powershell_classic
- 28 windows/powershell/powershell_module
- 109 windows/powershell/powershell_script
- 18 windows/process_access
- 633 windows/process_creation
- 1 windows/raw_access_thread
- 121 windows/registry_event
- 6 windows/sysmon
- 3 windows/wmi_event
