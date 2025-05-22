### BRAIN DUMP
<hr>

#### _"This file is my brain’s backup, stuffed with solutions, hacks, and how-tos for everything from coding chaos to operating system mysteries (and whatever else I’ve forgotten how to do... again)."_
<br>

### Memory Lane

[A](#a) • [B](#b)  • [C](#c) • [D](#d) • [E](#e) • [F](#f) • [G](#g) • [H](#h) • [I](#i) • [J](#j) • [K](#k) • [L](#l) • [M](#m) • [N](#n) • [O](#o) • [P](#p) • [Q](#q) • [R](#r) • [S](#s) • [T](#t) • [U](#u) • [V](#v) • [W](#w) • [X](#x) • [Y](#y) • [Z](#z)

<hr>
<br>

<!-- 
  • Example of Issue and Solution block
  #### HEADING
  - #### **Name problem is related to**
    - **[SOLUTION #]** _Small solution code example_
      - **ISSUE:** 
      - > What issue did you experience
      - **SOLUTION:** 
      - > The solution that worked
 -->

### A
###### [_Back to Memory Lane_](#memory-lane)


<br>

### B
###### [_Back to Memory Lane_](#memory-lane)

#### BASH ALIASES
  - #### **Setting up Bash Aliases**
    - **[SOLUTION]** _alias mkdir='mkdir -v'_
      - **ISSUE:** List of bash aliases
      - > Can never remember bash aliases
      - **SOLUTION:** 
      - > alias mkdir='mkdir -v'
      - > alias cp='cp -v'
      - > alias rm='rm -vrfi'
      - > alias updateme='sudo zypper dup && sudo zypper up && sudo omz update'

<br>

### C
###### [_Back to Memory Lane_](#memory-lane)

#### CSS
- #### **Root Variable Layout**
  - **[SOLUTION #]** _..._
    - **ISSUE: Can never remember my root variable setup** 
    - > This is just my .css root variable structure for how I develope my websites.
    - **SOLUTION:** 
    - > ```css
      >     :root {
      >     /* generic document setup */
      >     /* typeface */
      >     --typeface-inter: 'Inter', sans-serif;
      >     --typeface-ssp: 'Source Sans 3', sans-serif;
      > 
      >     /* percentage fonts */
      >     --percentage-font-10: 62.5%;
      >     --percentage-font-9: 56.25%;
      >     --percentage-font-8: 50%;
      >     --percentage-font-7: 43.75%;
      > 
      >     /* font size */
      >     --font-10: 1rem;
      >     --font-12: 1.2rem;
      >     --font-14: 1.4rem;
      >     --font-16: 1.6rem;
      >     --font-18: 1.8rem;
      >     --font-20: 2rem;
      >     --font-24: 2.4rem;
      >     --font-30: 3rem;
      >     --font-32: 3.2rem;
      >     --font-36: 3.6rem;
      >     --font-44: 4.4rem;
      >     --font-52: 5.2rem;
      >     --font-62: 6.2rem;
      >     --font-74: 7.4rem;
      >     --font-86: 8.6rem;
      >     --font-98: 9.8rem;
      > 
      >     /* font weight */
      >     --font-weight-400: 400;
      >     --font-weight-500: 500;
      >     --font-weight-700: 700;
      > 
      >     /* spacing system */
      >     --spacing-2: 0.2rem;
      >     --spacing-4: 0.4rem;
      >     --spacing-8: 0.8rem;
      >     --spacing-12: 1.2rem;
      >     --spacing-16: 1.6rem;
      >     --spacing-24: 2.4rem;
      >     --spacing-32: 3.2rem;
      >     --spacing-48: 4.8rem;
      >     --spacing-64: 6.4rem;
      >     --spacing-80: 8rem;
      >     --spacing-96: 9.6rem;
      >     --spacing-128: 12.8rem;
      > 
      >     /* border radius */
      >     --border-rad-05: 0.5rem;
      >     --border-rad-1: 1rem;
      >     --border-rad-100: 10rem;
      >     --border-rad-round: 50%;
      > 
      >     /* line height */
      >     --line-height-1: 1;
      >     --line-height-11: 1.1;
      >     --line-height-15: 1.5;
      >     --line-height-17: 1.7;
      > 
      >     /* letter spacing */
      >     --letter-space-n05: -0.5px;
      >     --letter-space-n1: -1px;
      >     --letter-space-p05: 0.5px;
      >     --letter-space-p1: 1px;
      > 
      >     --clr-shadow: hsl(210, 16%, 25%);
      >     --clr-background-shade: hsl(210, 38%, 35%);
      >     --clr-background-main: hsl(210, 38%, 90%);
      >     --clr-background-tint: hsl(210, 38%, 95%);
      >     --clr-headline: hsl(210, 52%, 10%);
      >     --clr-paragraph: hsl(210, 28%, 25%);
      >     --clr-stroke: hsl(210, 8%, 92%);
      >     --clr-accent: hsl(0, 0%, 70%);
      >     --clr-accent-tint: hsl(0, 0%, 80%);
      >     --clr-button: hsl(210, 10%, 85%);
      >     --clr-button-text: var(--clr-shadow);
      >     --clr-button-before: linear-gradient(140deg,
      >         hsl(0, 0%, 97%),
      >         hsl(0, 0%, 67%));
      >     --clr-button-plus: var(--clr-accent-tint);
      >     --clr-button-plus-text: var(--clr-shadow);
      >     --clr-button-plus-before: linear-gradient(140deg,
      >         var(--clr-accent-tint),
      >         var(--clr-accent));
      >     --clr-button-shadow: var(--clr-shadow);
      >   }
      > ```

<br>
 
### D
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### E
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### F
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### G
###### [_Back to Memory Lane_](#memory-lane)

#### **GIT SETUP**
- #### **Fresh setup of git on a new system**
  - **[SOLUTION]** _git config --list/--global_
    - **ISSUE:** 
    - > Setting up Git for the first time on a new machine, can never remember the basic config commands.
    - **SOLUTION:** 
    - > • git config --global user.name 'Set username here'
      - _Sets your username._
    - > • git config --global user.email 'Set email here'
      - _Sets your email._
        - **‼️IMPORTANT NOTE:** _Make sure you email is set the same as your GitHub accounts email, otherwise you will not see your contributions displayed on your page._
    - > • git config --global code.editor 'code --wait'
      - _Sets your editor for commit messages._
    - > • git config --global commit.template ~/path/to/commit-template.txt
      - _Sets the default commit message template to a custom template._
    - > • git config --list
      - _Lists or Displays your git config file._

#### **GIT COMMIT TEMPLATE**
  - #### **My custom Git commit template**
    - **[SOLUTION]** _git config --global commit.template ~/path/to/commit-template.txt_
    - **ISSUE:**
    - > ```txt
      > # ------------------------ COMMIT MESSAGE TEMPLATE ------------------------
      > # <type>(<scope>): <short summary>
      > # 
      > # A short, imperative summary of your change (max 50 characters).
      > # Use the present tense (e.g., "add", not "added" or "adds").
      > # 
      > # Example:
      > #   feat(navbar): add responsive menu toggle
      > 
      > # Optional body:
      > # 
      > # Explain *what* and *why* the change was made, not *how*.
      > # Wrap lines at 72 characters.
      > #
      > # Example:
      > # Updated the mobile navigation to use flexbox for layout,
      > # improving accessibility and consistency across screen sizes.
      > 
      > # Optional footer:
      > # 
      > # Use to reference issues or note breaking changes.
      > #
      > # Example:
      > # Closes #42
      > # BREAKING CHANGE: updated auth flow now requires re-login
      > 
      > # ------------------------ TYPE LEGEND ------------------------
      > # Common types you can use:
      > #
      > # feat:     A new feature
      > # fix:      A bug fix
      > # docs:     Documentation only changes
      > # style:    Visual or formatting changes (CSS, spacing, no logic)
      > # refactor: Code refactoring (no new features or fixes)
      > # test:     Adding or updating tests
      > # chore:    Other changes (build, tooling, CI, etc.)
      > #
      > # ------------------------ SCOPE EXAMPLES ------------------------
      > # Examples of scopes (where the change happened):
      > # navbar, auth, css, homepage, api, theme, footer, etc.
      > ```

<br>

#### GIT IGNORE
- #### **Default Git Ignore File**
  - **[SOLUTION #]** _touch .gitignore_
    - **ISSUE: Can never remember which files to exclude in my repositories** 
    - > These are the files to add to your .gitignore file
    - **SOLUTION:** 
    - > ```
      > #### • Personal Files
      > exercise-files/
      >
      > #### • Operating System Files
      > .DS_Store
      > Thumbs.db
      > desktop.ini
      >
      > #### • IDE and Text Editor Files
      > .idea/
      > .vscode/
      > *.pyc
      > __pycache__/
      > .project
      >
      > #### • Virtual Environments
      > venv/
      > env/
      >
      > #### • Dependency Management
      > node_modules/
      > yarn.lock
      > package-lock.json
      >
      > #### • Compiled Code and Binaries
      > *.class
      > *.jar
      > *.war
      > *.pyc
      >
      > #### • Logs and Temporary Files
      > *.log
      > *.tmp
      >
      > #### • Configuration Files
      > .env
      > .env.local
      > *.config
      > #### • Web Development
      > public/
      > build/
      >
      > #### • Miscellaneous
      > .travis.yml
      > .coverage
      >
      > #### • Personal Configuration
      > .vscode/settings.json
      > .editorconfig
      > ```

<br>
 
### H
###### [_Back to Memory Lane_](#memory-lane)



<br>
 
### I
###### [_Back to Memory Lane_](#memory-lane)



<br>
 
### J
###### [_Back to Memory Lane_](#memory-lane)



<br>
 
### K
###### [_Back to Memory Lane_](#memory-lane)



<br>
 
### L
###### [_Back to Memory Lane_](#memory-lane)

#### LINUX SETUP
  - #### **Linux fresh setup**
    - **[SOLUTION #]** _Curl/Vim/Git/Zsh/OMZ_
      - **ISSUE:** All things needed to setup your DevEnv
      - > Can never remember what is needed to install after a long time of using a specific OS, and where to find what.
      - **SOLUTION:** 
      - > Install Vim, Git, Curl, Zsh and then OMZ (oh my zshell)
      - > install [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions/blob/master/INSTALL.md) & [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting/blob/master/INSTALL.md)
      - > vim .zshrc and add your plugins, save & exit and source .zshrc
      - > touch .bash-aliases, create your bash aliases _[found here](#bash-aliases)_
      - > vim .zshrc and at the bottom add source $HOME/.bash_aliases


#### LIVE-SERVER (NPM)
  - #### **live-server installation using NPM**
    - **[SOLUTION #]** _npm search live-server/npm install -g live-server_
      - **ISSUE:** live-server installation through NPM
      - > As I usually only do this process once, I tend to forget the command for installing live-server globally using NPM (Node Package Manager).
      - **SOLUTION:** 
      - > First search the package name using `npm search live-server`.
      - > Then install live-server globally using `npm install -g live-server`.
      - > Then once in project folder, you can run `live-server`.

<br>
 
### M
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### N
###### [_Back to Memory Lane_](#memory-lane)

#### NODE.JS Installation
  - #### **Node.js Installation setup**
    - **[SOLUTION #]** _https://nodejs.org/en/download_
      - **ISSUE:** Node.js installation following site instructions.
      - > Using sudo apt install node, installs older version of node. So better is to follow sites instructions.
      - **SOLUTION:** 
      - > Visit [Node.js Website](https://nodejs.org/en/download)
      - > Follow instructions on Download page for your OS.

<br>
 
### O
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### P
###### [_Back to Memory Lane_](#memory-lane)

#### PYTHON
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
 
### Q
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### R
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### S
###### [_Back to Memory Lane_](#memory-lane)

#### SSH
- #### *ssh-keygen*
  - **[SOLUTION 1]** _ssh-key -t ed25519 -C 'name here'_
    - **ISSUE:** 
    - > Always forgetting the ssh keygen command
    - **SOLUTION:** 
    - > ssh-key -t ed25519 -C 'name here'

<br>
 
### T
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### U
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### V
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### W
###### [_Back to Memory Lane_](#memory-lane)

#### WSL
- #### **Connection issues**
   - **[SOLUTION 1]** _sudo vim /etc/resolv.conf_
      - **ISSUE:** WSL2 lost connection for no reason! 
      - > **SOLUTION:** Try checking if the nameserver address has changed. This solution worked for me when connection stopped working for no reason, The solution was changing the nameserver to 8.8.8.8.

<br>
 
### X
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### Y
###### [_Back to Memory Lane_](#memory-lane)


<br>
 
### Z
###### [_Back to Memory Lane_](#memory-lane)


<br>