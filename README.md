<p align="center"><img src="How-to-disable-VBS_HVCI/blob/main/Toogle-off.png" width="200"></a>
<h1 align="center"><b>How to disable VBS/HVCI to increase Performance in Windows 11</b></h1>
<br />

<p align="center">
<a href="https://ko-fi.com/k3v1991" alt="Ko-fi"><img src="https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white"> &emsp;
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="PayPal"><img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white"> &emsp;
<a href="https://github.com/K3V1991/Donate-Crypto/blob/main/README.md" alt="Crypto"><img src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white">
</p>
<hr>
<br />
<br />

## Check VBS/HVCI Status:
1. Open System Information
2. Scroll down to find the ```Virtualization-based security```. If it says ```Running``` VBS is enabled.
<br />
<br />

## Disable VBS/HVCI:
1. Search for ```Core isolation``` in Windows Search and click the top Result
2. Toggle ```Memory integrity``` to ```Off```
3. Reboot your PC as prompted
4. Check System Information again to see if Virtualization-based security is listed as ```Not enabled``` If so, you are done
<br />
<br />

## Disable VBS/HVCI via Registry Editor:
1. Open ```Registry Editor```
2. Navigate to ```HKEY_LOCAL_MACHINE\System\CurrentControlSet\Control\DeviceGuard```
3. Double-click ```EnableVirtualizationBasedSecurity``` and set it to ```0``` and click ```OK```
4. Close Registry Editor and reboot your PC
