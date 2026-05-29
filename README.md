# MedVirtuso MRI Viewer

## Overview

MedVirtuso MRI Viewer is a customized medical imaging viewer developed by MedMarvel Software Solutions.

The application is based on the open-source MRIcroGL project by Chris Rorden and has been adapted to provide a simplified, clinician-friendly interface for viewing MRI scans.

This software is intended for research, educational, and development purposes.

---

## Features

### Current Interface

* Layer management
* Grayscale image display
* Opacity adjustment
* Crosshair controls
* Zoom controls
* Smooth rendering option
* Ruler display option

### Interface Simplifications

The following MRIcroGL components have been removed or hidden to create a cleaner workflow:

* Darkest intensity controls
* Brightest intensity controls
* Coordinate display fields
* 2D slice navigation buttons
* Orientation labels
* Advanced controls not required for routine viewing

---

## Project Structure

```text
MRIcroGL/
├── mainunit.pas
├── mainunit.lfm
├── MRIcroGL.lpi
├── MRIcroGL.lpr
├── PythonBridge/
├── Metal-Demos/
└── ...
```

---

## Build Requirements

### Software

* Lazarus IDE
* Free Pascal Compiler (FPC)
* Windows 10/11

### Build

Open:

MRIcroGL.lpi

in Lazarus and build the project.

Alternatively:

```powershell
C:\lazarus\lazbuild.exe MRIcroGL.lpi
```

---

## Running

After a successful build:

```powershell
.\MRIcroGL.exe
```

---

## Development Workflow

Branches:

* main — stable release branch
* tanishqa — UI and MedVirtuso customizations
* kanan_branch — collaborative development

---

## License and Attribution

MedVirtuso MRI Viewer incorporates MRIcroGL.

MRIcroGL Copyright (c) Chris Rorden.

Original project:

https://github.com/rordenlab/MRIcroGL

This software includes components distributed under their respective open-source licenses.

Please refer to the License menu within the application and the original MRIcroGL repository for licensing information.

---

## Developed By

MedMarvel Software Solutions

Version 1.0
