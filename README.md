# Popcorn Game — C++ / WinAPI

A native Windows 2D arcade game prototype developed using **C++**, **Win32 API**, and **Windows GDI** as part of a guided programming course.

The project focuses on understanding native Windows application development, event-driven programming, and low-level graphical rendering without third-party GUI frameworks.

## Features

- Native Windows application using Win32 API
- Custom window creation and message processing
- Keyboard input handling
- Timer-based game events
- 2D graphics rendering using Windows GDI
- Interactive paddle movement
- Brick-based game level
- Graphics transformations and screen repainting

## Technologies

- C++
- Win32 API (Windows API)
- Windows GDI
- Microsoft Visual Studio / MSVC
- Event-Driven Programming

## Windows API Concepts

The project demonstrates practical usage of:

- `CreateWindowW` and `RegisterClassExW` — creating and registering application windows
- `WndProc` — processing Windows messages
- `GetMessage`, `TranslateMessage`, `DispatchMessage` — implementing the Windows message loop
- `WM_PAINT` — handling graphical updates
- `WM_KEYDOWN` — processing keyboard input
- `WM_TIMER` — handling timer events
- `HDC`, `HPEN`, `HBRUSH` — working with GDI resources
- `InvalidateRect` — requesting window repainting

## Project Structure

The project includes C++ source files, header files, and a Microsoft Visual Studio solution.

## Building and Running

1. Open the `.sln` solution in Microsoft Visual Studio.
2. Select a supported Windows build configuration.
3. Build the solution.
4. Run the application.

**Platform:** Windows.

## Project Background

This project was developed while following a C++ WinAPI programming course to gain practical experience with native Windows development.

It is an educational prototype, not a complete commercial game.

## Author

**Vladislav Churakov**

GitHub: https://github.com/Vladislav-Churakov
