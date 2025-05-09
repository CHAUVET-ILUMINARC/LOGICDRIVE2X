# LOGIC Drive 2X

## Software Versions
..........................................................................................................................................................................................................................................................................


[V2.14 - LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/f10fdb7eb758033734ed36db20567427276619d6/firmware/V2.14_250507.zip)
- Improved synchronization with Wallcon when multiple LOGIC Drive2X are linked together

..........................................................................................................................................................................................................................................................................


[V2.11 - LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/7eb3b56d28cbc827d1dc01139779bd22e7eeb329/firmware/V2.11_241009.zip)
- Fixed a bug

..........................................................................................................................................................................................................................................................................


[V2.10 - LOGIC Drive 2x](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/e22260eed2113e39ece7b5eba9544171aec7b2e3/firmware/V2.10_240826.zip)
- Added API command control interface
- Added group number control
- Modified the original 8 dynamic scenes to 64 static scenes
- Modified the multi-scene playback function
- Modified the search issue
- Modified the unicast packet data loss problem
- Modified the way to clear history
- Added the ability to cancel auto search when power up
- Added the function of auto search for history devices
- Added the ability for DHCP to automatically assign IP function
- Added gradient effect function
- Added GD MCU version software and increased the number of searches to 100 units
- Optimized the upgrade function
- Added infrared panel control

<span style="color:orange">⚠️</span> <strong>Warning:</strong>
<div style="margin-left: 2em; display: inline;">
  This update reduces the port fixture capacity from 40pcs down to 30pcs on drives with ST controllers. <br>
  Drives with GD controllers are immune from this reduction in fixture count/port. You can find which controller is used in your drive by reviewing the webserver. It is posted in the top-right section of the webservers.
</div>

 <br>
<span style="color:orange">⚠️</span> <strong>Warning:</strong>
<div style="margin-left: 2em; display: inline;">
 <br>
  When updating the drives with the ST microcontroller from V1.** to the 2.** firmware platform, the process takes up to 10 minutes. Please ensure you have a stable power supply before proceeding and do not interrupt the update until it completes.
</div>
..........................................................................................................................................................................................................................................................................

&nbsp;


[V1.11 – LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/e22260eed2113e39ece7b5eba9544171aec7b2e3/firmware/V1.11_221129.zip)
- Released initial software version
