# HTML Projects Collection

A collection of various HTML/JS experiments and small applications.

## Directory Structure
**main link is [here](https://hajun-jang.github.io/html-file/).**

- **[matrix/](./matrix/)**: Various implementations of the "Matrix Rain" visual effect.
  - [index.html](./matrix/index.html) / [ascii.html](./matrix/ascii.html): Classic Matrix rain using ASCII characters.
  - [modern-rain.html](./matrix/modern-rain.html): A high-performance version with Unicode characters and fade effect.
  - [unicode.html](./matrix/unicode.html): Matrix rain using a wide range of international Unicode characters.
- **[countdown/](./countdown/)**: Time-related countdown applications.
  - [index.html](./countdown/index.html) / [new-year-countdown.html](./countdown/new-year-countdown.html): A clean, responsive countdown timer for the upcoming New Year.
- **[music/](./music/)**: Musical experiments using the Web Audio API.
  - [index.html](./music/index.html) / [pi-song.html](./music/pi-song.html): An interactive application translating digits of Pi into melodies and chords.
  - [interactive-pi-melody.html](./music/interactive-pi-melody.html): Advanced interactive piano visualizer.
- **[test/](./test/)**: Playgrounds for minor test cases.
  - [index.html](./test/index.html) / [font-test.html](./test/font-test.html): A simple utility to check font rendering and system font availability.
- **[tycoon/](./tycoon/)**: Simulation and management tycoon games.
  - **[cafe/](./tycoon/cafe/)**: Pixel Brew Café simulation.
    - [index.html](./tycoon/cafe/index.html): Premium Coffee Shop Tycoon with local storage saving, audio synthesis, and admin command panel.
  - **[factory/](./tycoon/factory/)**: 3D Automation Factory Tycoon.
    - [index.html](./tycoon/factory/index.html): 3D custom grid-placement automation simulation using WebGL (Three.js), fluid pipes, and wireless energy relay systems.
  - **[hacknet/](./tycoon/hacknet/)**: Real-Time Shared Cooperative Hacknet Tycoon.
    - [index.html](./tycoon/hacknet/index.html): The main game board page (root path, automatically redirects to nested login if unauthenticated). Supports local offline mode by default, and upgrades to online multiplayer sync via the in-game settings gear.
    - [login/index.html](./tycoon/hacknet/login/index.html): Parameterized secure gateway authentication terminal for general users and the admin.
    - [signup/index.html](./tycoon/hacknet/signup/index.html): Registration interface supporting matching password validation and auto-login redirecting.

## How to Run

Simply open any of the `.html` files in a modern web browser, or host them statically on services like GitHub Pages.
For the **Hacknet Tycoon**, the game runs in single-player offline mode by default. To connect with peers, click the gear icon in the top right to configure your Supabase endpoint.
