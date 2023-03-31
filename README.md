# startup

Are you tired of pesky programs that open when you startup your computer? 


## Copy code from my github repositories. 

1.  Visit https://github.com/guzmanwolfrank/startup/blob/main/startup_programs.py and copy the code and save it in a text editor like notepad and name the file 
startup_programs.py. 

## Open Command Prompt 
2.  Open the Run dialog box. The Run dialog box, which you can open using the keyboard shortcut Win + R, allows you to open any Windows program by entering its name. Enter “cmd” and click “OK” to open Command Prompt.
![run](https://user-images.githubusercontent.com/29739578/229162515-c7f56abb-6a73-4013-8455-e1b8f7abe44e.jpg)

4.  Open the command prompt 

2.  Choose which file you want to remove from starting up when you start your computer. 

![startupcommandprompt](https://user-images.githubusercontent.com/29739578/229161551-1aaea283-cefe-46b9-9432-997aa80d3ca9.jpg)


3.  If you want to have this file as an executable file, open command prompt and install pysintaller using pip command:
  
    pip install pyinstaller 
    
    
  To make this an executable file (.exe)-- type the following script:
  
  pyinstaller --onefile startup_programs.py

![pybeta](https://user-images.githubusercontent.com/29739578/229137759-ecb49d6c-c628-469b-b24a-da65083318e7.jpg)


  
## Removes selected programs from windows automatic startup. 

![Screenshot 2023-03-31 093247](https://user-images.githubusercontent.com/29739578/229135201-ec648bbd-947a-45f2-b3bd-f85e5bae4b4d.png)

## Use command prompt and run the python file to then see which file you want to delete from startup. 



![Screenshot 2023-03-31 093630](https://user-images.githubusercontent.com/29739578/229135223-60005d5b-24d4-4bc9-8a81-f3b92353aae9.png)
