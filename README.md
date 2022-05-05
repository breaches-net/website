# breaches.net Website
![](https://a.pomf.cat/yoymgd.png)

Made using Hugo (https://gohugo.io/) & used the Theme https://themes.gohugo.io/themes/hugo-theme-hello-friend-ng/ as a template.

Want a breach added to the list?

- Create a new file in `/content/breaches/` folder. File name must have periods replaced with dots, and follow the format that all the other breach entries follow.
- Follow the rest of the steps given below.

Here is an example configuration of a breach with no description (A description isn't required, but it is encouraged to make one):
```
+++
title = "3DSISO"
domain = "https://3dsiso.com"
date_breached = "2015-09-11"
date = "2022-05-04"
record_count = "128,062"
privacy = "Public"
Verified = "True"
hashing = ["MD5"]
breached_data = ["Email addresses", "Passwords", "Usernames", "IP addresses"]
type = ["posts","post"]
categories = ["Gaming"]
acknowledged = "No"
+++
```

And one with a description:
```
+++
title = "Zynga"
domain = "https://zynga.com"
date_breached = "2019-09-01"
date = "2022-05-04"
record_count = "172,869,660"
privacy = "Public"
Verified = "True"
hashing = ["SHA-1"]
breached_data = ["Email addresses", "Passwords", "Phone numbers", "Usernames"]
type = ["posts","post"]
categories = []
acknowledged = "Yes"
acknowledged_url = "https://archive.md/MXs01"
+++

In September 2019, game developer <a href="https://www.cnet.com/news/words-with-friends-hack-reportedly-exposes-data-of-more-than-200m-players/" target="_blank" rel="noopener">Zynga (the creator of Words with Friends) suffered a data breach</a>. The incident exposed 173M unique email addresses alongside usernames and passwords stored as salted SHA-1 hashes.
```

For the hashing value(s), please use the proper capitalization (If the hash in the breach isn't listed here, then use whatever is correct):
```
sha256hmac
SHA1BCRYPT-CUSTOM
scrypt
3DES
CRC32
NSLDAPS
MySQL5
phpBB
Argon2id
base64
PBKDF2
Drupal
blowfish
Unknown
PBKDF1-SHA1
MySQL323
Wordpress
vB
SHA-256
PHPass
PBKDF2-HMAC-SHA1
PBKDF2-HMAC-SHA512
Joomla
SHA2-256
sha512crypt
SHA2-384
WHMCS
XF
SMF
SHA-256(AuthMe)
IPB
DEScrypt
phpBB3
MySQL
PBKDF2-SHA256
osCommerce
md5crypt
plaintext
MyBB
N/A
SHA-512
SHA-1
MD5
bcrypt
```

Some more things to note when submitting:

- If there is no passwords, put "N/A" for the hashes value. If passwords are not hashed with anything put "plaintext". If multiple hashing algorithms are used throughout the database (I.e. if they upgraded their systems, and switched from bcrypt to argon2id) then list all the different ones that were used.
- Make sure the date is correct, or if you're updating a current entry change the "date" value to the current day.
- If a website was breached in the past but it needs to be listed again due to another breach, add a number at the end of the name, (e.g. ogusers-com-1.md, ogusers-com-2.md)
