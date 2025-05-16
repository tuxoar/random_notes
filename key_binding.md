# Key Bindings Are Key
To enable the home, end and pg up / down bindings to your zsh, add the following to `~/.zshrc`:
````
bindkey '\e[H' beginning-of-line
bindkey '\e[F' end-of-line
bindkey '\e[5~' up-line-or-history
bindkey '\e[6~' down-line-or-history
````

For bash: 
````
"\e[H": beginning-of-line
"\e[F": end-of-line
"\e[5~": previous-history
"\e[6~": next-history
````

For vim: 
````
map <Home> ^
imap <Home> <Esc>^i
map <End> $
imap <End> <Esc>$a
````
