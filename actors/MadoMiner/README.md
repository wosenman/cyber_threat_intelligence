# MadoMiner - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [MadoMiner](https://vuldb.com/?actor.madominer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.madominer](https://vuldb.com/?actor.madominer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with MadoMiner:

* [VN](https://vuldb.com/?country.vn)
* [US](https://vuldb.com/?country.us)
* [CN](https://vuldb.com/?country.cn)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of MadoMiner.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [61.130.31.174](https://vuldb.com/?ip.61.130.31.174) | - | - | High
2 | [127.0.0.1](https://vuldb.com/?ip.127.0.0.1) | localhost | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _MadoMiner_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-25, CWE-29 | Pathname Traversal | High
2 | T1055 | CWE-74 | Injection | High
3 | T1059 | CWE-94, CWE-1321 | Cross Site Scripting | High
4 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | J2EE Misconfiguration: Weak Access Permissions for EJB Methods | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by MadoMiner. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/admin/upload/upload` | High
3 | File | `/api/baskets/{name}` | High
4 | File | `/api/gen/clients/{language}` | High
5 | File | `/cgi-bin/wlogin.cgi` | High
6 | File | `/config/getuser` | High
7 | File | `/config/myfield/test.php` | High
8 | File | `/debug/pprof` | Medium
9 | File | `/ecshop/admin/template.php` | High
10 | File | `/file/upload/1` | High
11 | File | `/forum/away.php` | High
12 | File | `/forum/PostPrivateMessage` | High
13 | File | `/goform/set_LimitClient_cfg` | High
14 | File | `/home/www/cgi-bin/login.cgi` | High
15 | File | `/multi-vendor-shopping-script/product-list.php` | High
16 | File | `/net-banking/customer_transactions.php` | High
17 | File | `/obs/book.php` | High
18 | File | `/ossn/administrator/com_installer` | High
19 | File | `/owa/auth/logon.aspx` | High
20 | File | `/pms/update_user.php?user_id=1` | High
21 | File | `/preview.php` | Medium
22 | File | `/requests.php` | High
23 | File | `/spip.php` | Medium
24 | File | `/sqlite3_aflpp/shell.c` | High
25 | File | `/sre/params.php` | High
26 | File | `/SVFE2/pages/feegroups/service_group.jsf` | High
27 | File | `/uncpath/` | Medium
28 | File | `/user/upload/upload` | High
29 | File | `/Users` | Low
30 | File | `/var/spool/hylafax` | High
31 | File | `/vendor` | Low
32 | File | `AccessibilityManagerService.java` | High
33 | File | `accountrecoveryendpoint/recoverpassword.do` | High
34 | File | `adclick.php` | Medium
35 | File | `add_contestant.php` | High
36 | File | `admin.php` | Medium
37 | File | `admin/edit_category.php` | High
38 | File | `admin/index.php` | High
39 | File | `admin/make_payments.php` | High
40 | File | `af_netlink.c` | Medium
41 | File | `album_portal.php` | High
42 | File | `api/auth.go` | Medium
43 | File | `api_jsonrpc.php` | High
44 | ... | ... | ...

There are 385 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.cyber45.com

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2023](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!