## 🎮 GTA NPC & Vehicle Cleanup

**GTA NPC & Vehicle Cleanup** is a lightweight, efficient client-side script for GTA V that automatically removes unwanted NPCs, random cops, garbage trucks, and vehicles. Designed to enhance gameplay experience by reducing clutter, improving server performance, and providing a cleaner, more immersive environment for players.

This script continuously controls game density multipliers and cleans the nearby area of vehicles, ensuring a smooth, optimized session for players and server admins.

## ✨ Features

* [x] Disables random cops and NPC spawns to reduce distractions.
* [x] Removes garbage trucks and random boats from the environment.
* [x] Sets all vehicle and pedestrian density multipliers to zero.
* [x] Continuously clears nearby vehicles within a large radius for cleaner gameplay.
* [x] Runs entirely client-side for easy deployment and compatibility.
* [x] Lightweight script with minimal performance impact.
* [ ] Planned: Configurable radius and selective NPC disabling options.

## ⚙️ How It Works

1. **Disable Spawns:**  
   The script disables random NPCs, cops, garbage trucks, and boats via native GTA V functions every frame.

2. **Density Control:**  
   All density multipliers for vehicles, peds, and scenarios are set to zero each tick, preventing new entities from spawning.

3. **Clear Vehicles:**  
   Vehicles in a 1000-unit radius around the player are cleared continuously to maintain an empty environment.

4. **Area Cleanup:**  
   Removes vehicle generators in a 1000x1000x1000 area centered on the player, further ensuring no new vehicles spawn.

## 🛠️ Installation & Setup

### Prerequisites

- A FiveM server or compatible GTA V mod environment.
- Basic knowledge of resource installation for GTA V mods.

### Installation Steps

1. Clone or download this repository.

2. Place the resource folder into your server’s `resources` directory.

3. Add the following line to your server configuration file (`server.cfg`):

```cfg
start remove-npc
````

---

4. Restart the server or resource to apply changes.

## 🔎 Usage

* The script runs automatically on client connection.
* No user interaction required.
* For best results, configure your server to start this resource by default.

## ⚠️ Permissions & Compatibility

* No special permissions required.
* Compatible with most GTA V servers and mod setups.
* Works best on FiveM or similar multiplayer frameworks.

## 📣 Contributing

Contributions, bug reports, and feature requests are welcome! Please:

* Fork the repository and create a feature branch.
* Commit your changes with clear messages.
* Submit pull requests with detailed descriptions.
* Report any issues via GitHub Issues.

## 📋 License

This project is licensed under the **MIT License** — permitting free use, modification, and distribution with minimal restrictions. See the [LICENSE](./LICENSE) file for full details.

## ✒️ Author

Created and maintained by **KaloudasDev**.
If you find this project useful, please ⭐ star the repository to support further development!