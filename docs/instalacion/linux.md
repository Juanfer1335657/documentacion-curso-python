---
title: Linux
sidebar_position: 2
---

# Linux

## Ubuntu / Linux Mint / Pop!\_OS / Elementary

estas distribuciones usan apt (Debian/Ubuntu)

```bash
# Actualiza los repositorios
sudo apt update

# Instala Python 3 y pip
sudo apt install python3 python3-pip -y

# Verifica la instalación
python3 --version
pip3 --version
```

## Fedora

Usa DNF:

```bash
# Instalar Python 3 (suele traerlo por defecto)
sudo dnf install python3 python3-pip -y

# Verificar versión
python3 --version
pip3 --version

```

## Arch Linux y derivadas (Manjaro, EndeavourOS, etc.)

Python suele venir preinstalado, pero por si acaso:

```bash
sudo pacman -Syu python python-pip
python --version
pip --version

```

## OpenSUSE (Leap / Tumbleweed)

```bash
sudo zypper refresh
sudo zypper install python3 python3-pip
python3 --version
pip3 --version
```

## Verificar instalación

En todas las distros puedes probar:

```bash
python3 --version
pip3 --version
```

O

```bash
python --version
pip --version
```
