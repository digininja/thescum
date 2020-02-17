## What is this about?

What started out as a simple way to show how to mass block the sun and all that is evil about them, has quickly turned into a 'how do we block all who use the Internet to spread hatred and lies?'

This is about the infrastructure these publications use to spread their hate. The Domain Name System (DNS) and complex Content Delivery Networks (CDNs) that host and serve. 

![dailymail](img/dailymail.png)

As time permits, I'll continue to map and explore their vast networks so you can use the info to block them as you see fit. 

### Online presence

![thesun](img/thesun-web.jpg)

This is how The Sun newspaper looks on the Internet. Too often, the main domain name isn't the only entity, todays websites consists of many different sub-domains. In order to not see the content they serve, you need to understand all the pieces that make up the puzzle. 

![The_Sun_Liverpool](img/The_Sun_Liverpool.jpg)

For more information as to why, [this](https://www.vice.com/en_uk/article/gyzmzb/boycott-the-sun-ban-merseyside-uk) should help.

### Which publications do you currently have mapped?

- The Sun https://thesun.co.uk
- The Daily Mail https://dailymail.co.uk
- The Daily Express https://dailyexpress.co.uk
- The Telegraph https://telegraph.co.uk

### How do you use this information?

You can start by taking either the `$name__ips.csv` file and adding it to your hosts file on your computer. This will stop any access to any site the sun has. It's pretty simple to do. 

Under Microsoft Windows, follow this [guide](https://gist.github.com/zenorocha/18b10a14b2deb214dc4ce43a2d2e2992)

Under Mac OS X, follow this [guide](https://www.hostinger.co.uk/tutorials/how-to-edit-hosts-file-macos) 

### Advanced usage

Sites like this need the support of the global ad and pervasive tracking network. In order to understand who support them, I've started to map who their partners are and this information can be found in the `$name_ips_expanded.csv` file. It's more of a work in progress. 
