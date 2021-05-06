# SICP Python epub compatible

I love the rewriting of [SICP with the Python language](https://www-inst.eecs.berkeley.edu//~cs61a/sp12/book/), distributed and parallel computing... But we just found it in HTML so I've decided to convert it in any format using `pandoc`

## Steps

If you don't want to build by yourself you can just download the ebook.epub. Otherwise you have to:

1. Install pandoc, on macOS just use `brew install pandoc`
2. Buil all chapters

```
pandoc introduction.md 01-building-abstractions-with-functions/1.1-introduction.md 01-building-abstractions-with-functions/1.2-the-elements-of-programming.md 01-building-abstractions-with-functions/1.3-define-new-functions.md 01-building-abstractions-with-functions/1.4-pratical-guidance-the-art-of-the-function.md 01-building-abstractions-with-functions/1.5-control.md 01-building-abstractions-with-functions/1.6-high-order-functions.md 02-buiding-abstractions-with-objects/2.1-introduction.md 02-buiding-abstractions-with-objects/2.2-data-abstraction.md 02-buiding-abstractions-with-objects/2.3-sequences.md 02-buiding-abstractions-with-objects/2.4-mutable-data.md 02-buiding-abstractions-with-objects/2.5-object-oriented-programming.md 02-buiding-abstractions-with-objects/2.6-implementing-classes-and-objects.md 02-buiding-abstractions-with-objects/2.7-generic-operations.md 03-the-structure-and-interpretation-of-computer-programs/3.1-introduction.md 03-the-structure-and-interpretation-of-computer-programs/3.2-functions-and-the-processes-they-generate.md 03-the-structure-and-interpretation-of-computer-programs/3.3-recursive-data-structures.md 03-the-structure-and-interpretation-of-computer-programs/3.4-exceptions.md 03-the-structure-and-interpretation-of-computer-programs/3.5-interpreters-for-languages-with-combination.md 03-the-structure-and-interpretation-of-computer-programs/3.6-interpreters-for-languages-with-abstraction.md 04-distributed-and-parallel-computing/4.1-introduction.md 04-distributed-and-parallel-computing/4.2-distributed-computing.md 04-distributed-and-parallel-computing/4.3-parallel-computing.md 05-sequences-and-coroutines/5.1-introduction.md 05-sequences-and-coroutines/5.2-implicit-sequences.md 05-sequences-and-coroutines/5.3-coroutines.md -o ebook.epub --css style.css --epub-cover-image=cover.jpg
```

## Bugs

I know there are some formatting issues, I'm gonna quickly fix them, or you can open a PR.