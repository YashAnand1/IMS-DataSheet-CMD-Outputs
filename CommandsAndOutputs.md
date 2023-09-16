# Outputs For Resource Related Commands

| S. No. | Command Combination               | Included Headers                                      | Sheet_Name|
|-------|-----------------------------------|---------------------------------------------------------|---|
| 1| `itldims get configmap`              | Hostname, App_Name, Public_IP, LB_IP | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes`       | Hostname, App_Name, Webapp_Path,	Environment	config_Map | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes -o wide`       | Hostname	App_Name	Tomcat_Name	Tomcat_port	Public_URL, Database, API | Data_NIC_AbhaProd_app |
| 3| `itldims get apps`         | Hostname, App_Name, Database, API, Environment | Data_NIC_AbhaProd_app |
| 4| `itldims get pv`         | Hostname, App_Name, IP, Internal_Partition, PV  | Data_NIC_AbhaProd_storage |
| 5| `itldims get storage`   |  | Data_NIC_AbhaProd_storage |
| 6| `itldims get storage -o wide`         |   | Data_NIC_AbhaProd_storage |
| 7| `itldims get ingress`   | | Data_NIC_AbhaProd_infra |
| 8| `itldims get services` |  | Data_NIC_AbhaProd_infra |
| 9| `itldims get infra` | |Data_NIC_AbhaProd_infra |
| 10| `itldims get infra -o wide` |  | Data_NIC_AbhaProd_infra |
