<!-- This file is automatically generated! -->
<!-- Do not manually edit! To make changes, edit build_readme.md instead. -->

# Getting Started

Click this button [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2FEducationalSciences693%2FTranscriptToCSV/HEAD) to run this project!

You'll find everything you need in `main.ipynb`!

# Files in this Project

- `README.md` That's what you're reading right now! This file is machine generated by the `build_readmd.sh` file.
- `apt.txt`, `Project.toml`, `Manifest.toml`, `config.jl`, and `postBuild` These are used to specify the exact environment needed for our code to run.
- `main.ipynb` This is where your code runs! It is a Jupyter notebook configured to use the [Julia](https://julialang.org/) programming language. It shows an example of running Epistemic Network Analysis to compare two Shakespeare plays.

# About

This script looks for a file in `data/transcript.txt` with format like the following:

```txt
>> Alice: Are we Group 1 or 2? Just the group.

>> Beth Anne: One.

>> Carol: So should we just like throw up a whiteboard and start trying to like collectively sketch a prototype?

>> Alice: Yeah, let's do that. Do we want to do that on Slide 24?
```

It then produces a DataFrame representation of that and stores that as a CSV file.

# Making Edits

Changes that you make on binder are temporary. You can download your files from binder, or you can make your own repo that lives on github.

To make your own repo copy of this project that you can edit:

1. Create a [copy of this template](https://github.com/EducationalSciences693/TranscriptToCSV/generate). It will need to be a public repo, but you can name it whatever you want
2. Create a [github personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token). It will need the `repo` and `workflow` scopes
3. Open your project on binder (the binder button in your README will automatically update to link to your project!)
4. Make edits to your project on binder like you normally would
5. Open a terminal on binder and run:
```sh
git pull
git add --all
git commit -m "some friendly message here"
git push
```
When prompted to enter your password, enter your personal access token instead.
