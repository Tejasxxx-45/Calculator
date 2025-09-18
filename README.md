# Super Calculator

**A swiss-army terminal + GUI utility** — calculator, converters, small file tools, simple editors, weather fetcher and a video player (audio included). Built in Python for local use.

---

## Introduction

Super Calculator is a single-file Python utility that bundles many small tools into one friendly (and rude) CLI: basic math, geometry (volumes & surface areas), unit converters, bitwise/programmer tools, data-size/temperature/energy converters, a sleep timer, browser opener, YouTube downloader, file manager & secure shredder, CPU/RAM monitor (GUI), Word/Excel/PPT simple GUI editors, a video player (VLC-backed, plays audio), a weather data fetcher (Open-Meteo), and a small game launcher helper.

It's intended to run locally on your machine (Windows/Linux) — **not** in limited online sandboxes like Programiz because many required system libraries are not available there.

---

## Features

- Basic math (add, sub, mul, div, pow, sqr, sqrt)
- Volume & surface area calculations (cube, cuboid, cylinder, cone, sphere)
- Unit converters (cm↔m, km↔m)
- Programmer calculator (bitwise ops, shifts, not)
- Integer representation (binary/hex/oct)
- Data size conversions (B, KB, MB, GB, TB)
- Temperature & energy converters
- Sleep timer (hh:mm:ss)
- Open a website in the default browser
- Download YouTube videos (via `yt_dlp`)
- File manager + secure shredder (overwrite & delete)
- CPU & RAM monitor (Tkinter GUI using `psutil`)
- Lightweight Word/Excel/PowerPoint editors (python-docx, openpyxl, python-pptx)
- Weather fetcher using Open-Meteo (via `openmeteo_requests` and caching)
- Video player with audio (uses VLC + `python-vlc`)
- Launch external games by path

Each feature is accessible from the main menu. The video player opens a file dialog and plays selected file via VLC; playback runs while your menu remains usable.

---

## Requirements

**System requirements**
- Python 3.8+ recommended
- VLC media player installed on the system (for video + audio playback)
  - Windows: https://www.videolan.org/vlc/
  - Linux: install via package manager (e.g. `sudo apt install vlc`)

**Python packages**

Below is a consolidated list of Python packages used by the program. Some are optional depending on which features you use.

```
python-vlc
opencv-python        # optional - used if you want OpenCV features
psutil
yt_dlp
python-docx          # `docx` module
openpyxl
python-pptx          # `pptx` module
requests_cache
pandas
openmeteo_requests
requests
```

> Note: `tkinter` is part of the standard library on most Python installations but may require separate OS packages (see Troubleshooting).

---

## Install (quick)
pip install python-vlc opencv-python psutil yt_dlp python-docx openpyxl python-pptx requests_cache pandas openmeteo_requests requests

## Contributing
We encourage updates and new ideas for this project!
If you have suggestions or want to contribute, please email me at tejaspratapsingh54@gmail.com — all suggestions will be considered.

Regards,
Tejas Pratap Singh


