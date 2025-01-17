# RemcosRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [RemcosRAT](https://vuldb.com/?actor.remcosrat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.remcosrat](https://vuldb.com/?actor.remcosrat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RemcosRAT:

* [US](https://vuldb.com/?country.us)
* [LA](https://vuldb.com/?country.la)
* [GB](https://vuldb.com/?country.gb)
* ...

There are 6 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RemcosRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [80.66.75.51](https://vuldb.com/?ip.80.66.75.51) | - | - | High
2 | [89.23.98.22](https://vuldb.com/?ip.89.23.98.22) | - | - | High
3 | [95.214.26.18](https://vuldb.com/?ip.95.214.26.18) | - | - | High
4 | [95.214.26.25](https://vuldb.com/?ip.95.214.26.25) | - | - | High
5 | [95.214.26.60](https://vuldb.com/?ip.95.214.26.60) | - | - | High
6 | [95.214.26.79](https://vuldb.com/?ip.95.214.26.79) | - | - | High
7 | [95.214.26.90](https://vuldb.com/?ip.95.214.26.90) | - | - | High
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RemcosRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RemcosRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/admin/attendance_row.php` | High
3 | File | `/admin/cms_content.php` | High
4 | File | `/admin/deduction_row.php` | High
5 | File | `/admin/departments/manage_department.php` | High
6 | File | `/admin/edit_subject.php` | High
7 | File | `/admin/invoice.php` | High
8 | File | `/admin/login.php` | High
9 | File | `/admin/maintenance/view_designation.php` | High
10 | File | `/admin/reportupload.aspx` | High
11 | File | `/admin/return_add.php` | High
12 | File | `/admin/sales/view_details.php` | High
13 | File | `/admin/service_requests/manage_inventory.php` | High
14 | File | `/admin/sys_sql_query.php` | High
15 | File | `/admin/transactions/track_shipment.php` | High
16 | File | `/admin/upload.php` | High
17 | File | `/adminPage/conf/reload` | High
18 | File | `/afltest/gpac/src/media_tools/av_parsers.c` | High
19 | File | `/ajax.php?action=read_msg` | High
20 | File | `/api/baskets/{name}` | High
21 | File | `/api/sys/login` | High
22 | File | `/application/index/controller/Databasesource.php` | High
23 | File | `/application/index/controller/File.php` | High
24 | File | `/application/plugins/controller/Upload.php` | High
25 | File | `/author_posts.php` | High
26 | File | `/be/rpc.php` | Medium
27 | File | `/blog` | Low
28 | File | `/category/order/hits/copyright/46/finish/1/list/1` | High
29 | File | `/cgi-bin/cstecgi.cgi` | High
30 | File | `/cgi-bin/login.cgi` | High
31 | File | `/cgi-bin/nas_sharing.cgi` | High
32 | File | `/cgi-bin/nightled.cgi` | High
33 | File | `/cgi-bin/vitogate.cgi` | High
34 | File | `/classes/Login.php` | High
35 | File | `/classes/Master.php?f=delete_category` | High
36 | File | `/classes/Master.php?f=delete_inquiry` | High
37 | File | `/classes/Master.php?f=delete_item` | High
38 | File | `/classes/master.php?f=delete_order` | High
39 | File | `/classes/Master.php? f=save_medicine` | High
40 | File | `/classes/Master.php?f=save_service` | High
41 | File | `/classes/Users.php?f=save` | High
42 | File | `/collection/all` | High
43 | File | `/config` | Low
44 | File | `/control/register_case.php` | High
45 | File | `/Controller/Ajaxfileupload.ashx` | High
46 | File | `/core/config-revisions` | High
47 | File | `/cupseasylive/currencylist.php` | High
48 | File | `/cupseasylive/grnlist.php` | High
49 | File | `/cupseasylive/locationmodify.php` | High
50 | File | `/cupseasylive/unitofmeasurementcreate.php` | High
51 | File | `/Device/Device/GetDeviceInfoList?deviceCode=&searchField=&deviceState=` | High
52 | File | `/dipam/save-delegates.php` | High
53 | File | `/Duty/AjaxHandle/UploadHandler.ashx` | High
54 | File | `/DXR.axd` | Medium
55 | ... | ... | ...

There are 481 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/52920/
* https://asec.ahnlab.com/en/65111/
* https://asec.ahnlab.com/en/66463/
* https://blog.morphisec.com/unveiling-uac-0184-the-remcos-rat-steganography-saga
* https://cert.gov.ua/article/6276567
* https://www.esentire.com/blog/from-onlydcratfans-to-remcosrat
* https://www.trustwave.com/en-us/resources/blogs/spiderlabs-blog/a-noteworthy-threat-how-cybercriminals-are-abusing-onenote-part-2/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
