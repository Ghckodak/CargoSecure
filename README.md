<h1 align="center"><a href="https://github.com/Ghckodak/CargoSecure" target="_blank">CargoSecure</a></h1>

>An Android APP solution by Haochen Gu, Eric Pan, Sharjil Mohsin and Yuheng Bai @McMaster University.

<p align="center">
<a href="#"><img alt="version" src="https://img.shields.io/badge/Version-1.2.0-blue.svg?style=flat-square"/></a>
<a href="#"><img alt="built with" src="https://img.shields.io/badge/Google Maps-green.svg?style=flat-square"/></a>
<a href="#"><img alt="built with" src="https://img.shields.io/badge/Java-yellow.svg?style=flat-square"/></a>
<a href="#"><img alt="built with" src="https://img.shields.io/badge/Android Studio-pink.svg?style=flat-square"/></a>

</p>

## Inspiration
>We looked at ways for detect a package being stolen and we thought hardware solutions would best so we thought using detection of a "key" while the package is being moved as a solution and moving the package without the "key" would be unauthorized and count as being stolen.

## What it does
>The gps tracker(phone in our case) would connect with a phone that has an app that would detect if any device once connected with it disconnects then the app would send a message to potential a server or police (another phone in our case).

## How we built it
>We used Android studio to create the app itself and format the UI. For the Connection portion of our device we got permission to access the devices WIFI component and we got the network information to check if the phone has WIFI and we used the "connectivity" command to check network information type this allows us to tell if a connection is present. For the Automated messaging we got the permission to use the phones SMS, then used the "IntentActionCall" command to actually call another person and used "SMSManager" command to send and SMS to another phone.

## Challenges
>A challenge was getting the automation of both the message sending and the status check of the package (in range or out of range).
