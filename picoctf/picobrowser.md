For this challenge, the main gist is to change the `User-agent` of the browser

To solve this challenge, run the follow command:
```
 curl --user-agent "picobrowser" "https://jupiter.challenges.picoctf.org/problem/28921//flag" | grep "pico"
```

The output obtained will be as follows:
```
<p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{p1c0_s3cr3t_ag3nt_84f9c865}</code></p>
```


The flag is : `picoCTF{p1c0_s3cr3t_ag3nt_84f9c865}`