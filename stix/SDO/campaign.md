# Campaign

Type Name: campaign

引用：https://docs.oasis-open.org/cti/stix/v2.1/cs01/stix-v2.1-cs01.html#_pcpvfz4ik6d6

"运动"是一组对抗行为，描述了一段时间内针对特定目标发生的一组恶意活动或攻击。活动通常具有明确定义的目标，并且可能是入侵集的一部分。

运动往往归因于入侵集和威胁行为者。威胁行为者可以重复使用入侵集中已知的基础设施，或可能设置用于开展该活动的新基础设施。

活动的特点可能是其目标及其造成的事件、针对人员或资源，以及它们使用的资源（基础设施、情报、恶意软件、工具等）。

例如，2016 年夏季，为了获取有关即将与另一家银行合并的秘密信息，可以使用特定变种的恶意软件和新的 C2 服务器来描述犯罪集团的攻击。

## Properties(属性)

<table class="a0" border="1" cellspacing="0" cellpadding="0" width="607" style="border-collapse:collapse;border:none">
 <tbody><tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Required Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">spec_version</span></b><span lang="EN" style="color:black">,
  </span><b><span lang="EN" style="font-family:Consolas;color:black">id</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">created</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:Consolas;color:black">modified</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Optional Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr style="height:21.0pt">
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt;
  height:21.0pt">
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
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Not Applicable Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">defanged</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">extensions</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Campaign Specific
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="607" colspan="3" valign="top" style="width:455.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">name</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">description</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">aliases</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">first_seen</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">last_seen</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">objective</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Property Name</span></b></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Type</span></b></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Description</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black"> (required)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The value of this
  property <b>MUST</b> be </span><span lang="EN" style="font-family:Consolas;
  color:#073763;background:#CFE2F3">campaign</span><span lang="EN" style="color:black">.</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">name</span></b><span lang="EN" style="color:black"> (required)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">A name used to identify
  the Campaign.</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">description</span></b><span lang="EN" style="color:black"> (optional)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">A description that
  provides more details and context about the Campaign, potentially including
  its purpose and its key characteristics.</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">aliases</span><span lang="EN"> </span></b><span lang="EN">(optional)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list</span><span lang="EN"> of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">string</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">Alternative names used to identify this
  Campaign</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">first_seen</span></b><span lang="EN" style="color:black"> (optional)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">timestamp</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The time that this
  Campaign was first seen.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN" style="color:black">A summary property of
  data from sightings and other data that may or may not be available in STIX.
  If new sightings are received that are earlier than the first seen timestamp,
  the object may be updated to account for the new data.</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">last_seen</span></b><span lang="EN" style="color:black"> (optional)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">timestamp</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The time that this
  Campaign was last seen.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN" style="color:black">A summary property of
  data from sightings and other data that may or may not be available in STIX.
  If new sightings are received that are later than the last seen timestamp, the
  object may be updated to account for the new data.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN" style="color:black">This <b>MUST</b> be
  greater than or equal to the timestamp in the </span><b><span lang="EN" style="font-family:Consolas;color:black">first_seen</span></b><span lang="EN" style="color:black"> property.</span></p>
  </td>
 </tr>
 <tr>
  <td width="185" valign="top" style="width:138.75pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">objective</span></b><span lang="EN" style="color:black"> (optional)</span></p>
  </td>
  <td width="172" valign="top" style="width:129.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="250" valign="top" style="width:187.5pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The Campaign’s primary
  goal, objective, desired outcome, or intended effect — what the Threat Actor
  or Intrusion Set hopes to accomplish with this Campaign.</span></p>
  </td>
 </tr>
</tbody></table>


## Relationships(关系)
这些是运动对象和其他 STIX 对象之间明确定义的关系。第一部分按属性名称及其相应目标列出嵌入关系。表的其余部分通过关系对象识别从此对象类型到其他对象类型的关系。反向关系部分从另一对象类型中说明针对此对象类型的关系。

关系不限于下面列出的关系。使用相关关系类型，或与开放词汇一样，用户定义的名称可以在任何对象之间创建关系。

<table class="af7" border="0" cellspacing="0" cellpadding="0" width="625" style="border-collapse:collapse">
 <tbody><tr>
  <td width="625" colspan="4" valign="top" style="width:468.5pt;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Embedded
  Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="230" colspan="2" valign="top" style="width:172.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">created_by_ref</span></b></p>
  </td>
  <td width="395" colspan="2" valign="top" style="width:296.25pt;border-top:none;
  border-left:none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identifier</span><span lang="EN"> (of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">identity</span><span lang="EN">)</span></p>
  </td>
 </tr>
 <tr>
  <td width="230" colspan="2" valign="top" style="width:172.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">object_marking_refs</span></b></p>
  </td>
  <td width="395" colspan="2" valign="top" style="width:296.25pt;border-top:none;
  border-left:none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">list</span><span lang="EN"> of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">identifier</span><span lang="EN"> (of type </span><span lang="EN" style="font-family:Consolas;
  color:#C7254E;background:#F9F2F4">marking-definition</span><span lang="EN">)</span></p>
  </td>
 </tr>
 <tr>
  <td width="625" colspan="4" valign="top" style="width:468.5pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Common Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="625" colspan="4" valign="top" style="width:468.5pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">duplicate-of</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">derived-from</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">related-to</span></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Source</span></b></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Relationship Type</span></b></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Target</span></b></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Description</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">attributed-to</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">intrusion-set</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">threat-actor</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that the
  Intrusion Set or Threat Actor that is involved in carrying out the Campaign.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, an </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">attributed-to</span><span lang="EN"> Relationship from the Glass Gazelle Campaign to the Urban Fowl
  Threat Actor means that the actor carried out or was involved in some of the
  activity described by the Campaign.</span></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">compromises</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">infrastructure</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that the
  Campaign compromises the related Infrastructure.</span></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">originates-from</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">location</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that the
  Campaign originates from the related Location.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, an </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">originates-from</span><span lang="EN"> relationship from the Glass Gazelle Campaign to a Location
  representing North America means that Glass Gazelle appears to originate from
  or is located in North America.</span></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">targets</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identity</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">location</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">vulnerability</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that the
  Campaign uses exploits of the related Vulnerability or targets the type of
  victims described by the related Identity or Location.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, a </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">targets</span><span lang="EN"> Relationship from the Glass Gazelle Campaign to a Vulnerability in a
  blogging platform indicates that attacks performed as part of Glass Gazelle
  often exploit that Vulnerability.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">Similarly, a </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">targets</span><span lang="EN"> Relationship from the Glass Gazelle Campaign to an Identity
  describing the energy sector in the United States means that the Campaign
  typically carries out attacks against targets in that sector.</span></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">uses</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">attack-pattern</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">infrastructure</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">malware</span><span lang="EN">, </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4">tool</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This Relationship describes that attacks
  carried out as part of the Campaign typically use the related Attack Pattern,
  Infrastructure, Malware, or Tool.</span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">For example, a </span><span lang="EN" style="font-family:Consolas;color:#073763;background:#CFE2F3">uses</span><span lang="EN"> Relationship from the Glass Gazelle Campaign to the xInject Malware
  indicates that xInject is often used during attacks attributed to that
  Campaign. </span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">A campaign, threat actor, intrusion set,
  malware, or tool takes infrastructure and compromises and/or uses it for
  their own.</span></p>
  </td>
 </tr>
 <tr>
  <td width="625" colspan="4" valign="top" style="width:468.5pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:black">Reverse Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="103" valign="top" style="width:77.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">indicator</span></p>
  </td>
  <td width="127" valign="top" style="width:95.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#073763;
  background:#CFE2F3">indicates</span></p>
  </td>
  <td width="131" valign="top" style="width:98.25pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">campaign</span></p>
  </td>
  <td width="264" valign="top" style="width:2.75in;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">See forward relationship for definition.</span></p>
  </td>
 </tr>
</tbody></table>


### 示例

```json
{
  "type": "campaign",
  "spec_version": "2.1",
  "id": "campaign--8e2e2d2b-17d4-4cbf-938f-98ee46b3cd3f",
  "created_by_ref": "identity--f431f809-377b-45e0-aa1c-6a4751cae5ff",
  "created": "2016-04-06T20:03:00.000Z",
  "modified": "2016-04-06T20:03:00.000Z",
  "name": "Green Group Attacks Against Finance",
  "description": "Campaign by Green Group against a series of targets in the financial services sector."
}
```