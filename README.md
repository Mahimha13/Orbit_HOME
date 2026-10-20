# ORBIT — Technology That Adapts to You

**ORBIT** is an interactive smart-home dashboard prototype designed to make home automation more intuitive, accessible, and user-friendly. It provides a centralized interface for managing simulated home devices, switching between personalized scenes, monitoring room conditions, and customizing accessibility settings.

## Overview

ORBIT demonstrates how a modern smart-home interface can combine device management, responsive design, interactive visualizations, and accessibility-focused controls in a single web application.

The project features a visual room interface, multiple automation presets, Standard and Assist modes, and a range of personalization options designed to improve the user experience.

## Features

- **Interactive Room Visualization:** Explore a simulated home environment with living room, bedroom, and kitchen views.
- **Smart Device Controls:** Interact with simulated lights, curtains, television, door lock, and climate settings.
- **Personalized Scenes:** Apply predefined settings for different activities and routines.
- **Standard and Assist Modes:** Switch between the regular dashboard experience and an accessibility-oriented interface.
- **Accessibility Customization:** Adjust text size, contrast, motion preferences, scanning speed, switch-key settings, and voice announcements.
- **Voice Announcements:** Use browser-based speech synthesis to provide spoken interface feedback.
- **Activity History:** View a record of interactions during the current session.
- **Responsive Interface:** Access the dashboard across different screen sizes.
- **Modern Visual Design:** Experience a polished interface with custom styling, animations, and interactive elements.

## Smart Scenes

ORBIT includes predefined scenes to demonstrate personalized home automation:

- **Good Morning** — A morning routine preset.
- **Movie Night** — A scene designed for watching movies.
- **Away** — A preset for leaving home.
- **Study** — A focused environment for studying.
- **Bedtime** — A nighttime routine.
- **Dinner Time** — A preset for mealtime.
- **Relax** — A relaxing environment.
- **Coming Home** — A preset for returning home.
- **Energy Saver** — A scene designed around energy-conscious settings.

These scenes demonstrate how multiple device settings can be grouped into convenient, one-step interactions.

## Technology Stack

- **HTML5** — Page structure and interface components.
- **CSS3** — Layout, styling, animations, and responsive design.
- **JavaScript** — Interactive controls, scene management, interface behavior, and activity tracking.
- **SVG** — Scalable visual elements for the room interface.
- **Web Speech API** — Browser-based speech synthesis for voice announcements.
- **Local Storage** — Persistence of supported interface preferences.

## Getting Started

ORBIT is implemented as a standalone HTML prototype and does not require a separate backend for its demonstration features.

### Prerequisites

- A modern web browser such as Google Chrome, Microsoft Edge, Firefox, or Safari.
- The project HTML file.

### Installation and Setup

1. Download or clone this repository.
2. Locate the `FINAL ORBIT.html` file.
3. Open the file in a modern web browser.
4. Explore the dashboard, interact with the device controls, and try the available scenes and accessibility settings.

Alternatively, run a local development server from the project directory:

```bash
python3 -m http.server 8000
```

Then open the following address in your browser:

```text
http://localhost:8000/FINAL%20ORBIT.html
```

## How to Use

1. Open the ORBIT dashboard in your browser.
2. Explore the available rooms through the interactive room interface.
3. Use the device controls to modify simulated home settings.
4. Select a smart scene to apply a predefined configuration.
5. Switch between Standard and Assist modes to explore different interface experiences.
6. Customize accessibility options according to your preferences.
7. Review the activity history to see interactions recorded during the current session.

## Project Structure

```text
ORBIT/
├── FINAL ORBIT.html
└── README.md
```

The application interface, styling, and JavaScript functionality are contained in the standalone HTML file.

## Important Note

**ORBIT is a front-end demonstration prototype.** Device interactions and automation scenes are simulated within the interface. The current implementation does not establish connections to physical smart-home devices or provide real-world device control. Voice functionality uses browser-based speech synthesis for announcements rather than a complete voice-command recognition system.

## Future Enhancements

Potential improvements include:

- Integration with real smart-home platforms and IoT devices.
- Voice-command recognition for hands-free control.
- User accounts and personalized home profiles.
- Real-time sensor data and environmental monitoring.
- Energy consumption tracking and analytics.
- Backend integration for persistent activity logs and device configurations.
- Additional accessibility features and user testing.

## Contributing

Suggestions, bug reports, and feature improvements are welcome. If you would like to contribute, fork the repository, create a branch for your changes, and submit a pull request describing your improvements.

## License

No license has been specified for this project. Add a suitable open-source license if you intend to permit reuse or redistribution.
