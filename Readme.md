## Speculation Control
Original function provided by MS here: https://www.powershellgallery.com/packages/SpeculationControl/1.0.0

Adapted so this outputs one single object

Get-MeltdownSpectreStatus

```
Hardware support for branch target injection mitigation is present   : False
Windows OS support for branch target injection mitigation is present : False
Windows OS support for branch target injection mitigation is enabled : False
BTIHardwarePresent                                                   : False
BTIWindowsSupportPresent                                             : False
BTIWindowsSupportEnabled                                             : False
BTIDisabledBySystemPolicy                                            : False
BTIDisabledByNoHardwareSupport                                       : False
Windows OS support for kernel VA shadow is present                   : False
Windows OS support for kernel VA shadow is enabled                   : False
KVAShadowRequired                                                    : True
KVAShadowWindowsSupportPresent                                       : False
KVAShadowWindowsSupportEnabled                                       : False
KVAShadowPcidEnabled                                                 : False
```