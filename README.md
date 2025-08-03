# Linux Resource Monitor

## Project Overview

This Python-based desktop application provides real-time monitoring of key system resources on Linux. It includes graphical interfaces for CPU, memory, GPU, and I/O monitoring, built using `tkinter`. The project separates back-end data collection logic from GUI display components for modularity and extensibility.

## Features

- View real-time CPU usage, process count, and load average
- Monitor RAM and swap memory usage
- GPU monitoring support (where available)
- I/O activity tracking (disk reads/writes, etc.)
- Modular GUI windows for each subsystem
- Uses `tkinter` for lightweight GUI rendering

## Folder Structure

> The `__pycache__/` directory is automatically generated and should not be edited.

## Requirements

- Python 3.10 or higher
- tkinter (usually included with standard Python installs)
- Optional: psutil (if used for system metrics)

Install dependencies

    pip install psutil

How to Run

    python main.py

# Notes
The tool is optimized for Linux-based systems.

GPU monitoring will only work on systems with supported drivers/tools installed.

You may need to grant certain permissions to access system-level data.
