
# Bitsight Scanning infrastructure

BitSight is like that nosy neighbor who catches a glimpse of you through the blinds and suddenly thinks they know your whole life story. They’re constantly scanning the internet—crawling websites, peeking into open ports—to piece together how secure (or insecure) your digital setup is.</p>

But here’s the funny part: with just a few crumbs of data, they start extrapolating like there’s no tomorrow. Spot one open port? They assume your entire network security is looser than a thrift shop sweater. See a couple of outdated software versions? Suddenly, they’ve decided your entire IT department is running on Windows XP and duct tape.<br>
Before you know it, BitSight has slapped you with a cybersecurity score, rating your digital fortress like a strict schoolteacher grading a half-finished homework assignment.</p>

BitSight doesn’t just rate you based on what they find—they rate you on what they think they’ve found. And yes, they’re making wild guesses based on just a few hints, like assuming your whole house is a mess because they saw a sock on your porch.</p>

A smart approach? Think of it like staging your house for a real estate agent: show off only the clean, organized rooms and keep the messy closets out of sight. In other words, strategically manage what BitSight can see, making sure they walk away impressed by your well-maintained cybersecurity posture, rather than poking around for skeletons in your digital closets.</p>

## Bitisght scanners: [link](https://github.com/vratiskol/Bitsight/blob/4dbd59a88fa191caa12d5313fdd983fcace6ec03/Bitsight_scanner_ips.txt)

45.156.128.0/22<br>
185.180.140.0/22<br>
185.226.196.0/23<br>
185.117.225.0/24<br>

### User-Agent used for Web scanning:

- User-Agent: Mozilla/5.0 (compatible; BitSightBot/1.0)
- User-Agent: Mozilla/5.0 (Windows NT 10.0; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/66.0.3359.117 Safari/537.36
- User-Agent: Mozilla/5.0 (X11; Linux x86_64) AppleWebKit/537.36 (KHTML, like Gecko) HeadlessChrome/90.0.4430.212 Safari/537.36
<br>
<br>
<br>

# How does BitSight's "Compromise System" Category work?

**Netflix Mode: ON**
<p>Imagine setting up a fake nightclub—complete with bouncers, flashing lights, and cheesy music—to catch all the party crashers who keep trying to get in with stolen invites. But, plot twist, just when they think they’ve snuck past the velvet rope and are ready to party, the doors swing open, and instead of a dance floor... they find themselves standing in a police station, under a spotlight, with officers ready to take notes on every move they’ve made.</p>

## Bitsight Sinkholes:
<p>
    A sinkhole is like one of those "Gotcha!" traps. Hackers are using C2 with shady domains that act like their secret command centers.
    Once BitSight and other cybersecurity teams figure out these domains are being used for mischief, they swoop in, buy the domains, and turn them into bait.
</p>
<p>
    BitSight sets up fake servers that look just like the original botnet command centers (same open port). Now, when infected computers come knocking, expecting some juicy hacker commands, they get redirected to BitSight’s "honeypot."
    It’s like trying to enter a secret club, only to realize it’s actually the police station.
</p>

## Why Should You Care (or Not)?
<p>
    When a company’s computers start chatting with these domains, BitSight’s fake server takes note—like that bouncer jotting down the names of everyone trying to crash the party. The IP addresses in the connection logs are cross-checked with BitSight’s records to see which companies’ assets are getting a little too cozy with these shady domains.
</p>
<p>
    Now, if you find your company's IP on this list, don’t panic (yet). It is a strong hint that your cyber defenses might be about as sturdy as a wet paper bag.
    Sure, for now, it's just connecting to BitSight's sinkhole, but if a real hacker had been behind it, you’d be looking at a one-way ticket to Doomsville for your systems.
</p>

### Bitsight Sinkhole IPs: [link](https://github.com/vratiskol/Bitsight/blob/2f1e16e4165094a700056345bbd8fd8e90abedd8/Bitsight_Sinkhole_ips.txt)

3.94.10.34<br>
3.237.86.197<br>
3.254.94.185<br>
13.251.16.150<br>
18.141.10.107<br>
18.143.144.165<br>
18.143.155.63<br>
18.203.171.243<br>
18.208.156.248<br>
18.246.231.120<br>
34.211.97.45<br>
34.218.204.173<br>
34.227.7.138<br>
34.246.200.160<br>
34.253.216.9<br>
35.91.124.102<br>
35.164.78.200<br>
44.200.43.61<br>
44.213.104.86<br>
44.213.120.30<br>
44.213.132.171<br>
44.221.84.105<br>
47.37.76.200<br>
47.129.31.212<br>
52.34.198.229<br>
54.80.154.23<br>
54.82.123.103<br>
54.154.201.6<br>
54.160.3.49<br>
54.169.255.239<br>
54.195.46.98<br>
54.202.86.255<br>
54.244.188.177<br>
107.20.97.152<br>
2600:9000:2002:bc00:8:1a6d:5f00:93a1<br>
2600:9000:2009:ec00:3:ef2f:7c00:21<br>
2600:9000:203c:7200:1e:142:8c00:93a1<br>
2600:9000:20ad:1800:14:90f0:1580:ab8e<br>

### Sinkhole Domains: [List of 100261 domains](https://github.com/vratiskol/Bitsight/blob/2f1e16e4165094a700056345bbd8fd8e90abedd8/Bitsight_Sinkhole_list_domains.csv)

