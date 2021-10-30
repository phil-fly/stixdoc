# STIX Domain Objects
    每个SDO对应CTI中的唯一概念。使用SDO，SCO和SRO作为基本模块，用户可以方便的创建和共享CTI。

## 每个SDO包含：

- Property：通用属性、SDO转专用属性
- Relationship：embedded relationships、common relationships

## 一些相似的SDO可以被归为一个大类，如：

- Attack Pattern, Malware, and Tool可以被归为TTP，因为它们描述了攻击行为和资源
- Campaign, Intrusion Set, and Threat Actor 可以被描述为“攻击者发动攻击的原因，以及如何组织（why and how）”