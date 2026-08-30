<div align="center">

# Clash in Space

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![pygame-ce](https://img.shields.io/badge/Library-pygame--ce-1D9BF0?logo=pygame&logoColor=white)
![Web](https://img.shields.io/badge/Target-Web%20Assembly-654FF0)
![GitHub Actions](https://img.shields.io/badge/CI-GitHub%20Actions-2088FF?logo=github-actions&logoColor=white)
[![pygbag_build](https://github.com/ShivamKR12/Clash-in-Space-Web/actions/workflows/pygbag.yml/badge.svg)](https://github.com/ShivamKR12/Clash-in-Space-Web/actions/workflows/pygbag.yml)
![License](https://img.shields.io/badge/License-MIT-green.svg)

</div>

A classic arcade-style space shooter game built with Python and Pygame Community Edition, optimized for the web. Dodge and destroy asteroids, fight for the high score!

<div align="center">
  <img src="screenshots/1.png" alt="Gameplay Screenshot" width="600">
</div>

## 🚀 Features

*   Classic top-down space shooter gameplay.
*   Engaging sound effects and background music.
*   Explosive visual effects.
*   Persistent high scores tracking across sessions.
*   Playable directly in the web browser.

## 🎮 Play Now

You can easily play the game directly in your web browser!

1.  Go to the [**Clash in Space - Web**](https://ShivamKR12.github.io/Clash-in-Space-Web) page.
2.  Wait for the assets to load and enjoy the game!

## 🕹️ How to Play

*   **Arrow Keys/WASD:** Move your ship.
*   **Spacebar:** Fire lasers.
*   **Escape:** Pause/Quit the game.

## 🛠️ Building From Source

If you want to run or build the game yourself, you'll need Python 3 and some dependencies.

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/ShivamKR12/Clash-in-Space-Web.git
    cd Clash-in-Space-Web
    ```

2.  **Create a virtual environment (recommended):**
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    ```sh
    pip install pygame-ce pygbag
    ```

4.  **Run the game locally:**
    ```sh
    python main.py
    ```

5.  **Build for the Web:**
    This project uses `pygbag` to build the Python code for a web-based environment.
    ```sh
    python -m pygbag --build main.py
    ```
    This will create a `build/web` directory containing the necessary files. You can test it locally using a web server or `python -m pygbag main.py`.

## ⚙️ Continuous Deployment

The project is configured with a GitHub Actions workflow (`.github/workflows/pygbag.yml`) that automatically builds and deploys the game to GitHub Pages.

A push to the `main` branch will trigger the workflow, which builds the application and pushes the contents of the `build/web` directory to the `gh-pages` branch.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
