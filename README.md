# sysadmin-toolbox

- [adminsys](#adminsys)
- [ssl/tls](#ssl-tls)
 - [tls-config](#tls-config)
- [Mails](#mails)
- [dns](#dns)
- [awesome list](#awesome-list)
- [infra](#infra)

## adminsys

* linux performance observability tools: [linuxperf](http://www.brendangregg.com/linuxperf.html)
* Bash Pitfalls - [bash.cumulonim.biz](http://bash.cumulonim.biz/BashPitfalls.html)

## ssl-tls

* **ssllabs.com** ([ssllabs.com](https://www.ssllabs.com/)) performs an analysis of the configuration of a SSL web server
* **xmpp.net** ([xmpp.net](https://xmpp.net/)) - testing the security of the Jabber/XMPP servers
* **starttls.info** ([starttls.info](https://starttls.info)) - same thing, but for mail server
* **CipherScan** ([github.com/jvehent](https://github.com/jvehent/cipherscan)) tests the ordering of the SSL/TLS ciphers on a given target, for all major versions of SSL and TLS. It also extracts some certificates informations, TLS options, OCSP stapling and more.
* percentage of email encrypted for the top domains in terms of volume of email to and from Gmail: [Google/saferemail](https://www.google.com/transparencyreport/saferemail/#search=orange.fr)


* [Aeris](https://imirhil.fr)' works on SSL/TLS:
 * [websites](https://imirhil.fr/tls/)
 * [porn](https://imirhil.fr/tls/porn.html)
 * [smtp](https://imirhil.fr/tls/smtp.html)
 * [xmpp](https://imirhil.fr/tls/xmpp.html)

### tls config

* **[Fr]** **jeveuxhttps.fr** ([jeveuxhttps.fr](https://www.jeveuxhttps.fr)) pour vous aider à mettre en place du SSL/TLS pour vos sites web
* Mozilla: [Security/Server Side TLS](https://wiki.mozilla.org/Security/Server_Side_TLS)

## Mails

* **mxtoolbox** ([mxtoolbox.com](http://mxtoolbox.com/)) will list MX records for a domain (verify reverse DNS records, perform a simple Open Relay check and measure response time performance, check each MX record (IP Address) against 105 DNS based blacklists)
* **anti-abuse.org** ([www.anti-abuse.org](http://www.anti-abuse.org/)) Instant Multi-RBL Check (Real-time BlackLists)
 * **RBLmon** ([RBLmon](http://www.rblmon.com/)) is a fully automated online service, which allows you to monitor your IP addresses against the most popular and commonly used real-time blacklists (RBLs).
* **IMAPsync** ([IMAPsync](https://github.com/imapsync/imapsync)) Synchronises mailboxes between two imap servers IMAP synchronisation, sync, copy or migration tool.

## DNS

* **[Fr]** liste des différents [enregistrements DNS](http://fr.wikipedia.org/wiki/Liste_des_enregistrements_DNS)
* [zonemaster.net](http://zonemaster.net) : domain check
* [dnssec-validator.cz](https://www.dnssec-validator.cz/) : DNSSEC/TLSA Validator plugin
* [whatsmydns.net](https://www.whatsmydns.net) : global DNS propagation checker
* [whois.domaintools.com](http://whois.domaintools.com/) - whois lookup / reverse whois lookup

## awesome list

* **Awesome security** [github.com/sbilly](https://github.com/sbilly/awesome-security)
* **Awesome pentest** [github.com/enaqx/](https://github.com/enaqx/awesome-pentest)
* **Awesome Malware Analysis**: [github.com/rshipp](https://github.com/rshipp/awesome-malware-analysis)
* **Awesome PHP**: [github.com/ziadoz](https://github.com/ziadoz/awesome-php)
* **Awesome python**:[github.com/vinta](https://github.com/vinta/awesome-python)
* **Awesome Ansible**:[github.com/jdauphant](https://github.com/jdauphant/awesome-ansible)
* [have i been pwned?](https://haveibeenpwned.com/) - Check if you have an account that has been compromised in a data breach


## infra

### France

* **[Fr]** Le [test de degrouptest.com](http://www.degrouptest.com) permet d'avoir un aperçu rapide des offres Internet que vous pouvez avoir ainsi que les caractéristiques de votre ligne (ne pas oublier le *mode expert* pour avoir encore plus de détails)
* **[Fr]** le [test d'éligibilité d'OVH](http://www.ovhtelecom.fr/adsl/eligibilite.xml) permet d'avoir de manière simple et rapidement toutes les informations qu'il vous faut : débits théoriques et réels de la ligne, distance du NRA, éligibilité VDSL...
