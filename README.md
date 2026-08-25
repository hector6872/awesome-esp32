# Awesome ESP32 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated collection of awesome ESP32 projects, inspiring builds, frameworks, and tools organized by real-world use cases.

[ESP32](https://www.espressif.com/en/products/socs/esp32) is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and dual-mode Bluetooth created by Espressif Systems.

# Content

- [Projects & Inspiration](#projects--inspiration)
  - [🎤 Presentation Remotes & Productivity Tools](#-presentation-remotes--productivity-tools)
  - [🐱 Virtual Pets, Fidgets & Interactive Toys](#-virtual-pets-fidgets--interactive-toys)
  - [🕒 Desk Companions, Smart Clocks & Ambient Displays](#-desk-companions-smart-clocks--ambient-displays)
  - [📖 E-Paper Readers & Digital Books](#-e-paper-readers--digital-books)
  - [🗣️ AI Voice Assistants & Communicators](#️-ai-voice-assistants--communicators)
  - [🎮 Handheld Gaming & Retro Emulation](#-handheld-gaming--retro-emulation)
  - [🏠 Smart Home Controllers & UI Dashboards](#-smart-home-controllers--ui-dashboards)
  - [🚴 Outdoor, Sports & Live Trackers](#-outdoor-sports--live-trackers)
  - [🎨 Creative Drawing & Acoustic Synthesis](#-creative-drawing--acoustic-synthesis)
  - [🔐 Hardware Security & Private Data Vaults](#-hardware-security--private-data-vaults)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

# Projects & Inspiration

## 🎤 Presentation Remotes & Productivity Tools

Turn a pocket-sized development board into a reliable presentation clicker or input gadget.

<p align="left">
  <a href="https://github.com/F86Pilot/m5stickc-plus-presenter"><img src="media/m5stickc-plus-presenter.jpg" height="120" alt="m5stickc-plus-presenter"></a>
</p>

- **Slide Clicker Remote for Talks & Lectures**: Use an M5Stick as a Bluetooth BLE keyboard remote to advance slides on Google Slides, PowerPoint, or Keynote with on-screen button guides and battery status. [m5stickc-plus-presenter](https://github.com/F86Pilot/m5stickc-plus-presenter)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/F86Pilot/m5stickc-plus-presenter"><img src="media/m5stickc-plus-presenter.jpg" width="400" alt="m5stickc-plus-presenter preview"></a>
  </details>

## 🐱 Virtual Pets, Fidgets & Interactive Toys

Create pocket companions, physical party games, and physics-driven desk toys.

<p align="left">
  <a href="https://github.com/canwar-dj/67"><img src="media/67.jpg" height="120" alt="67"></a>
  <a href="https://github.com/evandroguedes/doodlesoul"><img src="media/doodlesoul-1.jpg" height="120" alt="doodlesoul"></a>
  <a href="https://github.com/V4C38/esp32-fluidbox"><img src="media/esp32-fluidbox.jpg" height="120" alt="esp32-fluidbox"></a>
  <a href="https://github.com/toddsherman/pixelcat"><img src="media/pixelcat.jpg" height="120" alt="pixelcat"></a>
  <a href="https://github.com/frolic/pocket-pet"><img src="media/pocket-pet-1.jpg" height="120" alt="pocket-pet"></a>
</p>

- **Physical Party Throw-and-Catch Game**: A hot-potato style party game for Waveshare ESP32-S3 Touch AMOLED 2.06" that detects freefall when tossed and stops random numbers when caught. [67](https://github.com/canwar-dj/67)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/canwar-dj/67"><img src="media/67.jpg" width="400" alt="67 preview"></a>
  </details>
- **Unique Silicon-Generated Digital Pet**: Procedural companion for M5StickC Plus whose identity, personality, and doodle art style are permanently tied to the chip's unique MAC address with boiling-line animation. [doodlesoul](https://github.com/evandroguedes/doodlesoul)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/evandroguedes/doodlesoul"><img src="media/doodlesoul-1.jpg" width="400" alt="doodlesoul preview 1"></a>
    <a href="https://github.com/evandroguedes/doodlesoul"><img src="media/doodlesoul-2.gif" width="400" alt="doodlesoul preview 2"></a>
  </details>
- **Interactive 2D Fluid & Particle Physics Box**: Sensory fidget simulation where fluid and gravity react to touch and device tilt in real time. [esp32-fluidbox](https://github.com/V4C38/esp32-fluidbox)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/V4C38/esp32-fluidbox"><img src="media/esp32-fluidbox.jpg" width="400" alt="esp32-fluidbox preview"></a>
  </details>
- **Schedule-Aware Desk Pet Cat**: Animated pixel-art cat for ESP32-S3 AMOLED boards that learns your daily routines and schedules to seek attention when you are around. [pixelcat](https://github.com/toddsherman/pixelcat)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/toddsherman/pixelcat"><img src="media/pixelcat.jpg" width="400" alt="pixelcat preview"></a>
  </details>
- **Step-Counting Virtual Pet Watch**: Pocket-Pikachu-inspired companion for Waveshare ESP32-S3 Touch AMOLED 2.06" that levels up and walks through fields as you log real physical steps. [pocket-pet](https://github.com/frolic/pocket-pet)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/frolic/pocket-pet"><img src="media/pocket-pet-1.jpg" width="400" alt="pocket-pet preview 1"></a>
    <a href="https://github.com/frolic/pocket-pet"><img src="media/pocket-pet-2.jpg" width="400" alt="pocket-pet preview 2"></a>
  </details>

## 🕒 Desk Companions, Smart Clocks & Ambient Displays

Build glanceable screens that live on your desk without causing screen fatigue.

<p align="left">
  <a href="https://github.com/POWER-PILL/ASCII-Aquarium"><img src="media/ASCII-Aquarium-1.jpg" height="120" alt="ASCII-Aquarium"></a>
  <a href="https://github.com/Blueforcer/awtrix-ng"><img src="media/awtrix-ng.jpg" height="120" alt="awtrix-ng"></a>
  <a href="https://github.com/Meandmybadself/E-Ink-Countdown-Screen"><img src="media/E-Ink-Countdown-Screen.jpg" height="120" alt="E-Ink-Countdown-Screen"></a>
  <a href="https://github.com/datascale-ai/inksight"><img src="media/inksight-1.jpg" height="120" alt="inksight"></a>
  <a href="https://github.com/LJ545/TravelFrame"><img src="media/TravelFrame.jpg" height="120" alt="TravelFrame"></a>
</p>

- **Animated ASCII Fish Tank Clock**: Whimsical retro aquarium and clock for ESP32 Cheap Yellow Display (CYD) boards featuring touch feeding, live creature simulation, and Wi-Fi NTP time sync. [ASCII-Aquarium](https://github.com/POWER-PILL/ASCII-Aquarium)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/POWER-PILL/ASCII-Aquarium"><img src="media/ASCII-Aquarium-1.jpg" width="400" alt="ASCII-Aquarium preview 1"></a>
    <a href="https://github.com/POWER-PILL/ASCII-Aquarium"><img src="media/ASCII-Aquarium-2.jpg" width="400" alt="ASCII-Aquarium preview 2"></a>
  </details>
- **Networked LED Pixel Matrix Clock**: Retro pixel display that pulls notifications from Home Assistant, weather alerts, and custom on-device apps with MQTT/HTTP support. [awtrix-ng](https://github.com/Blueforcer/awtrix-ng)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/Blueforcer/awtrix-ng"><img src="media/awtrix-ng.jpg" width="400" alt="awtrix-ng preview"></a>
  </details>
- **Battery-Efficient E-Ink Countdown Display**: Low-power countdown screen for Heltec Vision Master E213 (ESP32-S3) showing days remaining until a target date with Wi-Fi NTP time sync and deep sleep. [E-Ink-Countdown-Screen](https://github.com/Meandmybadself/E-Ink-Countdown-Screen)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/Meandmybadself/E-Ink-Countdown-Screen"><img src="media/E-Ink-Countdown-Screen.jpg" width="400" alt="E-Ink-Countdown-Screen preview"></a>
  </details>
- **Calm E-Ink Desk Dashboard**: Battery-friendly paper display for ESP32-C3 showing live weather, reminders, daily quotes, and productivity countdowns with browser setup. [inksight](https://github.com/datascale-ai/inksight)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/datascale-ai/inksight"><img src="media/inksight-1.jpg" width="400" alt="inksight preview 1"></a>
    <a href="https://github.com/datascale-ai/inksight"><img src="media/inksight-2.jpg" width="400" alt="inksight preview 2"></a>
  </details>
- **Self-Hosted E-Ink Travel Milestones Frame**: Digital world map and travel tracker on an 800x480 e-ink display driven by ESP32, highlighting visited countries and live weather. [TravelFrame](https://github.com/LJ545/TravelFrame)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/LJ545/TravelFrame"><img src="media/TravelFrame.jpg" width="400" alt="TravelFrame preview"></a>
  </details>

## 📖 E-Paper Readers & Digital Books

Build portable e-book readers, EPUB engines, and distraction-free digital paper devices.

<p align="left">
  <a href="https://github.com/Free-Ink/freeink-sdk"><img src="media/freeink-sdk-1.jpg" height="120" alt="freeink-sdk"></a>
</p>

- **Hardware-Independent E-Paper Reader & UI SDK**: Modular firmware framework and immediate-mode UI layer (FreeInkUI) for building e-paper book readers (FreeInkBook EPUB engine) across diverse ESP32 e-ink screens. [freeink-sdk](https://github.com/Free-Ink/freeink-sdk)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/Free-Ink/freeink-sdk"><img src="media/freeink-sdk-1.jpg" width="400" alt="freeink-sdk preview 1"></a>
    <a href="https://github.com/Free-Ink/freeink-sdk"><img src="media/freeink-sdk-2.jpg" width="400" alt="freeink-sdk preview 2"></a>
  </details>

## 🗣️ AI Voice Assistants & Communicators

Harness on-device audio and cloud intelligence for speech-driven hardware.

<p align="left">
  <a href="https://github.com/steveruizok/chat-stick"><img src="media/chat-stick.jpg" height="120" alt="chat-stick"></a>
  <a href="https://github.com/F86Pilot/familybox"><img src="media/familybox-1.jpg" height="120" alt="familybox"></a>
  <a href="https://github.com/Tsixom0/Tsixom-Watch-Buddy-for-waveshare-esp32-s3-2.06-touch-amoled"><img src="media/Tsixom-Watch-Buddy-2.jpg" height="120" alt="Tsixom-Watch-Buddy"></a>
</p>

- **Live Speech-to-Speech AI Assistant**: Handheld conversational voice assistant for M5StickS3 and other ESP32-S3 devices powered by Gemini Live API and Cloudflare Workers. [chat-stick](https://github.com/steveruizok/chat-stick)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/steveruizok/chat-stick"><img src="media/chat-stick.jpg" width="400" alt="chat-stick preview"></a>
  </details>
- **Family Photo & Voice Messenger for Kids**: Photo and voice communicator for Waveshare ESP32-S3 Touch AMOLED 1.8" letting parents and young children exchange photos and voice notes without text. [familybox](https://github.com/F86Pilot/familybox)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/F86Pilot/familybox"><img src="media/familybox-1.jpg" width="300" alt="familybox preview 1"></a>
    <a href="https://github.com/F86Pilot/familybox"><img src="media/familybox-2.jpg" width="400" alt="familybox preview 2"></a>
  </details>
- **AI-Powered Smartwatch**: Wearable companion combining voice interaction, cloud AI integration, a custom graphics engine, and power management. [Tsixom-Watch-Buddy](https://github.com/Tsixom0/Tsixom-Watch-Buddy-for-waveshare-esp32-s3-2.06-touch-amoled)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/Tsixom0/Tsixom-Watch-Buddy-for-waveshare-esp32-s3-2.06-touch-amoled"><img src="media/Tsixom-Watch-Buddy-1.gif" width="350" alt="Tsixom-Watch-Buddy preview 1"></a>
    <a href="https://github.com/Tsixom0/Tsixom-Watch-Buddy-for-waveshare-esp32-s3-2.06-touch-amoled"><img src="media/Tsixom-Watch-Buddy-2.jpg" width="400" alt="Tsixom-Watch-Buddy preview 2"></a>
  </details>

## 🎮 Handheld Gaming & Retro Emulation

Build pocket game consoles and relive vintage computers.

<p align="left">
  <a href="https://github.com/rhys101/Beebem-ESP32-S3"><img src="media/Beebem-ESP32-S3-1.jpg" height="120" alt="Beebem-ESP32-S3"></a>
  <a href="https://github.com/MikeWilson/esp32-gameos"><img src="media/gameos-1.jpg" height="120" alt="gameos"></a>
  <a href="https://github.com/MikeWilson/infinite-golf"><img src="media/infinite-golf-1.jpg" height="120" alt="infinite-golf"></a>
</p>

- **Classic 8-Bit Computer Emulation**: Port of the BeebEm emulator to run classic BBC Micro and Master 128 software on ESP32-S3. [Beebem-ESP32-S3](https://github.com/rhys101/Beebem-ESP32-S3)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/rhys101/Beebem-ESP32-S3"><img src="media/Beebem-ESP32-S3-1.jpg" width="400" alt="Beebem-ESP32-S3 preview 1"></a>
    <a href="https://github.com/rhys101/Beebem-ESP32-S3"><img src="media/Beebem-ESP32-S3-2.jpg" width="400" alt="Beebem-ESP32-S3 preview 2"></a>
  </details>
- **Bare-Metal Handheld Game OS**: Minimalist game OS and games for Waveshare ESP32-S3 Touch AMOLED 1.8" written in pure C on ESP-IDF with procedural audio and visuals. [gameos](https://github.com/MikeWilson/esp32-gameos)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/MikeWilson/esp32-gameos"><img src="media/gameos-1.jpg" width="350" alt="gameos preview 1"></a>
    <a href="https://github.com/MikeWilson/esp32-gameos"><img src="media/gameos-2.jpg" width="350" alt="gameos preview 2"></a>
  </details>
- **Procedural Mini-Golf Game**: Procedurally generated mini-golf game with touch aiming and physical swing motion controls. [infinite-golf](https://github.com/MikeWilson/infinite-golf)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/MikeWilson/infinite-golf"><img src="media/infinite-golf-1.jpg" width="350" alt="infinite-golf preview 1"></a>
    <a href="https://github.com/MikeWilson/infinite-golf"><img src="media/infinite-golf-2.jpg" width="350" alt="infinite-golf preview 2"></a>
  </details>

## 🏠 Smart Home Controllers & UI Dashboards

Give your smart home physical touchscreens and intuitive controls.

<p align="left">
  <a href="https://github.com/aaronbeckmann/ESP-DashboardPlus"><img src="media/ESP-DashboardPlus-1.jpg" height="120" alt="ESP-DashboardPlus"></a>
  <a href="https://github.com/sieren/HomePoint"><img src="media/HomePoint-1.jpg" height="120" alt="HomePoint"></a>
</p>

- **Real-Time Web Dashboard Library**: Responsive web dashboard library for ESP32 with WebSocket updates, 16+ customizable cards (charts, gauges, toggles), and built-in OTA. [ESP-DashboardPlus](https://github.com/aaronbeckmann/ESP-DashboardPlus)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/aaronbeckmann/ESP-DashboardPlus"><img src="media/ESP-DashboardPlus-1.jpg" width="400" alt="ESP-DashboardPlus preview 1"></a>
    <a href="https://github.com/aaronbeckmann/ESP-DashboardPlus"><img src="media/ESP-DashboardPlus-2.jpg" width="400" alt="ESP-DashboardPlus preview 2"></a>
  </details>
- **Touchscreen Smart Home Hub**: Screen-based interface and dashboard to control HomeKit and MQTT smart lights, switches, and scenes. [HomePoint](https://github.com/sieren/HomePoint)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/sieren/HomePoint"><img src="media/HomePoint-1.jpg" width="400" alt="HomePoint preview 1"></a>
    <a href="https://github.com/sieren/HomePoint"><img src="media/HomePoint-2.jpg" width="400" alt="HomePoint preview 2"></a>
  </details>

## 🚴 Outdoor, Sports & Live Trackers

Dedicated offline maps and telemetry for adventures and tracking.

<p align="left">
  <a href="https://github.com/vmalis/AirESP32ace"><img src="media/AirESP32ace-1.jpg" height="120" alt="AirESP32ace"></a>
  <a href="https://github.com/lspr98/bike-computer-32"><img src="media/bike-computer-32-1.jpg" height="120" alt="bike-computer-32"></a>
  <a href="https://github.com/HenrysCat/esp32-cyd-ham-dashboard"><img src="media/ESP32-CYD-HAM-Dashboard.jpg" height="120" alt="ESP32-CYD-HAM-Dashboard"></a>
  <a href="https://github.com/jgauchia/IceNav-v3"><img src="media/IceNav-v3-1.jpg" height="120" alt="IceNav-v3"></a>
  <a href="https://github.com/seichris/open-bike-computer"><img src="media/open-bike-computer-1.jpg" height="120" alt="open-bike-computer"></a>
</p>

- **Aviation, Satellite & Launch Radar**: Interactive live radar tracking aircraft flights, weather passes, and space rocket launches. [AirESP32ace](https://github.com/vmalis/AirESP32ace)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/vmalis/AirESP32ace"><img src="media/AirESP32ace-1.jpg" width="400" alt="AirESP32ace preview 1"></a>
    <a href="https://github.com/vmalis/AirESP32ace"><img src="media/AirESP32ace-2.jpg" width="400" alt="AirESP32ace preview 2"></a>
  </details>
- **Offline GPS Cycling Computer**: Handlebar mini-map based on ESP32-C3 rendering offline OpenStreetMap maps and GPX routes without internet. [bike-computer-32](https://github.com/lspr98/bike-computer-32)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/lspr98/bike-computer-32"><img src="media/bike-computer-32-1.jpg" width="400" alt="bike-computer-32 preview 1"></a>
    <a href="https://github.com/lspr98/bike-computer-32"><img src="media/bike-computer-32-2.jpg" width="400" alt="bike-computer-32 preview 2"></a>
  </details>
- **Ham Radio Station Monitor**: HamClock-inspired dashboard for ESP32 Cheap Yellow Display tracking callsigns, propagation, and solar weather. [ESP32-CYD-HAM-Dashboard](https://github.com/HenrysCat/esp32-cyd-ham-dashboard)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/HenrysCat/esp32-cyd-ham-dashboard"><img src="media/ESP32-CYD-HAM-Dashboard.jpg" width="400" alt="ESP32-CYD-HAM-Dashboard preview"></a>
  </details>
- **Multi-GNSS Offline GPS Navigator**: Standalone GPS navigation system with offline OpenStreetMap support (rendered tiles or vector maps), 3D perspective maps, and waypoint routing using LVGL. [IceNav-v3](https://github.com/jgauchia/IceNav-v3)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/jgauchia/IceNav-v3"><img src="media/IceNav-v3-1.jpg" width="400" alt="IceNav-v3 preview 1"></a>
    <a href="https://github.com/jgauchia/IceNav-v3"><img src="media/IceNav-v3-2.jpg" width="400" alt="IceNav-v3 preview 2"></a>
  </details>
- **Smart Garmin-Mounted Bike Computer**: Sleek open-source bike computer for Waveshare AMOLED touchscreens featuring Apple Maps turn-by-turn navigation, workout syncing to Apple Health, and sensor connectivity. [open-bike-computer](https://github.com/seichris/open-bike-computer)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/seichris/open-bike-computer"><img src="media/open-bike-computer-1.jpg" width="400" alt="open-bike-computer preview 1"></a>
    <a href="https://github.com/seichris/open-bike-computer"><img src="media/open-bike-computer-2.jpg" width="400" alt="open-bike-computer preview 2"></a>
  </details>

## 🎨 Creative Drawing & Acoustic Synthesis

Explore artistic expression and procedural sound generation.

<p align="left">
  <a href="https://github.com/sha5b/M5Stack-Lyrebird"><img src="media/M5Stack-Lyrebird-1.jpg" height="120" alt="M5Stack-Lyrebird"></a>
  <a href="https://github.com/aliceisjustplaying/tinydraw"><img src="media/TinyDraw-1.jpg" height="120" alt="TinyDraw"></a>
</p>

- **Synthesized Bird Song Chorus**: Pocket dawn chorus synthesizing 2423 songbird species natively on-device via acoustic physical modeling. [M5Stack-Lyrebird](https://github.com/sha5b/M5Stack-Lyrebird)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/sha5b/M5Stack-Lyrebird"><img src="media/M5Stack-Lyrebird-1.jpg" width="400" alt="M5Stack-Lyrebird preview 1"></a>
    <a href="https://github.com/sha5b/M5Stack-Lyrebird"><img src="media/M5Stack-Lyrebird-2.jpg" width="400" alt="M5Stack-Lyrebird preview 2"></a>
  </details>
- **Touchscreen Sketching & Pixel Art Studio**: Pocket digital sketchbook with pressure support, layer management, and image export. [TinyDraw](https://github.com/aliceisjustplaying/tinydraw)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/aliceisjustplaying/tinydraw"><img src="media/TinyDraw-1.jpg" width="350" alt="TinyDraw preview 1"></a>
    <a href="https://github.com/aliceisjustplaying/tinydraw"><img src="media/TinyDraw-2.jpg" width="350" alt="TinyDraw preview 2"></a>
  </details>

## 🔐 Hardware Security & Private Data Vaults

Protect secrets with offline dedicated hardware.

<p align="left">
  <a href="https://github.com/Northstrix/Midbar"><img src="media/Midbar.jpg" height="120" alt="Midbar"></a>
</p>

- **Air-Gapped Encrypted Password & Data Vault**: Advanced hardware data vault designed to maximize security against unauthorized access to personal data. [Midbar](https://github.com/Northstrix/Midbar)
  <details>
    <summary>🖼️ Preview</summary>
    <br>
    <a href="https://github.com/Northstrix/Midbar"><img src="media/Midbar.jpg" width="400" alt="Midbar preview"></a>
  </details>

# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## ESP32 Awesome Lists

- [s0lness/awesome-esp32](https://github.com/s0lness/awesome-esp32) - Hand-picked ESP32 projects worth building, copying, or watching run.

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work under [CC0 1.0 Universal](LICENSE).
