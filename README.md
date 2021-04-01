## GUI-Cartoonify

This is a complete end to end OpenCV "Cartoonify Image" Desktop Application, test the application by clicking on the gui_app.exe file. The application is distributable and thus can be used by anynone without running it on Code Editor.

### How to set up locally?

- Fork the repository

- Git clone your forked repository
- Create virtual environment-
```
- python -m venv env
- source env/bin/activate (Linux)
- env\Scripts\activate (Windows)
```
- Install dependencies
```
- pip install opencv-python
- pip install tkinter
- pip install easygui
- pip install pillow
```  

### Steps to convert .py into .exe
```
- pip install pyinstaller
- pyinstaller --onefile -w gui_app.py
```  
### Future Functionality Implementation list:
```
- Sharpen Image
```  

### GUI Interface
-----
<img src="GUI.png" height="500px">

### Example
-------
<img src="Save.png" height="500px">
