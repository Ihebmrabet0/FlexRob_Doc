# FlexRob User Interface

Welcome to the user interface documentation for the **FlexRob** project. This user interface allows you to control an industrial robot using a handguiding device. Please note that the core control and communication with the robot are handled by a ROS2 system using MQTT, as documented separately.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Interface Features](#interface-features)
3. [Usage](#usage)

Certainly, if you typically use `npm run dev` for development, you can simplify the instructions. Here's a shortened version:

## Getting Started

Before using the FlexRob User Interface, ensure that the underlying ROS2 system, which controls the robot through MQTT, is set up and running as documented separately.

### Running the Vue Project

To run the Vue project for the FlexRob User Interface in development mode, follow these steps:

1. **Navigate to the Project Directory**: Open your terminal and navigate to the directory where your Vue.js project is located. Use the `cd` command to change directories if needed.

   ```bash
   cd /ros2_ws/FLEXROB UI/flexrob
   ```

2. **Install Dependencies**: If you haven't already, install the project dependencies using npm or yarn. Run one of the following commands based on your package manager:

   ```bash
   # Using npm
   npm install

   # Using yarn
   yarn install
   ```

3. **Run the Development Server**: Start the development server with hot-reloading by running:

   ```bash
   npm run dev
   ```

   This will launch the development version of your interface at `http://localhost:8080` in your web browser.
   Please check the configuration in `vue.config.js` if you want to change the port.



## Interface Features

### Handguiding Control

- **Enable/Disable Axis**: Use the interface to enable or disable specific robot axes (X, Y, Z, A, B, C) for precise handguiding control.

- **Movement Program**: Create, save, and load movement programs for the robot.

- **Run Program**: Execute saved movement programs for automated tasks.

- **Auto-Mode**: Access the Auto-Mode for palletizing objects automatically (Note: This feature may be under development or not fully functional).

## Usage

1. **Connect to ROS2**: Ensure that the underlying ROS2 system is running and correctly configured to communicate with your robot and MQTT broker.

2. **Handguiding Control**:
   
   - Toggle axes on/off as needed for manual control.
   - Create, save, and load movement programs for the robot.
   - Execute saved movement programs for automated tasks.
   - Access Auto-Mode for palletizing objects automatically (if available).

Please refer to the separate documentation for the ROS2 system for detailed information on setting up and configuring the core components of the FlexRob project.




---

Thank you for using the FlexRob User Interface. If you have any questions or encounter issues related to the interface, please reach out to our support team or refer to the ROS2 documentation for system-level concerns. Happy robot controlling!


[![Button Shield]][Shield]


<!---------------------------------------------------------------------------->

[Button Shield]: ../assets/images/FlexRob%20Views/logo.png

[Shield]: https://ihebmrabet0.github.io/FlexRob_Doc

