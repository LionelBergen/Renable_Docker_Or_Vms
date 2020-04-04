Run virtualbox after Docker (Enable VMs, disable Docker)
---------------------------
run elevated command prompt:
	dism.exe /Online /Disable-Feature:Microsoft-Hyper-V
    dism.exe /Online /Disable-Feature:HypervisorPlatform

Try turning off Hyper-V. IF that doesnt work, turn on, turn off and restart.

Last time restarting was needed

Run Docker after Virtualbox (Enable docker, disable VMs)
--------------------------------------------------------