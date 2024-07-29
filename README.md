# CMP9137 - Advanced Machine Learning Devcontainer

A template repository for teaching Tensorflow

## Use Case

You can use this repository use any version of Tensorflow on the lab machines, or at home.

## How to Use

1. Click the green 'Code' button on this page and download as a zip.
2. Open the 'Docker Desktop' application. Once it has launched you may minimise the window.
3. Extract that zip file to your desktop.
4. Open the  `C:\Users\Computing\Desktop\CMP9137-main` directory in File Explorer.
5. *By default*, this container runs Tensorflow version 2.10.0. If you require a different version, open the `.devcontainer` folder, right click the `devcontainer.json` file, click 'Edit in Notepad', and locate line 5: `"image": "tensorflow/tensorflow:2.17.0-gpu",`. This line may be edited to a different Tensorflow version. For example, you may change it to: `"image": "tensorflow/tensorflow:2.15.0-gpu",`. Different versions of tensorflow, with their corresponding preferred CUDA versions can be found at [www.tensorflow.org/install/source#gpu](https://www.tensorflow.org/install/source#gpu).
6. Right click in any blank space in the File Explorer window, and click 'Open in Terminal'
7. In the terminal, type `code .` and press enter.
8. Visual Studio Code will then launch. Click the blue 'Reopen in Container' button that pops up in the bottom right hand corner of the window.
9. *If you do not see the pop up*, press <kbd>F1</kbd> and type `Reopen in container`. Click the 'Dev Containers: Reopen in Container' option that appears in the top search bar.
10. If you are working from home, you will need to install the [Dev Containers Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) in VS Code to open in the container.
11. The container will now launch and will take a few minutes. You will eventually see a prompt in the terminal at the bottom of the window to press any key to close.
12. The docker container is now active. You may move any python tensorflow code you wish to run into the `C:\Users\Computing\Desktop\CMP9137-main` folder.
13. Run python files by opening a new terminal using <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>'</kbd> and typing `python3 YOUR_FILENAME.py`. There is a test file already in the folder which you can run to verify the Tensorflow version and whether the GPU is being used.
14. If you have any questions about how to use this docker container, please don't hesitate to ask your module coordinator, or SoCS Technicians at [help@socstech.support](mailto:help@socstech.support).
