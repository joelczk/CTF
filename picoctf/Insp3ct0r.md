This is a web exploitation challenge.
Upon inspecting the source code of the website, we find a comment:
```
<!-- Html is neat. Anyways have 1/3 of the flag: picoCTF{tru3_d3 -->
```

We also find that there are 2 other files that we can view --> `mycss.css` and `myjs.js`

Upon inspecting the source code of `mycss.css`, we find the following commented out code:
```
/* You need CSS to make pretty pages. Here's part 2/3 of the flag: t3ct1ve_0r_ju5t */
```

And inspecting the source code of `myjs.js`, we find the following commented out code:
```
/* Javascript sure is neat. Anyways part 3/3 of the flag: _lucky?2e7b23e3} */
```

Piecing the 3 comments together, we get that the flag is : `picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?2e7b23e3}`