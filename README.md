----
### <div align="center"> Some useful bash aliases.</div>

----

This README file is an exact copy of the bash_aliases file present in this repository.

----


\# File name: .bash_aliases  
\# Author: Amit Choudhary  
\# Email: amitchoudhary0523 AT gmail DOT com  

<br>

```
# Enable color support of ls and grep.
if [ -x /usr/bin/dircolors ]; then
    test -r ~/.dircolors && eval "$(dircolors -b ~/.dircolors)" || \
                            eval "$(dircolors -b)"
    alias l='ls --color=auto'
    alias ls='ls --color=auto'
    alias grep='grep --color=auto'
fi

alias ll='ls -l'
alias la='ls -A'
alias llh='ll -h'
alias lltr='ll -tr'
alias lltrh='ll -trh'

alias ls1='ls -1'

alias grepl='grep -l'
alias grepn='grep -n'

alias cp='cp -i'
alias mv='mv -i'
alias rm='rm -i'

alias vi='vim'

alias sudo='sudo '
```
