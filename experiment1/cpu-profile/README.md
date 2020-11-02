## CPU Profiling Comparison (druid-lab vs druid-prodeks)
We look at the CPU profiles of tasks that ingest different datasources. We only look at
`telemetry_metrics` and `telemetry_metrics_storage` which has significant traffic.

### telemetry_metrics
The two samples we take are from

    druid-prodeks  
    middle-manager-35.middle-manager.druid-prodeks.svc.cluster.local:8100  
    2020-11-02T20:15:05.415Z
    
    druid-lab  
    middle-manager-7.middle-manager.druid-lab.svc.cluster.local:8103  
    2020-11-02T20:12:03.095Z


### telemetry_metrics_storage
The two samples we take are from

    druid-prodeks
    middle-manager-50.middle-manager.druid-prodeks.svc.cluster.local:8100
    2020-11-02T21:15:04.697Z

    druid-lab
    middle-manager-1.middle-manager.druid-lab.svc.cluster.local:8100
    2020-11-02T20:12:03.095Z
