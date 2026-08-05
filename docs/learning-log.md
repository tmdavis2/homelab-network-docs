# Homelab Build Log 

A running log of setup steps, experiments, trial-and-error. 

---

## 08/05/2026

###  Starting Documentation 
* I have started putting together documentation on github of what I have done so far.
This is to show what I am learning day by day in real time as well as show what has
already been set up.
* At this point, the cluster has already been set up with 5 nodes. NextCloud is running in
a LXC, with tailscale set up so I am able to access nextcloud on other devices. I have also spun
up a VM running EVE-NG Freemium.

###  Learning EVE-NG/Serial Console
* I am reading a guide on how to use EVE-NG specifically for Cisco hardware. 
* Trying to figure out which images to install and how to install.
* Before installing images, trying to access EVE-NG vm terminal from
my laptop terminal.
* Cannot enter the VM because there is not a serial console configured.(I want to
use terminal on laptop instead of web GUI) A serial console is a direct text base interface, transmitting text commands over a serial communication port(RS-232, USB serial, Virtual serial interface). This bypasses the network as well
* Added serial port on the EVE-NG VM through Proxmox web GUI
* Can now access the VM directly through the serial port on host machine
* 
