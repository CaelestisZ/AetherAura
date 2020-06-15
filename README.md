# AetherAura

![AetherAura Logo](/info/banners/aetheraura.png)

> SE 7.1.1 kernel | FortunaX | Base: J510FN

## Supported devices

 - G530HXX
 - G530HXC
 - G530FZ
 - G530F
 - G530BT
 
## Release History

 - __Ascent__
     - Selective fortuna drivers updated
     - Reduced CPU average load
     - Enabled ARCH_POWER
     - Reduced kernel overheat
     - Powersuspend
     - MSM adreno idler
     - Added state_notifier
     - Added msm_limiter
     - Implemented custom voltage control
     - Introduced lpClock
     - Optimize KSM
     - And several performance optimizations
     
 - __BlueFlare__
     - Undervolt for better compatibility
     - Implemented fast idling of CPU
     - Implemented INTELLI_THERMAL driver
     - Tune task-scheduler for power savings
     - Implemented USB fast charge
     - Decrease swappiness to 20
     - TCP_Westwood: Tune-up
     - Fixed headphone buttons
     - And several optimizations to GPU
     
  - __ClangorousSoulblaze__
     - Kernel upstream: Linux 3.10.55
     - Implemented a simpler MSM_THERMAL monitor
     - Implemented Intelli-plug hotplug driver
     - Implemented Faux sound control
     - Sensors: updated drivers
     - Radio: fully functional
     - RIL: updated drivers
     - Fixed logcat issues
     
  - __DracoMeteor__
     - Implemented LCD notify
     - Implemented Dynamic fsync and async
     - Implemented Kcal color control
     - Enable adaptive LMK
     - Disable CRC by default

  - __Eternatus__
     - Disable zRAM
     - Enable SSWAP
     - Merge J510FNXXU2BRB1 ramdisk
     - Merge Aether post-boot scripts
     - Adjust LMK values for fortuna
     - Disable adaptive LMK by default
     - Enable hidden TCPs
        - Advanced
        - Cubic
        - Westwood
        - Vegas
        - Illinois
        - And more!
     - Implement IO schedulers
        - Improved BFQ
        - FIOPS
        - SIO
        - SIO+
        - ZEN
        - Tripndroid
        - And more!
     - Properly enabled ARCH POWER & gentle fair sleepers
     - Removed prima WLAN drivers
     - Built-in WiFi drivers
     
  - __FleurCannon__
     - Fixed loads of rushes with:
        - INTELLI_THERMAL
        - INTELLI_PLUG
        - MSM_THERMAL_SIMPLE
        - FAST_CHARGE
        - POWERSUSPEND
     - Enabled faster idling of CPU
     - Re-implemented prima WLAN drivers
     - cpufreq, cpuidle: add -O3 optimizations
