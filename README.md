# [LaTeX4Ei](http://latex4ei.de)

Mitschriften und Formelsammlungen in LaTeX für Elektro- und Informationstechnik (TUM).

<!-- mdformat-toc start --slug=github --no-anchors --maxlevel=6 --minlevel=2 -->

- [Mitarbeiten](#mitarbeiten)
- [Formelsammungen](#formelsammungen)
  - [Allgemein](#allgemein)
  - [1. Semester](#1-semester)
  - [2. Semester](#2-semester)
  - [3. Semester](#3-semester)
  - [4. Semester](#4-semester)
  - [Externe Formelsammlungen](#externe-formelsammlungen)
- [Formelsammlungen für Latex4ei](#formelsammlungen-f%C3%BCr-latex4ei)
- [Optional: Build with CMake](#optional-build-with-cmake)
  - [Steps to build](#steps-to-build)

<!-- mdformat-toc end -->

## Mitarbeiten

Guidelines fürs Mitarbeiten findest du [hier](CONTRIBUTING.md)

## Formelsammungen

### Allgemein

[Important Engineering Equations](http://latex4ei.de/downloads/Ingenieursgrundlagen.pdf)

### 1. Semester

| Formelsammlung                                                                   | Repository                                       |
| -------------------------------------------------------------------------------- | ------------------------------------------------ |
| [Analysis 1](https://github.com/latex4ei/Analysis-1/raw/gh-pages/Analysis-1.pdf) | [GitHub](https://github.com/latex4ei/Analysis-1) |

### 2. Semester

### 3. Semester

### 4. Semester

### Externe Formelsammlungen

Weitere, gute Formelsammlungen zu EI an der TUM findet ihr auch auf [www.ei-studium.de](http://www.ei-studium.de) oder [MaKeAppDev](https://makeappdev.github.io/TUM-Projekte). Ansonsten haben wir hier noch verstreute Formelsammlungen direkt verlinkt. Aber Achtung: Manche Formelsammlungen sind sehr alt und werden nicht mehr verbessert.

## Formelsammlungen für Latex4ei

**Required custom Package on GitHub:** [LaTeX4Ei](https://github.com/latex4ei/latex4ei-packages)

Public Version: [latex4ei.de](http://latex4ei.de)

## Optional: Build with CMake

Download [UseLaTeX.cmake](https://cmake.org/Wiki/CMakeUserUseLATEX) and move to `/usr/share/cmake-X.X/Modules/.`

### Steps to build

```shell
mkdir build
cd build
cmake ..
make
```
