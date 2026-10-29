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
  strongestAt: ["HTML", "CSS", "JavaScript", "SQL"],
  alsoWorkedWith: ["Flutter", "Dart", "Node.js", "C#", ".NET MAUI"],
  currentlyBuilding: "Pulsolux",
  nextStep: "internship year at SBV from August 2027",
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

## 💜 Built for my sister: Momento

My sister Dalila and three of her classmates wrote a full business plan for a memories app. It stayed on paper, so I built it. **Momento** saves not just a photo but the whole moment: the place, the people, the feeling, the scent and the sound.

<table>
<tr>
<td width="32%" valign="top">
  <img src="momento.jpg" alt="Momento screenshot" width="100%">
</td>
<td valign="top">

- 📱 **One codebase** for Android, iOS and the web, built with Flutter and Dart
- 🎙️ **Real sounds**: record the moment directly with the microphone
- 🔒 **No server**: all data stays on the device
- 🔎 **Smart search** that understands synonyms and seasons and forgives typos
- 🧪 **~12,600 lines**, 54 files and 59 tests, in German and English, light and dark mode
- 🧠 **Three things I changed on purpose**: no ID photo at sign-up (Swiss data protection), scents from a palette instead of "measured", and no videos so the storage doesn't explode

Their idea, my code. Their names are in the app.

[**Website**](https://momento.niltonbc.ch): try it in your browser or download the app

</td>
</tr>
</table>

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
| **Autumn 2026** | Momento, my sister's business plan turned into a real app |
| **Autumn 2026** | Pulsolux, pulse measurement with the phone camera |
| **August 2027** | Internship year at **SBV** 🚀 |

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

![HTML5](https://img.shields.io/badge/HTML5-7C3AED?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-7C3AED?style=flat-square&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-7C3AED?style=flat-square&logo=javascript&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-7C3AED?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-7C3AED?style=flat-square&logo=react&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-7C3AED?style=flat-square&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-7C3AED?style=flat-square&logo=expo&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-7C3AED?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-7C3AED?style=flat-square&logo=dart&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-7C3AED?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-7C3AED?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-7C3AED?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-7C3AED?style=flat-square&logo=sqlite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-7C3AED?style=flat-square&logo=supabase&logoColor=white)
![C#](https://img.shields.io/badge/C%23-7C3AED?style=flat-square&logo=dotnet&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-7C3AED?style=flat-square&logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7C3AED?style=flat-square&logo=vite&logoColor=white)
![Git](https://img.shields.io/badge/Git-7C3AED?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-7C3AED?style=flat-square&logo=visualstudiocode&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-7C3AED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-7C3AED?style=flat-square&logo=vercel&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-7C3AED?style=flat-square&logo=claude&logoColor=white)

## ⚽ Fun facts

- I built a football game because I love football, so testing it means going outside to play
- Big Benfica fan 🦅 and yes, I built a website for them too
- My portfolio has Portuguese azulejo tiles in the design, because that's where my roots are
- I speak five languages: Portuguese, German, English, French and Spanish
- I once tried to build my own little operating system (DoorSystem96). It had way too many bugs in the end, and it taught me more than any project that worked
- My favourite part of coding is the moment a bug finally makes sense

## 📫 Contact

[![Website](https://img.shields.io/badge/niltonbc.ch-7C3AED?style=for-the-badge&logo=googlechrome&logoColor=white)](https://niltonbc.ch)
[![Email](https://img.shields.io/badge/niltonbcarvalho09@gmail.com-7C3AED?style=for-the-badge&logo=gmail&logoColor=white)](mailto:niltonbcarvalho09@gmail.com)
