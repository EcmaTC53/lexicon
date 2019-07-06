# TC-53 Lexicon
To add to or edit any of the TC-53 lexica, open the markdown file in the src directory. This src file is a compact format HTML definition lists. You are free to add HTML into either the term or definition.

The src file has a ```.md``` extension so that it will render nicely on github, but it's really just an HTML file.

Don't sweat the compact HTML too much. It will be rendered as fully baked and valid HTML with RDFa tagging.

Sample lexicon.md file:
````html
<dl>Baseball Pitching Terms
<dt>Fastball<dd>A pitch thrown at or near maximum speed.
<dt>Change Up<dd>A pitch that mimics a fastball's mechanics, but is held deeper in the hand so that it arrives more slowly and throws off the batters timing.
<dt>Curve Ball<dd>A pitch thrown with forward rotation that causes it to dive before reaching the batter.
````

When you are done making edits to the src files, navigate to the root of the lexicon repo on your machine and run:
```bash
npx lexify
```
This will generate the html and jsonld files and drop them into the docs folder. The docs folder will be automatically published to http://EcmaTC53.github.io/lexicon when you push to the repository on master, or merge a pull request.

You can modify the HTML output by editing ```template\lexicon.mustache```

For more info on lexify visit [the repo](https://github.com/dtex/lexify)