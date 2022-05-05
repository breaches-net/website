# breaches.net Website
![](https://a.pomf.cat/yoymgd.png)

Made using Hugo (https://gohugo.io/) & used the Theme https://themes.gohugo.io/themes/hugo-theme-hello-friend-ng/ as a template.

Want a breach added to the list?
- Create a new file in `/content/breaches/` folder. File name must have periods replaced with dots, and follow the format that all the other breach entries follow.
- Use the tool found here: https://www.pompur.in/breach-report.html to format the file for you.
- Create either a Pull Request with the file added, or create a new issue with the output from the tool above.


Please also note that:
- If there is no passwords, put "N/A" for the hashes value. If passwords are not hashed with anything put "plaintext". If multiple hashing algorithms are used throughout the database (I.e. if they upgraded their systems and switched from bcrypt to argon2id) then list all the different ones that were used. Example of breach with multiple hashing alogrithms [here](https://raw.githubusercontent.com/breaches-net/website/main/content/breaches/1337-crew-to.md).
- Make sure the date is correct, or if you're updating a current entry change the "date" value to the current day.
- If a website was breached in the past but it needs to be listed again due to another breach, add a number at the end of the filename, (e.g. ogusers-com-1.md, ogusers-com-2.md)
