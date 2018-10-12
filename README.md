# Aircrack-ng

Scripts to run Wi-Fi password cracking demo

1. Setup the target network protected with WPA2 
2. Add the password/PSK to the end of `wordz.lst`
3. Run `./setup [network-channel] [network-bssid]`
    - `[network-channel]` = target network channel
    - `[network-bssid]` = target network access point/ router MAC address
4. Join the target network with a device to allow capture of the handshake
5. Run `./crack [network-bssid]`
