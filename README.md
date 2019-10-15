# jq-demo
Here are some simple jq examples that can serve to create a demo presentation.
All you need is a shell window and have `jq` installed; you may download it from
https://stedolan.github.io/jq/download/. To run the demo, type:
```
./step jqscript
```
and press return to execute each line (give it to the shell and show
the output). Most lines in the script include a comment (`# ...`)
that explains the significance of the current line. This comment won't
appear in the demo window (it's not printed by ``step``), but if you
have separate visual access to `jqscript`, these comments will remind
you of what to say.

In my (one-time) experience, this presentation takes about an hour
to deliver.

While running the demo, besides just pressting Enter, you may type an
arbitrary shell command and ``step`` will execute it instead, and leave
you positioned to the same place in the script. Or you may type `q`
to quit. Or you may type `x` to skip the current command and advance to
the next one.

Of course, the amazing `jq` is very feature-rich, so this demo covers
only a small part of its capabilities. I've included what I consider most
important. Please submit a ticket or a PR if there's something else you
think would be useful, but keep in mind that I want to keep this simple.

Another really great jq-related tool is fx:
https://medium.com/@antonmedv/discover-how-to-use-fx-effectively-668845d2a4ea
