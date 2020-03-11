# Make Coding Easy
### 1. **VS code task config** to make **competitive programming** easy and **programme ananlysis** ! <br>

This is a **.json** file which will help you to run your **cpp** file with one **click** or **shortcut**.
In this case , you **don't** need to write **input** in the command line or write **fopen** / **close** stuffs , programme will take input from a file **(input.txt)** automatically and give the output in another file **(output.txt)** .<br>
<br>
You can also find the programme **runtime status** which will help  you to calculate **execution time** as well as **memory usage** and many more !<br>

pre-requirments : 
- Visual Studio Code
- gcc/g++
- install Code Runner extension by Jun Han (if required)
- time 
  - install time : ```sudo apt install time```

How to setup :
- Go to Configure Default Build Task...
  - In Menu bar 
    - select Terminal
    - Configure Default Build Task
    - will get a  tasks.json file
    - replace the file with my tasks.json file or copy paste
    - save 
    - done 
    
Usage :
- Run : 
  - Shortcut type : **`ctrl+shift+b`** 
- You nee to give the input in the **input.txt** file
- output will be shown in the **output.txt** file
- ##### Bonus : programme status will be shown in the **sys.txt** file 
- people concern about more details such as **binary form** and **disassemble code** can check `tasks(more).json` file

### 2. VS CODE Snippet :
  - Download the cpp.json file 
  - Select User Snippets under **File** > **Preferences (Code > Preferences on macOS)**, and then select **cpp.json** 
  - copy or replace the cpp.json file with downloaded file and save !

### Happy Coding with VS Code
