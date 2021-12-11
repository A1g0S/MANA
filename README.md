# MANA: Beta version
Recon and vulnerability scanning automation tool

Stage one:
 Mana searches through apis and uses some tools for that to find subdomains, also it launches a bruteforce to find more subs.
 Mana finds every live http/s server on port 80 and 443.
 Mana finds history for every subdomain on archive.org.
 
Stage two:
 Mana scans for open ports every domain found in stage one.
 Then mana requests the urls from archive to find working ones and saves urls with .php, .jsp, .html, .js.
 Mana requests every live host found in stage one and saves the .body and .header for further analyzing.
 In the end mana saves titles found from previous requests and unique headers.
 
 Mana is in beta version, so it might not work properly.
 Please for any problem contact me!
 
 Install
   git clone https://github.com/A1g0S/MANA.git
   cd MANA
   chmod +x mana
 
