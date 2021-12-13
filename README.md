# Nite Ctf


# Qurious Case
## Chall Discription
 > Our question creator has deviated from the standard method of making questions. He has hidden >and corrupted the flag. Can you recover it?
   we were provided a dark image


 ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/HelloDarknessMyOldFriend%20(1).png)-
 
## Soultion:
- Initially by randomizing the colour pallate by cyberchef we get the QR code but the code is 1/4th missing.
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/download%20(1).png)
  
- So i fired up microsoft excel (no specific reason it was the best image editor i had) so edited the QR code to add the upper left box in the QR code.
  <!---![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/QR%20code%20excel.PNG)--->
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/QR%20code%20excel.PNG)-
- Now the QR code can be read so i went to https://merricx.github.io/qrazybox/ to corretly read the code.
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Qurious%20case.PNG)-
- after reading the corrected QR code i got the flag.
## Flag
- The flag was ```nite{tH@T'$_qRazzYyYy}```
