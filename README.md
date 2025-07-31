🧬 Evolution Simulator
A dynamic simulation modeling predator-prey ecosystem dynamics and evolution of traits over time
📋 Description
This Evolution Simulator is a visual, interactive predator-prey simulation built using the designer module in Python. It models the interactions between sheep (prey), wolves (predators), and grass (resources), incorporating:

Reproduction with inheritable traits (speed),

Energy consumption and replenishment,

Natural selection through energy-based survival,

Regrowing resources,

Real-time graphing of population and trait evolution.

🧩 Features
🐑 Sheep: Consume grass, reproduce with inheritable speed traits, and die if energy is depleted.

🐺 Wolves: Hunt sheep, gain energy from predation, reproduce with inheritable traits, and die if energy runs out.

🌱 Grass: Regrows over time after being consumed.

📈 Live Graphing:

Track population size over time.

Track mean energy levels.

Histogram of speed evolution for sheep and wolves.

🧪 Trait Inheritance: Offspring inherit parent speed with slight variation.

🧠 User Interaction:

Add sheep/wolves with a click.

Adjust fertility rates, grass growth, and trait evolution.

Reset simulation anytime.

Trigger graphing of population and traits from toolbar panels.

▶️ How to Run
Prerequisites:
Python 3.7+

designer module (https://pypi.org/project/designer/)

matplotlib for plotting graphs

Running the Simulation:
bash
Copy
Edit
python evolution_simulator.py
🖱️ Controls & Toolbar Zones
Feature	Action	Location (X, Y)
Add Sheep	Left-click	(1000–1100, >700)
Add Wolves	Left-click	(1100–1200, >700)
Increase Sheep Speed	Left-click	(200–300, >700)
Decrease Sheep Speed	Right-click	(200–300, >700)
Increase Wolf Speed	Left-click	(400–500, >700)
Decrease Wolf Speed	Right-click	(400–500, >700)
Increase Grass Growth Time	Right-click	(600–800, >700)
Decrease Grass Growth Time	Left-click	(600–800, >700)
Increase Sheep Fertility	Right-click	(300–400, >700)
Decrease Sheep Fertility	Left-click	(300–400, >700)
Increase Wolf Fertility	Right-click	(500–600, >700)
Decrease Wolf Fertility	Left-click	(500–600, >700)
Graph Population	Left-click	(0–100, >700)
Graph Energy Levels	Left-click	(100–200, >700)
Graph Wolf Speed Histogram	Left-click	(900–1000, >700)
Graph Sheep Speed Histogram	Left-click	(800–900, >700)
Restart Simulation	Left-click	Top-right 🔄 button

📊 Data Visualization
Population Graph: Number of sheep, wolves, and grass patches over time.

Energy Graph: Average energy of each species over time.

Evolution Graphs: Histograms showing the spread of inherited speed traits in wolves and sheep.

🧠 Learning Objectives
Understand predator-prey population dynamics.

Observe effects of reproduction rates and trait inheritance.

Visualize the role of energy in survival and reproduction.

Simulate natural selection and emergent behavior.

📁 File Structure
bash
Copy
Edit
evolution_simulator.py        # Main simulation script
README.md                     # Project overview and instructions
📌 Notes
You can customize initial_sheep_sample, wolf_fertility_rate, and other parameters at the top of the script.

Speed trait inheritance drives natural selection through energy-efficient survival.

👨‍🔬 Credits
Developed using the designer interactive simulation library.
Graphing powered by matplotlib.


