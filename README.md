# X299-EFI-Folder-Distributions

EFI-Folder distributions valid for ASUS Prime X299 Deluxe with enabled MSR register kernel write.

For X299 mainbaords with locked MSR register, check KernelPM and enable _xcpm_core_scope_msrs © Pike R. Alpha Kernel patch in config.plist - Section "Kernel and Kext Patches" of Clover Configurator

For X299 mainbaords different from ASUS check bootflag "npci=0x2000" in config.plist -  Section "Boot/Arguments/" of Clover Configurator
