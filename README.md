FntSample
=========

FntSample is a tool that can be used to make font samples that show coverage of the font and are similar in appearance to <a href="http://www.unicode.org/charts/" class="reference external">Unicode Charts</a>. 
It was developed by Eugeniy Meshcheryakov for use with <a href="http://dejavu-fonts.org/wiki/Main_Page" class="reference external">DejaVu Fonts</a> project. 
FntSample is licensed under <a href="http://www.gnu.org/licenses/gpl.html" class="reference external">GPL</a> version 3 or later.

Features
--------

-   Support for various font formats using <a href="http://www.freetype.org/" class="reference external">FreeType</a> library, including TrueType, OpenType, and Type1.
-   Creating samples in PDF, PostScript, and SVG formats.
-   Adding outlines with Unicode block names for PDF samples.
-   Selection of code ranges to show in charts.
-   Comparing of two font files with highlighting of added glyphs.
-   Runs on Linux and other Unix-like systems.

Getting It
----------

FntSample can be downloaded from the <a href="http://sourceforge.net/projects/fntsample" class="reference external">project page</a>. 
Development version is also available in Git repository:

    git://fntsample.git.sourceforge.net/gitroot/fntsample/fntsample

It is also possible to <a href="http://fntsample.git.sourceforge.net/git/gitweb.cgi?p=fntsample/fntsample;a=summary" class="reference external">browse</a> the repository.

For building fntsample the following libraries are needed: <a href="http://cairographics.org/" class="reference external">cairo</a>, <a href="http://www.fontconfig.org/wiki/" class="reference external">fontconfig</a>, <a href="http://www.freetype.org/" class="reference external">FreeType2</a>, <a href="http://library.gnome.org/devel/glib/" class="reference external">GLib</a>, and <a href="http://www.pango.org/" class="reference external">Pango</a>. They should be available in most Linux distributions. Additionally Unicode <a href="http://unicode.org/Public/UNIDATA/Blocks.txt" class="reference external">blocks</a> file is required.

Using It
--------

Please see <a href="fntsample.html" class="reference internal"><em>FntSample Manual</em></a> and <a href="pdfoutline.html" class="reference internal"><em>PDFOutline Manual</em></a> for usage instructions. Those documents also contain some examples. Examples of charts produced with fntsample can be found on DejaVu Fonts <a href="http://dejavu-fonts.org/wiki/PDF_samples" class="reference external">PDF Samples</a> page.
