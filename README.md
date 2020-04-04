Run virtualbox after Docker (Enable VMs, disable Docker)
---------------------------
run elevated command prompt:  
	dism.exe /Online /Disable-Feature:Microsoft-Hyper-V  
    dism.exe /Online /Disable-Feature:HypervisorPlatform

Try turning off Hyper-V. IF that doesnt work, turn on, turn off and restart. (Restarting IS required. It didn't work before restart, worked after)  
IF Hyper-V is enabled, you need to disable then restart. (restart is required after disabling for VM to work)

Run Docker after Virtualbox (Enable docker, disable VMs)
--------------------------------------------------------