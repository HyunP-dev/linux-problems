적절히 nomodeset을 해준 다음 설치를 끝내면 grub에서도 설정을 해줘야 하는데 /etc/default/grub 에서 다음과 같이 변수를 설정해주면 됨.
```
GRUB_CMDLINE_LINUX="rhgb quiet nomodeset"
```
