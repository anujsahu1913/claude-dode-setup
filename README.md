
Process to setup claude code in VSCode

First purchase pro plan.
Go to the terminal and paste 
curl -fsSL https://claude.ai/install.sh | bash

Output:

<img width="843" height="373" alt="image" src="https://github.com/user-attachments/assets/b1aba49b-819a-4c49-bde8-a3e189bbcbf4" />
 
Note: Since this path ~/.local/bin was not my native path for claude installation hence need to run

Run echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc

Go to your project directory say ~/projects/senecadairy/2026/May/15/bigcommerce-api/

Now run claude

Output:

<img width="1904" height="239" alt="image" src="https://github.com/user-attachments/assets/443961b7-a58c-445a-87f7-4f6e5ad55a41" />


Here is the input field in the terminal itself – now ask your query right here in your code base. This will read the entire directory and help you in many ways.
