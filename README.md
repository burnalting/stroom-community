# stroom-community
Stroom orientated event source agents, corresponding Stroom UI content and standalone Stroom UI content

# Agents and Stroom Content

### **LinuxAuditd**
  * Agent [stroom-community-linuxdaudit-agent](https://github.com/burnalting/stroom-community-linuxauditd-agent) - Linux based agent that periodically aggregates, enriches and posts Linux Auditd event data to a nominated Stroom proxy.
  * Content [stroom-community-linuxauditd-content](https://github.com/burnalting/stroom-community-linuxauditd-content) - [Stroom](https://github.com/gchq/stroom)  (version >= 7.2) UI content that translates the Linux Auditd data posted by the Linux Auditd Agent into the Stroom [Event Logging Schema](https://github.com/gchq/event-logging-schema)
  * Content Index [stroom-community-linuxauditd-index-internal](https://github.com/burnalting/stroom-community-linuxauditd-index-internal) - [Stroom](https://github.com/gchq/stroom)  (version >= 7.2) UI content that indexes Linux Auditd Event data using the internal Stroom indexing capability.
