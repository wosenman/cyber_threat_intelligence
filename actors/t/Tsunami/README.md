# Tsunami - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/?kb.cti) of the actor known as [Tsunami](https://vuldb.com/?actor.tsunami). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/?actor.tsunami](https://vuldb.com/?actor.tsunami)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Tsunami:

* [VN](https://vuldb.com/?country.vn)
* [CN](https://vuldb.com/?country.cn)
* [US](https://vuldb.com/?country.us)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Tsunami.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.101.118.127](https://vuldb.com/?ip.5.101.118.127) | - | - | High
2 | [5.181.25.210](https://vuldb.com/?ip.5.181.25.210) | vpn1255rm.com | - | High
3 | [5.181.80.119](https://vuldb.com/?ip.5.181.80.119) | rate-lead.cheapjerseysbrewers.com | - | High
4 | [20.151.71.228](https://vuldb.com/?ip.20.151.71.228) | - | - | High
5 | [23.95.226.157](https://vuldb.com/?ip.23.95.226.157) | 157-226-scilla.manykril.sbs | - | High
6 | [31.131.16.127](https://vuldb.com/?ip.31.131.16.127) | moy-dom.biz | - | High
7 | [37.44.244.106](https://vuldb.com/?ip.37.44.244.106) | - | - | High
8 | [37.44.244.124](https://vuldb.com/?ip.37.44.244.124) | - | - | High
9 | [45.9.148.44](https://vuldb.com/?ip.45.9.148.44) | - | - | High
10 | ... | ... | ... | ...

There are 35 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Tsunami_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Tsunami. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/#/network?tab=network_node_list.html` | High
2 | File | `/.env` | Low
3 | File | `/admin/app/profile_crud.php` | High
4 | File | `/admin/index.php` | High
5 | File | `/admin/list_localuser.php` | High
6 | File | `/admin/modules/product/controller.php?action=add` | High
7 | File | `/admin/orders/view_order.php` | High
8 | File | `/admin/suppliers/view_details.php` | High
9 | File | `/adminPage/main/upload` | High
10 | File | `/admin_ping.htm` | High
11 | File | `/api/sys/set_passwd` | High
12 | File | `/api/v1` | Low
13 | File | `/application/index/controller/Databasesource.php` | High
14 | File | `/application/index/controller/Icon.php` | High
15 | File | `/application/index/controller/Screen.php` | High
16 | File | `/application/plugins/controller/Upload.php` | High
17 | File | `/apps/reg_go.php` | High
18 | File | `/billing/bill/edit/` | High
19 | File | `/cgi-bin/cstecgi.cgi` | High
20 | File | `/cgi-bin/cstecgi.cgi?action=login&flag=1` | High
21 | File | `/cgi-bin/info.cgi` | High
22 | File | `/cgi-bin/mainfunction.cgi` | High
23 | File | `/cgi-bin/nas_sharing.cgi` | High
24 | File | `/cgi-bin/system_mgr.cgi` | High
25 | File | `/cgi-bin/wlogin.cgi` | High
26 | File | `/classes/Login.php` | High
27 | File | `/classes/Users.php` | High
28 | File | `/core/config-revisions` | High
29 | File | `/DesignTools/CssEditor.aspx` | High
30 | File | `/desktop_app/file.ajax.php?action=uploadfile` | High
31 | File | `/DXR.axd` | Medium
32 | File | `/ECT_Provider/` | High
33 | File | `/Employer/EditProfile.php` | High
34 | File | `/endpoint/delete-todo.php` | High
35 | File | `/EXCU_SHELL` | Medium
36 | File | `/fax/fax_send.php` | High
37 | File | `/finance/help/en/frameset.htm` | High
38 | File | `/forum/away.php` | High
39 | File | `/general/attendance/manage/ask_duty/delete.php` | High
40 | File | `/goform/` | Medium
41 | File | `/goform/SetStaticRouteCfg` | High
42 | File | `/group1/uploa` | High
43 | File | `/h/autoSaveDraft` | High
44 | File | `/home.php` | Medium
45 | File | `/Home/Index` | Medium
46 | File | `/hrm/leaverequest.php` | High
47 | File | `/inc/modules_install.php` | High
48 | File | `/index.php` | Medium
49 | File | `/itbox_pi/vpn_quickset_service.php?a=set_vpn` | High
50 | ... | ... | ...

There are 430 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://asec.ahnlab.com/en/54647/
* https://bazaar.abuse.ch/sample/02acdc11b6e22b8fa19ebafb10190ac28a7f0e5ee569a058c2df825337e4447a/
* https://bazaar.abuse.ch/sample/1b40a289556934d67a35d6422f66b3b062e616d0b7e00d23f543d25183ebe8d6/
* https://bazaar.abuse.ch/sample/2f1854f309c913068700c0c3efec3a84ea48e62393df38bab9c8233053e2b19b/
* https://bazaar.abuse.ch/sample/6c6888a75d6a62dc7414dd22d0b6a70456a108a14889b8406f7aeb8b61b34633/
* https://bazaar.abuse.ch/sample/7c4e9e95a27147623ec5b3be81c76c131a0871d75f50b148b93e88ef6ee0b468/
* https://bazaar.abuse.ch/sample/8a04585157033b86cb2c104f441d236bc3255b46127355f8342b75ab40eb3e35/
* https://bazaar.abuse.ch/sample/15c7fe5a56b80a43544c3227a8589045bf67d0a65c2ebba2506102250f6da963/
* https://bazaar.abuse.ch/sample/15e7942ebf88a51346d3a5975bb1c2d87996799e6255db9e92aed798d279b36b/
* https://bazaar.abuse.ch/sample/85cbeced4d53526b94815b894e09199f8f5f7d4c889643ad1cb23aeaf2f7619f/
* https://bazaar.abuse.ch/sample/601a9a769138a444dd359058dee0b4d797f8aef42d7c22dfb469bbaf55695ed6/
* https://bazaar.abuse.ch/sample/800c90c7b4eaf5562a0bcd6b640fd0a29a34aef48522fe579583d3866ca038f4/
* https://bazaar.abuse.ch/sample/938cd2020a8551d57ed522c81a4fca9df0cb22db221381ea0e19f0149ee8100e/
* https://bazaar.abuse.ch/sample/1917aa3e5bfd1c6a958ca61875c4f58edcbf68d5b954707523b3088fbb096363/
* https://bazaar.abuse.ch/sample/76420e2f4edda9c5b643b1d2d1ff895b02373a746a8d004e87f71e2b15122669/
* https://bazaar.abuse.ch/sample/355807fc92869c656200c3c8a7f41cd204c92a5abf3437324e4a0a6a8a68ed78/
* https://bazaar.abuse.ch/sample/656639f032e8e10efc8c581cf03bd2a75c89cdb71cf25e857f2bca1d8b983c42/
* https://bazaar.abuse.ch/sample/aaa03b1810498597909ddb7756779921fd187df1baea91faafeee0e00ffdaccc/
* https://bazaar.abuse.ch/sample/b30702b6432c4a5ca65ebc060b72f28ba71f60b20bb38b6f858af5e6aa61896f/
* https://bazaar.abuse.ch/sample/d335c83c0dd5bc9a078e796016f9a9f845ff89ee434c63c7a2e7b360e8be3e95/
* https://bazaar.abuse.ch/sample/db31b258371a7e643cb35cb84798090a00c6c02cd9879f02187cdbba60be1ce3/
* https://bazaar.abuse.ch/sample/e21ba3f25330cf22713367d510a50510ec807e73240f4f9ad3e37987754de534/
* https://bazaar.abuse.ch/sample/fe3c5c4f94b90619f7385606dfb86b6211b030efe19b49c12ead507c8156507a/
* https://blog.netlab.360.com/threat-alert-log4j-vulnerability-has-been-adopted-by-two-linux-botnets/
* https://exchange.xforce.ibmcloud.com/threats/guid:94e798f76e8cfd2feab41ea2d028135a
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/host/202.110.187.205/
* https://www.virustotal.com/gui/file/6c0dbbd757cac412e4f80a761d0084c4dcee7d0ec46d1a0bf769474f8ed153b3

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/?kb.cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2024](https://vuldb.com/?kb.changelog) by [vuldb.com](https://vuldb.com/?kb.about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/?kb.faq), read the [documentation](https://vuldb.com/?kb) or [contact us](https://vuldb.com/?contact)!
