# Books
1. The web application hacker's handbook
2. owasp testing guide
3. web hacking 101
4. breaking into infromation security
5. mastering mordern web peneteration testing

# Recon
* ASN's(autonomous system numbers)- http://bgp.he.net (ip ranges , keyword searches)
* ARIN & RIPE - [arin](http://whois.arin.net/ui) 
                 [ripe](http://apps.db.ripe.net/db-web-ui/#/fulltextsearch)  whoislookups all
* Rev whois - [rev](http://reverse.report)
* shodan - [shodan](shodan.io)
* we cannot miss out on **burp**
* domlink [domlink](https://github.com/vysecurity/DomLink)
* [builtwith](https://builtwith.com/) - they also has a browser plugin it tells about stack that site is bult on and analytics
  
     #### Subdomain scraping enumeration
       
     * google dorks
     * [robtex](https://robtex.com)
     * waybackmachine
     * [sublist3r](https://github.com/aboul3la/Sublist3r)
     * [Amass](https://github.com/caffix/amass)
     * [subfinder](https://github.com/ice3man543/subfinder)
     * [Cloudflare Enumeration Tool](https://github.com/mandatoryprogrammer/cloudflare_enum)
     #### subdomain bruteforcing
     
     * massdns
        ex:
        `.subbrute.py /root/work/bin/all.txt $TARGET.com | ./bin/massdns -r resolvers.txt -t A -a -o -w massdns_output.txt -`
     * gobuster
        ex
        `time gobuster -m dns -u  $TARGET.com -t 100 -w all.txt`
     * best dictonary file :
