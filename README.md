# GolfVR

I have developed this game on Meta Quest 2 using Unity. The game was made as a project submission for for my Masters Degree.

This project has essentially 2 components a Machine learning model and a VR Golf app.

The goal of this project was to try and capture the full swing of the golf club as people do in real life, but due to low sampling rates and collison issues in unity physics engine that motion is not translated seamlessly in the VR setting.

To address this issue I developed an LSTM model trained on trajectories pf the golf club head extracted from professional golf player swing clips. The model was incorporated in the VR app on the clubHead gameobject by exporting the pytorch model as an ONNX model.

## Gameplay

https://github.com/Sharma-pratham/GolfVR/assets/44340689/517c7bda-c9c5-4115-9379-317b93a97d5c

Full video link - https://drive.google.com/file/d/1PbNP06fnPYvYvsk-fOkW2E-Kixntb666/view?usp=drive_link
