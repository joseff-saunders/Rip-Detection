This is a trial script to identify subjectiveness in drawing the location of rip currents from 50 sample Sentinel-2 images.

To run externally, run the Rip_Annotation.ipynb file, and select Open in Colab. 

Run through each of the sections in Google Colab, await for a tick to appear in each section before progressing. 

The second to last section (# Dsiplay annotation UI) is where the rip identification occurs. 
  Each of the 50 images will be uploaded individually.
  If no rip is present in the imagery, press Skip.
  If a rip is present in the imagery, click and hold to draw an annotation box around the extent of the rip current. 
  Some images will have more than one rip currents within them, please annotate all.
  Once happy, press Submit to load the next image and store your annotations.
  To undo a box, simply click on it and it will dissappear. 

When complete, navigate to the Files tab on the far left of the Google Colab screen. Click the content/Rip-Detection/Rip folder. 

Download the rip_current_annotations.json file, rename to include your initials and email across. 
