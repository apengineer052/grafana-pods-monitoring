# grafana-pods-monitoring
Grafana Dashboard to effectively monitor your Kubernetes PODS and Containers

Monitoring kubernetes deployment in production or testing environment is necessary for system engineers and performance engineers. Grafana dashboards provide meaningful insight from the metrics collected from kubernetes cluster.

## Requirements
Grafana > 6.0

* Variable Definition for Dashboard
![VariablesDef](https://user-images.githubusercontent.com/41537135/132191169-d1dfa0a1-9d39-4191-8295-2611f8ed608a.PNG)

## Features

* CPU resources for POD/Container (Requested, Limit, Usage and usage percentage)
![PODS_CPUUtil_Table](https://user-images.githubusercontent.com/41537135/132192436-5859f5b6-3597-446d-92a5-0fff8469a808.PNG)

* Memory Resources for POD/Container (Requested, Limit, Usage and usage percentage)
![Mem_Util_Table1](https://user-images.githubusercontent.com/41537135/132192476-f085ca41-78a3-4dd7-b8e2-ab8dd1a992de.PNG)

* POD CPU Utilization Graph
![CPU_Util_Graph1](https://user-images.githubusercontent.com/41537135/132192623-299139d0-03aa-400e-b632-caeac2e0396d.PNG)

* POD Memory Utilization Graph
![Mem_Util_Table1](https://user-images.githubusercontent.com/41537135/132192658-bfebcd81-a3bc-4d3f-9d28-e3bc9a3ff27f.PNG)

* POD I/O Utilization Graph
![IO_Util_Graph1](https://user-images.githubusercontent.com/41537135/132192684-75bc232b-9719-4ab3-9a5e-29f53cb3b4a7.PNG)

