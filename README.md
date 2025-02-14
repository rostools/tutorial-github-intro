# TODO TITLE

## Description

TODO: Very brief intro, motivation, and overview of tutorial.

This repository contains the lesson, lecture, and assignment material
for the tutorial, including the website source files and other associated
tutorial administration files.

For more detail on the tutorial, check out the [welcome page]().

## Instructional Design

The lectures and lessons in this tutorial are designed to be presented
primarily with a participatory live-coding approach. This involves an
instructor typing and running code in
[RStudio](https://posit.co/products/open-source/rstudio/) in front of
the class, while the class follows along using their own computers.
Challenges are interspersed in the lesson material, allowing
participants to collaboratively work on smaller coding problems for a
few minutes. All lesson materials are provided ahead of time on the
tutorial website for participants to refer to during lectures.

## Lesson content

The teaching material is found mainly in these locations:

- `index.Rmd`: Contains the overview of the tutorial.
- `preamble/` folder: Contains the files necessary for use before the
    tutorial, for instance the syllabus, schedule, and pre-tutorial tasks.
- `sessions/` folder: Contains the files used during the tutorial (e.g.
    code-along material)
- `appendix/` folder: Contains the files used to support the tutorial,
    such as pre-tutorial tasks, code of conduct, resources, and
    instructions for instructors.
- `slides/`: The lecture slides are rendered into HTML slides from
    Markdown.

The website is generated from [Quarto](https://quarto.org/), so it
follows the file and folder structure conventions from that package.

## Contributing

If you are interested in contributing to the tutorial material, please
refer to the [contributing guidelines](CONTRIBUTING.md). For guidelines
on how to be a helper or instructor, check out the [For
Instructors](https://r-cubed.rostools.org/for-instructors.html) page.

Please note that the project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By contributing to or being involved in
this project, you agree to abide by its terms.

## Re-use

The tutorial is largely designed to be taught in the order given, as each
session builds off of the previous ones. The easiest way to use this
material is to use it as-is, making use of the tips and instructions
found throughout this page. The only thing you might want to make as
your own would be the slides, however, they are also good enough to use
on their own too.

But if you want to customize a bit more, the best approach is to [fork
the repository](TODO) into your own GitLab account and modify it to fit your
needs from there. The website is built automatically with GitHub Actions
and then published as a website through Netlify. More detail on how to
build your own website from the material is outside the scope of this
document but you can find more information on Quarto's
[Publishing](https://quarto.org/docs/publishing/) page.

To help with general admin tasks of running the tutorial, there is the
[r3admin](https://github.com/rostools/r3admin) R package. For details of
the license and acknowledgement of content used from sources, see the
[license](TODO) page of the website.

### How to cite the material

Please cite the material as:

> TODO: Update

Or as BibTeX:

TODO: Update
