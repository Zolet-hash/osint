## theharvester
- Discover email addresses and subdomains using theharvester
- gather organization data including email and breached data
- ```shell
  theharvester -d example.com -b all #search all sources
  theharvester -d example.com -b google #search google only
  theharvester -d example.com -b linkedin #search linkedin for employees
  theharvester -h
  # The addresses are valuable for social engineering and password attacks 
  # Subdomains reveals additional attack surfaces 
  # Always verify information gathered before using it
  ```
-
- ## h8mail
- Advanced email checking and breach checking with h8mail
- gather organization data including email and breached data
- ```shell
  h8mail -t example.com # Email enumeration for domain
  h8mail -t admin@example.com # check specific email for breaches
  h8mail -t example.com -o result.txt
  h8mail -t example.com -j # otput in JSON format
  h8mail -t example.com -v # verbous mode
  h8mail -t example.com -q # quiet mode
  h8mail -h
  # h8mail combines email discovery with breach checking
  # password breaches reveals compromised credentials
  # Email enumeration helps with social engineering
  # JSON output helps intergration with other tools
  ```
-
- # Asset discovery lab
- Discover and enumerate assets using DNS techniques, subdomain enumeration and search engines
- ## DNS with dig
-