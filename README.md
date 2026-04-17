# Automated Inspection Management Platform

## 📖 Introduction

This platform is an **automated inspection management system** designed for financial institutions and complex IT environments. It replaces traditional manual inspection methods with script-based, orchestrated automated tasks. It continuously monitors servers, databases, middleware, network devices, and other resources, automatically generates inspection reports, and sends upgrade notifications. This significantly improves operational efficiency, reduces missed/false detections, and enhances system security and stability.

## 🎯 Background & Pain Points

- **Low efficiency**: Repetitive tasks consume significant manpower, prone to omissions and errors.
- **High security risks**: Financial systems are prime targets; manual inspections often fail to detect configuration changes, certificate expirations, or port anomalies in time.
- **Insufficient data analysis**: Traditional methods lack the ability to mine inspection data and identify potential failures early.

This platform uses automation to achieve continuous monitoring, rapid problem identification, and timely responses, maximizing system availability.

## ✨ Core Features

| Module | Description |
|--------|-------------|
| **Resource Management** | Batch import / manually add application systems, middleware, network devices, etc. |
| **Job Management** | Provide local and remote inspection scripts, support syntax check and sensitive keyword check |
| **Orchestration Management** | Visually orchestrate inspection processes for the same resource by script order |
| **Inspection Tasks** | Support manual or scheduled automatic inspections, result logging, and notifications |
| **Inspection Reports** | Automatically generate detailed inspection reports for each resource |
| **Notifications** | Automatically send upgrade alerts when certificates or applications need updates |

## 🖥️ Supported Resource Types

### Platforms / OS
- AIX, Windows, Linux (Redhat/Kylin, etc.), UnixWare, HP-Unix, AS400
- Hardware, network devices, storage, virtualization, cloud platforms

### Databases & Middleware
- **Databases**: MySQL, Oracle, DB2, PostgreSQL, Redis
- **Middleware**: WebLogic, WAS, MQ, Kafka, Nginx, Tomcat, IHS

### Automation Job Types
- **Script jobs**: Shell, batch, Python
- **File jobs**: create/delete/modify/query, MD5 checksum, parsing
- **Database jobs**: SQL, stored procedure execution
- **FTP jobs**: common FTP operations

## 🔍 Typical Inspection Items

- **Operating System**: profile, hosts, sudoers, passwd, group, systeminfo, patch version, disk/swap space, logical volumes, HA/cluster services, network status, system performance, configuration file changes
- **Databases**: version, process status, application connections, instance configuration, HADR status
- **Middleware**: configuration files (e.g., httpd.conf, plugin-cfg.xml), service status, port listening, log checks
- **Network Devices**: CPU/memory usage, neighbor relationships, routing tables, log alerts, stack/HA status, temperature/power/fan parameters
- **Load Balancers / Firewalls**: operational status, version info, config backups, NAT connection count, redundancy protocol status

## 📊 Inspection Dashboard & Orchestration

- Visual inspection dashboard for overall system health
- Support for writing and debugging inspection scripts
- Flexible orchestration to combine multiple checks in sequence

## 📞 Contact
- **Project Website:** https://www.ylink.com.cn/

- **Issue Tracker:** GitHub Issues

- **Mailing List:** ylink_pd@yykj.com 
