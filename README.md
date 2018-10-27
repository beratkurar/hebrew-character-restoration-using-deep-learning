# hebrew-character-restoration-using-deep-learning
This project creates synthetic hebrew characters that are broken by overlapping Arabic characters. The aim is to train a deep learning network to learn restoring broken characters into their original forms.
### Create synthetic broken characters
Creates root Hebrew letters of 8 different fonts and root Arabic letters of 8 different fonts. Using these root letters creates homographic versions of root Hebrew letters and root Arabic letters in the number of a limit set by the user.
For every Hebrew letter an Arabic letter is randomly selected and randomly overlapped on this Hebrew letter. Overlapping letter parts are deleted to handle a broken Hebrew letter.

Following images show some original Hebrew letters, Hebrew letters overlapped by Arabic letters and the final broken Hebrew letters.

<img src="/images/original-hebrew-letters.png" alt="drawing" width="290"/> <img src="/images/arabic-overlap-hebrew.png" alt="drawing" width="290"/> <img src="/images/broken-hebrew-letters.png" alt="drawing" width="290"/>

