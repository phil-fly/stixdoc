# Attack Pattern

攻击模式是一种 TTP，它描述了对手试图破坏目标的方式。攻击模式用于帮助对攻击进行分类，将特定攻击概括为其遵循的模式，并提供有关攻击执行方式的详细信息。攻击模式的一个例子是"鱼叉网络钓鱼"：一种常见的攻击类型，攻击者向一方发送精心制作的电子邮件，目的是让他们点击链接或打开附件以传递恶意软件。攻击模式也可以更具体：由特定威胁行为人练习的鱼叉式网络钓鱼（例如，他们通常可能说目标赢得了比赛）也可以是攻击模式。

 

攻击模式 SDO 包含该模式的文本描述，以及对外部定义的攻击分类的引用，如 CAPEC[CAPEC]。


## Properties(属性)
<table class="af5" border="0" cellspacing="0" cellpadding="0" width="613" style="border-collapse:collapse">
 <tbody><tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Required Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">spec_version</span></b><span lang="EN" style="color:black">,
  </span><b><span lang="EN" style="font-family:Consolas;color:black">id</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">created</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:Consolas;color:black">modified</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Optional Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">created_by_ref</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">revoked</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:Consolas;color:black">labels</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">confidence</span></b><span lang="EN" style="color:black">,
  </span><b><span lang="EN" style="font-family:Consolas;color:black">lang</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">external_references</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:Consolas;
  color:black">object_marking_refs</span></b><span lang="EN" style="color:black">,
  </span><b><span lang="EN" style="font-family:Consolas;color:black">granular_markings</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Not Applicable Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">defanged</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">extensions</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Attack Pattern
  Specific Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="613" colspan="3" valign="top" style="width:459.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">name</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">description</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">aliases</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">kill_chain_phases</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top" style="width:129.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white;background:#073763">Property
  Name</span></b></p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white;background:#073763">Type</span></b></p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white;background:#073763">Description</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top" style="width:129.75pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black;background:#D9D9D9"> (required)</span></p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black;background:#D9D9D9">The
  value of this property <b>MUST</b> be </span><span lang="EN" style="font-family:
  Consolas;color:#073763;background:#CFE2F3">attack-pattern</span><span lang="EN" style="color:black">.</span></p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top" style="width:129.75pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">external_references
  </span></b></p>
  <p class="MsoNormal"><span lang="EN" style="color:black">(optional)</span></p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list</span><span lang="EN" style="font-family:Consolas;
  color:black"> </span><span lang="EN" style="color:black">of type</span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">
  external-reference</span></p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">A list of external
  references which refer to non-STIX information. This property <b>MAY </b>be
  used to provide one or more Attack Pattern identifiers, such as a CAPEC ID.
  When specifying a CAPEC ID, the </span><b><span lang="EN" style="font-family:
  Consolas;color:black">source_name</span></b><span lang="EN" style="color:black">
  property of the external reference <b>MUST </b>be set to </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">capec</span><span lang="EN" style="color:black"> and the </span><b><span lang="EN" style="font-family:Consolas;color:black">external_id</span></b><span lang="EN" style="color:black"> property <b>MUST</b> be formatted as </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">CAPEC-[id]</span><span lang="EN" style="color:black">.</span></p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top">
  <p class="MsoNormal"><b><span lang="EN">name</span></b>(required)</p>
  </td>
  <td width="167" valign="top">
  <p class="MsoNormal">string</p>
  </td>
  <td width="273" valign="top">
  <p class="MsoNormal">A name used to identify
  the Attack Pattern.</p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top">
  <p class="MsoNormal"><b>description</b>(optional)</p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal">A description that
  provides more details and context about the Attack Pattern, potentially
  including its purpose and its key characteristics.</p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top">
  <p class="MsoNormal"><b><span lang="EN">aliases</span><span lang="EN"> </span></b>(optional)</p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list of type string</p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">Alternative names used to identify this
  Attack Pattern.</span></p>
  </td>
 </tr>
 <tr>
  <td width="173" valign="top" style="width:129.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">kill_chain_phases</span></b><span lang="EN" style="color:black;background:white"> (optional)</span></p>
  </td>
  <td width="167" valign="top" style="width:125.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list</span><span lang="EN" style="color:#C7254E;background:
  #F9F2F4"> </span><span lang="EN" style="color:black">of type</span><span lang="EN" style="color:#C7254E;background:#F9F2F4"> </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">kill-chain-phase</span></p>
  </td>
  <td width="273" valign="top" style="width:204.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The list of Kill Chain
  Phases for which this Attack Pattern is used.</span></p>
  </td>
 </tr>
</tbody>
</table>


## Relationships(关系)

这些是攻击模式对象与其他 STIX 对象之间明确定义的关系。第一部分按属性名称及其相应目标列出嵌入关系。表的其余部分通过关系对象识别从此对象类型到其他对象类型的关系。反向关系部分从另一对象类型中说明针对此对象类型的关系。为了方便起见，它们被包括在这里。
关系不限于下面列出的关系。使用相关关系类型，或与开放词汇一样，用户定义的名称可以在任何对象之间创建关系。

<table class="af6" border="0" cellspacing="0" cellpadding="0" width="609" style="border-collapse:collapse">
 <tbody><tr>
  <td width="609" colspan="4" valign="top" style="width:456.75pt;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Embedded
  Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="234" colspan="2" valign="top" style="width:175.5pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">created_by_ref</span></b></p>
  </td>
  <td width="375" colspan="2" valign="top" style="width:281.25pt;border-top:none;
  border-left:none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identifier</span><span lang="EN"> (of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">identity</span><span lang="EN">)</span></p>
  </td>
 </tr>
 <tr>
  <td width="234" colspan="2" valign="top" style="width:175.5pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">object_marking_refs</span></b></p>
  </td>
  <td width="375" colspan="2" valign="top" style="width:281.25pt;border-top:none;
  border-left:none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list</span><span lang="EN"> of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">identifier</span><span lang="EN"> (of type </span><span lang="EN" style="font-family:Consolas;
  color:#C7254E;background:#F9F2F4">marking-definition</span><span lang="EN">)</span></p>
  </td>
 </tr>
 <tr>
  <td width="609" colspan="4" valign="top" style="width:456.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Common Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="609" colspan="4" valign="top" style="width:456.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">duplicate-of</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">derived-from</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">related-to</span></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Source</span></b></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Relationship Type</span></b></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Target </span></b></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Description</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">delivers</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">malware</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that this Attack
  Pattern is used to deliver this malware instance (or family).</span></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">targets</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identity</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">location</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">vulnerability</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that this Attack
  Pattern typically targets the type of victim, location, or vulnerability
  represented by the related Identity, Location, or Vulnerability object.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, a </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">targets</span><span lang="EN"> Relationship linking an Attack Pattern for SQL injection to an
  Identity object representing domain administrators means that the form of SQL
  injection characterized by the Attack Pattern targets domain administrators
  in order to achieve its objectives. </span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">Another example is a Relationship linking an
  Attack Pattern for SQL injection to a Vulnerability in blogging software
  means that the particular SQL injection attack exploits that vulnerability.</span></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">uses</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">malware</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">tool</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that the related
  Malware or Tool is used to perform the behavior identified in the Attack
  Pattern.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, a </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">uses</span><span lang="EN"> Relationship linking an Attack Pattern for a distributed denial of
  service (DDoS) to a Tool for Low Orbit Ion Cannon (LOIC) indicates that the
  tool can be used to perform those DDoS attacks.</span></p>
  </td>
 </tr>
 <tr>
  <td width="609" colspan="4" valign="top" style="width:456.75pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:black">Reverse Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">indicator</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">indicates</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">See forward relationship for definition.</span></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">course-of-action</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">mitigates</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">See forward relationship for definition.</span></p>
  </td>
 </tr>
 <tr>
  <td width="137" valign="top" style="width:102.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">intrusion-set</span><span lang="EN">,</span></p>
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">malware</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">threat-actor</span></p>
  </td>
  <td width="97" valign="top" style="width:72.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">uses</span></p>
  </td>
  <td width="120" valign="top" style="width:1.25in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span></p>
  </td>
  <td width="255" valign="top" style="width:191.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">See forward relationship for definition.</span></p>
  </td>
 </tr>
</tbody></table>


## 示例

鱼叉式网络钓鱼的通用攻击模式，引用 CAPEC

```json
{
  "type": "attack-pattern",
  "spec_version": "2.1",
  "id": "attack-pattern--0c7b5b88-8ff7-4a4d-aa9d-feb398cd0061",
  "created": "2016-05-12T08:17:27.000Z",
  "modified": "2016-05-12T08:17:27.000Z",
  "name": "Spear Phishing",
  "description": "...",
  "external_references": [
    {
      "source_name": "capec",
      "external_id": "CAPEC-163"
    }
  ]
}
```

特定形式的鱼叉式网络钓鱼的特定攻击模式，引用 CAPEC

```json
[
  {
    "type": "attack-pattern",
    "spec_version": "2.1",
    "id": "attack-pattern--7e33a43e-e34b-40ec-89da-36c9bb2cacd5",
    "created": "2016-05-12T08:17:27.000Z",
    "modified": "2016-05-12T08:17:27.000Z",
    "name": "Spear Phishing as Practiced by Adversary X",
    "description": "A particular form of spear phishing where the attacker claims that the target had won a contest, including personal details, to get them to click on a link.",
    "external_references": [
      {
        "source_name": "capec",
        "external_id": "CAPEC-163"
      }
    ]
  },
  {
    "type": "relationship",
    "spec_version": "2.1",
    "id": "relationship--57b56a43-b8b0-4cba-9deb-34e3e1faed9e",
    "created": "2016-05-12T08:17:27.000Z",
    "modified": "2016-05-12T08:17:27.000Z",
    "relationship_type": "uses",
    "source_ref": "intrusion-set--0c7e22ad-b099-4dc3-b0df-2ea3f49ae2e6",
    "target_ref": "attack-pattern--7e33a43e-e34b-40ec-89da-36c9bb2cacd5"
  },
  {
    "type": "intrusion-set",
    "spec_version": "2.1",
    "id": "intrusion-set--0c7e22ad-b099-4dc3-b0df-2ea3f49ae2e6",
    "created": "2016-05-12T08:17:27.000Z",
    "modified": "2016-05-12T08:17:27.000Z",
    "name": "Adversary X"
  }
]
```
