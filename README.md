# DocImg

DocImg comes with four programs, `docimg`, `imgdoc`, `docimg2`, `imgdoc2`.

* `docimg` paints one pixel per byte and doesn't make use of the alpha channel.
`imgdoc` can be used to convert a picture from `docimg` back into the original
file.
* `docimg2`, on the other hand, shoves up to three bytes into each pixel and
does make use of the alpha channel. Thus, `docimg2` produces smaller file sizes
and only about a third of the pixels that `docimg` produces. `imgdoc2` can be
used to convert a picture from `docimg2` back into the original file.

## Getting Started
Open up your terminal and execute the following:
```sh
$ git clone https://github.com/Python3-8/docimg.git DocImg
$ cd DocImg
```

### Running on Linux
On Linux, DocImg's programs can be run with ease, as shown below.
```sh
$ ./docimg -h
usage: docimg [-h] input output

DocImg, convert any file into a PNG image to share anywhere.

positional arguments:
  input       The input document to convert to PNG.
  output      The output filepath to save to.

optional arguments:
  -h, --help  show this help message and exit
```

### Running on Windows
Running on Windows is a little bit different from on Linux but it is also
very easy.
```sh
$ python3 docimg -h
usage: docimg [-h] input output

DocImg, convert any file into a PNG image to share anywhere.

positional arguments:
  input       The input document to convert to PNG.
  output      The output filepath to save to.

optional arguments:
  -h, --help  show this help message and exit
```

### Commands
Adding the `-h` flag to any of the four scripts displays its clearly described
usage, which can help in using the program.
