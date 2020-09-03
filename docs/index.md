# Orlo Security & Compliance
Our customers range from SMB to enterprise organisations such as banks, government departments and police forces, all of which trust us with their data. Keeping our customers' data safe is our priority.




## Overview

<!--- __Explanation:__ This section gives a quick introduction to your security overview. It provides with contact details and a link to your security.txt if you have any. --->

<!--- __Customization:__ Change the contact email. Remove the [Securitytxt](https://securitytxt.org/) link if you don’t have any. --->

Keeping our customers' data protected at all times is our highest priority. This security overview provides a high-level overview of the security practices put in place to achieve that objective.
Have questions or feedback? Feel free to reach out through your sales rep or account manager.

## Dedicated Security Team

<!--- __Recommended for:__ >Series A/Series B startups. If you handle sensitive data this hire should probably come as soon as possible. --->

<!--- __Explanation:__ A dedicated team (or employee) shows additional commitment to the security of your data. Add this section if you have at least ½ an employee dedicated to improving the security of your company. Add more information (specific achievements or past roles of your team members) if you think it brings value. --->

<!--- __Customization:__ Minor customization required. --->

Our security team is comprised of both senior leadership and developers all dedicated to improving the security of our organization. Our team have been trained in security through real world experience, courses and training. 
Our employees are trained on security incident response and are on call 24/7.

## Infrastructure

<!--- __Recommended for:__ Every company, except if you don’t collect sensitive user data or don’t have users. --->

<!--- __Explanation:__ This section is required in every security overview. It explains your overall infrastructure security. Your infra can either be a managed data center (AWS, Google Cloud, Heroku, etc.) or a physical data center (managed by you or a third-party). --->

<!--- __Customization:__ Add the sub-section(s) that fits your company. --->

<!--- __Explanation:__ Use this section if your company’s infrastructure is based on a cloud provider. --->

<!--- __Customization:__ Minor customization. Choose your cloud provider. Delete irrelevant names and links. --->

All of our services run in the cloud. We don’t host or run our own routers, load balancers, DNS servers, or physical servers.
Our service is built on Amazon Web Services, Google Cloud Platform, Microsoft Azure and RackSpace. They provide strong security measures to protect our infrastructure and are compliant with most certifications. You can read more about their practices here:
- [AWS](https://aws.amazon.com/security/)
- [Google Cloud Platform](https://cloud.google.com/security/)
- [Microsoft Azure](https://www.microsoft.com/en-us/trustcenter/security)
- [Rackspace](https://www.rackspace.com/en-gb/compliance)

If you would like to understand more about our infrastructure can view a system architecture diagram [here](files/orlo_architecture_diagram.pdf).

We carry out regular audits inline with the company audit plan against all of our sub processors, if you would like to review this you can see it here: [View List](./index.html?sub-processors)

**On-site Security**

The above cloud providers on-site security includes a number of features such as security guards, fencing, security feeds, intrusion detection technology, and other security measures. [Learn more about AWS physical security](https://aws.amazon.com/compliance/data-center/perimeter-layer/) and [controls](https://aws.amazon.com/compliance/data-center/controls/)

Orlo's offices require card access which is logged and the building requires a seperate pass and is manned 24hrs a day. No platform data is stored on site. 

**Data hosting**

We host all of our data in UK and EU data zones to comply with GDPR, if you would like to read more about data privacy 
and protection please see our [Privacy and Data Protection](./index.html?privacy_and_data_protection) resource.

## Network level security monitoring and protection

<!--- __Recommended for:__ Every company. --->

<!--- __Explanation:__ This section describes the tools in place to monitor and/or protect your network. Isolating networks and restricting accesses to internal services with assigned private IP addresses are security best practices you should follow as soon as possible. --->

<!--- __Customization:__ Medium customization. Delete the best practices you’re not following. --->

Our network security architecture consists of multiple security zones. We monitor and protect our network, to make sure no unauthorized access is performed using:
- A virtual private cloud (VPC), a bastion host and no public IP addresses.
- A firewall that monitors and controls incoming and outgoing network traffic.
- An Intrusion Detection and/or Prevention technologies (IDS/IPS) solution that monitors and blocks potential malicious packets.
- IP address filtering
- Port scanners to monitor open ports and changes
- We use Nagios to monitor our servers and alert us to any unexpected changes or anomalies

## DDoS protection

<!--- __Recommended for:__ >Series B companies where availability is a big business risk (think e-commerce, business relying on ads or APIs, etc.). --->

<!--- __Explanation:__ DDoS attacks consist of flooding a target with excessive requests to overload systems and stop legitimate requests. DDoS attacks shouldn’t be a big concern for smaller websites. This section describes the tools in place to mitigate DDoS attacks. Add this section to your overview if you use a CDN like Cloudflare, Incapsula, Akamai, etc. --->

<!--- __Customization:__ No customization. You can name your provider. Delete section if no DDoS protection is in place. --->

We use Distributed Denial of Service (DDoS) mitigation services powered by an industry-leading solution. You can read more about them here and there security: 
- [CloudFlare](https://www.cloudflare.com/en-gb/security/)
- [AWS Sheild](https://aws.amazon.com/shield/)

## Data encryption

<!--- __Recommended for:__ Every company, except if you don’t collect sensitive user data or don’t have users. --->

<!--- __Explanation:__ This part explains the encryption strategy at rest and in transit. There is no good reason not to do data encryption from day one. From data in transit (check your website with [SSLLabs](https://www.ssllabs.com) to encryption at rest ([in a database](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Overview.Encryption.html) or on your machine’s hard drives). To secure your user's passwords, you should either use [one-way encryption on salted passwords](https://blogs.dropbox.com/tech/2016/09/how-dropbox-securely-stores-your-passwords/) or use [bcrypt](https://en.wikipedia.org/wiki/Bcrypt). --->

<!--- __Customization:__ You could add more information on your encryption strategy (e.g. algorithm used), but it’s not required. --->

Encryption in transit: All data sent to, from or between our infrastructure is encrypted in transit via industry best-practices using Transport Layer Security (TLS). 
All our assets such as HTML, CSS and the likes are served over encrypted (TLS 1.1 and 1.2) which are rated "A" by sssllabs, you can see the report here here: https://goo.gl/36EK48. 
When using our web or mobile application all data is encrypted during transit to and from our servers (TLS 1.1 and 1.2) you which is graded "A" by sssllabs, you can see the report here here: https://goo.gl/ZujYmH

Password encryption: All passwords are encrypted using battled-proofed encryption algorithms in the database.

## Data retention and removal

<!--- __Recommended for:__ Every company, except if you don’t collect sensitive user data or don’t have users. --->

<!--- __Explanation:__ It’s a good practice to delete user data if not used. This should ideally happen after a specific period and on user request (also required for GDPR). Use this section if you have procedures in place to remove user data (after a period or user request). --->

<!--- __Customization:__ Highly customizable. Adapt the section to reflect your practices and define “usage data” (it could be events, logs etc.). Link to your privacy page. --->

We retain your data for as long as you have a active contract with us after which we will delete your all your data. 
Your data will be removed from our various backups 4 weeks after deletion.

If you would like to ready more about data privacy and protection please see our [resource here](./index.html?privacy_and_data_protection#what-happens-to-our-data-at-the-end-of-the-contract-)

Admins can request the removal of usage data by contacting [support@orlo.tech](mailto:support@orlo.tech)
Read more about our privacy settings at [orlo.tech/privacy-policy/](https://orlo.tech/privacy-policy/).


## Business continuity and disaster recovery

<!--- __Recommended for:__ Every company. --->

<!--- __Explanation:__ Backing up your critical assets is essential to ensure business continuity after a disaster. Add this section if you’re backing up data and if you test them regularly. Make sure your backups are properly encrypted. --->

<!--- __Customization:__ No customization. --->

**Uptime**

Orlo maintains a publicly available [system-status webpage](https://orlo.statuspage.io/uptime) which includes system availability details, scheduled maintenance, service incident history, and relevant security events. 
We also monitor all our upstream providers which can be found here as well. 


**Backups**

We back up all our critical assets to separate servers using encryption in transit. 
We manually document and audit the backups weekly through our audit plan to ensure they are valid and working and annually attempt to restore our entire system including the backups fully to guarantee a fast recovery in case of disaster. 

**Disaster Recovery**

Orlo holds and reviews regularly a business continuity policy and disaster recovery plan in case of a disaster to ensure minimal disruption for our customers. This is tested fully yearly and updated on changes to infrastructure.
We also review all social networks for up and coming changes as part of our audit plan to ensure our customers are not left behind or without service due to changes.
 
**Redundancy**

Orlo maintains highly available databases where possible mean that if a server was to go offline our service would continue with no interruption of no data loss.
Where we're not able to put inplace highly available databses we have hot slaves databases ready to go in case of server failure. 
All our networks are highly available (provided by cloud providers) and API servers are auto scaling

## Application security monitoring

<!--- __Recommended for:__ >Series A/Series B startups or earlier if you handle sensitive customer data. --->

<!--- __Explanation:__ This section describes the tools in place to monitor the security of your application in real-time. Being able to react quickly to attacks is key to limit damage. Add this section to your overview if you use an application security monitoring solution. --->

<!--- __Customization:__ Medium customization. Delete the tools you’re not using. --->

- We use technologies to monitor exceptions, logs and detect anomalies in our applications.
- We collect and store logs to provide an audit trail of our applications activity.
- Our audit plan covers security checks
- Our servers automatically run and update antivirus scanners
- 

We have procedures in place to to triage and remedy reported bugs and security vulnerabilities for product and service offering.

## Application security protection

<!--- __Recommended for:__ >Series A/Series B startups or earlier if you handle sensitive customer data. --->

<!--- __Explanation:__ This section describes the tools in place to protect your application from attacks in real-time. Most of the serious data breaches come from application vulnerabilities. Add this section to your overview if you use an application security protection tool to prevent data leaks or takeovers. --->

<!--- __Customization:__ Medium customization. Delete the tools you’re not using. --->

- We do not deploy or need installed any applications on your systems. Orlo runs entirely through the browser and support Internet Explorer 11+, Chrome, Firefox 
- We use security headers to protect our users from attacks. You can check our grade on [this security scanner](https://www.sqreen.com/scan?url=https://app.socialsignin.co.uk).
- We use security automation capabilities that automatically detect and respond to threats targeting our apps and check vulnerabilities in our dependencies. 


## Secure development

<!--- __Recommended for:__ >Series A/Series B startups. --->

<!--- __Explanation:__ This part describes the tools and processes in place to avoid pushing code vulnerabilities to production. The more mature the company, the more tools you should have in place. --->

<!--- __Customization:__ Delete the tools you don’t use. --->

We use the following best practices to ensure the highest level of security in our software:
- Developers participate in regular security training to learn about common vulnerabilities and threats
- All code is committed and tracked to individuals
- We do not use live data for testing or on local development environments
- We review our code for security vulnerabilities and validate all inputs to maintain integrity of data
- We regularly update our dependencies and make sure none of them has known vulnerabilities automatically through every deployment
- We use Static Application Security Testing (SAST) to detect basic security vulnerabilities in our codebase automatically in every deployment
- We rely on yearly third-party CREST accredited security experts to perform penetration tests of our applications. We fix all critical, high risks found immediately and medium and low risks are scheduled in to the road map respectively. 

## Responsible disclosure

<!--- __Recommended for:__ >Series A/Series B startups. --->

<!--- __Explanation:__ Use this section if you welcome responsible disclosure (you should). It describes your bug bounty policy and coverage. A high proportion of reported issues aren’t relevant, so be sure to have internal security knowledge to triage and respond to reports quickly. It is a best practice to reward security researchers (within the range of possibility for you). --->

<!--- __Customization:__ Low customizations. Adapt the coverage and exclusions, and add the proper contact email or [keybase](https://keybase.io/). Using a hosted public bug bounty program on HackerOne or BugCrowd? Just replace the content of this section with a link to your profile. --->

Please avoid automated testing and only perform security testing with your own data. Please do not disclose any information regarding the vulnerabilities until we fix them. 

You can report vulnerabilities by contacting [support@orlo.tech](mailto:support@orlo.tech). Please include a proof of concept. We will respond as quickly as possible to your submission.

**Accepted vulnerabilities are the following:**
- Cross-Site Scripting (XSS)
- Open redirect
- Cross-site Request Forgery (CSRF)
- Command/File/URL inclusion
- Authentication issues
- Code execution
- Code or database injections

**This does NOT include:**
- Logout CSRF
- Account/email enumerations
- Denial of Service (DoS)
- Attacks that could harm the reliability/integrity of our business
- Spam attacks
- Clickjacking on pages without authentication and/or sensitive state changes
- Mixed content warnings
- Lack of DNSSEC
- Content spoofing / text injection
- Timing attacks
- Social engineering
- Phishing
- Insecure cookies for non-sensitive cookies or 3rd party cookies
- Vulnerabilities requiring exceedingly unlikely user interaction
- Exploits that require physical access to a user's machine

## User protection and product security features

<!--- __Recommended for:__ >Series A/Series B startups or earlier if you handle medical/financial data or have enterprise customers.  --->

<!--- __Explanation:__ This section provides additional safety for your customers. Data breaches using account takeovers are on the rise. Adding product security features to protect your users is a good practice. Add this section if you implemented product security features like: 2-factor authentication, rate limiting, delegate authentication, etc.  --->

<!--- __Customization:__ Customization needed. Delete the features your product doesn’t offer and add more detail.  --->

**2-factor authentication**

We provide a 2-factor authentication mechanism, minimum password complexity and SSO to protect our users from account takeover attacks. Setting up this extra security measure is optional but highly recommended to increase the security of sensitive data.

**Account takeover protection**

We protect our users against data breaches by monitoring and blocking brute force attacks. You also have the ability to logout remotely any session if a device has gone missing or otherwise.

**Single sign-on**

Single sign-on (SSO) SAML is offered for our enterprise customers.
Single sign-on (SSO) is available using your Google account.

**Role-based access control**

Role-based access control (RBAC) is offered on all our accounts and allows our users to define roles and permissions. You can read more about this in our documentation here: [Support Portal](http://support.orlo.tech/support/solutions/articles/36000072166-user-settings-and-permissions)

## Compliance
<!--- __Recommended for:__ >Series A/Series B startups or earlier if you handle medical/financial data or have enterprise customers.  --->

<!--- __Explanation:__ This section is key for some businesses. You should add this section if your company is certified or compliant to specific regulations.  --->

<!--- __Customization:__ Very customizable. Choose the elements you’re compliant to. Do not hesitate to link to other pages or resources that detail more your compliance.  --->

**PCI Compliance**

We do not process any payment information and hence we do not need PCI compliance

**GDPR**

We’re compliant to the General Data Protection Regulation (GDPR). The purpose of GDPR is to protect the private information of EU citizens and give them more control over their personal data. Please see our [privacy policy](https://orlo.tech/privacy-policy/) for more information.

We engage with privacy by design and work closely with the social networks and legal teams to make sure that we’re doing our utmost to make sure that we do not unfairly use data collected and that it is used only for the purpose of providing you (the customer) our service. 
You can find out more from our [Privacy and Data Protection Page](./index.html?privacy_and_data_protection)


## Employee access

<!--- __Recommended for:__ >Series A/Series B. --->

<!--- __Explanation:__ This section explains your policy on internal access to user data. You should limit access as much as possible. Acceptable use cases are for support, debugging, etc. Mature companies should also implement strong audit logs. --->

<!--- __Customization:__ This section should be customized to reflect your internal practices. --->

- Our strict internal procedure prevents unnecessary employees or administrator from gaining access to user data. Limited exceptions can be made for customer support.
- All employees with access to live data has been vetted and DBS checked
- All our employees have Non-Disclosure and Confidentiality Agreements in there contract to protect our customers' sensitive information. We also maintain good on boarding and off boarding practices
