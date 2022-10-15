#!/bin/bash

# cd "C:\Users\brand"


echo "Organizing your files"


mv *.png *.jpg *.jpeg *.tif *.tiff *.bpm *.gif *.eps *.raw Pictures

mv *.mp3 *.m4a *.flac *.aac *.ogg *.wav Music

mv *.mp4 *.mov *.avi *.mpg *.mpeg *.webm *.mpv *.mp2 *.wmv Videos

mv *.pdf *.rar *.zip *.doc *.docx *.txt *.odt *.ppt *.pptx Documents



cd Scripts
mv organize.sh .. #the organize script is also sorted into the scripts folder, so take it out.
cd ..

echo "Done!"





