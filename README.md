# Motec Camera Visualizer  

The **Motec Camera Visualizer** is a Windows-based application designed to display, arrange, and record video streams from Motec cameras. It provides a flexible software alternative to hardware monitors, optimized for low latency and reliable performance in vehicle cabins and industrial environments.  

---

##  Features  

- Display **as many camera streams in parallel as you wish**  
- Record **multiple streams simultaneously**  
- Supports **RTP, DHCP, MCP, SOME/IP** protocols  
- Codec support: **H.264, MJPEG**  
- **14 view modes** (grid, PiP, split, triple, quad, custom, etc.)  
- Favorites & layout management  
- **DVR loop recording** with incident saving  
- **Freeze detection** and live indicators  
- **Barcode and QR code detection** (for navigation/warehouse use cases)  
- Bandwidth & storage monitoring  

---

## System Requirements  

- **OS:** Windows 7 or later  
- **Hardware:**  
  - Sufficient CPU/GPU performance for video decoding  
  - Network interface with camera access  
  - Adequate storage for recording  

---

## Installation  

1. Download the application
2. Extract the `.zip` file to a directory of your choice.  
3. Launch `MotecCameraVisualizer.exe`.  
   - No installation process is required.  
4. On first start, allow firewall access so the application can receive video streams.  

> ⚠️ **Note:** If firewall permission is denied, open `firewall.cpl`, select **Allow an App or Feature**, and enable **MotecCameraVisualizer** for network access.  

---

## Open Source Components  

- [AForge.NET v2.2.5](https://www.aforgenet.com/framework/) – LGPL v3  
- [ZXing.NET v0.16.9](https://github.com/micjahn/ZXing.Net/) – Apache 2.0  
- [Accord.NET v3.8.0](http://accord-framework.net/) – LGPL  

---

## Support  

For technical support, please contact:  

**Motec GmbH**  
Oberweyerer Str. 21  
65589 Hadamar-Steinbach, Germany  

+49 6433 9145-9888  
[www.motec-cameras.com](https://www.motec-cameras.com)  
