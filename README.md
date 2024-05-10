#  **Self Driving with ANN and Genetic Algorithm Optimizer in JavaScript**

### **Summary** :

This project is a simulation of a self-driving car written in JavaScript. It showcases how a simple neural network can be trained to navigate a virtual road while avoiding obstacles, providing a foundational insight into the world of autonomous vehicles. The simulation leverages an intuitive graphical interface with dynamic visualization of the neural network. 

The Neural Network, the mutation algorithm and all the functionalities have been implemented analyticaly without the use of open-source libraries. For the mutation and the update of the weights during training we used a Genetic algorithm optimizer. 

### **Features**

1) Neural Network-Based Navigation: Uses a custom neural network to receive sensor inputs and control driving.
2) Road and Traffic Simulation: Simulates a multi-lane road with traffic obstacles.
3) Sensor Integration: Virtual sensors detect road borders and surrounding traffic.
4) User Control and AI Learning: Offers both manual (keyboard) control and autonomous driving.
5) Performance Tracking and Saving: Saves the best-performing neural network for later use.

### **Project Structure**

- **index.html**: Main page containing the car and network canvases. Links the JavaScript files.
- **car.js**: Defines the Car class, responsible for movement, control, and drawing.
- **road.js**: Manages road lanes, boundaries, and visualization.
- **controls.js**: Handles user input via keyboard for car navigation.
- **sensor.js**: Provides the Sensor class to simulate environmental detection.
- **network.js**: Implements the neural network logic.
- **visualizer.js**: Draws the neural network and layers on a canvas.
- **main.js**: Coordinates all components and runs the main animation loop.
- **utils.js**: Contains utility functions for interpolation and collision detection.

### **How to use :**

1) clone repository : 
git clone <your-repository-url>
2) Open '**index.html**' in your browser
3) Start Simulation (starts eveery time you reload the page)
4) Use save and discard buttons in your browser to save the best model every time it perfoms better
        - Save: Click the Save button to store the best-performing neural network to local storage.
        - Discard: Click the Discard button to remove the saved neural network.
5) You can play and modify any parametr through **main.js**


**Future Enhancements**

- Add dynamic traffic generation.
- Implement more sophisticated neural networks.
- Improve road and obstacle variety.
- Integrate external machine learning libraries.
