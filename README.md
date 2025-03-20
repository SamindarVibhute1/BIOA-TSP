# BIOA-TSP
BIOA-TSP: Beagle-Inspired Optimization Algorithm for Traveling Salesman Problem
🐾 Overview
BIOA-TSP is a Python implementation of the Beagle-Inspired Optimization Algorithm (BIOA) applied to the Traveling Salesman Problem (TSP). Inspired by the scent-tracking behavior of beagle dogs, BIOA introduces a multi-phase metaheuristic for robust and adaptive search strategies. This implementation is modular and can be extended to other combinatorial optimization tasks.

🎯 Key Features
Nature-Inspired Algorithm based on scent-tracking behavior.
Three-phase search mechanism: Random Sniffing, Zigzag Tracking, and Circular Intensified Search.
Adaptive search dynamics using Scent Intensity, Zigzag Search Factor, and Spiral Search Decay.
Benchmark ready for solving standard TSP problems.
Visualization module for convergence plots and optimized tour path.
Lightweight and easy to customize for other optimization tasks.
📂 Project Structure
graphql
Copy
Edit
BIOA-TSP/
│
├── bioa_tsp.py            # Main BIOA-TSP algorithm
├── tsp_data.json          # Sample TSP data (10 cities)
├── results/
│   ├── convergence_plot.png
│   └── optimized_tour.png
├── requirements.txt       # Dependencies
└── README.md              # Project description (this file)
🚀 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/BIOA-TSP.git
cd BIOA-TSP
Install required packages:

bash
Copy
Edit
pip install -r requirements.txt
🛠 Usage
Run the algorithm:

bash
Copy
Edit
python bioa_tsp.py
Outputs:

convergence_plot.png: Shows the cost (tour length) over iterations.
optimized_tour.png: Displays the final optimized tour.
Prints the best tour distance and city sequence to the console.
📊 Visualization
Convergence Plot


Optimized Tour


🔍 Algorithm Phases
Random Sniffing Phase
Simulates global search using random scent detection patterns.

Zigzag Tracking Phase
Adaptive exploration-exploitation via zigzag maneuvers.

Circular Intensified Search Phase
Local search intensification using spiral-like search behavior.

⚙️ Parameters
Parameter	Description	Default
n_cities	Number of cities in TSP	10
n_agents	Number of candidate solutions	30
max_iter	Maximum number of iterations	200
S_min, S_max	Sniffing Intensity range	[0.2, 0.9]
w_min, w_max	Zigzag Search Factor range	[0.2, 1.0]
R_decay	Spiral Search Decay rate	0.99
🌍 Applications
Combinatorial Optimization
Vehicle Routing & Logistics
Path Planning for Robotics
Facility Layout Design
🔮 Future Work
Hybridization with ACO, PSO, or DE for improved performance.
Benchmark testing on large-scale TSP instances (up to 100+ cities).
Multi-objective TSP and dynamic variant adaptations.
Real-life scenarios, e.g., delivery route planning and manufacturing workflows.
🧑‍💻 Contributing
Contributions are welcome! Please fork the repo, create a new branch, and submit a pull request.

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙌 Acknowledgements
Inspired by the natural scent-tracking behavior of beagle dogs and research on nature-inspired algorithms.
BIOA-TSP: Beagle-Inspired Optimization Algorithm for Traveling Salesman Problem
Developer : Samindar J. Vibhute
samindarvibhute1@gmail.com
