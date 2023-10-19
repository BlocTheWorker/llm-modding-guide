# LLM Modding Guide - Github Code

<br/>
<div style="text-align:center; overflow:hidden; max-height:400px;">
  <img src="./docs/resource/images/genimg4.jpeg" alt="Cover Image" style="width:90%; height:auto; object-fit:cover; object-position:center;">
</div>
<br/>
<br/>

This is a simple general guide for modders who want to use LLM to modify their favorite games.

### How are pages generated?
It uses `mkdocs` and `mkdocs-material` to read from .md files, and Github CI generates the page whenever a pull request is merged into the main branch.

## Running Locally
You need Python and mkdocs to run it. Refer to the [mkdocs-material getting started page](https://squidfunk.github.io/mkdocs-material/getting-started/) to see what you need.

## How can you contribute?
Did you notice something that needs to be updated? Or do you have more information you want to share about this subject? Or do you want this document to reach more people by translating it? Then you can simply create your branch and make a Pull request to the main branch.

### How to translate?
- Edit the mkdocs.yml file and add your language.
```yml
languages:
    ...
        - locale: cst
          name: Custom
          build: true
```
- Create a folder with the locale name, which is `cst` in this case.
- Copy the content of the `en` folder and translate the .md files.
Done! It should show up in the language dropdown.


