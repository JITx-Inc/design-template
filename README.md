# Getting started with a JITX Design

Select the green `Use This Template` button towards the top of this page and create a new repository. If you do not see this button, sign into GitHub.

Name your repository, select private or public, and select `Create repository from template` The repository will be created.

Select the green `Code` button and select the little clipboard icon to copy the repository source location

In a terminal window on your machine, clone your repository by typing `git clone --recursive ` and paste in the location you copied. The command should look like this:

```
git clone --recursive git@github.com:<username>/<repository>.git .
```

Open VSCode and select `File` then `Open Folder...` and open the folder location of the repository. Setting this directory in VSCode allows features like Go-to definition and Autocomplete to work.

In VSCode, select `Terminal` then `New Terminal`

In the terminal window in VSCode, type:

```
jitx repl design-generator.stanza
```


# Library Management

This repo will keep your library code in step with your design using git submodules. For managing the version of `open-components-database` (OCDB), you must update it manually using Git:

```bash
cd open-components-database
git checkout master
git pull
```

You can also add your own design libraries and link them in by editing the `stanza.proj` file to include them. 


# Additional Resources:

- [Running your first design](https://docs.jitx.com/learn-jitpcb/first-design.html)
- [Stanza Cheat Sheet](https://docs.jitx.com/stanza.html)
- [Stanza By Example](http://lbstanza.org/stanzabyexample.html)
- [JITX Reference](https://docs.jitx.com/reference/SUMMARY.html)
