# ✈️ LookUp

> Never miss the aircraft flying above you.

LookUp is an Android application that detects aircraft approaching your location and notifies you before they pass overhead. Simply grant location permission, and LookUp continuously monitors nearby flights, displaying live flight information and sending timely notifications.

---

## 📱 Features

- ✈️ Live aircraft detection
- 🔔 Flight approach notifications
- 📍 Real-time GPS location tracking
- 🌍 Interactive map view
- 📊 Live flight information
- ⏱ Countdown until aircraft passes overhead
- 🚀 Background monitoring
- 🌙 Dark modern UI
- ⚡ Lightweight and fast

---

## Screenshots

| Dashboard | Notification | Map |
|------------|-------------|------|
| Add screenshot | Add screenshot | Add screenshot |

---

# Flight Information

LookUp displays:

- Flight Number
- Airline
- Altitude
- Speed
- Distance
- Estimated Time Until Overhead

Example

```
RYR80ZY

Ryanair

Altitude : 10,800 ft

Speed : 297 knots

Distance : 12 km

Passes overhead in 4 minutes
```

---

# How It Works

1. User opens the app.
2. Location permission is requested.
3. GPS location is obtained.
4. Nearby aircraft are fetched.
5. Flights are filtered based on your location.
6. The closest approaching aircraft is displayed.
7. A notification is sent before the aircraft passes overhead.

---

# Permissions

LookUp requires the following Android permissions.

| Permission | Purpose |
|------------|----------|
| Fine Location | Detect nearby aircraft |
| Coarse Location | Approximate location |
| Background Location | Continue monitoring in background |
| Notifications | Aircraft alerts |
| Foreground Service | Background monitoring |
| Receive Boot Completed | Restart monitoring after reboot |
| Vibrate | Notification vibration |

---

# Built With

- React Native
- Expo
- TypeScript
- Google Maps
- Android Foreground Service
- Expo Notifications
- Expo Location
- Expo Task Manager
- Expo Background Task

---

# Project Structure

```
LookUp
│
├── app
│   ├── (tabs)
│   ├── _layout.tsx
│
├── assets
│
├── src
│   ├── components
│   ├── hooks
│   ├── services
│   ├── tasks
│   ├── utils
│
├── android
│
├── app.json
├── eas.json
└── package.json
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/yourusername/LookUp.git
```

Install dependencies

```bash
npm install
```

Start Expo

```bash
npx expo start
```

Run Android

```bash
npx expo run:android
```

---

# Production Build

APK

```bash
eas build --platform android --profile preview
```

Android App Bundle

```bash
eas build --platform android --profile production
```

---

# Requirements

- Android 10+
- Internet connection
- GPS enabled
- Location permission

---

# Privacy

LookUp only uses your location to detect nearby aircraft.

The app:

- Does not sell your data.
- Does not collect personal information.
- Does not require account creation.
- Stores only local app settings.

---

# Roadmap

Upcoming features

- ⭐ Flight history
- ⭐ Flight radar mode
- ⭐ Aircraft photos
- ⭐ Airline information
- ⭐ Flight route visualization
- ⭐ Custom notification distance
- ⭐ Multiple nearby aircraft
- ⭐ Weather overlay
- ⭐ Widgets
- ⭐ Wear OS support
- ⭐ iOS version

---

# Known Limitations

- Background monitoring behavior depends on Android manufacturer battery optimization.
- Continuous GPS usage may increase battery consumption.
- Flight availability depends on third-party flight data providers.

---

# Contributing

Contributions, feature requests, and bug reports are welcome.

Feel free to fork the repository and submit a pull request.

---

# License

This project is licensed under the MIT License.

---

# Developer

**Vivek Reddy Kesavarapu**

Freak Codes

GitHub:
https://github.com/truly-vivek

---

# Support

If you encounter any issues or have suggestions, please open an issue on GitHub or contact the developer.

---

## ⭐ If you like LookUp

Give the repository a ⭐ on GitHub to support future development.
