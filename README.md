# Simple Steganography

This is a quick example of how to hide data in image files using the `cat` command.

After cloning this repo, run these commands:

```text
$ cd data
$ cat kitten.jpg secrets.zip > output/pic.jpg
```

- If you open `pic.jpg` you will see the image.
- If you change the file extension to `pic.zip` you can extract the zip file.
