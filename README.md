# Head-End Health and Availability: Monitoring the BMS Itself (Design Stage)

**Monitoring the building-automation system as a system, the way BMS supervisors are judged on uptime: integration and device availability, controller health, network and internet status, backup success and a scheduled restore test, with availability KPIs and alarms routed through the alarm strategy.**

[![YouTube](https://img.shields.io/badge/YouTube-The%20Control%20Cabinet-red?logo=youtube)](https://www.youtube.com/channel/UC5Cupmz7vlfcodpCX7k8iuQ)
[![Portfolio](https://img.shields.io/badge/Portfolio-the--control--cabinet-24292f?logo=github)](https://github.com/the-control-cabinet/the-control-cabinet)
![Domain](https://img.shields.io/badge/BMS-system%20health-blue)
![Status](https://img.shields.io/badge/Status-Design%20stage-yellow)

> **The short version:**
> - **Availability KPIs:** % of integrations loaded, devices online by type (ESPHome, Zigbee, BLE proxies), gateway health (RAMSES-II, Zigbee, MQTT).
> - **Platform health:** host CPU, memory, disk, database size, add-on status, update backlog.
> - **Network:** router WAN status, latency/speed tests, local DNS/DHCP health.
> - **Recovery:** nightly backup verified off-site, and an **annual restore test** onto spare hardware with a timed recovery.

**Portfolio position:** Management level · system health. Feeds: [alarm strategy](https://github.com/the-control-cabinet/alarm-and-trend-strategy) (P3 alarms). Related: [integration schedule](https://github.com/the-control-cabinet/home-assistant-integration-schedule) · [ESPHome fleet](https://github.com/the-control-cabinet/esphome-fleet-standards) · [O&M pack](https://github.com/the-control-cabinet/om-manual-handover-pack)

---

## Documents

| Doc | Contents |
|---|---|
| [01 KPIs and points](docs/01-kpis.md) | What is measured |
| [02 Alarms](docs/02-alarms.md) | Thresholds and routing |
| [03 Disaster-recovery restore test](docs/03-restore-test.md) | Annual timed recovery |

## Roadmap
- [ ] Availability entities and a health dashboard
- [ ] Alarms into the alarm register
- [ ] First timed restore test
- [ ] Monthly availability report

## Skills demonstrated (as built)
| Skill | Evidence |
|---|---|
| System health monitoring | Availability KPIs across integrations and devices |
| Resilience | Backup verification and timed restore test |
| Operations | Alarm thresholds and a monthly availability report |

📺 [The Control Cabinet on YouTube](https://www.youtube.com/channel/UC5Cupmz7vlfcodpCX7k8iuQ)

*Built and documented by James · part of [The Control Cabinet BMS portfolio](https://github.com/the-control-cabinet/the-control-cabinet). MIT Licence.*
