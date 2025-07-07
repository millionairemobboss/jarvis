# Jarvis

An interactive, gesture-controlled 3D hologram. Built with [OpenCV](https://opencv.org/), [Mediapipe](https://developers.google.com/mediapipe), [Websockets](https://socket.io/), [Flask](https://flask.palletsprojects.com/en/3.0.x/), [Next.js](https://nextjs.org/), and various [Poimandres](https://github.com/pmndrs) React packages for Three.js. 

![jarvisgif](https://github.com/ishaan1013/jarvis/assets/69771365/e2c0a4f3-3458-4a7c-8be5-e5847a60743e)


Click to view our [Video Demonstration](https://www.youtube.com/watch?v=qOElePxRUAs)

## Running Locally

It works just fine on any regular screen (without the hologram effect, of course). But feel free to build a Pepper's Ghost hologram if you'd like. 

### Cloning the repository the local machine.

```bash
git clone https://github.com/millionairemobboss/jarvis
```

### Backend setup

- Set up a webcam facing upwards, in front of your screen and a little bit below.
- Ensure OpenCV recognizes your webcam in `backend/camera.py`
- 🐍 Run the flask app, which will be available at `http://localhost:8000`.

```bash
flask run
```

### Running the frontend app

```bash
npm install
```

Then, run the application in the command line and it will be available at `http://localhost:3000`.

```bash
npm run dev
```

#### Notes
- Viewing and manipulating 3D models can be resource-intensive.
- Voice control uses the WebSpeechAPI which currently works best on Chrome, Microsoft Edge, or Safari 14.1
