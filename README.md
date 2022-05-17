# Cybersecurity-Report

## A brief report on recent web security breaches.

### Okta Breach, 2022

  In March of 2022, a hacker group known as Lapsus$ announced via Telegram (a secure messaging app) that they had successfully breached Okta, an authentication provider company. Okta was forced to acknowledge the hack after Lapsus$ posted screenshots confirming the attack. Lapsus$ accomplished the breach by using publicly accessible hacking tools and remote access services to intrude Okta's third party VPN service. Over the course of five days, they were able to navigate deeper into company systems. By combing through company slack channels, hackers discovered support engineers had stored AWS (Amazon Web Services) keys in the channels. They were only able to gain access on par with support engineers, so the service itself was not breached. However, this did affect 2.5% of customers, and called into question Okta's own internal security practices.
  Lapsus$ had published a spreadsheet of admin names and last known passwords they found during the breach. Investigation into the screenshots revealed that the third party company in question was Sykes. A statement from the owner of Sykes, Sitel, stated that one of their subprocessors detected irregular sign-in attempts from the laptop of one of their engineers, and blocked the request, then contained the access attempt. The company did not elaborate on how, but they announced they had properly contained the breach. Laspus$ has not elaborated on exactly how this breach was accomplished, only the results of their infiltration.


Sources : 
  https://www.cnn.com/2022/03/23/tech/okta-breach-acknowledgment/index.html
  https://techcrunch.com/2022/03/22/okta-january-hack-breach/
  
  
### Broadvoice Breach, 2020
  
  A security consultant named Bob Diachenko, collaborating with Comparitech, a tech research firm, discovered a security flaw in Broadvoice. The US based VoIP (Voice over Internet Protocol) provider had a configuration error that made it easy to access the data of around 350 million users. This data included names, passwords, and call transcripts. The users included medical companies and other businesses that involve extremely sensitive private information exchanged via the phone. The breach also presented a risk for a follow-up attack, as the sensitive data could be used in sweeping phishing attacks. While the security flaw was quickly patched, there was no way to confirm whether or not bad actors had gained access to it.
  The flaw in question was a Broadvoice database that was open to access without any authentication required. If the data was accessed, it would be considered a Zero-Day attack, as it would have occurred prior to Broadvoice's knowledge of the flaw, or in the miniscule slice of time between them being warned and the subsequent fix. A breach like this can be averted by routine security checks to overcome human error. If the databases required their passwords to be updated on a regular basis, the fact that one of them lacked a password outright may have been discovered sooner.
  
  Sources : 
    https://www.techradar.com/news/clone-350-million-customer-details-leaked-in-broadvoice-scandal
  
