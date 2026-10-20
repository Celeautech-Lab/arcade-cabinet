## Bill of Materials (BOM)

### 1. Electronics

| Component | Specifications / Reference | Qty | Notes & Compatibility |
| :--- | :--- | :---: | :--- |
| **Raspberry Pi** | Raspberry Pi 3B+ *(or Pi 4 / Pi 5)* | 1 | Compatible with any board supported by [Recalbox](https://www.recalbox.com/) *(if using Pi 4/5: a Micro-HDMI to HDMI adapter is required)*. |
| **Raspberry Pi Case** | Case with active cooling fan (5V GPIO fan + heatsinks) | 1 | Essential to keep the Pi cool inside the enclosed cabinet. Mounted inside using double-sided tape. |
| **MicroSD Card** | 16 GB minimum (32 GB to 128 GB recommended, Class 10 / UHS-I) | 1 | For the Recalbox OS and game ROMs. |
| **24" Monitor** | 24" (16:9), VESA 100×100 mm, HDMI input *(Model used: **Philips 243V7Q**)* | 1 | Panel dimensions without stand: **540 × 325 × 45 mm**. The cabinet provides a 20 mm clearance on each side (max accepted width: ~580 mm). |
| **2-Player Arcade Kit** | 2P "Zero Delay" USB encoders, 2 joysticks, and LED chrome buttons *(Model used: **Fosiya 2-Player LED Arcade Kit**)* | 1 kit | Includes 2 USB encoder boards, 2× 8-way joysticks, and 18–20 LED push buttons (5V powered via the encoders).<br> **Note on button size:** Although marketed as "30 mm" (outer bezel diameter), their threaded body is **28 mm** and fits snugly into the cabinet's **Ø 28 mm** laser-cut holes. |
| **5V Power Supply** | **5V DC / 6A (30W)** switching power supply | 1 | Powers the Raspberry Pi and the audio amplifier (avoids undervoltage warnings caused by the LED buttons). |
| **Audio Amplifier** | 5V DC stereo mini amplifier, 3.5 mm Jack input | 1 | Connected to the Raspberry Pi via 3.5 mm audio jack and powered by the 5V PSU. |
| **Speakers** | **2-inch (Ø ~50–53 mm), 4 Ω, 5W** full-range stereo stereo speakers *(Model used: **Zalati EK1949**)* | 2 | Mounted behind the speaker grille. |
| **USB Flush Mount Cable** | USB 3.0 male-to-female threaded round panel mount extension cable, 1 m *(Model used: **Bolongking USB 3.0 Flush Mount**)* | 1 | Fits into a standard Ø 28–30 mm round hole. Allows plugging in an external USB drive or controller. |
| **IEC Power Inlet** | IEC 320 C14 fused rocker switch module (10A / 250V, "3-in-1" snap-in / screw-mount type) | 1 | Main power switch on the left panel. Salvaged from a **Creality Ender 3** PSU (standard ~47 × 27 mm panel cutout, 40 mm screw hole spacing — widely available as a generic 3D printer replacement part). |
| **Power Strip** | 2-outlet minimum power strip | 1 | Mounted inside the cabinet (powers the 24" monitor and the 5V DC power supply). |
| **Cables & Wiring** | - 1× HDMI cable (1 m)<br>- 1× 3.5 mm male-to-male audio jack cable (1 m)<br>- 1× IEC C13 mains power cord<br>- Electrical wires (mains AC & 5V DC) | 1 set | Internal wiring according to the [wiring diagram](Media/wiring_diagram.png). |

>  **Important Note on Arcade Buttons:** Many arcade kits (like the Fosiya kit used here) advertise their buttons as **30 mm** — which actually refers to the outer lip/bezel diameter — while the threaded barrel itself is **28 mm**. The cabinet's DXF files are cut at **Ø 28 mm**, providing a tight, play-free fit. **Do not enlarge the holes to 30 mm** unless you have measured your button threads with calipers first.

---

### 2. Hardware & Fasteners

| Component | Dimensions / Specifications | Qty | Usage |
| :--- | :--- | :---: | :--- |
| **M4 Machine Screws** | **M4 × 15 mm** | 4 | VESA mount (100×100 mm) to attach the monitor to its wooden bracket. |
| **Joystick Fasteners** | Included in the arcade kit | 1 set | Mounting the 2 joysticks under the control panel. |
| **Wood Screws** | **3 × 10 mm** | ~100 | General assembly and mounting of the 3D-printed brackets / internal components. |
| **Mounting & Cable Management** | Heavy-duty double-sided tape, nylon zip ties, and hot glue | As needed | Securing the Raspberry Pi case inside the cabinet, plus internal cable management for the 2P arcade harness and small components. |
