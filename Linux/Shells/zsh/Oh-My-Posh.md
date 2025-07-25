Setup:
1) Install a nerd font
2) Configure terminal to use font and zsh
3) add to .profile:
	- /home/clayton/.local/bin
4) curl -s https://ohmyposh.dev/install.sh | bash -s
5) customize prompt
	- add as last line of ~/.zshrc:
		- eval "$(oh-my-posh init zsh)"
6) reload shell:
	- exec zsh
7) custom theme
	- https://ohmyposh.dev/docs/themes
	- download themes:
		- oh-my-posh get themes --output ~/.poshthemes
