## Monthly Notices of the Royal Astronomical Society (MNRAS ) - Lyx template

**Update 2017**: Since the creation of this, MNRAS has moved from Wiley-Blackwell to Oxford University Press. The `mn2e.cls` class has been renamed to `mnras.cls`.

This is a (several year old) LyX layout file and example Lyx document for the MNRAS `mn2e.cls` file. 

### Installation

1. Put mn2e.cls in your latex class file directory, mn2e.bst in your latex bibtex directory. 
2. Put mn2e.layout in your lyx layout directory
3. Reconfigure latex 
4. Reconfigure LyX

And you should be all configured.

For example, for me on my mac (with mactex), I would run:

```
cp mn2e.cls ~/Library/texmf/tex/latex/
cp mn2e.bst ~/Library/texmf/bibtex/bst/
cp mn2e.layout ~/Library/Application\ Support/LyX-1.6/layouts/
sudo texhash
```

Then just open LyX, and run reconfigure from the menu. After that you should be good to go, so try opening `mn2esample.lyx` and making a PDF! Happy writing.

### Links

* [MNRAS template on CTAN](http://www.ctan.org/tex-archive/macros/latex/contrib/mnras)

* [MNRAS bibliography](https://github.com/timj/mn2e-bst)

