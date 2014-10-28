MOOCczar
========

A modular system for managing MOOC research data.  These systems are in early testing stages, and contributions and feedback is welcome.

Data Analytics Platform
--------

The Data Analytics Platform is a series of services which are used together to provide various access to the <a href="https://edx-wiki.atlassian.net/wiki/display/OA/Research+Data+Package+Details" target="_blank">edX Research Data Package</a>, and can be used as an API gateway to other data sources.  The platform is segmented into three services, each of which work with eachother.  Each service is extensible and can be modified independantly of the other services.  Contributions are welcome to all of the services.  They are best setup in order:

1. Optimus Ingestor - https://github.com/UQ-UQx/optimus_ingestor (ingests raw data into databases)
2. UQx API - https://github.com/UQ-UQx/uqx_api (provides REST endpoints to ingested data)
3. Dashboard_JS - https://github.com/UQ-UQx/dashboard_js (visualises datasets)

Overview:
![Data Analytics Platform Overview](/README_data_analytics_platform_overview.png?raw=true "Data Analytics Platform Overview")

See each of the repositories README files for more indepth installation instructions.

Additionally, there is an <a href="https://github.com/UQ-UQx/uqx_ansible">ansible scripts</a> repository which can assist in installing and configuring all of the services.

Course Report Generator
--------

The Course Report Generator is a set of tools used internally by UQx to automate the process of creating publications for disseminating knowledge about the courses.  The generator leverages data from a number of sources, including the Data Analytics Platform.  The generator involves a number of different repositories:

1. Course Information - Coming Soon
2. Course Reports - Coming Soon
