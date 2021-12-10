# More on Encryption with SSL  
  
### SSL is used on almost every website you visit  
  
SSL stands for Secure Socket Layer. It is the algorithm used for encrypting data between your browser and the server that hosts whatever website you visit, assuming it has SSL enabled.  
SSL uses asymetic encryption. This way the browser can share its public key with the server and the server can share its key with the browser.  
  
This is done to ensure that the browser and server can communicate with each other, but they cannot decrypt messages meant for each other.  
  
Using this same method I will give an example below:  
We will call my browser "A", google.com will be "B" and a hackers scam website will be "C"  
  
So if A visits C, B and C will exchange their public keys. C can technically store that public key for as long as they want.  
  
Now if C somehow manages to hack my network and they can recieve all my packets sent from my website.  
  
After this I could go to B (google.com) and start seaching things. This means that C can see everything I am searching on google now. Right?  
  
  
WRONG! Since C has my public key they can encrypt messages for me to decipher, but they cannot decipher messages that I send.  


  
  
  


[Last Page](./page3.md)  
