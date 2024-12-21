# My Config Git

    [alias]
    	s = !git status -s
    	c = !git add --all && git commit -m
            ca = !git add --all && git cz
    	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'


- git config --global core.editor code
- git config --global --edit
