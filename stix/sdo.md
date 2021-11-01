# STIX Domain Objects
引用:https://docs.oasis-open.org/cti/stix/v2.1/cs01/stix-v2.1-cs01.html#_nrhq5e9nylke

此规范定义了 STIX 域对象 （SDOs） 集，每个对象都对应于 CTI 中通常表示的独特概念。个人可以使用 SDOs、STIX 可观测对象 （SCO） 和 STIX 关系对象 （SROs） 作为构建基石，创建并共享广泛而全面的网络威胁情报。

下面定义的每个 SDO 都提供了属性信息、关系信息和示例。属性信息包括常见属性以及每个 SDO 特定的属性。关系信息包括嵌入式关系（例如，created_by_ref）、共同关系（例如相关关系）和 SDO 特定关系。前瞻性关系（即从SDO 到其他 SDO 或 SDO 的关系）已完全定义，而反向关系（即来自其他 SDO 或 SDO 的 SDO 关系）则被复制以方便起见。

有些 SDO 是相似的，可以归为一类。攻击模式、恶意软件和工具都可以被视为战术、技术和程序 （TTP） 类型：它们描述攻击者用于实施攻击的行为和资源。同样，战役、入侵集和威胁行为者都描述了关于对手为什么实施攻击以及他们如何组织自己的信息。



威胁情报主要的分类对象，包含了一些威胁的behaviors和construct，共有18种类型：
## [Attack Pattern](SDO/attack-pattern.md)
Type Name: attack-pattern

TTP类型之一，它描述了攻击者试图破坏目标的方式，对应于TTP中的战术。可用于帮助对攻击进行分类，将特定的攻击概括为其遵循的模式，并提供有关如何进行攻击的详细信息。如spear fishing就是一种攻击模式，而更具体的描述，如被特定攻击者实施的spear fishing也是一种攻击模式。
## Campaign：

表示某次具体的攻击活动。A Campaign is a grouping of adversarial behaviors that describes a set of malicious activities or attacks (sometimes called waves) that occur over a period of time against a specific set of targets. Campaigns usually have well defined objectives and may be part of an Intrusion Set.
## Course of Action：
用于预防攻击或对攻击做出响应的行为，它回包含技术，自动化响应（补丁、重新配置防火墙），或高级别的动作（如员工培训或者策略制定）。
## Grouping：
Grouping表示分析和调查过程中产生的数据（待确认的线索数据）；还可以用来声明其引用的STIX对象与正在进行的分析过程有关，如当一个安全分析人员正在跟其它人合作，分析一系列Campaigns和Indicators的时，Gouping会引用一系列其它SDO、SCO和SRO（Grouping就表示协作分析吧）.
除了embedded relationship和common relationship之外，没有明确定义Grouping对象和其它STIX对象之间的关系。
## Identity：
Identity可以代表特定的个人、组织或团伙；也可以代表一类个人、组织、系统或团伙。Identity SDO可以捕获基本标识信息，联系信息以及Identity所属的部门。 Identity在STIX中用于表示攻击目标，信息源，对象创建者和威胁参与者身份。
## Indicator：
Indicator表示可用于检测可疑行为的模式。如用STIX Patterning Language来描述恶意域名集合（第九章）。
## Infrastructure：(基础设施)
TTP的类型之一，用于描述系统、软件服务等其它的物理或虚拟资源；如攻击者使用的C2服务器，防御者使用的设备和服务器，以及作为被攻击目标的数据库服务器等；
## Intrusion Set：
Intrusion set是由某个组织所使用的恶意行为和资源的集合。一个Intrusion Set可能会捕获多个Campaigns，他们共同指向一个Threat Actor。新捕获的活动可以被归因于某个Intrusion Set，而Actors可以在Intrusion之间跳转，甚至从属于多个Intrusion Set。Intrusion Set和Campaigns对比：Where a Campaign is a set of attacks over a period of time against a specific set of targets to achieve some objective, an Intrusion Set is the entire attack package and may be used over a very long period of time in multiple Campaigns to achieve potentially multiple purposes.
由Intrusion Set找出Threat Actors，nation state或者nation state中的某个APT组织，是一个溯源的过程。
## Location：
表示具体地点，可以与Identity或Intrusion Set相关联，表示其位置；与Malware或Attack Pattern相关联，表示其目标。
## Malware
TTP类型之一，表示恶意软件或代码。
## Malware Analysis
捕获了在恶意软件实例或恶意软件家族分析过程中，动态分析或静态分析的结果。
## Note
其他对象中不存在的额外信息；例如，分析人员可以在一个Campaign对象中添加注释，以表明他在黑客论坛上看到了与该Campaign相关的帖子。同样，Note对象也没有定义与其他STIX Object之间的关系。
## Observed Data
与网络安全相关的可观察对象（raw information）集合，其引用对象为SCO，包含从analyst reports, sandboxes, and network and host-based detection tools等收集的信息。

必须包含objects或者object_refs属性，表示对SCO的引用

Observed Data只有反向关系。此外，还会被Sighting SRO所指向：Sightings represent a relationship between some intelligence entity that was seen (e.g., an Indicator or Malware instance), where it was seen, and what evidence was actually seen. The evidence (or raw data) in that relationship is captured as Observed Data（Sighting中的证据就是Observed Data）。
## Opinion
Opinion是对STIX对象中信息正确性的评估。
## Report
威胁情报报告。
## Threat Actor
攻击的个人、团体或组织；其与Intrusion Set不同，Threat Actor会同时支持或附属于不同的Intrusion Set、团体或组织。
## Tool
Tool是威胁参与者可以用来执行攻击的合法软件。与Malware不同，Tool一般是合法软件，如Namp、VNC。
## Vulnerability
漏洞。用于连接相关漏洞的外部描述（external_references），或还没有相关描述的0-day漏洞。