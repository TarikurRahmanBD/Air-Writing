# Air Writing

## Project Overview

**Air Writing** is a cyberpunk-style air drawing experience that lets you draw glowing red laser strokes using your hand movements. The application uses a webcam, OpenCV, and MediaPipe hand tracking to detect finger gestures and render dynamic neon effects in real time.

## How to Install & Run

Follow these steps to get the app running on Windows:

1. Open a PowerShell terminal.
2. Navigate to the project folder and the `AR` application directory:

```powershell
cd "F:\Code Test\Taha Shaikh\Air_-Writing-main\Air_-Writing-main\AR"
```

3. Create a Python virtual environment:

```powershell
python -m venv .venv
```

4. Activate the virtual environment:

```powershell
.\.venv\Scripts\Activate.ps1
```

5. Install the required dependencies:

```powershell
pip install -r requirements.txt
```

6. Run the application:

```powershell
python main2.py
```

> If the app is launched from the workspace root, use:
>
> `python .\AR\main2.py`

## Features

- **Real-time hand tracking** using MediaPipe
- **Air drawing controls** with finger gestures
- **Neon laser stroke rendering** with glow effects
- **Particle sparks and animated cursor** for enhanced visuals
- **Clear canvas gesture** using an open palm
- **Stroke move mode** using pinch gesture
- **Beginner-friendly UI** with on-screen HUD and instructions

## Controls

- **One finger up** → Draw mode
- **Open palm** → Clear the canvas
- **Pinch** → Select and move existing drawing
- **Q / ESC** → Quit the application

## About the Developer

**Tarikur Rahman**

- GitHub: https://github.com/tarikurrahmanbd
- Portfolio: https://yourtarikur.netlify.app/
- Social / Handle: tarikurrahman08
- Email: tarikurrahman2008@gmail.com

## License

This project is licensed under the **MIT License**.
