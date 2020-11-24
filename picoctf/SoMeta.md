This is a forensics challenge mainly focusing observing and analysing metadata in image files.

For this challenge, we will be using `exiftool` in Ubuntu. Run the command `exiftool pico_img.png` to view all the metadata of the image file. WE will obtain the following output:
```
ExifTool Version Number         : 11.88
File Name                       : pico_img.png
Directory                       : .
File Size                       : 106 kB
File Modification Date/Time     : 2020:11:25 01:29:43+08:00
File Access Date/Time           : 2020:11:25 01:30:00+08:00
File Inode Change Date/Time     : 2020:11:25 01:29:59+08:00
File Permissions                : rwxrwxrwx
File Type                       : PNG
File Type Extension             : png
MIME Type                       : image/png
Image Width                     : 600
Image Height                    : 600
Bit Depth                       : 8
Color Type                      : RGB
Compression                     : Deflate/Inflate
Filter                          : Adaptive
Interlace                       : Noninterlaced
Software                        : Adobe ImageReady
XMP Toolkit                     : Adobe XMP Core 5.3-c011 66.145661, 2012/02/06-14:56:27
Creator Tool                    : Adobe Photoshop CS6 (Windows)
Instance ID                     : xmp.iid:A5566E73B2B811E8BC7F9A4303DF1F9B
Document ID                     : xmp.did:A5566E74B2B811E8BC7F9A4303DF1F9B
Derived From Instance ID        : xmp.iid:A5566E71B2B811E8BC7F9A4303DF1F9B
Derived From Document ID        : xmp.did:A5566E72B2B811E8BC7F9A4303DF1F9B
Warning                         : [minor] Text chunk(s) found after PNG IDAT (may be ignored by some readers)
Artist                          : picoCTF{s0_m3ta_d8944929}
Image Size                      : 600x600
Megapixels                      : 0.360
```

Observing the output closely, we observe that the flag is actually hidden in the `Artist` field of the metadata.

Flag is : `picoCTF{s0_m3ta_d8944929}`