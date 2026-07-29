## Build Information
```
Kernel: Mimir Kernel
Device: Motorola One
Compiler: GCC 4.9 (20150123)
Branch: lineage-18.1
Last build date: 20260729
```
## Changelog
**20260729**

* Enable power-saving workqueue by default
* misc, qcom: msm-core, power: bcl and mdss: queue work on system_power_efficient_wq
* add more wakelocks to the default block list
* boeffla_wl_blocker: Correct implemention driver v1.1.0
* drivers: power: Fix 2% battery level drop
* killing wakelocks after almost three minutes
* nohz: fix idle and iowait stats discrepancy
* tick/nohz: Optimize nohz idle enter
* cpufreq: cache tunables for ondemand and conservative governors
* cpu-hotplug: Always use real time scheduling when hotplugging a CPU
* block: cfq: tuning and burning
* cpufreq: Optimizing interactive Governor
* mm: swap: swap pages one at a time
* power: process: decrease time to enter sleep
* kgsl: Properly set GPU timeout: 80 > 64
* Merge patches CVE-2018-1066 until CVE-2024-27425
* Merge patches CVE-2015-1339 until CVE-2017-1000370

**20260718**

* Enable CONFIG_OVERLAY_FS
* add generic wakelock blocker driver v1.1.0
* Enable cpu-boost and adjust configs
* msm: mdss: convert threads to interruptible
* thermal_core: Use power efficient workqueue
* block: Do not wake the request CPU if idle
* mm: get 7% more pages in a pagevec
* block: More power efficiency
* include: EXT4 optimizations
* devfreq: Add adrenoboost control
* cpufreq: suspend cpufreq governors on shutdown
* Restrict perf event sampling CPU time to 5%
* Disable GFS for better UI performance
* Don't force compilation of memlat devfreq governors
* PM / freezer: Reduce freeze timeout to 1 second for Android
* Adjust clocks for 2016/345 mhz
* Rebrand localversion of Mimir
