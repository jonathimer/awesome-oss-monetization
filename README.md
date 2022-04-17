> WARN: this is still work in progress!

[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)

# Awesome OSS Monetization
A curated list of awesome monetization approaches for open source software. 
Currently, probably with a slight bias towards open source libraries (like react.js, core-js, etc.) rather than open source programs (like OpenOffice, MariaDB, etc.). 

Furthermore, the monetization approaches are meant for maintainers of the OSS - not external third-parties trying to make money with an OSS (e.g., by getting hired as an Consultant for an OSS). 

__Table of Contents__
- [Awesome OSS Monetization](#awesome-oss-monetization)
  - [Monetization Approaches](#monetization-approaches)
    - [Unconditional Funding](#unconditional-funding)
    - [Paid Access](#paid-access)
    - [Paid Content](#paid-content)
    - [Paid Licences](#paid-licences)
    - [Paid Services](#paid-services)
    - [Paid Use](#paid-use)
    - [Paid Work](#paid-work)
    - [Special Monetization Approaches](#special-monetization-approaches)
  - [Notes](#notes)
    - [Used Characteristics](#used-characteristics)
    - [Monetization Risks](#monetization-risks)
  - [Links to other Monetization Lists](#links-to-other-monetization-lists)

This list is the result of extensive internet research, compiling all the monetization approaches we could find from various sources. Please note that the list, classification and terminology represents a subjective opinion on the subject.

Feel free to commit corrections, additions, or further examples. The contribution guidelines are [here](./contributing.md)

---
## Monetization Approaches

In the following sections you can find the categorized list of monetization approaches for open-source software. The categories are based on the concept the payer is paying for - e.g., the category "Paid Content" combines approaches where a User pays for some additional content such as Merchandise.

An explanation of the [Used Characteristics](#used-characteristics) with metrics can be found below.

### Unconditional Funding
* [Private Donations](./approaches/private-donations.md)
* [Corporate Sponsoring](./approaches/corporate-sponsoring.md)
* [Funding Grants & Stipends](./approaches/grants-and-stipends.md)

### Paid Access
* [Paid Early Access](./approaches/early-access.md)
* [Paid Community Access](./approaches/memberspace.md)
* [Advertisements on Website(s)](./approaches/advertisements.md)

### Paid Content
* [Paid Online Courses](./approaches/paid-courses.md)
* [Paid Naming Rights](./approaches/paid-version-names.md)
* [Paid Merchandise or Books](./approaches/paid-merchandise.md)
* [Paid Tools / Extensions / Plugins](./approaches/paid-tools.md)
* [Paid Newsletter](./approaches/paid-newsletter.md)

### Paid Licences
* [Paid Commercial Use / Dual-Licensing](./approaches/dual-licensing.md)
* [Paid Premium Version / Open Core](./approaches/open-core.md)
* [Licensing the Brand](./approaches/license-brand.md) 
* [Sell White Label](./approaches/white-label.md) 

### Paid Services
* [Paid Hosting / Open SaaS](./approaches/paid-hosting.md)
* [Widget Frosting](./approaches/widget-frosting.md)
* [Paid Content Service](./approaches/paid-content-service.md)
* [Paid Data Storage](./approaches/paid-storage.md)

### Paid Use
* [Paid Usage](./approaches/paid-usage.md)
* [Kickback from Hoster](./approaches/kickback.md)
* [Paid Unlocking](./approaches/paid-unlocking.md)
* [Sell Telemetry](./approaches/telemetry.md)
* [Blockchain-based distribution](./approaches/blockchain-distribution.md)

### Paid Work
* [Paid Support](./approaches/paid-support.md)
* [Paid Bugfixes / Bounties](./approaches/paid-bugfixes.md)
* [Paid Feature Development](./approaches/paid-features.md)
* [Paid Version Development / Crowdfunding](./approaches/paid-versions.md)
* [Paid Consultations](./approaches/paid-consultations.md)
* [Paid Training & Certifications](./approaches/paid-certifications.md)
* [Employment](./approaches/employement.md)

### Special Monetization Approaches
* [Raise Venture Capital](./approaches/raise-venture-capital.md)
* [Sell Project](./approaches/acquisition.md)
* TBD: Paid Binary / Selling without proprietary license (https://en.wikipedia.org/wiki/Business_models_for_open-source_software#Selling_without_proprietary_license) [Paid Binary](./approaches/paid-binary.md) 

---
## Notes

### Used Characteristics
In order to compare, evaluate, and explain the monetization approaches, several characteristics were used: 
* __Effort to set-up__: The amount of work required to start the monetization approach. [None; Low; Medium; High; N/A]
* __Effort to maintain income__: The amount of work needed to keep the monetization going. 
* __Visibility__: The ease with which a user of the OSS notices the monetization approach. 
* __Necessity to pay__: The need for the user of an OSS to accept and pay. 
* __Scalability__: The ease and number of users or companies that can be reached to pay. 
* __One-time Income__: The level of one single contribution. 
* __Recurring Income__: The level of monthly contribution that can be expected. 
* __Entry Threshold for client__: The amount of effort necessary to contribute money. 
* __Clients needed for full income__: The amount of payers necessary to get to 5k USD (pre-Tax) per month. 

* __Effort for marketing__: The amount of work necessary to make the monetization opportunity known to the public. 
* __Countervalue__: The value a contributor of money gets if he pays. 
* __Perfect for software type__: The types of OSS that would benefit the most from this onetization approach. 

* __Additional Work__: The amount of (continuous) work required in addition to working on the OSS. 
* __Upfront Cost__: The monetary cost to setup the monetization approach (e.g., for external services) - excluding cost for private bank accounts, tax advisors, etc. 
* __Continuous Cost__: The monetary cost to maintain the monetization approach over time (e.g., for the hosting of certificates)
* __Recipient__: The entity receiving the monetization result - and who might distribute it further (I: Individual, C: Collective/Company)
* __Competitors__: The kind of competitors for this monetization approach (M: Other maintainers, C: Contributors, O: Other Developers, Companies, or Content creators)

### Monetization Risks
If you want to monetize your open-source project several factors have to be considered. For legal and tax related info you should ask a lawyer or tax advisor - potentially, for all countries in which your contributors live in.
* __Not having a License__: If the current version your project has no declared license, it's legal status in undefined and you should clarify it (esp. with all other maintainers and contributors). Without a license, each user of the OSS needs explicit permission from each contributor/author to use it.
* __Not having a CLA__: If your project does not have a [CLA (Contributor License Agreement)](http://oss-watch.ac.uk/resources/cla) each contributor still holds the full rights to their contributed source code and could sue against a monetization. Github has a clause in their ToS which covers [this](https://docs.github.com/en/site-policy/github-terms/github-terms-of-service#6-contributions-under-repository-license), but if you want to monetize you all should agree on the terms and sign a CLA or remove code from contributors unwilling to sign the new terms. Furthermore, a CLA protects the project if a contributor has copied (stolen) code from somone / somewhere else.
* __Not having a concensus about monetization itself__ can become a problem - esp. when mixing monetization efforts (e.g., donations) by individuals and projects. If you want to monetize you should ask all contributors if, who, and how you should monetize. A contract clarifying the willingness to monetize might be a good idea (Please ask a lawyer for help).
* __Not having a concensus about distribution of income__ in the collective can become a reason for dispute. If you want to monetize you should vote on how you want to distribute the income. The recipients of the money can be contributors but also bug bounties, conferences, or non-profits. A contract defining the distribution might be a good idea (Please ask a lawyer for help).
* __Receiving money as a private person__: might be a bad idea - esp. if it is meant for the project. The money would have to be taxed twice - first by the individual and then by the final recipient. Furthermore, the taxation depends on the country / jurisdiction the recipients live in (or pay taxes in if they are Digital Natives). If you collect money for the project it might be a good idea to use a [fiscal host](https://docs.opencollective.com/help/fiscal-hosts/fiscal-hosts). As an individual it would be good to be registered as a Freelancer, to tax the income - but in some countries the normal income tax declaration might be sufficient (Please ask a tax advisor in your country).
* __Not paying taxes__ (as a project or individual) is always a bad idea. Even if you get only a dollar as a donation you should clarify how you have to declare the income and pay taxes (Please ask a tax advisor in your country).
* __Using a private bank account__ for collecting funds for your project is not a good idea. An extra bank account or fiscal host for the project to collect the funding and distribute it from there will help in being transparent.

## Links to other Monetization Lists
[1] https://en.wikipedia.org/wiki/Business_models_for_open-source_software

[2] https://github.com/nayafia/lemonade-stand 

[3] https://www.oss.fund

[4] [Charvat, Karel & Cerba, Otakar & Ježek, Jan & Fryml, Josef & Pospisil, Martin. (2009). Open Source Business Models and Strategies.](https://www.researchgate.net/publication/236023177_Open_Source_Business_Models_and_Strategies)

[5] [Sayeed, L., Verma, S., & Bora, A. (2002). Open Source Software Licensing and Business Models. In Proceedings of the Seventh Asia-Pacific Decision Sciences Institute Conference.](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.457.6814&rep=rep1&type=pdf)

