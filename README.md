		BOOZT
ipaddress
104.16.166.228

BOOZTLET

Total Unique Subdomains Found: 11
www.booztlet.com
email.booztlet.com
click.email.booztlet.com
image.email.booztlet.com  access denied
pages.email.booztlet.com
pub.email.booztlet.com
view.email.booztlet.com
nw.booztlet.com
nw2.booztlet.com
t.booztlet.com
t-dev.booztlet.com

BOOZT

[-] Total Unique Subdomains Found: 25
www.boozt.com
blog.boozt.com *
calendar.boozt.com *
delivery-time.boozt.com   404 not found
eccoemv.boozt.com
email.boozt.com
click.email.boozt.com
image.email.boozt.com
view.email.boozt.com
emv.boozt.com
gcp.boozt.com
m.boozt.com
mail.boozt.com
ns1.boozt.com
ns4.boozt.com
nw.boozt.com
parcel-api.boozt.com
rel.boozt.com
sendgrid.boozt.com
o1.sendgrid.boozt.com
shop.boozt.com
sp.boozt.com
sp-dev.boozt.com
t.boozt.com
www.t.boozt.com


Nmap scan report for 104.16.167.228
Host is up (0.00052s latency).
Not shown: 65523 filtered ports
PORT     STATE SERVICE
80/tcp   open  http
443/tcp  open  https
2052/tcp open  clearvisn
2053/tcp open  knetd
2082/tcp open  infowave
2083/tcp open  radsec
2086/tcp open  gnunet
2087/tcp open  eli
2095/tcp open  nbx-ser
2096/tcp open  nbx-dir
8443/tcp open  https-alt
8880/tcp open  cddbp-alt


nmap -sV email.boozt.com
Starting Nmap 7.70 ( https://nmap.org ) at 2020-01-29 13:06 IST
Nmap scan report for email.boozt.com (136.147.129.27)
Host is up (0.0020s latency).
rDNS record for 136.147.129.27: reply-mx.s7.exacttarget.com
Not shown: 999 filtered ports
PORT   STATE SERVICE    VERSION
25/tcp open  tcpwrapped

 nmap -sV click.email.boozt.com
Starting Nmap 7.70 ( https://nmap.org ) at 2020-01-29 13:07 IST
Nmap scan report for click.email.boozt.com (13.111.45.146)
Host is up (0.029s latency).
Not shown: 996 filtered ports
PORT    STATE  SERVICE    VERSION
25/tcp  open   tcpwrapped
80/tcp  open   tcpwrapped
113/tcp closed ident
443/tcp open   tcpwrapped

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 51.11 seconds



nmap -PN -sV -p0-65535 104.16.167.228
PORT     STATE SERVICE       VERSION
80/tcp   open  http          cloudflare
443/tcp  open  ssl/https     cloudflare
2052/tcp open  clearvisn?
2053/tcp open  ssl/http      nginx
2082/tcp open  infowave?
2083/tcp open  ssl/http      nginx
2086/tcp open  gnunet?
2087/tcp open  ssl/http      nginx
2095/tcp open  nbx-ser?
2096/tcp open  ssl/http      nginx
8080/tcp open  http-proxy    cloudflare
8443/tcp open  ssl/https-alt cloudflare
8880/tcp open  cddbp-alt?



dns servers

Checking for wildcard DNS...
Nope. Good.
Now performing 2280 test(s)...
104.16.152.195	calendar.boozt.com
104.16.153.195	calendar.boozt.com
104.16.149.195	calendar.boozt.com
104.16.150.195	calendar.boozt.com
104.16.151.195	calendar.boozt.com
104.16.152.195	groups.boozt.com
104.16.151.195	groups.boozt.com
104.16.153.195	groups.boozt.com
104.16.150.195	groups.boozt.com
104.16.149.195	groups.boozt.com
104.16.166.228	m.boozt.com
104.16.167.228	m.boozt.com
104.16.153.195	mail.boozt.com
104.16.152.195	mail.boozt.com
104.16.151.195	mail.boozt.com
104.16.149.195	mail.boozt.com
104.16.150.195	mail.boozt.com
104.16.150.195	nw.boozt.com
104.16.152.195	nw.boozt.com
104.16.153.195	nw.boozt.com
104.16.151.195	nw.boozt.com
104.16.149.195	nw.boozt.com
216.239.38.21	t.boozt.com
216.239.32.21	t.boozt.com
216.239.36.21	t.boozt.com
216.239.34.21	t.boozt.com
104.16.166.228	www.boozt.com
104.16.167.228	www.boozt.com

Subnets found (may want to probe here using nmap or unicornscan):
	104.16.149.0-255 : 4 hostnames found.
	104.16.150.0-255 : 4 hostnames found.
	104.16.151.0-255 : 4 hostnames found.
	104.16.152.0-255 : 4 hostnames found.
	104.16.153.0-255 : 4 hostnames found.
	104.16.166.0-255 : 2 hostnames found.
	104.16.167.0-255 : 2 hostnames found.
	216.239.32.0-255 : 1 hostnames found.
	216.239.34.0-255 : 1 hostnames found.
	216.239.36.0-255 : 1 hostnames found.
	216.239.38.0-255 : 1 hostnames found.

Done with Fierce scan: http://ha.ckers.org/fierce/
Found 28 entries.

Have a nice day.



whatweb 104.16.167.228
http://104.16.167.228 [403 Forbidden] CloudFlare, Cookies[__cfduid], Country[UNITED STATES][US], HTML5, HTTPServer[cloudflare], HttpOnly[__cfduid], IP[104.16.167.228], Script[text/javascript], Title[Direct IP access not allowed | Cloudflare], UncommonHeaders[cf-ray], X-Frame-Options[SAMEORIGIN], X-UA-Compatible[IE=Edge]
