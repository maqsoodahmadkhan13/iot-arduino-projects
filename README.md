# IoT Arduino Projects

A growing collection of Arduino / IoT projects, organized by difficulty level and built/tested in **[Wokwi](https://wokwi.com)**. Projects target boards from the Arduino family (Uno, Nano, Mega) and can be run either in the simulator or on real hardware.

## Repo Structure

```
iot-arduino-projects/
├── README.md              ← you are here
├── LICENSE
├── .gitignore
├── beginner/
│   └── README.md          ← phase overview + project index
├── intermediate/
│   └── README.md
└── advanced/
    └── README.md
```

Each phase folder holds its own project subfolders as they're added, e.g.:

```
beginner/
├── README.md
└── <project-name>/
    ├── README.md
    ├── <project-name>.ino
    └── diagram.json   (Wokwi diagram, if simulated)
```

## Phases

| Phase | Focus | Link |
|---|---|---|
| 🟢 Beginner | Digital I/O, analog sensors, simple actuators — no networking | [`beginner/`](./beginner) |
| 🟡 Intermediate | Displays, I2C/SPI/UART, sensor fusion, basic Wi-Fi | [`intermediate/`](./intermediate) |
| 🔴 Advanced | Full IoT: MQTT/HTTP, cloud dashboards, automation logic | [`advanced/`](./advanced) |

## Simulator

All projects are built and tested in **Wokwi** (wokwi.com), which runs actual compiled Arduino firmware on a virtual board rather than approximating circuit behavior — so what runs in simulation matches what runs on real hardware. Projects with a Wokwi diagram include a `diagram.json` you can drop straight into wokwi.com.

## Getting Started

1. Open the phase folder that matches your level for its project index.
2. Open a project folder for its wiring, parts list, and code.
3. Either:
   - Paste the code + `diagram.json` into [wokwi.com](https://wokwi.com) to simulate instantly, or
   - Wire it up on real hardware and upload via the Arduino IDE / PlatformIO.

## License

MIT — see [LICENSE](./LICENSE).
