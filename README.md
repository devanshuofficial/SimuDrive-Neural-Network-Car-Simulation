🧠🚗 NeuroDrive – Self‑Driving Car Simulator
NeuroDrive is a 100% client-side, browser-based simulation that demonstrates how self-driving cars can learn using artificial intelligence—specifically neural networks and evolutionary algorithms. Just open index.html in your browser and watch virtual cars sense, learn, and navigate—all built with pure HTML, CSS, and JavaScript.

✨ Key Features
Real-Time AI Simulation – Cars learn and evolve as they drive.

Neural Network Visualizer – See how the AI "thinks" in real time.

Physics-Based Movement – Acceleration, steering, and collision handling.

Genetic Algorithm-Based Learning – AI improves without labeled data or external training sets.

Persistent Learning – Best-performing AI is stored in the browser.

No Installation Required – Fully frontend project; runs in any modern browser.

🧠 Algorithm Used
The intelligence behind NeuroDrive is based on Artificial Neural Networks (ANNs) combined with a simple Genetic Algorithm:

Artificial Neural Network (ANN)
A feedforward neural network is manually implemented in JavaScript.

Inputs: Sensor data (distances to road borders and other cars).

Outputs: Control signals (forward, left, right, reverse).

The network consists of an input layer, one or more hidden layers, and an output layer.

Activation and forward propagation are calculated without any external library.

Genetic Mutation Algorithm
No pre-labeled data is used—cars learn via a mutation-based evolutionary approach.

Each AI car starts with a slightly mutated version of the best-performing network.

After each simulation run, the car that travels the farthest without crashing is considered the best.

This "best brain" is saved using localStorage and cloned/mutated to generate the next generation of AI agents.

This process mimics natural selection and helps improve driving behavior over time—even in a fully unsupervised setup.

🛠 Technologies Used
HTML5 – Page structure and canvas elements.

CSS3 – Basic layout and visual styling.

JavaScript (ES6) – Core logic, car behavior, AI, and visualization.

Canvas API – Renders both the simulation and neural network in real time.

LocalStorage – Saves the best neural network across browser sessions.

📁 Project Structure
index.html – Main page with two canvas elements.

style.css – UI layout and appearance.

main.js – Initialization and simulation loop.

/core – Logic for car movement, controls, sensors, and road rendering.

/nn – Modules for building and visualizing neural networks.

/docs – Optional folder for screenshots, gifs, or documentation.
