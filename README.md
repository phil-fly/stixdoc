# stixdoc

STIX（Structured Threat Information Expression）是一种用于交换网络威胁情报（cyber threat intelligence，CTI）的语言和序列化格式。STIX的应用场景包括：协同威胁分析、自动化威胁情报交换、自动化威胁检测和响应等。
## STIX对网络威胁情报的描述方法如下：
<table>
<tr>
    <td colspan="6" align="center">STIX Objects</td>
    <td rowspan="3">STIX Bundle Objects</td>
</tr>
<tr>
    <td colspan="3" align="center">STIX Core Objects</td>
    <td colspan="3" align="center">STIX Meta Objects</td>
</tr>
<tr>
    <td>STIX Domain Objects（SDO）</td>
    <td>STIX Cyber-observable Objects（SCO）</td>
    <td>STIX Relationship Objects（SRO）</td>
    <td>Extension Definition Objects</td>
    <td>Language Content Objects</td>
    <td>Marking Definition Objects</td>
</tr>
</table>


---

## 资料整理

[威胁画像：对STIX2.0标准12个构件的解读](https://www.secrss.com/articles/13297)

[《信息安全技术网络安全威胁信息格式规范》(GB/T 36643-2018)](http://openstd.samr.gov.cn/bzgk/gb/newGbInfo?hcno=971636AF85AD7158EA50BB428F67C803)

[STIX标准 身份的类别(identity_class)公开字典](stix/identity_class_list.md)
[STIX标准 行业领域(Sectors)公开字典](stix/Sectors_list.md)

[威胁源标签](stix/Threat_Actor _Label.md)

## 笔记




关键字说明：
- SDO：[STIX Domain Objects](stix/sdo.md)
- SCO: [STIX Cyber-observable Objects](stix/sco.md)威胁情报中具体的可观察对象，用于刻画基于主机或基于网络的信息。
- SRO: [STIX Relationship Objects](stix/sro.md)
- TTP: 攻击技术手法

- 可观察对象：可以是动态的事件，也可以是静态的资产，例如HTTP会话、X509证书、文件、系统配置项等。
