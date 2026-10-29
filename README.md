<p align="center">
  <img src="banner.svg" alt="Nilton Barroso Carvalho" width="100%">
</p>

## Yo Family 🫂

I'm Nilton, application developer in training from Bern. I like turning ideas into apps that actually run on a real phone, and I care more about *does it work* than about how many frameworks I can list.

```ts
const nilton = {
  location: "Bern, Switzerland",
  training: "Informatiker EFZ Applikationsentwicklung + Berufsmaturität",
  school: ["IMS bwd Bern", "gibb"],
  favouriteStack: ["TypeScript", "React", "React Native"],
  alsoWorkedWith: ["C#", ".NET MAUI", "Flutter", "Node.js"],
  currentlyBuilding: "Pulsolux",
  nextStep: "internship year from August 2027",
  speaks: ["pt", "de", "en", "fr", "es"],
};
```

---

## ⭐ Spotlight: Geo-Kick

**Play for real. Rise virtually.** A football game for Android where you check in at real pitches near you, collect players and lead your own club from Division 4 up to Division 1.

<p align="center">
  <img src="geo-kick-gallery.png" alt="Geo-Kick screenshots" width="100%">
</p>

- 📍 **GPS check-in** at real pitches from OpenStreetMap, only within a 100 m radius
- 🛡️ **Anti-cheat**: geofencing, fake-location detection and a motion sensor check
- 🃏 **Packs, squad and tactics** with formations, chemistry and a simulated league
- 📴 **Offline-first**: all game data lives on the phone, only the leaderboard goes online
- 🧪 **Tested game logic**: a script with 50+ automatic checks for rewards, schedules and simulation
- 🔨 **100+ commits** in about one month, built as my own project next to school

[**Repository**](https://github.com/notling09/Geo-Kick) · [**Download for Android**](https://geo-kick.vercel.app/)

<details>
<summary><b>How it's built</b></summary>
<br>

```mermaid
flowchart LR
    GPS[GPS + motion sensor] --> CI[Check-in & anti-cheat]
    OSM[OpenStreetMap / Overpass] --> MAP[Map with pitches]
    MAP --> CI
    CI --> STORE[Game state · Zustand]
    STORE <--> DB[(SQLite on the phone)]
    STORE --> ENGINE[Game engine: packs, league, match simulation]
    STORE -. only the leaderboard .-> SB[(Supabase)]
```

React Native · Expo · TypeScript · Zustand · SQLite · MapLibre · Supabase

</details>

---

## 🔬 Right now: Pulsolux

A Flutter app that **measures your pulse with the smartphone camera**. Put your finger on the camera and flash, and the app reads the tiny changes in brightness with every heartbeat (photoplethysmography).

- Signal filtered with a 0.7–3.5 Hz band-pass, then peak detection, double-checked with an FFT
- Two modes: flash (reflection) or an external light (transmission)
- No internet, no diagnosis: all data stays on the phone
- Tested on Samsung S25 and iPhone 17 Pro, about 1–6 bpm off in first tests
- Next up: a measurement series with ~15 people against a pulse oximeter

Built as our IDPA at the IMS with Cat Tuong Nguyen and Luis Rosado.

---

## 🧭 My path so far

| When | What |
|---|---|
| **2024** | Started the IMS: application development + Berufsmaturität |
| **2025** | First apps in C#: a Snake game and a recipe app with .NET MAUI |
| **2026** | Full-stack web apps with React, Express and SQLite at school |
| **Summer 2026** | Built Geo-Kick, 100+ commits in about a month |
| **Autumn 2026** | Pulsolux, pulse measurement with the phone camera |
| **August 2027** | Internship year 🚀 |

<details>
<summary><b>📚 School projects</b></summary>
<br>

| Project | What it is | Stack |
|---|---|---|
| [2XKO Combo Trainer](https://github.com/notling09/2XKO-Timing-Trainer) | Build, save and practise fighting game combos with a timing trainer | React, TypeScript, Vite |
| [How to Survive](https://github.com/notling09/HowToSurvive-DaysOfTheWeek) | Full-stack app with login where users write and like tips for every weekday | React, Express, SQLite, JWT |
| [EnerGym](https://github.com/notling09/EnerGym) | Fitness tracker with progress charts, badges and a REST API | React, TypeScript, Express, SQLite |
| [CookEasy PT](https://github.com/notling09/CookEasyPT) | Recipe app for Portuguese dishes with favourites and a shopping list | C#, .NET MAUI |
| [Snake: Jungle Edition](https://github.com/notling09/SnakeGame-Jungle-Edition) | Classic Snake game for Windows | C#, WinForms |

</details>

---

## 🛠️ Tech

![TypeScript](https://img.shields.io/badge/TypeScript-7C3AED?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-7C3AED?style=flat-square&logo=javascript&logoColor=white)
![React](https://img.shields.io/badge/React-7C3AED?style=flat-square&logo=react&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-7C3AED?style=flat-square&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-7C3AED?style=flat-square&logo=expo&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-7C3AED?style=flat-square&logo=flutter&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-7C3AED?style=flat-square&logo=nodedotjs&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-7C3AED?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-7C3AED?style=flat-square&logo=supabase&logoColor=white)
![C#](https://img.shields.io/badge/C%23-7C3AED?style=flat-square&logo=dotnet&logoColor=white)
![Git](https://img.shields.io/badge/Git-7C3AED?style=flat-square&logo=git&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-7C3AED?style=flat-square&logo=claude&logoColor=white)

## ⚽ Fun facts

- I built a football game because I love football, so testing it means going outside to play
- I speak five languages: Portuguese, German, English, French and Spanish
- My favourite part of coding is the moment a bug finally makes sense

## 📫 Contact

[![Website](https://img.shields.io/badge/niltonbc.ch-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://niltonbc.ch)
