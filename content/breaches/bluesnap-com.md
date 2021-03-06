+++
title = "Regpack"
domain = "https://bluesnap.com"
date_breached = "2016-05-20"
date = "2022-05-04"
record_count = "104,977"
privacy = "Public"
Verified = "True"
hashing = ["N/A"]
breached_data = ["Browser user agent details", "Credit card CVV", "Email addresses", "IP addresses", "Names", "Partial credit card data", "Phone numbers", "Physical addresses", "Purchases"]
categories = []
acknowledged = "No"
+++
In July 2016, a tweet was posted with a link to an alleged data breach of <a href="http://bluesnap.com" target="_blank" rel="noopener">BlueSnap, a global payment gateway and merchant account provider</a>. The data contained 324k payment records across 105k unique email addresses and included personal attributes such as name, home address and phone number. The data was verified with multiple Have I Been Pwned subscribers who confirmed it also contained valid transactions, partial credit card numbers, expiry dates and CVVs. A downstream consumer of BlueSnap services known as <a href="http://www.regpacks.com/" target="_blank" rel="noopener">Regpack</a> was subsequently identified as the source of the data after they identified human error had left the transactions exposed on a publicly facing server. A full investigation of the data and statement by Regpack is detailed in the post titled <a href="https://www.troyhunt.com/someone-just-lost-324k-payment-records-complete-with-cvvs/" target="_blank" rel="noopener">Someone just lost 324k payment records, complete with CVVs</a>.
