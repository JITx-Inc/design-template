# Getting started with a JITX Design

Clone this template repository:

```
git clone --recursive git@github.com:JITx-Inc/design-template.git .
```

Open the REPL:

![Open the Repl](https://raw.githubusercontent.com/JITx-Inc/jitpcb-vscode-resources/feature/JITX-279/improve-gif/repl.gif)

alternatively:

```
jitx repl
```

Load your design

```
stanza> load "design-generator.stanza"
```

# Library Management

This repo will keep your library code in step with your design using git submodules. For managing the version of `open-components-database` (OCDB), you must manually update the hash.

```bash
cd open-components-database
git checkout master
git pull
```

You can also add your own design libraries and link them in by editing the `stanza.proj` file to include them. 


# Additional Resources:

- [Stanza Cheat Sheet](https://docs.jitx.com/stanza.html)
- [Stanza By Example](http://lbstanza.org/stanzabyexample.html)
- [Running your first design](https://docs.jitx.com/learn-jitpcb/first-design.html)
- [JITX Reference](https://docs.jitx.com/reference/SUMMARY.html)
