# Metasploit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the campaign known as _Metasploit_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor](https://vuldb.com/?actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Metasploit:

* [US](https://vuldb.com/?country.us)
* [RU](https://vuldb.com/?country.ru)

## Actors

These _actors_ are associated with Metasploit or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Metasploit](https://vuldb.com/?actor.metasploit) | High
2 | [Andariel](https://vuldb.com/?actor.andariel) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Metasploit.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [34.124.148.215](https://vuldb.com/?ip.34.124.148.215) | 215.148.124.34.bc.googleusercontent.com | [Metasploit](https://vuldb.com/?actor.metasploit) | Medium
2 | [35.185.187.24](https://vuldb.com/?ip.35.185.187.24) | 24.187.185.35.bc.googleusercontent.com | [Metasploit](https://vuldb.com/?actor.metasploit) | Medium
3 | [94.232.43.201](https://vuldb.com/?ip.94.232.43.201) | - | [Metasploit](https://vuldb.com/?actor.metasploit) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Metasploit. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059 | CWE-94 | Argument Injection | High
3 | T1505 | CWE-89 | SQL Injection | High

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Metasploit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `default.asp` | Medium
2 | File | `tv_email.php3` | High
3 | Argument | `cid` | Low
4 | ... | ... | ...

There are 1 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/59318/
* https://asec.ahnlab.com/en/64034/
* https://thedfirreport.com/2023/09/25/from-screenconnect-to-hive-ransomware-in-61-hours/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
