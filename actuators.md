# Spring Boot Actuator Endpoint Bruteforce Wordlist

When hunting for exposed Spring Boot Actuator endpoints, use this comprehensive wordlist with tools like **ffuf, gobuster, and feroxbuster**.

---

## **📌 Bruteforce Wordlist for Actuator Endpoints**

```
# Default Actuator Base Path

actuator
actuator/

# Common Actuator Endpoints (Spring Boot 2.x/3.x)

actuator/health
actuator/info
actuator/env
actuator/metrics
actuator/loggers
actuator/threaddump
actuator/heapdump
actuator/logfile
actuator/configprops
actuator/beans
actuator/mappings
actuator/scheduledtasks
actuator/caches
actuator/conditions
actuator/auditevents
actuator/sessions
actuator/shutdown
actuator/startup
actuator/prometheus
actuator/httpexchanges
actuator/quartz
actuator/sbom

# Legacy Spring Boot 1.x Endpoints (No "/actuator" Prefix by Default)

health
info
env
metrics
loggers
trace
dump
heapdump
logfile
beans
autoconfig
mappings
configprops
flyway
liquibase
auditevents
shutdown

# Spring Cloud & Extended Actuator Endpoints

actuator/gateway
actuator/gateway/routes
actuator/refresh
actuator/restart
actuator/jolokia
actuator/hawtio
actuator/hawtio/index.html

# Miscellaneous Actuator Endpoints

actuator/httpexchanges
actuator/conditions
actuator/flyway
actuator/liquibase
actuator/integrationgraph
actuator/heapdump
actuator/loggers
actuator/metrics
actuator/auditevents

management
management/
management/health
management/info
management/env
management/metrics
management/configprops
management/beans
management/loggers

manage
manage/
manage/health
manage/info

admin
admin/
admin/health
admin/env

monitoring
monitoring/
monitoring/health
monitoring/info
monitoring/env

internal
internal/
internal/health
internal/info
internal/env
```
