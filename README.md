## Getting Started

Run `rake doctor` to find any potential missing dependencies on your system. To do this you're going to need [Rake](http://rake.rubyforge.org/). It can be installed with:

    gem install rake

If this doesn't work then you'll need to install [Ruby](http://ruby-lang.org).

Next, you're going to want to open up `report.tex` and change the details at the top to be yours. I'd love it if you all submitted your thesis as me but I don't think that it would be looked too kindly upon.

## Rake Commands

* `rake` - This will build the document and clean up any temporary files.
* `rake build` - This will build the document into a PDF.
* `rake view ` - Display the document.

### Checker Tasks

* `rake check` - Check the document for common errors.
* `rake check:duplicates` - Check the document for accidental duplicate words.
* `rake check:passive` - Check the document for passive speech.
* `rake check:spell` - Spell check the document.
* `rake check:syntax` - Check the document for syntax errors.
* `rake check:weasel` - Check the document for words which aren't useful.

### Misc. Tasks

* `rake clean` - Remove any temporary products.
* `rake clobber` - Remove any generated file.
* `rake count` - Count the number of words in the document.

