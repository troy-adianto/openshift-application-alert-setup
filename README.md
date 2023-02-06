# OPENSHIFT APPLICATION ALERT SETUP
Tested in OpenShift Container Platform 4.11

# Cluster Task (by Cluster Admin)
* Enable User Workload Monitoring & Alert Manager
  
   [cluster-monitoring-config.yaml](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/admin/cluster-monitoring-config.yaml).
  
* Configure Global Email Server/Slack
  
  [Configure alert receivers](https://docs.openshift.com/container-platform/4.11/monitoring/managing-alerts.html#configuring-alert-receivers_managing-alerts)

* Create Role Binding to Developer in the namespace

   [developer-rolebinding.yaml](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/admin/developer-rolebinding.yaml)
   
   
# Developer Task (by Developer Admin)

[Demo Video](https://www.youtube.com/watch?v=xquU48TgS6E)

* Create Application Service Monitor
   
   [service-monitor-sample.yaml](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/dev/service-monitor-sample.yaml)

* Create Application Alert Rule
   
   [prometheus-rule-sample](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/dev/prometheus-rule-sample.yaml)

* Create Alert Routing
  
   [alert-manager-routing-sample.yaml (email)](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/dev/alert-manager-routing-sample.yaml)

  [alert-manager-routing-sample-slack-yaml (slack)](https://github.com/troy-adianto/openshift-application-alert-setup/blob/main/dev/alert-manager-routing-sample-slack.yaml)





