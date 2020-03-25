# Overview - Cyber Threats Abusing COVID-19

Real-time updates by CERT-EU : https://media.cert.europa.eu/cert/filteredition/en/Cybersecurity-Covid-19.html

## Phishing
Many emails themed with COVID-19 are sending office documents with malicious attachments or links to dropper sites (trickbot, hancitor, others). Moreover there are many sites with urls design to lure users interested in covid-19 to malicious sites to drop desktop/mobile malware.

- U.S. Department of Health & Human Services open redirect is currently being used by attackers to push malware : https://www.bleepingcomputer.com/news/security/hhsgov-open-redirect-used-by-coronavirus-phishing-to-spread-malware/
- COVID-19 Real Time Scam Hunter : https://thugcrowd.com/covid-19/
- COVID-19 fake domains feed : https://twitter.com/RiskIQ/status/1239619032933748738?s=20
- Compilation of Phining covid-19 themed + yara rules to detect malicious emails: https://cofense.com/solutions/topic/coronavirus-infocenter/#yara-rule
- Covid-19 themed word + macro dropping trickbot:  https://twitter.com/malware_traffic/status/1241072162750029825?s=20
- Fake “Corona Antivirus” distributes BlackNET remote administration tool : https://blog.malwarebytes.com/threat-analysis/2020/03/fake-corona-antivirus-distributes-blacknet-remote-administration-tool/
- Coronavirus outbreak - Joint Statement European Commission, ENISA, CERT-EU and Europol : https://ec.europa.eu/digital-single-market/en/news/coronavirus-outbreak-joint-statement-european-commission-enisa-cert-eu-and-europol
- KPOT infostealer: https://isc.sans.edu/forums/diary/More+COVID19+Themed+Malware/25930/
- Fake email from WHO: https://isc.sans.edu/diary/25922
- Fake covid-19 site as bait: https://thehackernews.com/2020/03/covid-19-coronavirus-hacker-malware.html
- CoronaVirus Themed Malspam(Hancitor malware): https://threatblogs.wordpress.com/2020/03/23/coronavirus-themed-malspamhancitor-malware/

## Covid-19 map copycat or fake tracking apps
Many versions of malware pretending to be the official map were found in the wild.
- coronavirus maps to spread malware (They're scraping user data, including user names, passwords and credit card numbers.) https://www.weforum.org/agenda/2020/03/hackers-are-using-coronavirus-maps-to-spread-malware 
- COVID-19, Info Stealer &  the Map of Threats – Threat Analysis Report: https://blog.reasonsecurity.com/2020/03/09/covid-19-info-stealer-the-map-of-threats-threat-analysis-report/
- https://thehackernews.com/2020/03/coronavirus-maps-covid-19.html
- CovidLock: Mobile Coronavirus Tracking App Coughs Up Ransomware: https://www.domaintools.com/resources/blog/covidlock-mobile-coronavirus-tracking-app-coughs-up-ransomware

## Cyber attacks
Currently there are a series of DDOS hitting critical infra (mirai like + others) as well as targeted attacks against healthcare institutions
- Laboratory hit in czech:  https://securityaffairs.co/wordpress/99598/hacking/covid-19-czech-hospital-hit-cyberattack.html
- Reflective DNS Ddos : https://isc.sans.edu/forums/diary/A+Quick+Summary+of+Current+Reflective+DNS+DDoS+Attacks/25916/
- Hackers Hijack Routers’ DNS to Spread Malicious COVID-19 Apps: https://www.bleepingcomputer.com/news/security/hackers-hijack-routers-dns-to-spread-malicious-covid-19-apps/
- World Health Organization targeted: https://news.trust.org/item/20200323182423-bgpm7/


## Magecart alert
Due to the fact that most people are buying online because of social distancing card skimmers risk is very high. Megacart actors are experts when it comes to inject their code on 3rd parties webshops so people can be greatly affected by this threat. Increase of 20% of magecart activity has been confirmed
- Increase of 20% of activity : https://twitter.com/ydklijnsma/status/1241463181593079809?s=20
- Blender manufacturer NutriBullet on Wednesday said it had identified and removed malicious code on its website that allowed attackers to steal data from customers: https://www.darkreading.com/attacks-breaches/skimmer-may-have-put-nutribullet-customers-card-data-at-risk-for-nearly-a-month/d/d-id/1337346

## Peace offering by big threat actor names.
Maze, DoppelPaymer, Ryuk, Sodinokibi/REvil, PwndLocker, and Ako have informed that they wont target healthcare institution while the covid-19 crisis. However it doesn't mean that they are not getting access to their networks. There is a big chance that as soon as the crisis is over many hospital will be affected since currently cybersecurity is not a priority to them.
- Ransomware Gangs to Stop Attacking Health Orgs During Pandemic: https://www.bleepingcomputer.com/news/security/ransomware-gangs-to-stop-attacking-health-orgs-during-pandemic/
- https://www.wired.com/story/ransomware-magecart-coronavirus-security-news/?mbid=social_twitter&utm_brand=wired&utm_campaign=wired&utm_medium=social&utm_social-type=owned&utm_source=twitter
- Given these recent successes of deploying ransomware via AZORult and Emotet, RiskIQ assesses that it’s only a matter of time before cybercriminals return to this methodology: https://cdn.riskiq.com/wp-content/uploads/2020/03/Coronavirus-Outbreak-Intelligence-Brief-RiskIQ.pdf
### And its gone:
- Maze ransomware attackers extort vaccine testing facility: https://www.scmagazine.com/home/security-news/ransomware/maze-ransomware-attackers-extort-vaccine-testing-facility/
- Healthcare hit with ransomware, despite promised truce: https://risky.biz/newsletter2/
- Netwalker hits spanish hospitals: https://elpais.com/espana/2020-03-23/la-policia-detecta-un-ataque-masivo-al-sistema-informatico-de-los-hospitales.html

## Working from home (WFH) Risks
As people work from home there is the risk of infection been unnoticed. Normally your workstation is inside your company network, now it is not and most likely you are using the ISP's DNS rather than the company one normally used and monitored by SoC, so if you get infected now it is harder to notice until is too late. Moreover to have more flexibility companies are allowing people to use their home computers to access company resources via VPN. This systems could have been already compromise and are not hardened. Lastly many many campaigns have mutated towards a covid-19 theme but this doesn't mean that normal cyber threats have stopped. So no malware campaigns shall be neglected in either case covid-19 or not covid-19 themed.

- In a rush to enable working from home, organizations are exposing their assets online, opening themselves to attacks: https://twitter.com/_CPResearch_/status/1242528620477849602?s=20

## Other Threats regarding covid-19
- Is APT27 Abusing COVID-19 To Attack People ?!: https://marcoramilli.com/2020/03/19/is-apt27-abusing-covid-19-to-attack-people/ 

## COVID-19 malware samples 
- MalwareBazaar Database: https://bazaar.abuse.ch/browse/tag/COVID-19/
- any run: https://app.any.run/submissions/#tag:covid19

# Advisory to avoid covid-19 cyber threats
Phishing in the Time of COVID-19: How to Recognize Malicious Coronavirus Phishing Scams: https://www.eff.org/deeplinks/2020/03/phishing-time-covid-19-how-recognize-malicious-coronavirus-phishing-scams

# COVID-19 IOCs
- All IOC's are provided "as-is", please use your own verification methodology before deploying them in production network: https://github.com/parthdmaniar/coronavirus-covid-19-SARS-CoV-2-IoCs/
- OTX covid-19 pulses: https://otx.alienvault.com/browse/pulses?q=covid
- Carbonblack Covid19 IOCS: https://github.com/carbonblack/tau-tools/tree/master/threat_hunting/IOCs/COVID-19%20Post%20IOCs






