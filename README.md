# macos-phpswitch
Easily switch php version on mac when using brew.


Installation:
1. Create a folder in your home directory named ‘bin’
2. Copy this code in a file with the name ‘phpswitch’
3. Open your terminal, go to the bin folder and run the following command: ‘chmod +x phpswitch’
4. Go back to your home folder, open .bash_profile (or the config file of your terminal e.g. .zshrc), and add "$HOME/bin" to your $PATH, or add the following line when $PATH doesn't exist  ‘export PATH=$PATH”:$HOME/bin”’
5. Restart your terminal. You can now use the 'phpswitch' command
