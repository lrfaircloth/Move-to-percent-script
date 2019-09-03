# Move-to-percent-script
This script moves the cursor to a given point in a highlighted section of a spectrogram. 
For example, it will move the cursor in a highlighted vowel to a point 25% of the way through the highlighted segment. 
This is useful for hand-checking measurements that were taken at different points during a segment. 

This is a Praat editor script, which works differently than most Praat scripts. 
Open the spectrogram (and textgrid if you have one) in Praat using the "View & Edit" button. 
In the spectrogram window, select "file" and then "open editor script", and open this script. 
The script is written to go to the point 30% of the way through the highlighted section in the spectrogram. 
You can change this value on the second line by changing 0.3 to a different decimal place. 
(ie 0.25 will move the cursor to 25% of the vowel, 0.6 will move the cursor to 60% of the vowel)

The script is written to list the formants at that point. You can delete the last line to move the cursor to the desired 
point without reading the formants. 

If you are measuring lots of formants, use the "measure formants" script, which will take measurements for all your files
and create a spreadsheet of results. 
