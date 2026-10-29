# 02 Alarms

[← Back to README](../README.md)

| Alarm | Condition | Priority |
|---|---|---|
| Integration failed | Config entry in error > 15 min | P3 |
| Device group degraded | > 2 devices of a type offline > 30 min | P3 |
| Gateway silent | RAMSES-II or Zigbee no messages for 10 min | P2 (heating/safety data at risk) |
| Backup failed | No successful backup in 26 h | P3 |
| Disk high | > 85 % | P3 |
| Internet down | WAN down > 10 min | P4 (local control continues) |

Routed per the [alarm strategy](https://github.com/the-control-cabinet/alarm-and-trend-strategy).
