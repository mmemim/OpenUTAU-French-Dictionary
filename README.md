# OpenUTAU-French-Dictionary
French Dictionary for [OpenUTAU](https://www.openutau.com/), based on the [French CMU Pronouncing Dictionary](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/French/), modified for easier ease in OpenUTAU.

This dictionary is meant to be used with French CVVC Phonemizer, compatible with Petit Mot, Gros Mot & Fraloids voicebanks & the French VCCV Phonemizer, compatible with m2RUg. 
You can learn more about French UTAUs on [frenchutauhelp.carrd.co](https://frenchutauhelp.carrd.co/).

✨ Feel free to contribute ✨

### See also

* [Google Drive mirror for this dictionary download](https://drive.google.com/file/d/1m-wnt5reJ0d9rGC2e1jMlZUMeioA5Lnw/view)
* [French UTAUs voicebanks and tutorials -> utaufrance.com](https://utaufrance.com/) 


## Download instructions

If you just want to install the dictionary without contributing, you won't need a Github account or to understand how to use Git.
Just follow the two steps below : 

-  First, download the [cmudict_fr.txt](https://github.com/mmemim/OpenUTAU-French-Dictionary/blob/main/cmudict_fr.txt) file by clicking on the filename
and then click on the download icon in the upper left corner of the file browser, as shown in the image below.

![](pictures/Download_dict_file_only.png)

-  Then drag and drop the file inside your OpenUtau `Dictionaries` folder. If the folder didn't existe, create one at the root of your OpenUtau folder.

![](pictures/Drag_file_in_correct_folder.jpg)

## How to add a word

Please follow the alphabetical order when adding a new word inside the `cmudict_fr.txt` file.

* Write your word first, then add two blanks space before the first phoneme of the pronunciation.
* Each phoneme in the pronunciation is separated by a single blank space.
* Be careful not to accidentally add another blank space at the very end of the line, but just a line break.
* After saving the file, you can close and re-open OpenUtau to force the dictionary to reload.

If you're not sure about how to write the prononciation, you can use the phonetic assistant in FrenchG2P as shown in the picture below.
You will find it in OpenUtau under the "Tools" tab.

![](pictures/Phonetic_assistant.png)