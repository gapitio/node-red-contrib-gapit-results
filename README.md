# node-red-contrib-gabit-results

The *gapit-results-to-influx-batch* 
<a href="http://nodered.org" target="_new">Node-RED</a> node transforms 
output in the *gapit_results* format, e.g. from the 
[gapit-snmp node](https://flows.nodered.org/node/@gapit/node-red-contrib-gabit-snmp), 
to the format required by the *influx batch* node (from 
`node-red-contrib-influxdb`).

This module is meant to be used as a dependency in other modules, i.e., 
it's installed automatically along with nodes it can be used with 
(like *gapit-snmp*).
