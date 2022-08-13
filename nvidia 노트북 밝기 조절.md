```
GRUB_CMDLINE_LINUX_DEFAULT="nvidia.NVreg_RegistryDwords=EnableBrightnessControl=1"
```
/etc/default/grub에서 `GRUB_CMDLINE_LINUX_DEFAULT`에 `nvidia.NVreg_RegistryDwords=EnableBrightnessControl=1`를 추가해준 뒤, `sudo update-grub` 해주면 된다.
