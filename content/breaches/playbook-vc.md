+++
title = "Playbook"
domain = "https://playbook.vc"
date_breached = "2020-10-19"
date = "2022-05-04"
record_count = "50,538"
privacy = "Not rated"
Verified = "True"
hashing = ["PBKDF2"]
breached_data = ["Email addresses", "Job titles", "Names", "Passwords", "Phone numbers", "Social media profiles"]
categories = []
acknowledged = "No"
+++
In September 2021, <a href="https://www.bankinfosecurity.com/articles.php?art_id=17696" target="_blank" rel="noopener">a publicly accessible PostgresSQL database belonging to the Playbook service was identified</a>. Run by VC firm Plug and Play Ventures, the database had been exposed since October 2020 and contained more than 50 thousand unique email addresses along with names, phone numbers, job titles and passwords stored as PBKDF2 hashes. It took more than 2 weeks after being notified of the exposed data to properly secure it. It's unknown whether Plug and Play Ventures notified impacted individuals as they ceased responding to queries from the press.
