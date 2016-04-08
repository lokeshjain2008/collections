### i always thought of having to delete and navigate in command line/terminal. But this sucks. 
Finally i got how to move in the terminal.

- ctrl+A :Naviagate to the begining of line
- ctrl+E :End of the line
- ctrl+K :Delete till the cursor
- ctrl+W :Delete the word
- ctrl+u :Delete the whole line
- pbcopy :get the copy
- pbpaste :Make the paste
- ctrl+r :will do the recursive search in the command history.

## tricks
1. use variable in the command line: 

```bash
☁  one_blog [master] work=date 
☁  one_blog [master] echo ${work}
date
☁  one_blog [master] ${work}
Fri Apr  8 12:23:14 IST 2016
☁  one_blog [master] echo "Hey string interpolation ${work}"
Hey string interpolation date
☁  one_blog [master] echo "we can run in the string using ``"
we can run in the string using 
☁  one_blog [master] echo `Tell me the time devoted in the work ${work}`
zsh: command not found: Tell

☁  one_blog [master] echo "Tell me the time devoted in the work `${work}`"
Tell me the time devoted in the work Fri Apr  8 12:24:52 IST 2016


```

### `export` command explained 
Follow the [link](http://how-to.linuxcareer.com/learning-linux-commands-export) for detailed explanation and use of `export`




