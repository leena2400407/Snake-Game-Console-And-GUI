# Snake Pro

A feature-rich C++ implementation of the classic Snake game, offering two distinct gameplay experiences: a nostalgic, retro Windows Console application and a smooth, modern Windows Forms Graphical User Interface (GUI). 

This project goes beyond traditional mechanics by adding unique gameplay modifiers, power-ups, and special event modes to customize your arcade experience.

## 🎮 Features & Game Modes

### 1. Retro Console Mode
* **Terminal Interface:** Built purely inside the Windows Command Prompt using basic character graphics.
* **Colored Output:** Leverages native Windows console styling to separate the snake's head, body segments, portals, and different food types visually.

### 2. Modern GUI Mode
* **Windows Forms (C++/CLI):** Clean desktop window container with modern styling and responsive element rendering.
* **Smooth Rendering:** Uses `DoubleBuffered` rendering and `AntiAlias` smoothing for fluid snake animations and animations.
* **Visual Effects:** Implements 3D-shaded fruit types and multi-gradient colors for the snake body.

### ⚙️ Gameplay Modifiers (Extras Menu)
Both game versions allow you to toggle specific options to alter the difficulty and mechanics:
* **Portals:** Spawns interconnected portals on the board. Entering one teleports the snake out of the other.
* **Speed Food:** Special items that grant a temporary velocity boost.
* **Enhanced Food:** High-reward items that grant double points and increase snake length aggressively.
* **Wrap Mode:** Toggles whether the boundaries loop around or result in an instant Game Over upon collision.
* **Christmas Theme (GUI exclusive):** Alters the background aesthetic, turns regular apples into snowballs/presents, and outfits the snake with a festive Santa hat.

---

## 🕹️ Controls

The game relies on standard desktop controls for navigation:
* **`W`**: Move Up
* **`A`**: Move Left
* **`S`**: Move Down
* **`D`**: Move Right
* **Menus:** Use number inputs followed by `Enter` (Console) or mouse clicks (GUI) to navigate menus.

---

## 🛠️ Project Structure

* `ConsoleApplication2.cpp` — Complete logical engine and loop management for the console-based environment.
* `GUI.h` — Windows Forms declaration, event processing, rendering routines, and state machines for the modern UI.
* `main.cpp` — The startup entryway configuration initialization for the visual GUI subsystem.

---

## 🚀 Getting Started

### Prerequisites
* **Operating System:** Windows (relies on `<Windows.h>`, Windows Forms architectures, and `<conio.h>`).
* **IDE:** Microsoft Visual Studio (2019, 2022, or newer recommended).
* **Workload Requirements:** Ensure **Desktop development with C++** and **.NET desktop development** (specifically supporting C++/CLI support tools) are installed via your Visual Studio Installer.

### Compilation and Execution
1. Clone this repository to your local system.
2. Open the project solution file inside Visual Studio.
3. Choose your desired configuration template target (Console deployment vs. GUI implementation).
4. Build and run the project by pressing `F5` or hitting the **Local Windows Debugger** action button.
