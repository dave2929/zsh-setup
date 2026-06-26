# zsh-setup
my zsh setup

Install Oh-My-ZSH!
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"  

Install PowerLevel9k!
git clone https://github.com/bhilburn/powerlevel9k.git ~/.oh-my-zsh/custom/themes/powerlevel9k

TODO:
Customize the Prompt a Bit!
PowerLevel9k has crazy customization options, so you need to check on their wiki, but for the video I went just with:

POWERLEVEL9K_DISABLE_RPROMPT=true
POWERLEVEL9K_PROMPT_ON_NEWLINE=true
POWERLEVEL9K_MULTILINE_LAST_PROMPT_PREFIX="▶ "
POWERLEVEL9K_MULTILINE_FIRST_PROMPT_PREFIX=""


https://medium.com/@alex285/get-powerlevel9k-the-most-cool-linux-shell-ever-1c38516b0caa


Install zsh-autosuggestions
Install zsh-syntax-highlighting
https://tcude.net/enabling-command-autocomplete-in-zsh/
ripgrep or grep

review all oh-my-zsh plugins
https://hamvocke.com/blog/a-quick-and-easy-guide-to-tmux/
