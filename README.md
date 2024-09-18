# hash-generator
Python hash MD5/SHA-256 generator

Steps to create an executable:

    Install PyInstaller: Open your terminal or command prompt and install PyInstaller using pip:

        pip install pyinstaller

Create the Executable: Once PyInstaller is installed, you can create the executable by running the following command in the same directory as your script:

        pyinstaller --onefile --noconsole your_script_name.py



Explanation of the options:
    --onefile: This tells PyInstaller to package everything into a single executable file.
    --noconsole: This ensures that no terminal or console window is opened when running the application. Since your application has a GUI (tkinter), you don't need the console window.

    Locate the Executable: After running the command, PyInstaller will create a dist directory. Inside this directory, you'll find the standalone executable (for example, your_script_name.exe on Windows).

    Run the Executable: You can now distribute and run this .exe file on any machine without Python installed.

Example:

If your Python script is named file_hash_generator.py, you would run:

bash

pyinstaller --onefile --noconsole file_hash_generator.py

After the process is complete, the executable will be located in the dist/ directory, and you can double-click it to open the application with the GUI.