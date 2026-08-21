# Awesome ESP32 [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated collection of awesome ESP32 projects, inspiring builds, frameworks, and tools organized by real-world use cases.

[ESP32](https://www.espressif.com/en/products/socs/esp32) is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and dual-mode Bluetooth created by Espressif Systems.

# Content

- [Official Resources](#official-resources)
- [Projects & Inspiration](#projects--inspiration)
  - [🎤 Presentation Remotes & Productivity Tools](#-presentation-remotes--productivity-tools)
  - [🐱 Virtual Pets, Fidgets & Interactive Toys](#-virtual-pets-fidgets--interactive-toys)
  - [🕒 Desk Companions, Smart Clocks & Ambient Displays](#-desk-companions-smart-clocks--ambient-displays)
  - [🗣️ AI Voice Assistants & Communicators](#️-ai-voice-assistants--communicators)
  - [🎮 Handheld Gaming & Retro Emulation](#-handheld-gaming--retro-emulation)
  - [🏠 Smart Home Controllers & UI Dashboards](#-smart-home-controllers--ui-dashboards)
  - [🚴 Outdoor, Sports & Live Trackers](#-outdoor-sports--live-trackers)
  - [🎨 Creative Drawing & Acoustic Synthesis](#-creative-drawing--acoustic-synthesis)
  - [🔐 Hardware Security & Private Data Vaults](#-hardware-security--private-data-vaults)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)
- [License](#license)

# Official Resources

- [Espressif ESP32 Official Page](https://www.espressif.com/en/products/socs/esp32) - Official product landing page.
- [ESP-IDF Documentation](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/) - Official Espressif IoT Development Framework documentation.
- [Espressif GitHub Organization](https://github.com/espressif) - Official open-source repositories from Espressif Systems.

# Projects & Inspiration

## 🎤 Presentation Remotes & Productivity Tools

Turn a pocket-sized development board into a reliable presentation clicker or input gadget.

- **Slide Clicker Remote for Talks & Lectures**: Use an M5Stick as a Bluetooth BLE keyboard remote to advance slides on Google Slides, PowerPoint, or Keynote with on-screen button guides and battery status. [m5stickc-plus-presenter](https://github.com/F86Pilot/m5stickc-plus-presenter)

## 🐱 Virtual Pets, Fidgets & Interactive Toys

Create pocket companions, physical party games, and physics-driven desk toys.

- **Physical Party Throw-and-Catch Game**: A hot-potato style party game for Waveshare ESP32-S3 Touch AMOLED 2.06" that detects freefall when tossed and stops random numbers when caught. [67](https://github.com/canwar-dj/67)
- **Unique Silicon-Generated Digital Pet**: Procedural companion for M5StickC Plus whose identity, personality, and doodle art style are permanently tied to the chip's unique MAC address with boiling-line animation. [doodlesoul](https://github.com/evandroguedes/doodlesoul)
- **Interactive 2D Fluid & Particle Physics Box**: Sensory fidget simulation where fluid and gravity react to touch and device tilt in real time. [esp32-fluidbox](https://github.com/V4C38/esp32-fluidbox)
- **Schedule-Aware Desk Pet Cat**: Animated pixel-art cat for ESP32-S3 AMOLED boards that learns your daily routines and schedules to seek attention when you are around. [pixelcat](https://github.com/toddsherman/pixelcat)
- **Step-Counting Virtual Pet Watch**: Pocket-Pikachu-inspired companion for Waveshare ESP32-S3 Touch AMOLED 2.06" that levels up and walks through fields as you log real physical steps. [pocket-pet](https://github.com/frolic/pocket-pet)

## 🕒 Desk Companions, Smart Clocks & Ambient Displays

Build glanceable screens that live on your desk without causing screen fatigue.

- **Animated ASCII Fish Tank Clock**: Whimsical retro aquarium and clock for ESP32 Cheap Yellow Display (CYD) boards featuring touch feeding, live creature simulation, and Wi-Fi NTP time sync. [ASCII-Aquarium](https://github.com/POWER-PILL/ASCII-Aquarium)
- **Networked LED Pixel Matrix Clock**: Retro pixel display that pulls notifications from Home Assistant, weather alerts, and custom on-device apps with MQTT/HTTP support. [awtrix-ng](https://github.com/Blueforcer/awtrix-ng)
- **Calm E-Ink Desk Dashboard**: Battery-friendly paper display for ESP32-C3 showing live weather, reminders, daily quotes, and productivity countdowns with browser setup. [inksight](https://github.com/datascale-ai/inksight)

## 🗣️ AI Voice Assistants & Communicators

Harness on-device audio and cloud intelligence for speech-driven hardware.

- **Live Speech-to-Speech AI Assistant**: Handheld conversational voice assistant for M5StickS3 and other ESP32-S3 devices powered by Gemini Live API and Cloudflare Workers. [chat-stick](https://github.com/steveruizok/chat-stick)
- **Family Photo & Voice Messenger for Kids**: Photo and voice communicator for Waveshare ESP32-S3 Touch AMOLED 1.8" letting parents and young children exchange photos and voice notes without text. [familybox](https://github.com/F86Pilot/familybox)
- **AI-Powered Smartwatch**: Wearable companion combining voice interaction, cloud AI integration, a custom graphics engine, and power management. [Tsixom-Watch-Buddy](https://github.com/Tsixom0/Tsixom-Watch-Buddy-for-waveshare-esp32-s3-2.06-touch-amoled)

## 🎮 Handheld Gaming & Retro Emulation

Build pocket game consoles and relive vintage computers.

- **Classic 8-Bit Computer Emulation**: Port of the BeebEm emulator to run classic BBC Micro and Master 128 software on ESP32-S3. [Beebem-ESP32-S3](https://github.com/rhys101/Beebem-ESP32-S3)
- **Bare-Metal Handheld Game OS**: Minimalist game OS and games for Waveshare ESP32-S3 Touch AMOLED 1.8" written in pure C on ESP-IDF with procedural audio and visuals. [gameos](https://github.com/MikeWilson/esp32-gameos)
- **Procedural Mini-Golf Game**: Procedurally generated mini-golf game with touch aiming and physical swing motion controls. [infinite-golf](https://github.com/MikeWilson/infinite-golf)

## 🏠 Smart Home Controllers & UI Dashboards

Give your smart home physical touchscreens and intuitive controls.

- **Real-Time Web Dashboard Library**: Responsive web dashboard library for ESP32 with WebSocket updates, 16+ customizable cards (charts, gauges, toggles), and built-in OTA. [ESP-DashboardPlus](https://github.com/aaronbeckmann/ESP-DashboardPlus)
- **Touchscreen Smart Home Hub**: Screen-based interface and dashboard to control HomeKit and MQTT smart lights, switches, and scenes. [HomePoint](https://github.com/sieren/HomePoint)

## 🚴 Outdoor, Sports & Live Trackers

Dedicated offline maps and telemetry for adventures and tracking.

- **Aviation, Satellite & Launch Radar**: Interactive live radar tracking aircraft flights, weather passes, and space rocket launches. [AirESP32ace](https://github.com/vmalis/AirESP32ace)
- **Offline GPS Cycling Computer**: Handlebar mini-map based on ESP32-C3 rendering offline OpenStreetMap maps and GPX routes without internet. [bike-computer-32](https://github.com/lspr98/bike-computer-32)
- **Ham Radio Station Monitor**: HamClock-inspired dashboard for ESP32 Cheap Yellow Display tracking callsigns, propagation, and solar weather. [ESP32-CYD-HAM-Dashboard](https://github.com/HenrysCat/esp32-cyd-ham-dashboard)

## 🎨 Creative Drawing & Acoustic Synthesis

Explore artistic expression and procedural sound generation.

- **Synthesized Bird Song Chorus**: Pocket dawn chorus synthesizing 2423 songbird species natively on-device via acoustic physical modeling. [M5Stack-Lyrebird](https://github.com/sha5b/M5Stack-Lyrebird)
- **Touchscreen Sketching & Pixel Art Studio**: Pocket digital sketchbook with pressure support, layer management, and image export. [TinyDraw](https://github.com/aliceisjustplaying/tinydraw)

## 🔐 Hardware Security & Private Data Vaults

Protect secrets with offline dedicated hardware.

- **Air-Gapped Encrypted Password & Data Vault**: Advanced hardware data vault designed to maximize security against unauthorized access to personal data. [Midbar](https://github.com/Northstrix/Midbar)

# Other Awesome Lists

Other amazingly awesome lists can be found in the [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) list.

## ESP32 Awesome Lists

- [s0lness/awesome-esp32](https://github.com/s0lness/awesome-esp32) - Hand-picked ESP32 projects worth building, copying, or watching run.

# Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related or neighboring rights to this work under [CC0 1.0 Universal](LICENSE).
