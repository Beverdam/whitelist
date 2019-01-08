<p align="center">
  <img width="550" src="https://raw.githubusercontent.com/anudeepND/whitelist/master/images/logo.png">
</p>
       
 Op basis van het goede werk van anudeepND, wilde ik graag een whitelist maken voor veelbezochte Nederlandse sites. Ik heb top top 100 sites gepakt van Nederland. Dit is gedaan op basis van eigen inzicht dus garantie tot aan de deur. Wil je graag een domein laten toevoegen? Wil je een bestaan document laten aanpassen? Maak dan gerust een <a href="https://github.com/Beverdam/whitelist/issues">issue</a> aan.  

Om deze domeinen toe te voegen aan je huidige setup,draai whitelist.sh.

 <p align="center">
  <img height="430" src="https://raw.githubusercontent.com/anudeepND/whitelist/master/images/run.gif">
</p> 
         
* * *
           
### Installatie en gebruik

git clone https://github.com/Beverdam/whitelist.git
cd whitelist/scripts
sudo chmod +x whitelist.sh
sudo ./whitelist.sh

**Je hoeft niet steeds deze repo te clonen om een bijgewerkte whitelist file te krijgen. Ga naar 'whitelist/scripts' en voer 'sudo ./whitelist.sh' uit.

***
Hieronder een goedkope copy-pasta van de orginele repro over het spotten van advertentie domeinen.

### How do I determine an ad domain?
         
***DNSthingy Assistant***
         
<a href="https://chrome.google.com/webstore/detail/dnsthingy-assistant/fdmpekabnlekabjlimjkfmdjajnddgpc">This browser extension</a> will list all of the domains that are queried when a web page is loaded. You can often look at the list of domains and cherry pick the ones that appear to be ad-serving domains.     
        
<p align="center">
  <img width="600" height="500" src="https://raw.githubusercontent.com/anudeepND/blacklist/master/images/img1.jpeg">
</p>
      
***Using inbuilt Developer tool***     
          
For Chrome ctrl+shift+I will land you in Developer tools menu.
      
<p align="center">
  <img width="450" height="600" src="https://raw.githubusercontent.com/anudeepND/whitelist/master/images/img2.jpeg">
</p>      
          
***Using an Android app*** 
     
[Net Guard](https://play.google.com/store/apps/details?id=eu.faircode.netguard) is an Android app that can be used to monitor any specific apps, works on unrooted devices too.   
        
<p align="center">
  <img width="500" height="400" src="https://raw.githubusercontent.com/anudeepND/whitelist/master/images/img3.jpeg">
</p>
             
***
        
### Licentie
```
MIT License

Copyright (c) 2018 Anudeep ND <anudeep@protonmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
