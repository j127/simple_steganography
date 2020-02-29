# Simple Steganography

This is a quick example of how to hide data in image files using the `cat` command.

After cloning this repo, run these commands:

```text
$ cd data
$ cat kitten.jpg secrets.zip > output/pic.jpg
$ cat kitten.png secrets.zip > output/pic.png
```

- If you open `pic.jpg` you will see the image.
- If you change the file extension to `pic.zip` you can extract the zip file.
- You can also split the image from the zip file with `split -b 175499 output/pic.png` where `175499` is the size of the image in bytes.

Read more [here](https://www.ostechnix.com/hide-files-inside-images-linux/).

The included images are in the public domain.
