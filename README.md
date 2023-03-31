# startup

Are you tired of pesky programs that open when you startup your computer? 


## Copy code from my github repositories. 

1.  Visit https://github.com/guzmanwolfrank/startup/blob/main/startup_programs.py and copy the code and save it in a text editor like notepad and name the file 
startup_programs.py. 

## Open Command Prompt 
2.  Open the Run dialog box. The Run dialog box, which you can open using the keyboard shortcut Win + R, allows you to open any Windows program by entering its name. Enter “cmd” and click “OK” to open Command Prompt.
![run](https://user-images.githubusercontent.com/29739578/229162515-c7f56abb-6a73-4013-8455-e1b8f7abe44e.jpg)

## Navigate to File Location 
3.  Navigate on the command prompt to the file location.  
        
        You can use the cd command to change drives towards the destination while using command prompt. 
        
![cdcommand](https://user-images.githubusercontent.com/29739578/229164247-830bd7c1-3c17-479c-8cd1-989834ddff3a.jpg)

## Run the Python Script
4.  Once you have located your file location and set it on the command prompt, run the file by typing the following script and pressing enter:
        
        python startup_programs.py 


The program will run and you will see a list of files/apps that open automatically every time you turn on your windows pc:

![runprog](https://user-images.githubusercontent.com/29739578/229165589-23c9371a-aee6-4fad-927d-aab1a3be45a9.jpg)


2.  Choose which file you want to remove from starting up when you start your computer. Do this by typing the name of the program shown on the 
list on the command prompt screen.  Press Enter. 

![startupcommandprompt](https://user-images.githubusercontent.com/29739578/229161551-1aaea283-cefe-46b9-9432-997aa80d3ca9.jpg)


3.  If you want to save this program as a downloadable application/.exe file,  open command prompt and install pysintaller using pip command:
  
    pip install pyinstaller 
    
    
 6. After installing pyinstaller to your source folder, make the program into an executable file (.exe)-- type the following script in your command prompt:
  
  pyinstaller --onefile startup_programs.py

![pybeta](https://user-images.githubusercontent.com/29739578/229137759-ecb49d6c-c628-469b-b24a-da65083318e7.jpg)



![Screenshot 2023-03-31 093630](https://user-images.githubusercontent.com/29739578/229135223-60005d5b-24d4-4bc9-8a81-f3b92353aae9.png)
