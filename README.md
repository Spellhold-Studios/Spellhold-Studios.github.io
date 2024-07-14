# About Spellhold-Studios.github.io
This repository hosts our [GitHub Pages](https://spellhold-studios.github.io/) (currently with the index of mods as the homepage) and HTML readmes of SHS mods, which can be linked to, e.g. from a mod repository.

> GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website. It can be used to create websites for project documentation, online blogs or landing pages.

:link: [About GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)

### Contents

- [How to link to a readme](#thinking-how-to-link-to-a-readme)
- [How to add a readme](#inbox_tray-how-to-add-a-readme)

## :thinking: How to link to a readme

Navigating to the HTML file through GitHub UI will only allow you to view the source of a given readme, which is typically:

```
https://github.com/Spellhold-Studios/Spellhold-Studios.github.io/blob/main/readmes/MOD_REPOSITORY_NAME/README_FILENAME.html
```

Linking to that will result in the browser displaying the GitHub page with the HTML source code rather than the rendered webpage. ([Example](https://github.com/Spellhold-Studios/Spellhold-Studios.github.io/blob/main/readmes/template-gwendolyne/mymod-readme-english.html))

Instead, you need to tap into the actual SHS website deployed via GitHub Pages and access the readme file through a web subdirectory, like so:

```
https://spellhold-studios.github.io/readmes/MOD_REPOSITORY_NAME/README_FILENAME.html
```

This should lead to a rendered HTML readme. ([Example](https://spellhold-studios.github.io/readmes/template-gwendolyne/mymod-readme-english.html))

:warning: **GitHub Pages is case-sensitive** without redirection. This means that if there is a difference in letter case between the link and the actual destination, you will get the "page not found" error.

For example, a given readme filename is `Readme-MyMod.html` and it has been uploaded as `/readmes/my-mod/Readme-MyMod.html` to our Pages. The working link should then be:

```
https://spellhold-studios.github.io/readmes/my-mod/Readme-MyMod.html
```

The following link will get you the 404 error:

```
https://spellhold-studios.github.io/readmes/my-mod/readme-mymod.html
```

Which is why we encourage our Modders to stick to the guidelines in the next section.

## :inbox_tray: How to add a readme

First read our [Contributing Guidelines](https://github.com/Spellhold-Studios/.github/blob/main/CONTRIBUTING.md). If you are an SHS Modder and would like to add your mod readme, e.g. through a pull request, follow these steps:

:one: **Create a dedicated subfolder** named after your mod repository:
   
`Spellhold-Studios.github.io/readmes/MOD_REPOSITORY_NAME/`
   
where `/MOD_REPOSITORY_NAME/` should be lowercase, e.g. `/my-mod/`

`Spellhold-Studios.github.io/readmes/my-mod/`

That way `/readmes/` will keep the alphabetical order of repository subfolders.

:two: **Upload your readmes with their original filenames**, regardless of letter case.

While it would be logical to make your readme filename lowercase for consistency, your project may already have an existing structure of references, e.g. multiple readmes each pointing to other HTML files to switch languages. Unless you want to go through the source code of every single HTML in your mod package, we recommend leaving everything as is. For example:

`Spellhold-Studios.github.io/readmes/my-mod/Readme-MyMod.html`
   
We allow this because the HTML file is stored in its dedicated lowercase subfolder, so it will not affect the alphabetical order of our readme directory.

:three: **Check the previous section on [linking to readmes](#thinking-how-to-link-to-a-readme)**. Following our example, the working link would then be:

```
https://spellhold-studios.github.io/readmes/my-mod/Readme-MyMod.html
```
