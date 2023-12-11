Welcome to Subtron, your go-to tool for comprehensive subdomain enumeration and live domain testing. Powered by a sophisticated combination of Subfinder, Amass, and Assetfinder, Subtron is designed to streamline identifying potential vulnerabilities within web domains. Leveraging the robust capabilities of these tools, Subtron conducts thorough subdomain enumeration swiftly and efficiently.

What sets Subtron apart is its integration with HTTPX, enabling real-time testing of live domains to uncover security loopholes. The tool meticulously analyzes live domains, capturing the findings and storing them in the 'final.txt' file for in-depth examination and further analysis.



## Installation:
```
git clone https://github.com/atulxerma/subtron.git
```
```
chmod +x setup subtron
```
```
bash setup
```
no need to run the setup file if you have subfinder, assetfinder, amass and httpx already in your machine if yes skip bash setup and run:
```
sudo cp subtron /usr/local/bin
```

now you can use Subtron anywhere from the terminal

## Usage:
subtron target.com

## Tip:
config your amass config.ini file for better results
https://github.com/OWASP/Amass/blob/master/examples/config.ini
