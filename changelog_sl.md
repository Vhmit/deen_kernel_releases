## Build Information
```
Kernel: Mimir Kernel
Device: Motorola One
Compiler: GCC 4.9 (20150123)
Branch: lineage-19.1
Last build date: 20260921
```
## Changelog
**20260921**

* Enable BORE scheduler
* BACKPORT: sched/fair: reweight_task
* zram: remove max_comp_streams internals
* zram: user per-cpu compression streams
* qos: Don't allow userspace to impose restrictions on CPU idle levels
* msm: kgsl: Remove sync debug name generation from hot path
* msm: mdss: Remove sync debug name generation from hot path
* msm: kgsl: Remove POPP
* msm: kgsl: Wake GPU upon receiving an ioctl rather than upon touch input
* kernel: Don't allow IRQ affinity masks to have more than one CPU
* ARM: dts: msm8953: Set GPU idle timeout to 64 ms
* Gain 30% Linux Disk performance
* Optimize console frameBuffer for an up to 70% increase in performance
* drivers: gpu: msm: use funroll-loops and ffast-math
* drivers: gpu: msm: use interruptable wait
* gpu: adreno: Increase data processing limit
* drivers: thermal: Make failed sensor read a debug message
* drivers: thermal: step_wise: Optimize mitigation evaluation
* drivers: msm_thermal: ignore sensor -19

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
