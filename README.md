# OpenUTAU-French-Dictionary
French Dictionary for [OpenUTAU](https://www.openutau.com/), based on the [French CMU Pronouncing Dictionary](https://sourceforge.net/projects/cmusphinx/files/Acoustic%20and%20Language%20Models/French/), modified for easier ease in OpenUTAU.

This dictionary is meant to be used with French CVVC Phonemizer, compatible with Petit Mot, Gros Mot & Fraloids voicebanks & the French VCCV Phonemizer, compatible with m2RUg. You can learn more about French UTAUs [here](https://utaufrance.com/).


## Download instructions

Please place the `cmudict_fr.txt` file in the `Dictionaries` folder of your OpenUTAU install. If it doesn't exist, you can create one.

#### Google Drive mirror for Download: https://drive.google.com/file/d/1m-wnt5reJ0d9rGC2e1jMlZUMeioA5Lnw/view


## How to contribute

To add a word, you should format it like this 

`word  ww oo rr dd` 

with the word you want to have, **2 spaces**, the phonetics spaced out written in Arpabet. You can and should add additional prononciations with (2), (3) etc.

For example, if I wanted to add `parfaitement` I'd add:

`parfaitement  pp aa rr ff ai tt ee mm an` basic form

`parfaitement(2)  pp aa rr ff ai tt ee mm an tt` basic form with liaison

`parfaitement(3)  pp aa rr ff ai tt mm an` shortened form

`parfaitement(4)  pp aa rr ff ai tt mm an tt` shortened form with liaison

Here is a chart of the arpabet phonetics compared to other common phonetics system:


| Arpabet  | Mot | m2RUg |
| ------------- | ------------- | ------------- |
| aa  | ah  | A  |
| ai  | ae  | E  |
| ei  | eh  | e  |
| ee/eu | ee  | 2  |
| oe | oe  | 9  |
| ii | ih  | i  |
| au | oh  | o  |
| oo | oo  | O  |
| ou | ou  | u  |
| uu | uh  | y  |
| an | en  | a  |
| in/un | in  | U  |
| on | on  | 0  |
| yy  | y  | j  |
| ww  | w  | w  |
| uy  | ui  | H  |
| bb | b  | b  |
| dd | d  | d  |
| ff | f  | f  |
| gg | g  | g  |
| kk | k  | k  |
| ll | l  | l  |
| mm | m  | m  |
| nn | n  | n  |
| gn | ny  | J  |
| pp | p  | p  |
| rr | r  | R  |
| ss | s  | s  |
| ch | sh  | S  |
| tt | t  | t  |
| vv | v  | v  |
| zz | z  | z  |
| jj | j  | Z  |
| ww aa | oi  | wA  |


Feel free to contribute.

More info on French UTAUs here -> https://utaufrance.com/
