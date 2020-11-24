This is merely a forensics challenge, playing around with file extensions

Firstly, we have to check the file type using the command `file flag.txt`, and we obtain the following output:
```
flag.txt: PNG image data, 1697 x 608, 8-bit/color RGB, non-interlaced
```

From the above output, we can conclude that the `flag.txt` file is instead a PNG file. Changing the file extension from `flag.txt` to `flag.PNG` will show an image with the flag.

Flag is : `picoCTF{now_you_know_about_extensions}`