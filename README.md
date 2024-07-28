# CHEERS IN AIR 

This script makes use of MindAR to present a 3D champange glass in AR. The code is modified based on the tutorial on [MindAR](https://hiukim.github.io/mind-ar-js-doc/)
Following is the step-by-step explaination of my each step. Hope you enjoy! 

1. Create a 3D object
   I use [Meshy](https://app.meshy.ai/) **text to 3D model** service to generate a champange glass. And I download GLB file (which is format can be used cross different platform,and I worked with GLB a lot in the past)

2. Make a marker
   - For generating a marker, I use **Canva** links to **Mojo's** **text to image** service to generate a logo. The condition is to have high contrast image and have some detail that the MindAR marker generator can recognise.
   - Upload to MindAR marker generator and download the **.mind** file
   - Save it in GitHub and find the link to access the **.mind** file (usually in the form of https://<UserName>.github.io/<ProjectName>/<FileName>.mind)
3. Replace the links in the example code with the links on github repo.
4. Create a QR code using **Canva** **Gen QR**'s service.


