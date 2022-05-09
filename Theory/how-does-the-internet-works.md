

### How does the *internet* Works
 
The internet is a wire, buried in the ground. Computers connected directly to the internet are called **Servers** while the computers you and I use are **clients** because they are not connected directly to the internet, but through an Internet Service Provider. Routers shuttle packets of information across the internet, and transmit e-mail, pictures, and web pages.

Internet addresses are in the form **nnn.nnn.nnn.nnn** where nnn must be a number from 0 - 255. This address is known as an **IP address.** (IP stands for **Internet Protocol**; more on this later.)
The picture below illustrates how internet works

![diagram](/Theory/how-does-the-internet-works1.png)

 #### Example

When you opened your email, your email application sent a request to your email provider *(for example, Gmail)* through your laptop’s Network Interface Card to your **Wireless Access Point (WAP)** using your local **WiFi**. The WAP then sent the request through a wire to the local router.

The local **router** took that request and sent it to another router, which then sent to another router, and another router, all the way through a chain of routers until the data was transferred over one of the transatlantic communication cables to the United States.

There, it ended up at a Google data center (because you use Gmail). Google then processed your request to get any new emails that had come in since you last loaded your email. They packaged up your new, unread emails in a digital package called a “response,” and sent that package back to the same address (your laptop) that requested the updates. The response probably took different routes on the way back, but it went through the same mechanisms.

The data was transferred from the Google data center through multiple lines and reached your home router/modem, which made the data available over your home WiFi. Your laptop’s Network Interface Card received the response, sent it to your email application, and then voilà—your new emails fill up your inbox! . 

**[read more ...](https://web.stanford.edu/class/msande91si/www-spr04/readings/week1/InternetWhitepaper.htm)**

This document was reviewed by [NordineBeCode](https://github.com/ElazzouziNordineBeCode)
