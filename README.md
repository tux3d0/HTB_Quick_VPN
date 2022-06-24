# HTB_Quick_VPN
A quick and basic shell script for connecting to the different Hack The Box VPNs. 

<b> Please put all of your vpn files into $HOME/vpn. </b>
If you have a different dir you have your files stored in, you can simply change the paths and or file name in the script.

More updates to come

-Tuxnix

# Customisation:

You can select the VPNs from your current working directory by removing `$HOME/vpn`

```sh
[-] starterPoint() {
	sudo openvpn $HOME/vpn/starting_point_$usrName.ovpn
}
[+] starterPoint() {
	sudo openvpn starting_point_$usrName.ovpn
}
```
This can also be used to select any folder you want instead of the home directory.
