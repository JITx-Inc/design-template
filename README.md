# Starting a JITX design

Clone this repository, or use the 'Use this template' button to create a new repository (then clone that one)

To initialize:
```
cd design-template
git submodule update --init
```

Now you can run the design generator:
```
jitpcb repl design-generator.stanza
```

# Library management

This repo will keep your library code in step with your design. For managing the version of open-components-database, treat it like any other git repository:
```
cd open-components-database
git checkout master
git pull
```
You can also add your own design libraries (as submodules if you wish), and link them in by editing `stanza.proj` to include them.
