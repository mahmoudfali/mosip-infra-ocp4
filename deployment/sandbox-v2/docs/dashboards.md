# Dashboards Guide

This document contains miscellaneous tips to use various dashboards that are made available as part of the default sandbox installation.

## Kibana
As part of sandbox installation a default dashboard is installed to view logs of all MOSIP services.  To view the dashboard
1. Go to Kibana Home
1. On the drop down on the top left select Kibana->Dashboard
1. In the list of dashboards search for "MOSIP Service Logs" 
1. Select the dashboard.

## Kubernetes dashboard
* Dashboard links:
    * MZ: `https://<sandbox domain name>/dashboard-mz`
    * DMZ: `https://<sandbox domain name>/dashboard-dmz`
* The tokens for above dashboards are available on the console machine at `/home/mosipuser/mosip-infra-ocp4/deployment/sandbox-v2/tmp`

## Grafana
* Link:
   * `https://<sandbox domain name>/grafana`

* Recommended charts:
  * 11074
