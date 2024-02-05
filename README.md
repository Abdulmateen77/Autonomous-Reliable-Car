# Autonomous Reliable Car

## Overview

This repository contains the codebase for an Autonomous Reliable Car. The project focuses on developing a robust and reliable autonomous car system with various features such as obstacle avoidance, distance keeping, and blob detection.

## Features

- **Obstacle Avoidance:** The car is equipped with infrared sensors to detect obstacles and take appropriate actions to avoid collisions.

- **Distance Keeping:** Utilizing ultrasonic sensors, the car maintains a safe distance from obstacles in its path.

- **Blob Detection:** The car employs a camera and advanced image processing to detect and track blobs, enhancing its awareness of the surroundings.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [WiringPi Library](http://wiringpi.com/) for Raspberry Pi GPIO access.
- [Curses Library](https://en.wikipedia.org/wiki/Curses_(programming_library)) for terminal-based UI.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/autonomous-reliable-car.git
   ```

2. Compile the code:

   ```bash
   cd autonomous-reliable-car
   gcc -o camcar -Wall -Werror -lcurses -lwiringPi -lpthread -linitio camcar.c
   ```

3. Run the executable:

   ```bash
   ./camcar
   ```

## Usage

- Ensure all the required dependencies are installed.
- Connect the necessary sensors and actuators to your Raspberry Pi.
- Run the compiled executable, and the car should demonstrate autonomous behavior.


## Acknowledgments

- [4tronix](https://4tronix.co.uk/) for the Initio robot car and library.

