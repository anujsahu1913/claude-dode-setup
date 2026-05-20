
                                  **Process to setup claude code via SSH on linux **

1- First purchase pro plan. Also for free with Free API Keys.

2- Go to the terminal and paste 
curl -fsSL https://claude.ai/install.sh | bash

Output:

<img width="843" height="373" alt="image" src="https://github.com/user-attachments/assets/b1aba49b-819a-4c49-bde8-a3e189bbcbf4" />
 
Note: Since this path ~/.local/bin was not my native path for claude installation hence need to run

3- Run echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc

4- Go to your project directory say ~/projects/******/******/******/custom-api/

5- Now run claude

Output:

<img width="1904" height="239" alt="image" src="https://github.com/user-attachments/assets/443961b7-a58c-445a-87f7-4f6e5ad55a41" />

Here is the input field in the terminal itself – now ask your query right here in your code base. This will read the entire directory and help you in many ways.

<img width="1718" height="190" alt="image" src="https://github.com/user-attachments/assets/9e7f145d-6a1f-4d8a-b517-49c43f07ec06" />




                                  **Process to setup claude code in VSCode**

1- Here you need to go to Extension->Find Claude Code-> Click Install

Extension will look something like this:

<img width="1315" height="197" alt="image" src="https://github.com/user-attachments/assets/e771ae38-f5a0-49e4-89e7-a597ff8eef08" />

2- After installation you will get an option to login into claude account. Here are the options you gonna see.

<img width="679" height="595" alt="image" src="https://github.com/user-attachments/assets/84a205c2-6d05-43c1-91f5-c8ceacaf328e" />

3- If you have paid subscription click on the first option i.e. Claude.ai Subscription.

4- They may take you for 2FA authentication via phone number or email.

5- After sucessfully logged in you will be having the option to use Claude in your VSCode.

6- Here write your prompt an that will help you out in your project.

<img width="446" height="380" alt="image" src="https://github.com/user-attachments/assets/a2ba7849-5ae9-43e2-b691-a3d4c57731e5" />

