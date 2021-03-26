# chat
Anonymous Encrypted Chat over TOR network
* The program is for linux/ubuntu distros.
* The requieremnts are:
*  tor service # sudo apt install tor
* python modules: pip install cython socks cryptography errno select
* run with command python3 Anon_Crypt_chat.py
* [1]create server (installs tor service and creates a hidden serice which will use for chat server)
* [2]load server (opens 3 tabs,1 - runs python server,2 - runs tor server,3 - the main menu from which we enter in the chat).
* [3]enter chat (enter in the chat when you are done with the server).
