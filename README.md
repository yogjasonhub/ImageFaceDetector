# ImageFaceDetector
To use openCV, follow these steps:
1. Install openCV (latest version)

2. Setup Environment Variable in "This PC" properties

    a. Advanced System Settings
    
    b. Environment Variables...
    
    c. Click "Path"
    
    d. Click "New"
    
    e. add path to "your_file_directory\opencv\build\x64\vc16\bin
    
3. Download Visual Studio (latest version)

    a. create new project (Win32 Console Application)
    
    b. name your project
    
    c. Make sure it is set to x64 and not x86 since we are using opencv
    
    d. add your app file and copy my code to use (you will need to tweak some directory code)
    
4. Go to project properties

    a. C/C++, General, Additional Include Directories
    
        i. add path "your_file_directory\opencv\build\include"
        
    b. C/C++, Preprocessor, Preprocessor Definitions
        i. add "_CRT_SECURE_NO_WARNINGS"
    c. Linker, General, Additional Library Directories
    
        i. add path "your_file_directory\opencv\build\x64\vc16\lib"
        
    d. Linker, Input, Additional Dependencies
    
        i. Add library file "opencv_world(version)d.lib"
        
5. Click "Apply"

6. Ready to code now
 
