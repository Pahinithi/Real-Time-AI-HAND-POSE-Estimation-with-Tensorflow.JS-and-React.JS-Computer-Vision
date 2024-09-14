# Real-Time AI Hand Pose Estimation

Harness the power of **TensorFlow.js**, **React.js**, and **JavaScript** to detect and visualize hand poses in real-time using your webcam. This project implements a **hand pose estimation model** using TensorFlow's handpose library and allows you to interact with the model in a web browser.


## Table of Contents
- [Demo](#demo)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Demo

**Live Demo**: [Click here to view the live demo]()

- The app detects hand movements and visualizes key points in real-time.
- Once you open the app, you can click "Start Detection" to begin capturing hand pose from your webcam.

## Features

- Real-time hand pose detection using TensorFlow.js.
- Detects key points on each finger and joints.
- Draws hand mesh over webcam video feed.
- Infinity Gauntlet-style colors for key points and joints.
- Simple, responsive, and visually appealing UI.
  
## Installation

Follow these steps to set up the project locally.

### Prerequisites

- Node.js installed (version 14+)
- npm or Yarn

### Steps

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Pahinithi/Real-Time-AI-HAND-POSE-Estimation-with-Tensorflow.JS-and-React.JS-Computer-Vision
   cd Real-Time-AI-Hand-Pose-Estimation
   ```

2. **Install dependencies**:

   With npm:
   ```bash
   npm install
   ```

   With Yarn:
   ```bash
   yarn install
   ```

3. **Start the development server**:

   ```bash
   npm start
   ```

4. **Open in your browser**:
   Navigate to `http://localhost:3000` in your browser to view the app.

## Usage

1. Once the app is running, you will see the homepage with the "Start Detection" button.
2. Click the button, and the app will start accessing your webcam to detect hand poses in real-time.
3. The model will detect key points on your hand, and the hand mesh will be displayed over the webcam feed.
4. To stop the detection, simply close the browser tab.

## Project Structure

```bash
Real-Time-AI-Hand-Pose-Estimation/
├── node_modules/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── serviceWorker.js
│   ├── setupTests.js
│   └── utilities.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
```

### Key Files:

- **App.js**: Main React component that controls the webcam and renders the handpose detection.
- **utilities.js**: Contains helper functions like `drawHand` to render key points and joints of the hand on the canvas.
- **index.html**: Basic HTML structure for the app.
- **App.css**: Styling for the application.

## Screenshots

<img width="1728" alt="CV02" src="https://github.com/user-attachments/assets/c42edc28-ac53-431b-b4a6-821c49a066b4">


<img width="1728" alt="Screenshot 2024-09-14 at 21 07 56" src="https://github.com/user-attachments/assets/efe08a9c-2270-4aba-87ad-4026e6e65332">


## Technologies Used

- **React.js**: Front-end library to build the UI.
- **TensorFlow.js**: For real-time hand pose estimation using pre-trained models.
- **Webcam.js**: To access the user's webcam feed.
- **Bootstrap**: For responsive and simple UI design.
- **JavaScript (ES6+)**: Core language for front-end development.
  
## Acknowledgements

- TensorFlow.js Hand Pose Estimation Model: [TensorFlow Handpose Model](https://github.com/tensorflow/tfjs-models/tree/master/handpose).

## License

This project is licensed under the MIT License.

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)


