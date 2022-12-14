# Click Spikes Assessments
## **Requirements**
1. [Julia](https://julialang.org/downloads/)
2. [NodeJS](https://nodejs.org/en/download/)
3. [Git](https://git-scm.com/downloads)
4. [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VSCode extension or [Serve](https://www.npmjs.com/package/serve) NodeJS package

## **Installation**
* Install [Julia](https://julialang.org/downloads/) and [NodeJS](https://nodejs.org/en/download/)
* To check julia and nodejs install correctly on the machine, open terminal and run the below command.

    **NodeJS**
    ```sh
    node -v
    npm -v
    ```
    **Julia**
    ```sh
    julia -v
    ```
    **Git**
    ```sh
    git --version
    ```
    **NOTE**: If the above command not work then try to add path to the environment variable.
* Install [Serve](https://www.npmjs.com/package/serve) package globally from npm.
    ```
    npm install --global serve
    ```
    To see serve package install or not, run the below command to terminal
    ```
    serve -v
    ```
    ![Install tools](https://img001.prntscr.com/file/img001/2Va-ENO9QSa3y2yuxq7zoQ.png)

    **<center>OR</center>**

    [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) VSCode extension for those who are using [Visual Studio Code](https://code.visualstudio.com/) editor
    
    ![VSCode Live Server Extension](https://img001.prntscr.com/file/img001/ReCGLAHETgm8jHLIigguZA.png)
* Now clone this project and go to the project directory
    ```
    git clone https://github.com/nobir/ClickSpikesInterviewAssignment.git
    cd ClickSpikesInterviewAssignment
    ```

## **FAQs**
### **How to run the Application?**
  1. Open terminal and go to project directory
      ```
      cd ~/path/to/project
      ```
      ![Project Directory](https://img001.prntscr.com/file/img001/laf7FrWxQ6Wbr2Flj7BtiQ.png)
  2. Then run nodejs application
      ```
      node node_server.js
      ```
      it will create a local server `http://localhost:8080/`
  3. After that open another terminal and go to the project directory and run the below command for running the front-end application
      ```
      serve -s ./
      ```
      It will create a local server `http://localhost:3000/`
      ![Serve](https://img001.prntscr.com/file/img001/tveVeEqASWCHceY9Uk8NIA.png)

      **<center>OR</center>**

      open the project folder in vscode and open the `index.html`. Now, right click anywhere in the editor and click the option called `Open with Live Server`
      ![Open with Live Server](https://img001.prntscr.com/file/img001/c4HPnShdS--HOeQiVQxi6A.png)
      It will create a local serve `http://localhost:5500/`
  4. Now go to the default browser and hit the `http://localhost:3000/` or `http://localhost:5500/` depending on which localhost tool are using
### **Why you have commented like `@type {HTMLElement} parentElement` to the script.js?**
  >The first reason is that I am using VSCode. If I commented like this, I could get the intelligence from the VSCode. It helps me a lot and at the same time it abstractly describes what the statement does.