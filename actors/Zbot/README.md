# Zbot - Cyber Threat Intelligence

These _indicators_ were collected during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Zbot](https://vuldb.com/?actor.zbot). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ is able to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.zbot](https://vuldb.com/?actor.zbot)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Zbot:

* US
* ES
* RU
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Zbot.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | 3.223.115.185 | ec2-3-223-115-185.compute-1.amazonaws.com | - | Medium
2 | 12.96.218.170 | - | - | High
3 | 13.32.204.55 | server-13-32-204-55.iad66.r.cloudfront.net | - | High
4 | 18.207.9.28 | ec2-18-207-9-28.compute-1.amazonaws.com | - | Medium
5 | 20.189.173.20 | - | - | High
6 | 20.189.173.22 | - | - | High
7 | 23.56.9.181 | a23-56-9-181.deploy.static.akamaitechnologies.com | - | High
8 | 23.96.30.229 | - | - | High
9 | 23.193.42.12 | a23-193-42-12.deploy.static.akamaitechnologies.com | - | High
10 | 23.227.38.32 | myshopify.com | - | High
11 | 24.115.94.180 | 24.115.94.180.res-cmts.ovr.ptd.net | - | High
12 | 24.120.165.58 | wsip-24-120-165-58.lv.lv.cox.net | - | High
13 | 27.54.110.77 | 77.110.54.27.dhcp.mct.ne.jp | - | High
14 | 32.178.143.61 | mobile-32-178-143-61.mycingular.net | - | High
15 | 34.72.197.182 | 182.197.72.34.bc.googleusercontent.com | - | Medium
16 | 35.177.71.77 | ns1.symbiant.net | - | High
17 | 36.2.242.186 | 36-2-242-186.aichi.otk.vectant.ne.jp | - | High
18 | 39.116.90.10 | - | - | High
19 | 41.168.5.140 | - | - | High
20 | 45.60.77.201 | - | - | High
21 | 46.165.243.51 | - | - | High
22 | 49.212.235.209 | www3469.sakura.ne.jp | - | High
23 | 50.7.252.125 | - | - | High
24 | 50.72.177.24 | S01069050ca30b943.wp.shawcable.net | - | High
25 | 50.116.43.143 | li480-143.members.linode.com | - | High
26 | 51.178.156.9 | ip9.ip-51-178-156.eu | - | High
27 | 52.85.132.44 | server-52-85-132-44.iad50.r.cloudfront.net | - | High
28 | 52.137.90.34 | - | - | High
29 | 52.168.117.173 | - | - | High
30 | 52.182.143.212 | - | - | High
31 | 52.185.71.28 | - | - | High
32 | 58.1.158.10 | ntaich204010.aich.nt.ngn.ppp.infoweb.ne.jp | - | High
33 | 58.68.2.214 | - | - | High
34 | 58.185.131.158 | - | - | High
35 | 59.90.221.6 | static.bb.hyd.59.90.221.6.bsnl.in | - | High
36 | 60.244.81.6 | 60-244-81-6.apol.com.tw | - | High
37 | 61.7.235.35 | - | - | High
38 | 61.32.242.131 | - | - | High
39 | 62.49.180.189 | - | - | High
40 | 62.76.47.5 | 62-76-47-5.vm.clodoserver.ru | - | High
41 | 62.76.178.192 | ballistica.ru | - | High
42 | 62.76.185.233 | 62-76-185-233.vm.clodoserver.ru | - | High
43 | 62.76.188.38 | 62-76-188-38.vm.clodoserver.ru | - | High
44 | 64.219.121.189 | - | - | High
45 | ... | ... | ... | ...

There are 174 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected ATT&CK techniques used by Zbot. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
2 | T1068 | CWE-264, CWE-284 | Execution with Unnecessary Privileges | High
3 | T1110.001 | CWE-798 | Improper Restriction of Excessive Authentication Attempts | High
4 | ... | ... | ... | ...

There are 7 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Zbot. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?ajax-request=jnews` | High
2 | File | `/admin/admin.php` | High
3 | File | `/admin/imageslider/file.php` | High
4 | File | `/cgi-bin/luci` | High
5 | File | `/cgi-bin/viewcert` | High
6 | File | `/core/vb/vurl.php` | High
7 | File | `/etc/ldap.conf` | High
8 | File | `/importTool/preview` | High
9 | File | `/mods/_core/courses/users/create_course.php` | High
10 | File | `/phppath/php` | Medium
11 | File | `/plugins/Dashboard/Controller.php` | High
12 | File | `/server-status` | High
13 | File | `/uncpath/` | Medium
14 | File | `adclick.php` | Medium
15 | File | `add_comment.php` | High
16 | File | `admin-ajax.php` | High
17 | File | `admin.php` | Medium
18 | File | `admin/class-bulk-editor-list-table.php` | High
19 | ... | ... | ...

There are 154 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2021/02/threat-roundup-0129-0205.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0205-0212.html
* https://blog.talosintelligence.com/2021/02/threat-roundup-0212-0219.html
* https://blog.talosintelligence.com/2021/03/threat-roundup-0226-0305.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0507-0514.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0514-0521.html
* https://blog.talosintelligence.com/2021/05/threat-roundup-0521-0528.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0528-0604.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0604-0611.html
* https://blog.talosintelligence.com/2021/06/threat-roundup-0617-0624.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0625-0702.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-0702-0709.html
* https://blog.talosintelligence.com/2021/07/threat-roundup-for-july-9-to-july-16.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1008-1015.html
* https://blog.talosintelligence.com/2021/10/threat-roundup-1015-1022.html
* https://blog.talosintelligence.com/2021/12/threat-roundup-1126-1203.html
* https://blog.talosintelligence.com/2022/02/threat-roundup-0204-0211.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2022](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!