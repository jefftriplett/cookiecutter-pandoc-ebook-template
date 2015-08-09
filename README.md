# cookiecutter-pandoc-ebook-template

This project is a cookiecutter wrapper for Evan David Goer's [pandoc-ebook-template](https://github.com/evangoer/pandoc-ebook-template) project which creates ebooks out of Pandoc Markdown.

## Using this template

    $ pip install cookiecutter
    $ cookiecutter https://github.com/jefftriplett/cookiecutter-pandoc-ebook-template.git

You will be prompted for all relevate information.

## Building your book

To build your ebook, first follow [David's instructions](https://github.com/evangoer/pandoc-ebook-template/blob/master/README.rst) to make sure you have:
- [git](http://git-scm.com/)
- [make](http://www.gnu.org/software/make/) (OS X users should install XCode
and [download the command line tools](http://stackoverflow.com/questions/9329243/xcode-4-4-command-line-tools).)
- [pandoc](http://johnmacfarlane.net/pandoc)
- [latex](http://www.latex-project.org/) (OS X users should probably
install [MacTex](http://tug.org/mactex/).)

You should be able to run `make` form inside your ebook's folder to generate your eboo.

    $ make

## License

BSD licensed.
