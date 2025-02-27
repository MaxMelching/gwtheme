# GW Theme In Google Slides

Tutorial for the GWtheme Google Slides template defined at https://github.com/MaxMelching/gwtheme.

1. Make your preferred settings in the `google_slides_template.tex` file and
   compile it.

1. Run the `google_slides_create_bgs.sh` file, paying attention to the output
   name.

1. Open the Google Slides template and copy it to create the document that you
   will be editing (copying under _File/Make Copy_).

1. Copy the titlepage, sectionpage, standard page pngs (indices 0, 1, 2 in
   the png images that the shell script puts out) into the Google slides GW
   template. In order to do that, go to _View/Theme builder_ or
   _Slide/Edit Design_. There you can edit the "master slide", from which all
   other styles are derived. When this is done, you can change the appearance
   of specific slides, such as the title page or section pages.

   A good overview about editing themes in Google slides is given in
   https://www.slideson.com/edit-theme-builder-master-slides-in-google-slides/.
