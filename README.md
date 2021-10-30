# stixdoc

## 示例

## 资料整理

[威胁画像：对STIX2.0标准12个构件的解读](https://www.secrss.com/articles/13297)

[《信息安全技术网络安全威胁信息格式规范》(GB/T 36643-2018)](http://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=971636AF85AD7158EA50BB428F67C803)

[STIX标准 身份的类别(identity_class)公开字典](stix/identity_class_list.md)
[STIX标准 行业领域(Sectors)公开字典](stix/Sectors_list.md)

[威胁源标签](stix/Threat_Actor _Label.md)

## 笔记


## STIX 12构件
- Attack Pattern (攻击模式)：描述攻击者试图破坏目标的方式
- Campaign (攻击活动): 描述一系列针对特定目标的恶意行为或一段时间内发动的攻击
- Course of Action
- Identity
- Indicator
- Intrusion Set
- Tool
- Malware
- Observed Data
- Report
- Threat Actor
- Vulnerability

关键字说明：
- SDO：[STIX Domain Objects](stix/sdo.md)
- SCO: [STIX Cyber-observable Objects](stix/sco.md)威胁情报中具体的可观察对象，用于刻画基于主机或基于网络的信息。
- SRO: [STIX Relationship Objects](stix/sro.md)
- TTP: 攻击技术手法

- 可观察对象：可以是动态的事件，也可以是静态的资产，例如HTTP会话、X509证书、文件、系统配置项等。