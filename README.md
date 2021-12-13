# Nite Ctf
# Qurious Case
* Chall Discription
 > Our question creator has deviated from the standard method of making questions. He has hidden >and corrupted the flag. Can you recover it?
- we were provided a dark image https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/HelloDarknessMyOldFriend%20(1).png
- 
- Soultion:
  Initially by randomizing the colour pallate by cyberchef we get the QR code but the code is 1/4th missing.
- So i fired up microsoft excel (no specific reason it was the best image editor i had) and edited the QR code to add the upper left box in the QR code.
- Now the QR code can be read so i went to https://merricx.github.io/qrazybox/ to corretly read the code.
- after reading the corrected QR code i got the flag. 
