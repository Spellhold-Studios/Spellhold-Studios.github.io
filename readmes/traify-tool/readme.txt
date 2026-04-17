This simple tool can be used to automate traification of a mod. It is a command-line tool and requires a copy of WeiDU, so they should be both put in your $PATH (or in your BG2 directory). Your mod should have translations packaged in mymod/tra/english, while its D, BAF etc. files can live anywhere in the mymod hierarchy (but outside of mymod/tra). Setup-mymod.tp2 should live inside mymod if you want it traified.

The program can be run in two modes.

If you want to just traify, run it like this:

    traify mymod english

This will scan the mymod file hierarchy, skipping mymod/tra, and traifies every single *.d, *.baf, *.tp* it finds there, putting the traified file in its old position and the resulting tra in mymod/tra/english. Whatever.d uses whatever.tra, while *.baf and *.tp* use setup.tra. This mode also ensures that partially traified mods aren't broken (old @xxx references are preserved, and new references are appended to the bottom).

The tool can also generate .d, .baf etc. files that use local strings rather than @references. Run it like this:

    traify mymod english english spanish french italian

This traifies like in the prior case, then generates, in mymod/tra/{english,spanish,french,italian}/decompiled a version of all *.d, *.baf, *.tp* files, that uses local strings rather than @references. This assumes that whatever.d has its strings in whatever.tra, while *.baf or *.tp* has its strings in setup.tra.

Moreover, you can pass additional options to WeiDU; they must be put after the primary language, followed by -- and by the target languages. Examples:

    traify mymod english --traify-comment --nogame --

    traify mymod english --traify-comment --nogame -- english spanish french italian

--traify-comment --nogame will be thus passed to every instance of WeiDU; the -- is just a marker.

Source code for the tool is available at GitHub (https://github.com/vbigiani/traify-tool). The download contains the Windows binary; users of other operating systems can grab the fully equivalent 'traify.sh' from Github.
