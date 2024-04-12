# CMP9137 - Advanced Machine Learning Devcontainer

A template repository for teaching Tensorflow

## Use Case

You can use this repository use any version of Tensorflow on the lab machines, or at home.

## How to Use

1. Click the green 'Code' button and download as a zip.
2. Extract the zip file to the desktop.
3. Open the 'Docker Desktop' application. Once it has launched you may minimise the window.
4. Go to the C:\Users\Computing\Desktop\CMP9137-main\CMP9137-main directory in File Explorer.
5. By default, this container runs Tensorflow version 2.10.0. If you require a different version, open the .devcontainer folder, right click the devcontainer.json file, click 'Edit in Notepad', and locate line 5: '"image": "tensorflow/tensorflow:2.10.0-gpu",'. This line may be edited to a different Tensorflow version. For example, you may change it to: '"image": "tensorflow/tensorflow:2.15.0-gpu",'. Different versions of tensorflow, with their corresponding preferred CUDA versions can be found at www.tensorflow.org/install/source#gpu
6. Right click in any blank space in the File Explorer window, and click 'Open in Terminal'
7. In the terminal, type 'code .' and press enter.
8. Visual Studio Code will then launch. Click the blue 'Reopen in Container' button that pops up in the bottom right hand corner of the window.
9. If you do not see the pop up, press F1 and type 'Reopen in container'. Click the 'Dev Containers: Reopen in Container' option that appears in the top search bar.
10. The container will now launch and will take a few minutes. You will eventually see a prompt in the terminal at the bottom of the window to press any key to close.
11. The docker container is now active. You may move any python tensorflow code you wish to run into the C:\Users\Computing\Desktop\CMP9137-main\CMP9137-main.
12. Run python files by opening a new terminal using Ctrl+Shift+' and typing python3 "YOUR_FILENAME.py".
13. If you have any questions about how to use this docker container, please don't hesitate to ask your module coordinator, or SoCS Technicians at help@socstech.support
