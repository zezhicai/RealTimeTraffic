function:
===============

A real time road traffic condition(congestion or not) ananlysis system with realtime mass GPS data collected from Taxis and buses based on Twitter storm stream computing framwork. 

A demo of this system, please visit : http://210.75.252.140:8080/infoL/sslk_weibo.html

the traffic condition updates every 30 seconds.


To Deploy:
====

(1) you need a powerfull storm cluster: http://storm.apache.org;

(2) you need a whole city GIS(geographic information system) road databaes or   ArcGIS .shp files;

(3) you need to download open sourced geoTools .jar file (http://www.geotools.org/) and put in  folder storm/lib.

Submit Storm topology:
====
storm jar real-time-traf-0.0.1-SNAPSHOT.jar  realTraffic.RealTimeTrafficTopology  realtimeTraffic

 
