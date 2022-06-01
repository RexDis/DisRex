# DisRex
Software to Display SIgnage

To open an environment on windows.
1. Launch Powershell as administrator.
2. Change directory to your cloned repo:
    "PS C:\WINDOWS\system32> cd C:\Users\user1\Documents\GitHub\DisRex"
3. Type in the terminal . .\bin\activate
    3b. If you recieve an error/ warning regarding the unsage and running of scripts you must enable scripts with the command "Set-ExecutionPolicy RemoteSigned -Scope CurrentUser" then rerun the command . .\bin\activate
4. You should now see (DisRex) at the start of the line.
5. Now run the command "python mysite\manage.py runserver"
6. You should now see a line similar to "Starting development server at http://127.0.0.1:8000/" Copy this web address in your web browser to view your virtual environment. 
7. To close the environment simply return to powershell and enter the pause-break key. (NOTE: some machines may not have a pause-break. Research your computer's alternative often relating to Fn + Ctrl)
