#### • useful-solutions
### This file is solely for remembering solutions on how to do things, topics can range from programming to OS solution and more.

<br>

#### • NAVIGATION
- [Python](#•-python)
  - [Python Virtual Environment](#python-virtual-environment)- 
- [WSL](#•-wsl)
  - [Connection Issues](#connection-issues)

<br>

<!-- 
  • Example of Issue and Solution block
  #### 📚 HEADING
  - **Name problem is related to**
    - **[SOLUTION #]** _Small solution code example_
      - **ISSUE:** 
      - > What issue did you experience
      - > **SOLUTION:** 
      - > The solution that worked
 -->




#### 📚 PYTHON
- #### **Python Virtual Environment**
  - **[SOLUTION]** _python -m venv venv_
    - **ISSUE:**
    - > Trying to use PIP, but need venv
    - **SOLUTION:**
    - > 1. Create a folder either in your home directory or project folder to hold your venv with `mkdir venvs`.
    - > 2. `cd venvs` and then initialize `python3.11 -m venv my-project-name`
    - > 3. `cd path/of/project` and activate the virtual environment using `source path/of/venvs/project-name/bin/activate`, at which point you terminal should update to indicate you are within the venv surrounded in brackets.
    - > 4. To deactivate the venv, simply run `deactivate` in the terminal to stop.

<br>

#### 📚 WSL
- #### **Connection issues**
   - **[SOLUTION 1]** _sudo vim /etc/resolv.conf_
      - **ISSUE:** WSL2 lost connection for no reason! 
      - > **SOLUTION:** Try checking if the nameserver address has changed. This solution worked for me when connection stopped working for no reason, The solution was changing the nameserver to 8.8.8.8.
