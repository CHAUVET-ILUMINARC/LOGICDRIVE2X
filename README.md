# LOGIC Drive 2X

## Software Versions

---

⚠️ **Please Be Advised:**  
Logic devices are updated via the webserver on the drive and wall panel. The drives and wall panels can update themselves as well as fixtures connected to their outputs. We recommend using the **Chrome browser** for this process.  

---

### [V2.14 – LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/f10fdb7eb758033734ed36db20567427276619d6/firmware/V2.14_250507.zip)  
- Improved synchronization with Wallcon when multiple LOGIC Drive 2X units are linked together.  

---

### [V2.11 – LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/7eb3b56d28cbc827d1dc01139779bd22e7eeb329/firmware/V2.11_241009.zip)  
- Fixed a bug.  

---

### [V2.10 – LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/e22260eed2113e39ece7b5eba9544171aec7b2e3/firmware/V2.10_240826.zip)  
- Added API command control interface  
- Added group number control  
- Expanded from 8 dynamic scenes to 64 static scenes  
- Updated multi-scene playback function  
- Fixed search issue  
- Fixed unicast packet data loss problem  
- Improved history clearing  
- Added option to cancel auto search on power-up  
- Added automatic history device search  
- Added DHCP auto-assign IP functionality  
- Added gradient effect function  
- Added GD MCU software support; increased search capacity to 100 units  
- Optimized upgrade function  
- Added infrared panel control  

⚠️ **Warning – Fixture Capacity Reduction**  
- Drives with **ST controllers**: fixture capacity per port reduced from 40 pcs → 30 pcs  
- Drives with **GD controllers**: unaffected  
- To check your controller type, open the webserver (top-right section)  

⚠️ **Warning – Firmware Migration (ST Microcontroller Only)**  
- Updating from V1.** to V2.** firmware may take **up to 10 minutes**  
- Ensure stable power supply and **do not interrupt** the update  

---

### [V1.11 – LOGIC Drive 2X](https://github.com/CHAUVET-ILUMINARC/LOGICDRIVE2X/blob/e22260eed2113e39ece7b5eba9544171aec7b2e3/firmware/V1.11_221129.zip)  
- Initial software release  

---

## Important Compatibility Notice  
- **Logic V2.** platform is **not compatible** with V1.** platform  
- All drives, wall panels, and fixtures must be on the same platform version  
- If drives/wall panels are updated but fixtures are not, fixtures may stop functioning and become invisible in the system  
