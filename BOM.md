## Bill of Materials (BOM)

### 1. Electronics

| Component | Specifications / Reference | Qty | Notes & Compatibility |
| :--- | :--- | :---: | :--- |
| **Raspberry Pi** | Raspberry Pi 3B+ *(or Pi 4 / Pi 5)* | 1 | Runs [Recalbox](https://www.recalbox.com/), installed directly using **Raspberry Pi Imager**. The installation procedure is detailed in the README. *(If using Pi 4/5: a Micro-HDMI to HDMI adapter is required.)* |
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
| **Wood Screws (screen support)** | **4 × 15 mm** | 8 | Fix the screen support (with the monitor attached) onto the two wooden battens. |
| **Mounting & Cable Management** | Heavy-duty double-sided tape, nylon zip ties, and hot glue | As needed | Securing the Raspberry Pi case inside the cabinet, plus internal cable management for the 2P arcade harness and small components. |
| **Metal Angle Bracket** | Sized to suit your audio amplifier | 1 | Provides a mounting surface for the audio amplifier, secured using heavy-duty double-sided tape or hot glue. Choose the bracket size according to your amplifier model. |
| **M5 Machine Screws** | **M5 × 35 mm** | 2 | Locker pins in CAD |
| **Wooden Dowel** | **Ø 8 × 620 mm** | 1 | Cut to length for cabinet assembly. (back panel support in CAD) |
| **Wooden Battens** | **33 × 33 × 620 mm** | 2 | Cut to length for cabinet assembly. (screen support bar in CAD) |

---

### 3. 3D-Printed Parts

The original parts were printed in **TPU 64D**, but **PLA or another rigid filament** is also suitable.

| File | Qty | Notes |
| :--- | :---: | :--- |
| `back_panel_latch.3mf` | 3 | Back panel latch. |
| `back_panel_locker.3mf` | 4 | Back panel locking component. |
| `volume_button.3mf` | 1 | Volume control knob. |

---

### 4. Laser-Cut Parts

All panels are made from **MDF**. Use the thickness specified below for each DXF file.

| File | Material | Thickness | Qty | Notes |
| :--- | :--- | :---: | :---: | :--- |
| `back_panel.dxf` | MDF | **6 mm** | 1 | Rear panel. |
| `bottom_panel.dxf` | MDF | **6 mm** | 1 | Bottom panel. |
| `control_panel.dxf` | MDF | **9 mm** | 1 | Main control panel. |
| `front_control_panel.dxf` | MDF | **9 mm** | 1 | Front control panel. |
| `front_panel.dxf` | MDF | **6 mm** | 1 | Front panel. |
| `left_panel.dxf` | MDF | **10 mm** | 1 | Left side panel. |
| `marquee.dxf` | MDF | **6 mm** | 1 | **Customization recommended:** personalize the marquee artwork for a finish similar to the [finished cabinet photo](Media/REAL_powered_side_and_front_view.png). |
| `right_panel.dxf` | MDF | **10 mm** | 1 | Right side panel. |
| `screen_panel.dxf` | MDF | **6 mm** | 1 | Screen panel. |
| `screen_support.dxf` | MDF | **10 mm** | 1 | Monitor support. |
| `top_back_panel.dxf` | MDF | **6 mm** | 1 | Upper rear panel. |
| `top_panel.dxf` | MDF | **6 mm** | 1 | Top panel. |
| `under_control_panel.dxf` | MDF | **6 mm** | 1 | Under-control panel. |
| `under_top_panel.dxf` | MDF | **6 mm** | 1 | Under-top panel. |
