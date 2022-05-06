layout: page
title: "Security Overview"
permalink: /security

Keeping our customers' data protected at all times is our highest priority. This security overview provides a high-level overview of the security practices put in place to achieve that objective.

Have questions or feedback? Feel free to reach out to us at
[security@hellowalla.com](mailto:security@hellowalla.com)

## Infrastructure
### Cloud infrastructure

All of our services run in the cloud in US-only regions. We don’t host or run our own routers, load balancers, DNS servers, or physical servers. Our service is built on Amazon Web Services (AWS). They provide strong security measures to protect our infrastructure and are compliant with most certifications. You can read more about their practices here: [AWS](https://aws.amazon.com/security/)
                              
### Software
Our software infrastructure is updated regularly with the latest security patches.
            
## Network-level security monitoring and protection
We utilize AWS Virtual Private Cloud (VPC) and benefit from VPC's security and isolation strategies. You can read more about their capabilities and practices [here](https://aws.amazon.com/vpc/).

We monitor and protect our network to make sure no unauthorized access is performed using:
* A Runtime Application Self-Protection (RASP) & In-App WAF that monitors and blocks attacks.
* An Intrusion Detection and/or Prevention technologies (IDS/IPS) solution that monitors and blocks attacks.
* IP address filtering

## Data encryption
### Encryption in transit: 
All data sent to or from our infrastructure is encrypted in transit via industry best-practices using Transport Layer Security (TLS). You can see our SSLLabs report [here](https://www.ssllabs.com/ssltest/analyze.html?d=manage.hellowalla.com).
                
### Encryption at rest:
Data encrypted at rest uses battled-proofed encryption (AES-GCM) in the database.
              
## Data retention and removal

Any user can request that Walla completely delete their data from all databases and their request will be carried out within 24 hours of the request. Alternatively, Walla businesses can delete their customers' data from within Walla's Front Desk software. All data is then immediately and completely removed from the database server. Within 30 days all data will be permanently deleted from backups. Read more about our privacy   practices in our [privacy policy](https://www.hellowalla.com/privacy).

## Business continuity and disaster recovery</h2>
We back up all our critical assets and regularly attempt to restore the backup to guarantee a fast recovery in case of disaster. All our backups are encrypted and retained for a maximum of 30 days.

## Constant monitoring
We have systems dedicated to maintaining your account’s security on our systems and monitoring tools we’ve set up to alert us to any nefarious activity against our domains. In the unfortunate circumstance where someone malicious does successfully mount an attack, we will immediately notify all affected customers.
       
## Application security monitoring
* We use a security monitoring solution to get visibility into our application security, identify attacks and respond quickly to a data breach.
* We use technologies to monitor exceptions, logs and detect anomalies in our applications.
* We collect and store logs to provide an audit trail of our application's activity.
* We use trace monitoring in our services layer.

## Application security protection
* We use a runtime protection system that identifies and blocks OWASP Top 10 and business logic attacks in real-time.
* We use security headers to protect our users from attacks. You can check our grade on [Mozilla Observatory](https://observatory.mozilla.org/analyze/manage.hellowalla.com).
* We use security automation capabilities that automatically detect and respond to threats targeting our apps.
* We use a vulnerability scanner as part of our continuous integration workflow allowing us to prevent security issues before source code is committed.
* We use a security monitoring solution that tracks all third-party libraries and notifies our teams if there is any security advisory so that we can patch the library as quickly as possible.

## Penetration testing
We perform periodic penetration tests via a selected third-party vendor.

## Secure development
We develop the following security best practices and frameworks (OWASP Top 10, SANS Top 25). We use the following best practices to ensure the highest level of security in our software:
* Developers proactively read up on common vulnerabilities and threats
* We review our code for security vulnerabilities
* We have automated monitors that regularly update our dependencies and make sure none of them has known vulnerabilities
* We use Static Application Security Testing (SAST) to detect basic security vulnerabilities in our codebase
* We rely on quarterly third-party penetration tests of our applications

## Responsible disclosure
You can report vulnerabilities by contacting [security@hellowalla.com](security@hellowalla.com).

Please include a proof of concept. We will respond as quickly as
possible to your submission and will not take legal action if you follow [the rules](https://cheatsheetseries.owasp.org/cheatsheets/Vulnerability_Disclosure_Cheat_Sheet.html).

**Coverage**: *.hellowalla.com
                            
## User protection
* **Account takeover protection**: We protect our users against data breaches by monitoring and blocking brute force attacks.

## Compliance
### PCI Compliance
All payment instrument processing is safely outsourced to Stripe which is certified as a PCI Level 1 Service Provider. We do not collect any payment information and are therefore not subject to PCI obligations.
            
### GDPR
We are compliant with the General Data Protection Regulation (GDPR). More can be read about that in our [terms](/terms).

### Data Residency
All data is hosted in a US region and data is not transferred outside of the US.
                   
## Payment information
All payment instrument processing is safely outsourced to Stripe which is certified as a PCI Level 1 Service Provider. We do not collect any payment information and are therefore not subject to PCI obligations.

## Audits and Certifications
Walla's infrastructure subprocessors have obtained third-party certifications and compliance audits.

* AWS
	* [PCI DSS](https://aws.amazon.com/compliance/pci-dss-level-1-faqs/)
	* [HIPAA](https://aws.amazon.com/compliance/hipaa-compliance/)
	* [ISO](https://aws.amazon.com/compliance/iso-certified/)
	* [SOC](https://aws.amazon.com/compliance/soc-faqs/)
* [Postmark - PCI, ISO, and SOC](https://postmarkapp.com/eu-privacy#security-and-privacy)
* [Stripe - PCI](https://stripe.com/docs/security/stripe)

