WIP : CAPI
need to enable custom resource definitions on kube-state-metrics to collect
capi metrics need kube-state-metrics > v2.5.0

set of alarms to use with weave gitops. 
flux, weave gitops and capi





```
# HELP capi_machinedeployment_status_conditions
# TYPE capi_machinedeployment_status_conditions gauge
capi_machinedeployment_status_conditions{type="Available"} 1
capi_machinedeployment_status_conditions{type="Ready"} 1
# HELP capi_machinedeployment_spec_replicas
# TYPE capi_machinedeployment_spec_replicas gauge
capi_machinedeployment_spec_replicas 3
# HELP capi_machinedeployment_info
# TYPE capi_machinedeployment_info gauge
capi_machinedeployment_info{version="v1.23.3"} 1
# HELP capi_machinedeployment_phase
# TYPE capi_machinedeployment_phase gauge
capi_machinedeployment_phase{phase="Running"} 1
capi_machinedeployment_phase{phase="ScalingUp"} 0
```