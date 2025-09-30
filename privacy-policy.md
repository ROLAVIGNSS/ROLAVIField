# ROLAVIField — Privacy Policy

**Effective date:** September 30, 2025  
**Last updated:** September 30, 2025

ROLAVIField is a mobile application developed by **ROLAVI GNSS S.A.C. (Peru)** for surveying, cartography, and GIS workflows that integrate high-accuracy **ROLAVI GNSS** receivers. This policy explains what information the app processes, how it is used, and your choices.

---

## 1) Who we are
**ROLAVI GNSS S.A.C.**  
Email: **contact.rolavi@rolavisurveyor.com**  
Country of operation: **Peru**

---

## 2) What the app does
ROLAVIField connects to GNSS receivers (e.g., ROLAVI devices) via **Bluetooth** and/or **TCP** and lets you create and manage surveying/GIS projects (points, lines, polygons, attributes, and related metadata). You can export data in standard geospatial formats you choose.

---

## 3) What data we collect
**We do not collect, store, or process personal data on our servers.**  
- **No analytics SDKs**  
- **No advertising SDKs**  
- **No background collection to ROLAVI servers**

All processing happens **on your device** or to **endpoints you configure** (for example, a TCP/NTRIP service you control). If you voluntarily email us logs or datasets for support, we will use them only to troubleshoot your request and then delete them within a reasonable time.

---

## 4) Data processed on your device
- **Survey project data**: coordinates, timestamps, accuracy metrics, feature attributes, and other geospatial metadata you create or import.  
- **Device GNSS/location signals**: used to display position and quality in the app; not sent to our servers.  
- **Connection credentials** (e.g., Bluetooth pairing, optional TCP/NTRIP credentials): stored **locally on your device** and transmitted **only** to the endpoints you configure.

You control exports (e.g., CSV, KML, GeoJSON). The app does not upload project data to ROLAVI.

---

## 5) Network transmission (Bluetooth/TCP/NTRIP)
ROLAVIField can transmit GNSS messages (e.g., NMEA/RTCM) **only** to devices/servers you specify. We **do not** proxy or receive these streams. Depending on your configuration, connections may be plain TCP or secured (e.g., TLS/HTTPS) if your chosen endpoint supports it. We recommend using secure endpoints whenever available.

---

## 6) Permissions and purpose
- **Location**: required to access GNSS/location for mapping and, on newer Android versions, to scan/connect via Bluetooth.  
- **Bluetooth** (including Bluetooth LE/Scan/Connect/Advertise where applicable): to discover and communicate with ROLAVI GNSS and compatible sensors.  
- **Network (Internet)**: to reach user-configured endpoints (e.g., NTRIP/TCP) and to enable any online functionality you choose.  
- **Storage / Photos & Media** (if requested by your OS): to read/write project files and exports you create.  
- **Foreground service** (if used): to keep GNSS connections active during long-running fieldwork.

These permissions are used **only** for the stated core functionality.

---

## 7) Data sharing and selling
- **We do not sell data.**  
- **We do not share data with third parties** except when **you** direct the app to transmit to services you control (e.g., your NTRIP caster or TCP host).  
- Any third-party service you connect is governed by its own terms and privacy policy.

---

## 8) Retention and deletion
- Survey data and credentials are stored **locally** on your device until **you** delete them (from within the app or your device’s file manager).  
- ROLAVI GNSS S.A.C. does not retain copies of your data.

---

## 9) Security
We design ROLAVIField so that processing stays on your device and transmissions go only to endpoints you configure. Because field workflows may use plain TCP depending on your setup, we encourage using secure endpoints (TLS/HTTPS) whenever supported and protecting your device with a passcode/biometrics.

---

## 10) Children
ROLAVIField is intended for professional/educational surveying use and is **not directed to children under 13**. We do not knowingly collect personal information from children.

---

## 11) Your choices
- You can **export**, **backup**, or **delete** your projects at any time.  
- You may **revoke** app permissions in your device settings (note: some features may stop working).  
- You can change or remove endpoints (Bluetooth/TCP/NTRIP) you previously configured.

---

## 12) Changes to this policy
We may update this policy as the app evolves. We will update the “Last updated” date above and, when appropriate, provide notice in-app or via our website.

---

## 13) Contact us
Questions or requests about privacy?  
**contact.rolavi@rolavisurveyor.com**  
**ROLAVI GNSS S.A.C. (Peru)**

---

### Google Play “Data safety” summary (for your Play Console)
- **Data collection:** No data collected by the developer.  
- **Data sharing:** No data shared by the developer.  
- **Location:** Used on device for core functionality (not collected).  
- **App activity/Device or other IDs:** Not collected.  
- **Financial info/Contacts/Calendar/Messages/Photos & Videos:** Not collected (unless the user explicitly picks files to import/export).  
- **Encryption:** Depends on user-selected endpoints; encourage TLS/HTTPS where available.  
- **Data deletion:** User can delete local data at any time.
