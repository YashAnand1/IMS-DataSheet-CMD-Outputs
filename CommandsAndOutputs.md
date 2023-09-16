# Outputs For Resource Related Commands

| S. No. | Command Combination               | Included Headers                                      | Sheet_Name|
|-------|-----------------------------------|---------------------------------------------------------|---|
| 1| `itldims get configmap`              | Hostname, App_Name, Public_IP, LB_IP | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes`       | Hostname, App_Name, Webapp_Path,	Environment	config_Map | Data_NIC_AbhaProd_app |
| 2| `itldims get nodes -o wide`       | Hostname	App_Name	Tomcat_Name	Tomcat_port	Public_URL, Database, API | Data_NIC_AbhaProd_app |
| 3| `itldims get apps`         | Hostname, App_Name, Database, API, Environment | Data_NIC_AbhaProd_app |
| 4| `itldims get pv`         | Hostname, App_Name, IP, Internal_Partition, PV  | Data_NIC_AbhaProd_storage |
| 5| `itldims get storage`   | Hostname, IP, Internal_Disk, Internal_Partition, VG, PV | Data_NIC_AbhaProd_storage |
| 6| `itldims get storage -o wide`         | Hostname, IP, Internal_Disk, External_Disk, Internal_Partition, External_Partition, VG, PV, NFS, lvm | Data_NIC_AbhaProd_storage |
| 7| `itldims get ingress`   | | Data_NIC_AbhaProd_infra |
| 8| `itldims get services` | Hostname, IP, Listening_Port, Machine_Type, Running_Services | Data_NIC_AbhaProd_infra |
| 9| `itldims get infra` | Hostname, IP, CPU, RAM, Type, OS |Data_NIC_AbhaProd_infra |
| 10| `itldims get infra -o wide` | Hostname, IP, Listening_Port, CPU, RAM, Type, Netmask, OS, Gateway, Running_Services | Data_NIC_AbhaProd_infra |


| S. No. | Command Combination       | output|        | Remarks                                      
| 1| `itldims get ns`              | FINO, NIC  |to include projects  |                              
| 1| `itldims get pods`              | App instances | |  

| PVC            | Individual Application Shared Storage          | RWO/RWX - SAN Volume/NAS Volumes            |
| Ingress        | Incoming LBs - HAProxy                           |                    -                       |
