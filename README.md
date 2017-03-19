# raspi-ath9k-remove-wifi-restriction
A raspi kernel patch to remove wifi restrictions for the ath9k driver, intended for AR9271 WiFi dongles such as TP-LINK TL-WN722N. 

Warning: this is **illegal** if you operate without the proper radio licenses, such as a ham radio license. The patched driver **will** allow you to apply frequencies and powers that are outside of typical ISM allocations *and* ham radio allocations in certain countries, so please cross-check with your local regulations. 


Based on [hatsunearu/EZ-WifiBroadcast](https://github.com/user/hatsunearu/EZ-WifiBroadcast). Should apply to 4.4.y branch correctly on the [official raspi linux repo](https://github.com/raspberrypi/linux)

