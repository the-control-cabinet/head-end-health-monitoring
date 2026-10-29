# 03 Disaster-recovery restore test

[← Back to README](../README.md)

1. Take the latest off-site backup.
2. Restore onto spare hardware or a VM with the network isolated.
3. Time it to "dashboards up" and "integrations loaded"; note what didn't restore cleanly (e.g. hardware-bound dongles, tokens).
4. Record the RTO (recovery time) and lessons in the [O&M pack](https://github.com/the-control-cabinet/om-manual-handover-pack).
