# Monitoring with a DevOps Mindset

The old way:

- Focus primarily on system and infrastructure metrics
- Related to availability and performance
- "Is the server up?"
- Performance measured inconsistently

Consequences of the old way:

- *Reactive* dashboards sounded the alarm
- No proactive alerts before a problem
- False alarms cause alerts to be ignored

The old way of monitoring is not a recipe for long-term success:

- If the server is up, it does not need that the application is available
- Alerts that require no actions are sent
- Stable infrastructure does not mean stable apps

## Business Metrics as a Way of Monitoring

- Metric dip alerts team to investigate
  - We are used to 10,000 transactions and suddenly it drops to 100
- Track MTTD
- Automated alerts triggers system to solve in seconds
  - As opposed to 30 minutes to call help desk

Proactive monitoring leads to job satisfaction

## Observability is Becoming the Industry Norm

- Observability: we have the instrumentation we need to understand what is happening within a software
- Focuses on the development of the application
  - Not pull and monitoring for threshold
  - Nor find healthchecks
  - It answers any arbitrary question about how the software works
- Charity Majors (Honeycomb CEO) on Benefits of Observability
  - Health of the system no longer matters
  - What matters is the health of each event
    - or each individual user's experience
    - or each shopping cart user's experience
  - Observability instead of monitoring
    - It's about unknown unknowns
    - No longer known unknowns

## You Can't Monitor Everything

- Auto-remediate what you can
- Fail gracefully where you can't
- Shift ops load to providers as much as you can

You cannot predict all unknown unknown
Focus energy where you can predict:

- Instrumentation
- Resilience to failure
- Fast and safe deployment (and rollback)
  - Canaries
  - Gradual rollouts
  - Feature flags

## Stop the Sustained Barrage

- If we know how to fix it, fix it
- Auto-remediate the problem
- Make system resilient enough to wait
  - Disable paging alert in off hours
    - Engineers should mostly get paged about novel and undiagnosed issues
