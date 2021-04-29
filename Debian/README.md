### VM
---
#### Installation
	1. Download Linux Image
	2. Download VirtualBox	
---

#### Configuration VBOX
	1. Choose what os and folder where you going to install
	2. 4GB RAM, 100GB HDD, 2 CPU, 128MB GPU,
	3. VBoxVGA, Biderectional for clipboard and drag'n'drop
---

#### Post-Installation
	1. Update the system
	2. Guest additions
		a. Devices -> Insert Gues CD image
		b. Check for kernel headers, dkms framework, build-tools
		c. if none installed `sudo apt install dkms linux-headers-$(uname -r) build-essential`
		d. Install Guest Additions `sudo sh /media/cdrom0/VBoxLinuxAdditions.run`
	3. Synaptic, ufw, ubuntu-restricted-extra `sudo apt install ttf-mscorefonts-installer rar unrar libavcodec-extra gstreamer1.0-libav gstreamer1.0-plugins-ugly gstreamer1.0-vaapi`
	4. (link1)[https://www.youtube.com/watch?v=BWBHJmAmZgk], (link2)[https://www.youtube.com/watch?v=BWBHJmAmZgk]
---

#### Tools
	1. C, C++, Python, Java, Dotnet
	2. Terminator - (Theme, Hot-Keys), 
	   Sublime - (Theme, Compilers, Packages (backrefs, jsonschema, markupsafe, mdpopups, ptyprocess, pygments, pymdownx, pyte, python-jinja2, python-markdown, pyyaml, sublcodeintel, wcwidth, fileIcon, terminus, emmet)) 
	   Visual Studio Code 
	5. Leanpeas, Wordlists
	6. Strings
---

### SSH
	1. To home network
---

##### Pen-test Tools
	1. Reconnaissance
		a. traceroute
		b. nmap
	2. Metasploit
	3. Sniffing and Spoofing
		a. Wireshark
		b. Bettercap
	4. Exploitation
		a. SET (Social Engineering Toolkit)
	5. Wireless Attack
		a. aircrack-ng
		b. fluxion
	6. Password Attacks
		a. hydra
		b. john the ripper
		c. crunch
		d. beef
		e. Hash-Identifier and FindMyHash
	7. Database Assessnent
		a. SQLMap
	8. Web Application Analysis
		a. JoomScan & WPScan
		b. httrack
		c. owasp-zap
		d. BurpSuit
		e.SQLiv
	9. Vulnerability Analysis
		a. Nikto
	10. Information Gathering
		a. dirbuster / gobuster
		b. nmap
		c. Maltegoce
		d. whois
		e. WhatWeb
		f. TraceRoute
	11. Anonimity
		a. Proxychains
		b. MacChanger
	12.
		a. NetCat
---
