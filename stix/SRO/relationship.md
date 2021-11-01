# Relationship
Type Name: relationship

引用：https://docs.oasis-open.org/cti/stix/v2.1/cs01/stix-v2.1-cs01.html#_e2e1szrqfoan

关系对象用于将两个 SDO 或 SOS 连接在一起，以描述它们之间的关系。如果 SDOs 和 SNO 在图表中被视为"节点"或"节点"，则关系对象 （SROs） 表示"边缘"。

STIX 定义许多关系类型，将 SDO 和 SFO 连接在一起。这些关系包含在每个 SDO 和 SCO 定义下的"关系"表中。应使用规范中定义的关系类型来确保一致性。规范定义关系的一个例子是，指示指示指示活动。该关系类型列在指标 SDO 定义的关系部分。

STIX 还允许从任何 SDO 或 SCO 到本规范中未定义的任何 SDO 或 SCO 的关系。这些关系可能使用相关关系类型，也可能使用用户定义的关系类型。例如，用户可能希望将恶意软件直接链接到工具。他们可以使用相关说明说恶意软件与工具相关，但无法描述如何使用交付方式（他们确定的用户定义名称）来表示更多详细信息。

请注意，STIX 中的某些关系可能看起来像是"捷径"。例如，指示器不会真正检测到活动：它会检测该活动经常使用的活动（攻击模式、恶意软件、基础架构等）。虽然一些分析师可能希望所有源数据，并认为快捷方式具有误导性，但在许多情况下，仅提供要点（快捷方式）并遗漏低级详细信息是有帮助的。在其他情况下，低级别分析可能不知道或无法共享，而高级别分析是。由于这些原因，可能看起来是"捷径"的关系不排除在STIX之外。

## 规范定义关系摘要
所有规范定义关系的 [关系摘要表](relationshipTable.md) ，该关系摘要表提供方便。如果表与与每个 SDO 定义的关系存在差异，则必须将与 SDO 定义的关系视为权威性关系。

## Properties(属性)

<table class="afff6" border="1" cellspacing="0" cellpadding="0" width="624" style="border-collapse:collapse;border:none">
 <tbody><tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Required Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">spec_version</span></b><span lang="EN" style="color:black">,
  </span><b><span lang="EN" style="font-family:Consolas;color:black">id</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">created</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:Consolas;color:black">modified</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Optional Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
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
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Not Applicable Common
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;background:#CFE2F3;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">defanged</span></b><span lang="EN" style="color:black">, </span><b><span lang="EN" style="font-family:
  Consolas;color:black">extensions</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Relationship Specific
  Properties</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="624" colspan="3" valign="top" style="width:6.5in;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">relationship_type</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">description</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">source_ref</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">target_ref</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">start_time</span></b><span lang="EN">, </span><b><span lang="EN" style="font-family:Consolas">stop_time</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Property Name</span></b></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Type</span></b></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Description</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">type</span></b><span lang="EN" style="color:black"> (required)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:#D9D9D9;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The value of this
  property <b>MUST</b> be </span><span lang="EN" style="font-family:Consolas;
  color:#073763;background:#CFE2F3">relationship</span><span lang="EN" style="color:black">.</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">relationship_type</span></b><span lang="EN" style="color:black"> (required)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">The name used to
  identify the type of Relationship. This value <b>SHOULD </b>be an exact value
  listed in the relationships for the source and target SDO, but <b>MAY </b>be
  any string. The value of this property <b>MUST </b>be in ASCII and is limited
  to characters a–z (lowercase ASCII), 0–9, and hyphen (-).</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas;color:black">description</span></b><span lang="EN" style="color:black"> (optional)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">string</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  background:white;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="color:black">A description that
  provides more details and context about the Relationship, potentially
  including its purpose and its key characteristics.</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">source_ref</span></b><span lang="EN"> (required)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identifier</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">The </span><b><span lang="EN" style="font-family:Consolas">id</span></b><span lang="EN"> of the source (from)
  object. The value <b>MUST</b> be an ID reference to an SDO or SCO (i.e., it
  cannot point to an SRO, Bundle, Language Content, or Marking Definition).</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">target_ref</span></b><span lang="EN"> (required)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">identifier</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">The </span><b><span lang="EN" style="font-family:Consolas">id</span></b><span lang="EN"> of the target (to) object.
  The value <b>MUST</b> be an ID reference to an SDO or SCO (i.e., it cannot
  point to an SRO, Bundle, Language Content, or Marking Definition).</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">start_time</span></b><span lang="EN"> (optional)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">timestamp</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">This optional timestamp represents the earliest
  time at which the Relationship between the objects exists. If this property
  is a future timestamp, at the time the </span><b><span lang="EN" style="font-family:Consolas">start_time</span></b><span lang="EN"> property is
  defined, then this represents an estimate by the producer of the intelligence
  of the earliest time at which relationship will be asserted to be true. </span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">If it is not specified, then the earliest
  time at which the relationship between the objects exists is not defined.</span></p>
  </td>
 </tr>
 <tr>
  <td width="195" valign="top" style="width:146.25pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">stop_time</span></b><span lang="EN"> (optional)</span></p>
  </td>
  <td width="153" valign="top" style="width:114.75pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4">timestamp</span></p>
  </td>
  <td width="276" valign="top" style="width:207.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><span lang="EN">The latest time at which the Relationship
  between the objects exists. If this property is a future timestamp, at the
  time the </span><b><span lang="EN" style="font-family:Consolas">stop_time</span></b><span lang="EN"> property is defined, then this represents an estimate by the
  producer of the intelligence of the latest time at which relationship will be
  asserted to be true. </span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">If </span><b><span lang="EN" style="font-family:
  Consolas">start_time</span></b><span lang="EN"> and </span><b><span lang="EN" style="font-family:Consolas">stop_time</span></b><span lang="EN"> are both
  defined, then </span><b><span lang="EN" style="font-family:Consolas">stop_time</span></b><span lang="EN"> <b>MUST</b> be later than the </span><b><span lang="EN" style="font-family:Consolas">start_time</span></b><span lang="EN"> value. </span></p>
  <p class="MsoNormal"><span lang="EN">&nbsp;</span></p>
  <p class="MsoNormal"><span lang="EN">If </span><b><span lang="EN" style="font-family:
  Consolas">stop_time</span></b><span lang="EN"> is not specified, then the
  latest time at which the relationship between the objects exists is either
  not known, not disclosed, or has no defined stop time.</span></p>
  </td>
 </tr>
</tbody></table>

## Relationships(关系)

<table class="afff7" border="0" cellspacing="0" cellpadding="0" width="623" style="border-collapse:collapse">
 <tbody><tr>
  <td width="623" colspan="2" valign="top" style="width:467.0pt;border:solid black 1.0pt;
  background:#073763;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="color:white">Embedded
  Relationships</span></b></p>
  </td>
 </tr>
 <tr>
  <td width="249" valign="top" style="width:187.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">created_by_ref</span></b></p>
  </td>
  <td width="373" valign="top" style="width:280.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><font _mstmutation="1"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4" _mstmutation="1">identifier</span><span lang="EN" _mstmutation="1"> (of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4" _mstmutation="1">identity</span></font><span lang="EN">)</span></p>
  </td>
 </tr>
 <tr>
  <td width="249" valign="top" style="width:187.0pt;border:solid black 1.0pt;
  border-top:none;padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><b><span lang="EN" style="font-family:Consolas">object_marking_refs</span></b></p>
  </td>
  <td width="373" valign="top" style="width:280.0pt;border-top:none;border-left:
  none;border-bottom:solid black 1.0pt;border-right:solid black 1.0pt;
  padding:5.0pt 5.0pt 5.0pt 5.0pt">
  <p class="MsoNormal"><font _mstmutation="1"><span lang="EN" style="font-family:Consolas;color:#C7254E;
  background:#F9F2F4" _mstmutation="1">list</span><span lang="EN" _mstmutation="1"> of type </span><span lang="EN" style="font-family:Consolas;color:#C7254E;background:#F9F2F4" _mstmutation="1">identifier</span><span lang="EN" _mstmutation="1"> (of type </span><span lang="EN" style="font-family:Consolas;
  color:#C7254E;background:#F9F2F4" _mstmutation="1">marking-definition</span></font><span lang="EN">)</span></p>
  </td>
 </tr>
</tbody></table>