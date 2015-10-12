# sysadmin-toolbox

- [adminsys](#adminsys)
- [ssh](#ssh)
- [ssl/tls](#ssl-tls)
- [debian](#debian)
- [mails](#mails)
- [dns](#dns)
- [web](#web)
- [backup](#backup)
- [awesome list](#awesome-list)
- [misc](#misc)

## adminsys

* linux performance observability tools: [linuxperf](http://www.brendangregg.com/linuxperf.html)
* Bash Pitfalls - [bash.cumulonim.biz](http://bash.cumulonim.biz/BashPitfalls.html)

## ssh

*  Hardening ssh Servers - [mozilla](https://wiki.mozilla.org/Security/Guidelines/OpenSSH#OpenSSH_server) / [cloud.geek.nz](http://feeding.cloud.geek.nz/posts/hardening-ssh-servers/) / [stribika](http://stribika.github.io/2015/01/04/secure-secure-shell.html)
*  
## ssl-tls

* **ssllabs.com** ([ssllabs.com](https://www.ssllabs.com/)) performs an analysis of the configuration of a SSL web server
* **xmpp.net** ([xmpp.net](https://xmpp.net/)) - testing the security of the Jabber/XMPP servers
* **starttls.info** ([starttls.info](https://starttls.info)) - same thing, but for mail server
* **CipherScan** ([github.com/jvehent](https://github.com/jvehent/cipherscan)) tests the ordering of the SSL/TLS ciphers on a given target, for all major versions of SSL and TLS. It also extracts some certificates informations, TLS options, OCSP stapling and more.
* Mozilla: [Security/Server Side TLS](https://wiki.mozilla.org/Security/Server_Side_TLS)
* **[Fr]** **jeveuxhttps.fr** ([jeveuxhttps.fr](https://www.jeveuxhttps.fr)) pour vous aider à mettre en place du SSL/TLS pour vos sites web
*
* [Aeris](https://imirhil.fr)' works on SSL/TLS:
 * [websites](https://imirhil.fr/tls/)
 * [porn](https://imirhil.fr/tls/porn.html)
 * [smtp](https://imirhil.fr/tls/smtp.html)
 * [xmpp](https://imirhil.fr/tls/xmpp.html)

## debian

* [mastering debian](https://raphaelhertzog.com/mastering-debian/) par Raphaël Hertzog
* [Contributing to Debian](https://raphaelhertzog.com/contributing-to-debian/) par Raphaël Hertzog
* [Debian Packaging Tutorials](https://raphaelhertzog.com/debian-packaging/) par  Raphaël Hertzog
* Usual Debian Server Setup - [cloud.geek.nz](http://feeding.cloud.geek.nz/posts/usual-server-setup/)

## mails

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

## web

mirroring a website:
* wget (see [fosswire.com/](http://fosswire.com/post/2008/04/create-a-mirror-of-a-website-with-wget/) or [guyrutenberg.com](http://www.guyrutenberg.com/2014/05/02/make-offline-mirror-of-a-site-using-wget/)
* [httrack](https://httrack.com)

## backup

if you don't want to backup everything, dont forget:
* ssh, gpg, jabber and otr (.purple/), keypassx (*.kdb), 

## awesome list

* **Awesome security** [github.com/sbilly](https://github.com/sbilly/awesome-security)
* **Awesome pentest** [github.com/enaqx/](https://github.com/enaqx/awesome-pentest)
* **Awesome Malware Analysis**: [github.com/rshipp](https://github.com/rshipp/awesome-malware-analysis)
* **Awesome PHP**: [github.com/ziadoz](https://github.com/ziadoz/awesome-php)
* **Awesome python**:[github.com/vinta](https://github.com/vinta/awesome-python)
* **Awesome Ansible**:[github.com/jdauphant](https://github.com/jdauphant/awesome-ansible)
* [have i been pwned?](https://haveibeenpwned.com/) - Check if you have an account that has been compromised in a data breach


## misc

### CMS

* [Remonter une attaque avec les logs](https://www.libwalk.so/2015/04/29/analyse-log.html) (Fr)
* Drupal: [hardening](https://www.drupal.org/security/secure-configuration) / [security advisories](https://www.drupal.org/security)
* Spip: [security screen](http://www.spip.net/en_article4201.html)
* Wordpress: [hardening](http://codex.wordpress.org/Hardening_WordPress)


### infra

#### France

* **[Fr]** Le [test de degrouptest.com](http://www.degrouptest.com) permet d'avoir un aperçu rapide des offres Internet que vous pouvez avoir ainsi que les caractéristiques de votre ligne (ne pas oublier le *mode expert* pour avoir encore plus de détails)
* **[Fr]** le [test d'éligibilité d'OVH](http://www.ovhtelecom.fr/adsl/eligibilite.xml) permet d'avoir de manière simple et rapidement toutes les informations qu'il vous faut : débits théoriques et réels de la ligne, distance du NRA, éligibilité VDSL...
