<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:191b1c%2C100:2c4b8c&text=Bobby%20Huang&fontColor=f6f6f3&fontSize=44&fontAlignY=38&desc=I%20build%20open-source%20tools%20and%20ship%20them%20far%20enough%20that%20somebody%20else%20can%20use%20them.&descAlignY=58&descSize=15&animation=fadeIn">
  <img alt="Bobby Huang" src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:e4e3dc,100:7fa0d8&text=Bobby%20Huang&fontColor=1a1c1a&fontSize=44&fontAlignY=38&desc=I%20build%20open-source%20tools%20and%20ship%20them%20far%20enough%20that%20somebody%20else%20can%20use%20them.&descAlignY=58&descSize=15&animation=fadeIn">
</picture>

[![Website](https://img.shields.io/badge/bobbyhuang.dev-2c4b8c?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMiAzMiI+PHN0eWxlPi5tYXJrLXRpbGUgeyBmaWxsOiAjZWRlZWVhOyBzdHJva2U6ICNkMGQxY2Q7IH0gICAgLm1hcmstcnVsZSB7IGZpbGw6ICMyYzRiOGM7IH0gICAgLm1hcmstYiB7IGZpbGw6ICMxYTFjMWE7IH0gIDwvc3R5bGU+PHJlY3QgY2xhc3M9Im1hcmstdGlsZSIgeD0iLjUiIHk9Ii41IiB3aWR0aD0iMzEiIGhlaWdodD0iMzEiIHJ4PSIyLjUiIC8+PHJlY3QgY2xhc3M9Im1hcmstcnVsZSIgeD0iNiIgeT0iMSIgd2lkdGg9IjIiIGhlaWdodD0iMzAiIC8+PHBhdGggY2xhc3M9Im1hcmstYiIgZD0iTTIwLjU0IDI4UTE5LjQzIDI4IDE4LjYxIDI3LjU3UTE3Ljc4IDI3LjE1IDE3LjI2IDI2LjM0UTE2LjczIDI1LjUzIDE2LjUgMjQuNEwxNS45NyAyM0wxNi42NiAyMi4xUTE2LjgyIDIyLjY5IDE3LjE0IDIzLjE0UTE3LjQ2IDIzLjU5IDE3Ljk0IDIzLjg0UTE4LjQxIDI0LjEgMTkuMDMgMjQuMVExOS45OCAyNC4xIDIwLjcyIDIzLjU1UTIxLjQ2IDIzIDIxLjg5IDIxLjkzUTIyLjMzIDIwLjg2IDIyLjMzIDE5LjMyUTIyLjMzIDE2Ljc4IDIxLjUgMTUuNzZRMjAuNjcgMTQuNzMgMTkuNDIgMTQuNzNRMTguODEgMTQuNzMgMTguMjEgMTUuMDRRMTcuNjIgMTUuMzQgMTcuMiAxNS44NVExNi43OCAxNi4zNSAxNi42NiAxNi45M0wxNi40OSAxNi4yNkwxNi42NiAxNS4xM1ExNy4wMSAxMy43NyAxNy41OCAxMi44MlExOC4xNSAxMS44NyAxOS4wNyAxMS4zNlEyMCAxMC44NSAyMS4zOCAxMC44NVEyMi44OSAxMC44NSAyNC4xNyAxMS44MVEyNS40NSAxMi43NyAyNi4yNCAxNC42NVEyNy4wMiAxNi41MyAyNy4wMiAxOS4zMVEyNy4wMiAyMS45OCAyNi4xNiAyMy45M1EyNS4zIDI1Ljg4IDIzLjg0IDI2Ljk0UTIyLjM3IDI4IDIwLjU0IDI4Wk0xMS45OCAyNy44VjRIMTYuNjZWMTIuMzFWMjMuMDFMMTYuNTMgMjMuODVMMTYuNDkgMjQuOTVMMTYuMjYgMjcuOFoiIC8+PC9zdmc+)](https://bobbyhuang.dev)
[![Email](https://img.shields.io/badge/Email-1a1c1a?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bobbyhuang.dev@gmail.com)
[![YouTube](https://img.shields.io/badge/YouTube-1a1c1a?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@itzmolder)

</div>

## About

My current focus is [**Intentum**](https://github.com/intentum-agent/intentum), an open-source
tool for building products with AI agents inside Pi. My broader interests are
**machine learning**, **OSINT**, and **AI agents**.

The projects below exist because I wanted the thing and it did not exist in the shape I wanted it.
The part I care about most is not the feature list. It is the release, the README, and the first
five minutes of using the thing.

## Projects

### [intentum](https://github.com/intentum-agent/intentum)

*A tool for building products with AI agents inside Pi. My current focus.*

One agent handles the design conversation, while a separate agent carries out the implementation in its own Git worktree. A controller manages project state, pausing, recovery, and integrating the result. It is still in active development, with the current milestone focused on making that workflow reliable with a single implementation agent.

### 🌅 [hourglow](https://github.com/bobbyhuang-dev/hourglow)

*A macOS wallpaper scheduler that follows the daylight.* [Website →](https://hourglow.bobbyhuang.dev)

macOS Tahoe stopped rotating its dynamic wallpapers through the day. HourGlow brings that back and generalises it: any number of time slots, each bound to a wallpaper, triggered by clock time, sunrise/sunset offsets, or solar phases. Sun times are computed on-device with the NOAA algorithm, so nothing touches the network.

`Swift 6.3` `SwiftUI` `zero dependencies` `< 5 MB`

### 🍅 [marzano](https://github.com/bobbyhuang-dev/marzano)

*A local-first task list with a built-in Pomodoro timer.* [Try it →](https://marzano.bobbyhuang.dev)

Tasks with due dates, colour-coded tags, and a Pomodoro timer credited to the task you pick. Runs entirely in the browser: no account, no server, no network calls. The timer is rebuilt from wall-clock time, so it survives reloads, backgrounded tabs, and a sleeping machine.

`React 19` `TypeScript` `Vite` `Tailwind v4` `Cloudflare Workers`

## Now

> updated 2026-09-05

1. **Focusing on Intentum**, making the handoff from a design conversation to implementation reliable, including pausing, recovering, and integrating changes.
2. **Learning ML from the mathematics up**, not from the framework down. Right now that means calculus and NumPy, so array code stops being something I copy and starts being something I can read.
3. **Keeping marzano and hourglow installable** by somebody who is not me. Releases, READMEs, onboarding.

## Toolbox

<div align="center">

![Swift](https://img.shields.io/badge/Swift-1a1c1a?style=flat-square&logo=swift&logoColor=F05138)
![TypeScript](https://img.shields.io/badge/TypeScript-1a1c1a?style=flat-square&logo=typescript&logoColor=3178C6)
![React](https://img.shields.io/badge/React-1a1c1a?style=flat-square&logo=react&logoColor=61DAFB)
![Astro](https://img.shields.io/badge/Astro-1a1c1a?style=flat-square&logo=astro&logoColor=BC52EE)
![Vite](https://img.shields.io/badge/Vite-1a1c1a?style=flat-square&logo=vite&logoColor=646CFF)
![Tailwind](https://img.shields.io/badge/Tailwind-1a1c1a?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-1a1c1a?style=flat-square&logo=cloudflareworkers&logoColor=F38020)
![Python](https://img.shields.io/badge/Python-1a1c1a?style=flat-square&logo=python&logoColor=3776AB)
![NumPy](https://img.shields.io/badge/NumPy-1a1c1a?style=flat-square&logo=numpy&logoColor=4DABCF)

</div>

<div align="center">

<sub>Friends: <a href="https://github.com/BenjaminD2023">@BenjaminD2023</a> · <a href="https://github.com/fzlzjerry">@fzlzjerry</a></sub>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:2c4b8c%2C100:191b1c&section=footer">
  <img alt="" src="https://capsule-render.vercel.app/api?type=waving&height=90&color=0:7fa0d8,100:e4e3dc&section=footer">
</picture>

</div>
