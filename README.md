# Developing-a-website
Assignment 2 of Designing for User Experience module 



The main change that will be made is to the menu. it will group common food categories together so they are easer to find. This change was made for the Adhd user. This would mean they will be able to make desicions faster and more effectively then getting overwhelmed with a mass amount of food listing.


challenge faced during developement minnimise the use of java script .intially i avoided using javascript as the assaignment focus was on html and css and that is why i copy and pasted simmiliar headers on seprate pages. However when i began programinng the menu and basket structures it became obvious for me that i will noot be able to avoid it as the pages require javascrip in order to communicate and store the items that have been ordered. This also saved me from writting down the same food items for multiple sections.

One issue with the initial game platform was that the basket was already showing items when the user first visited the site. This shouldn’t have happened because it made it look like previous users’ data was being carried over.To fix this, I used JavaScript to control the basket state using session-based storage. This means the basket is now set up to reset whenever a new session starts, so no old items are kept when a user loads or refreshes the page.This change ensures the basket always starts empty, making the behaviour more consistent and improving the overall user experience.

Another issue that stood out was that user could place a order with entering their detial(e.g. date, time, phone number). This was fixed by implimenting Javascript again and making sure the order does not go through if those areas are not filled.

