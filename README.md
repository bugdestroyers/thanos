<h1 align="center">
	<br>
	<a href="https://github.com/bugDestroyers/thanos">
		<img src="https://github.com/bugdestroyers/thanos/blob/master/thanos-1.png" alt="Thanos">
	</a>
	<br>
	Thanos
	<br>
</h1>	

<h4 align="center">HTTP Status Checker</h4>

<p align="center">
	<a href="https://github.com/bugDestroyers/thanos/releases">
		<img src="https://img.shields.io/github/release/bugDestroyers/Thanos.svg">
	</a>
	<a href="https://github.com/bugdestroyers/thanos/blob/master/LICENSE">
		<img src="https://img.shields.io/github/license/bugDestroyers/thanos">
	</a>
	<a href="https://github.com/bugDestroyers/thanos/issues?q=is%3Aissue+is%3Aclosed">
		<img src="https://img.shields.io/github/issues-closed-raw/bugDestroyers/Thanos.svg">
	</a>
</p>

<!-- ![demo](home/nullr3x/Downloads/thanos.png) -->

### ❱ Introduction
Thanos is a fast HTTP Status Checker tool. It takes a list of domains or subdomains & provide output as the list of probe url's with the http status code & it also identify the Cname of that Domain/Subdomain which shows an Not-Found error.

### Installation
> **NOTE:** You need to install this module separately **sudo apt install python3-dns**
```
git clone https://github.com/bugDestroyers/thanos
cd thanos
sudo python3 setup.py install
```

### Features
- Multi-Threading
- Launching parallel tasks
- Simple & Easy modification code base for contributers.
- Fast Probing
- Easy detection of HTTPS where port 80 is no inactive.
- Supports hosts, URLs, CIDR & ASNs(Coming Soon) as input.
- Exception Handling
- Easy to Use
- Cross Platform

### Usage

Short Form    | Long Form     | Description
------------- | ------------- |-------------
-c            | --config      | Path to a file that is a newline-delimited list of URLs
-d            | --directory   | path to a file that store_falses resolved list of URLs
-r            | --read-cache  | Read configured path
-del          | --del-cache   | Remove previous added path
-f            | --filename    | Path to file that contain list of subdmain to parse
-o            | --output      | Option to save resolved domain in following extensions eg. .txt, .csv, .json
-e            | --ignore-ssl  | Ignore errors in SSL handshakes
-v 			  | --version	  | Print thanos version
-h            | --help        | Show the help message and exit


#### How to use Thanos?
A detailed usage guide is available on [Usage](https://github.com/bugDestroyers/Thanos/wiki/Usage) section of the Wiki.\
An index of options is given below:

- [Configure permanent path to store data]()
- [Store data to temporary path]()
- [Ouput extensions]()
- [Ignore SSL Handshaking]()
- [Read previous configured path]()
- [Delete previous configured path]()
- [Read version of Thanos]()
