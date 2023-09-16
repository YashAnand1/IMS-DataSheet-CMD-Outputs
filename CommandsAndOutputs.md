# Outputs For Resource Related Commands

| S. No. | Command Combination               | Included Headers                                      | Sheet_Name|
|-------|-----------------------------------|---------------------------------------------------------|
| 1| `itldims get configmap`              | Hostname, App_Name, Public_IP, LB_IP | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes`       | Hostname, App_Name, Webapp_Path,	Environment	config_Map | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes -o wide`       | Hostname	App_Name	Tomcat_Name	Tomcat_port	Public_URL, Database, API | Data_NIC_AbhaProd_app |
| 3| `itldims get apps`         | Hostname, App_Name, Database, API, Environment | Data_NIC_AbhaProd_app |
| 4| `itldims get pv`         | Hostname, App_Name, IP, Internal_Partition, PV  | Data_NIC_AbhaProd_storage |
| 5| `itldims get storage`         | Displays values of a specific server Type  | User can find values of a specific server Type |
| 6| `itldims get ingress`   | Displays values of a specific Attribute   | User can find all the RAMs of all servers |
| 7| `itldims get services` | Displays all value of attribute from specific server Type/IP | User can find if any attribute is 'None' on '10.249.221.22' |
| 8| `itldims get infra` | Displays all Server IPs containing a specific value  | User can find if any attribute is 'None' on '10.249.221.22' |
| 9| `itldims get infra -o wide` | Displays value of a key, when the key is mentioned | User can find the value directly from the entire key |
