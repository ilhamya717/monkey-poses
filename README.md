How to Run  

    1   Clone this repository:  
        
        git clone https://github.com/ilhamya717/monkey-poses.git
        
        cd monkeyposes  
    
    2   Activate your virtual environment:  
    
        source ~/venvs/monkey/bin/activate  
        
    3   Run the script:  
    
        python gesture_tracker.py  
        
    4    If camera access is denied on macOS:  
        
    ⁃    Go to System Settings → Privacy & Security → Camera  
    ⁃    Enable access for “Visual Studio Code” or “Terminal”.  

  VS Code Setup  

    If you use Visual Studio Code, make sure VS Code uses the correct Python interpreter from your virtual environment.

    Create this file:  
    
    .vscode/settings.json  
    
    Add this content:  
    
    {
      "python.defaultInterpreterPath": "/Users/ilkesayki/venvs/gesture312/bin/python"
    }  
    
    
     Without this, VS Code may try to run with the system Python



# Monkey Poses - “Monkey Meme”
Real-time hand and face gesture detection using Python and OpenCV.
This project uses your webcam to recognize different gestures — like pointing, face proximity, and idle state — and triggers actions or visual changes based on them.

 Requirements

Before running the project, make sure you have the following installed:  
    
    1   Python  

        -You need Python 3.8+. Check your version:

        python3 --version

        -If you don’t have it, install from python.org/downloads.

    2   Create and Activate a Virtual Environment  

        -We recommend using a virtual environment (so dependencies don’t conflict):  

        python3 -m venv ~/venvs/monkey  
        source ~/venvs/monkey/bin/activate

        (py -3.11 -m venv venv)
        venv\Scripts\Activate.ps1 
        
        

    3   Install Dependencies

        pip install opencv-python mediapipe numpy absl-py

 
    4. Run the script
       py gesture
       py -3.11 monkey_poses.py
    

    


