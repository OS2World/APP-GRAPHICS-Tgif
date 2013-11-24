Tgif-4.1.15
compiled w/ emx0.9d 
Thomas Hoffmann (thoffman@zappa.sax.de), 08jun1999

This is a preliminary port of tgif. It is not polished, but one
can do most of the drawing work and some of the "specials".
I did enhance the drive awareness in some places, i.e. tgif uses
a temp dir as given in TMP and can be used from other drives
than its installation drive.

Please report all the bugs you encountered to me.

Note: For some nice effects (load/save .gz files, import/
export of special formats, image processing) you need additional
tools (gzip/gunzip, netpbm stuff, ghostscript ...).

You can regard this patch as an extensions of Alexander Mai's
contribution to the official distribution. Only that I called
the template Tgif.tmpl-emx (instead of Tgif.tmpl-os2).
