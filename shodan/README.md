# Shodan

- [Shodan](#shodan)
  - [Explore](#explore)
  - [Images](#images)
  - [Maps](#maps)
  - [Autonomous System Numbers (ASN)](#autonomous-system-numbers-asn)
  - [City](#city)
  - [Country](#country)
  - [Vulnerability](#vulnerability)
  - [Product](#product)
  - [Ransomware](#ransomware)
  - [Industrial Systems](#industrial-systems)
  - [Hacking Raspeberry Pi-Holes](#hacking-raspeberry-pi-holes)
  - [Cheatsheet](#cheatsheet)
  - [CheatSheet](#cheatsheet-1)
  - [Censys (alternative)](#censys-alternative)
  - [Zoomeye (alternative)](#zoomeye-alternative)

## Explore

[Shodan explore] - <https://www.shodan.io/explore>

## Images

[Shodan images] - <https://images.shodan.io/>

## Maps

[Shodan maps] - <https://maps.shodan.io/>

## Autonomous System Numbers (ASN)

- IP address into an ASN - <https://www.ultratools.com/tools/asnInfo>

- `asn:AS14061`

## City

- `city:madrid`

## Country

- `country:fr`

## Vulnerability

- `vuln:ms17-010`
- `vuln:CVE-2014-0160`

## Product

- `product:MySQL`

## Ransomware

- `has_screenshot:true encrypted attention`

## Industrial Systems

- `screenshot.label:ics`

## Hacking Raspeberry Pi-Holes

- <https://github.com/bee-san/How-I-Hacked-Your-Pi-Hole/blob/master/README.md>

## Cheatsheet

- port: Search by specific port
  - `proftpd port:21`
- net: Search based on an IP/CIDR
  - `net:34.98.0.0/16`
- hostname: Locate devices by hostname
  - `hostname:"google"`
- server:
  - `server: "apache 2.2.3"` or `apache 2.2.3`
- os: Search by Operating System
  - `os:"windows xp"`
- city: Locate devices by city
  - `city:"Madrid"`
- country: Locate devices by country
  - `country:"FR"`
- geo: Locate devices by coordinates
  - `geo:"48.1667,-100.1667"`
- org: Search by organization
  - `org:"Google"`
- before/after: Timeframe delimiter
  - `nginx before:13/04/2020 after:13/04/2018`
- has_screenshot:
  - `has_screenshot:true city:"George Town"`
- Wifi Passwords:
  - `html:"def_wirelesspassword"`
- hash: Search based on banner hash
- has_screenshot: true Filter search based on a screenshot being present
- title: Search based on text within the title

- Windows RDP Password
  - `"\x03\x00\x00\x0b\x06\xd0\x00\x00\x124\x00"`
- Misconfigured WordPress Sites
  - `http.html:"* The wp-config.php creation script uses this file"`
- Mongo DB servers
  - `"MongoDB Server Information" port:27017 -authentication`
- Jenkins
  - `x-jenkins 200`
- FTP servers allowing anonymous access
  - `"220" "230 Login successful." port:21`
- Android Root Bridge
  - `"Android Debug Bridge" "Device" port:5555`
- Hiring
  - `"X-Recruiting:"`
- Self Signed Certificates
  - `ssl:"qnap"`


## CheatSheet

- <https://thedarksource.com/shodan-cheat-sheet/>
- <https://securitytrails.com/blog/top-shodan-dorks>

## Censys (alternative)

[Censys] - <https://censys.io/>

## Zoomeye (alternative)

[Zoomeye] - <https://www.zoomeye.org>
