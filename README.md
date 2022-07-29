# DonationFeature

Make a card donation of $10 using test data
Cypress Vrsion: Latest 10.3.1(It has lots of changes in the over all structure of cypress from 9th versions,it support chrome,edge,electron browsers which can be switched while running project considering as cross browser test)
Chrome version: 103
edge version: 103
electron: 100
![image](https://user-images.githubusercontent.com/48355699/181423006-76e3d0f4-631b-43ba-a051-666c655895a7.png)

and in cypress 9.5.1
Two scripts:
CancerResearchDonation1.js : For the positive end to end scenario using iframe function added in command.js file
CancerResearchDonation2.js : For the positive end to end scenario by imprting iframe library from cypress
Note: The iframe is not getting loaded in cypress for credit card number,expiry date, cvv.
      The input boxes are getting disabled while running via automation
      
Tried:
1.Added command in command.js to handle Iframe element
2.Imported iframe inbuild package

Steps:
1.Please download the zip file and extract in local.
2.Run command npm install D cypress-iframe (required to support inbild iframe pacage mentioned above)
3.Run the scripts from integration folder above code



TestData.json is the file where input data/details are stored for the scripts.
