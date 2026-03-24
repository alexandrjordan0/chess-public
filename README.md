# Chess Mobile Application

**Author:** Alexandr Jordán

A native Android chess application optimized for offline play. Built with Kotlin and Jetpack Compose, it features a clean UI, full chess rules implementation, and a dual-engine AI system.

> Achievement: 2nd place in the Olomouc Region SOČ competition, IT category

---

## Key Features

* **Game Modes:**

  * Offline 1v1 on a single device (with custom piece rotation for face-to-face play)
  * Single-player against bots

* **Dual AI System:**

  * Level 1: Custom heuristic evaluation bot
  * Levels 2+: Integration of the advanced **Karballo Chess Engine** via UCI protocol

* **Full Mechanics:**

  * En Passant
  * Castling
  * Pawn Promotion
  * Strict rule enforcement:

    * Checkmate
    * Stalemate
    * Threefold repetition
    * Insufficient material

* **Game Management:**

  * Configurable time controls
  * Move history tracking
  * PGN export

* **UI/UX:**

  * Fully responsive Jetpack Compose UI
  * Dark/Light themes
  * English/Czech localization

---

## Tech Stack

* **Language:** Kotlin
* **UI:** Jetpack Compose
* **Architecture & Tools:** MVVM, Coroutines, SharedPreferences

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/alexandrjordan/ChessPublic.git
cd ChessPublic
```

Open the root directory in **Android Studio** (Flamingo 2022.2.1 or newer).

> Avoid diacritics in the project path to prevent Gradle and Android SDK build issues.

---

## Karballo Chess Engine

This project utilizes the **Karballo Chess Engine** by Alberto Alonso Ruibal, licensed under the MIT License.

```
Copyright (c) 2017 Alberto Alonso Ruibal

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
