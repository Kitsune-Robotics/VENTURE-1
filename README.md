[![Docs](https://github.com/Kitsune-Robotics/VENTURE-1/actions/workflows/docs_workflow.yml/badge.svg)](https://github.com/Kitsune-Robotics/VENTURE-1/actions/workflows/docs_workflow.yml)


# VENTURE-1

![Banner](Static/Banner.png)

```mermaid
journey
    title VENTURE Project Timeline

    section Completed
        - Frame Welded : 5 : Mike

    section In Progress
        - Drivetrain Functional : 3 : Joe, Mike
        - KIT Controller Prototype : 3 : Joe
        - FENNEC Modem Prototype : 1 : Joe
        - Web GUI : 2 : Joe
        - KIT Controller Nav : 1 : Joe

    section Future
        - CANIO Firmware : 0 : Joe
        - Robotstreamer Integration : 0 : Joe
        - Discord Integration : 0 : Joe

```

This repo contains all the firmware and hardware for the VENTURE-1.

If you're looking for the latest docs/builds, see our [Releases Page](https://github.com/Kitsune-Robotics/VENTURE-1/releases).

# Getting Started

First, clone this repo (and optionally checkout a branch)

```shell
git clone https://github.com/Kitsune-Robotics/VENTURE-1.git --recurse-submodules
cd VENTURE-1
```

# Init Submodules

Some libraries and resources are included as submodules, run the following
command to initialize them before opening the main sch

(If you get a missing library error, make sure to do this)

```shell
git submodule update --init --recursive
```


## Project Layout

If you want to use this project template for yourself, you can find it [here!](https://github.com/KenwoodFox/Project-Template)
