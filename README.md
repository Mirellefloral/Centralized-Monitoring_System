# Centralized-Monitoring_System
Implementation of a centralized monitoring system for the dual-site national messaging infrastructure of ANTIC

ANTIC manages a distributed messaging infrastruct accross two locations: there is the site principal which is the main site containing primary mail servers, back-up servers and storage servers as well as other network devices and there is the site de secours which is a redundant site of the main sit containing redundant mail servers. These two sites are remotely monitored from the main site by the monitoring server deployed at the main site which monitor critical metrics in real time and send email alerts if a set threshold value is exceeded
