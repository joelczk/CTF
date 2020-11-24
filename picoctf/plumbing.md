This challenge has to do with redirection of the program

One way of doing this is to find for the flag using the `grep` command as follows:
```
nc jupiter.challenges.picoctf.org 4427 | grep "picoCtf"
```

The output obtained will be as follows:
```
picoCTF{digital_plumb3r_5ea1fbd7}
```

The flag is : `picoCTF{digital_plumb3r_5ea1fbd7}`