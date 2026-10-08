# 🌍 STD Track — Realtime Radar Frontend (Vercel Ready)

Modern, tactical real-time transport radar dashboard for tracking Airplanes ✈️, Trains 🚆, Ships 🚢, Buses 🚌, and Cars 🚗.

---

## ⚡ Features
- **Dark Radar Map:** Powered by Leaflet & CartoDB Dark Matter.
- **WebSocket Streaming:** Connects to FastAPI backend (`/ws/telemetry`) on Heroku or Render with automatic failover to local engine.
- **OpenSky ADS-B API:** Ingests live commercial flight transponders.
- **Full Telemetry Drawer:** Speed, altitude, heading, route progress, fuel, and transponder info.
- **Lock Camera & Route Trails:** Follow any moving vehicle smoothly.

---

## 🚀 Deploy on Vercel (1-Click)

1. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **"Add New Project"**.
3. Select the repository **`LuciferRJ29/std-track-frontend`**.
4. Framework Preset will be automatically detected as **Vite** / Static HTML.
5. Click **"Deploy"**!

Within ~15 seconds, your website will be live at `https://std-track-frontend.vercel.app` (or your custom domain).

---

## 🛠️ Local Development

```bash
# 1. Open index.html directly in browser
# OR
npm install
npm run dev
```
