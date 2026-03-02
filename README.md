# ezhuth (Qt 5.12)

**ezhuth** is a lightweight desktop screen writing tool developed for teaching purposes.
It allows writing and drawing directly on the screen during classes, presentations, and demonstrations.

This project is released as a **binary-only AppImage** to showcase the application while keeping the source code proprietary.

## Features

* Write directly on the desktop screen
* Designed for teaching and live explanations
* Lightweight and fast
* Built with Qt 5.12
* Distributed as AppImage (no installation required)
* Works on Linux systems running X11

## Why source code is not included

This application was created as a proprietary teaching tool.
Because of its intended usage, the source code cannot be made public.

This repository exists to demonstrate the project and provide the released binary.

## Requirements

* Linux system running X11
* AppImage support (usually available by default)

## Running

Make the AppImage executable:

```
chmod +x ezhuth.AppImage
```

Run:

```
./ezhuth.AppImage
```

## Notes

* Wayland is not supported (X11 only)
* No external Qt installation required
* All dependencies are bundled inside the AppImage

## Author

NewtronReal

## License

Binary release only.
All rights reserved.
