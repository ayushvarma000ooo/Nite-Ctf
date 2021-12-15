# Nite Ctf


# Qurious Case
## Chall Discription
   Our question creator has deviated from the standard method of making questions. He has hidden >and corrupted the flag. Can you recover it?
   we were provided a dark image


 ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/HelloDarknessMyOldFriend%20(1).png)
 
## Soultion:
- Initially by randomizing the colour pallate by cyberchef we get the QR code but the code is 1/4th missing.
  
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/download%20(1).png)
  
- So i fired up microsoft excel (no specific reason it was the best image editor i had) so edited the QR code to add the upper left box in the QR code.
  <!---![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/QR%20code%20excel.PNG)--->
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/QR%20code%20excel.PNG)
- Now the QR code can be read so i went to https://merricx.github.io/qrazybox/ to corretly read the code.
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Qurious%20case.PNG)
- after reading the corrected QR code i got the flag.
## Flag
- The flag was ```nite{tH@T'$_qRazzYyYy}```

# Zombie-Apocalypse 1
## Chall Discription
   zombies are coming, seek shelter quickly
   
   image was given
   
   ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%201/1%20zombies.jpg)
   
## Soultion:
- we ran steghide on the image wich showed a .txt file
 
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%201/unknown%20(1).png)
  
  "i found this inside the zombie-apocalypse-1 file:
oops, i lied! there's no flag here. however, your effort shall not go to waste:

we're ALWAYS attacked by aliens, and now zombies too?!
good thing there's an official contingency plan in place, but what is it? i hope it isn't a joke though

flag format: all lowercase, no spaces"
- it ment we have to osint the flag 
- after searching on our mighty search engine google we got a [pdf](https://www.stratcom.mil/Portals/8/Documents/FOIA/CONPLAN_8888-11.pdf?ver=2016-10-17-114016-887) which indicated the zombie attack plan (which sounds crazy) it was conplan8888 which was the flag

## Flag
- The flag was ```nite{conplan8888}```

# Zombie-Apocalypse 2
## Chall Discription

Great! You've managed to contact what's left of the government. they alloted you bunker where you'll be staying with other survivors. It's like 7th heaven compared to the hell out here! But where is it ?

Flag Format: nite{statename_bunkernumber} replace spaces with underscore

image was given

![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%202/chal_file.jpg)

## Soultion:
- At first glance it appered as an OSINT challange so i went to tineye to do the reverse search the image which ultimately lead to a many news sites which told the location of the photograph

 ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%202/Capture.PNG)
 
- It was south_dakota it was one part of the flag for the second part we needed to know the correct bunker number as there are many bunkers at that place.
- looking at the challange discription, it said _It's like 7th heaven compared to the hell out here_ which indicated 7 planes of the image and something is there at the 7th plane so we went to https://stegonline.georgeom.net to extract the data
- exracting data by selecting 7th order RGB values we get  
 
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%202/Capture1.PNG)
  ![App Screenshot](https://github.com/ayushvarma000ooo/Nite-Ctf/blob/main/Zombie-Apocalypse%202/Capture%202.PNG)
 
  so we got the bunker number which was ```69420``` (XD)
- according to the flag format nite{statename_bunkernumber}

## Flag
The flag was ```nite{south_dakota_69420}```



  
   
