---
title: KSCATEGORY_PREFERRED_MIDIOUT_DEVICE
description: KSCATEGORY_PREFERRED_MIDIOUT_DEVICE
ms.assetid: b3d93d21-d4f8-4f00-9947-034790f3f7b1
keywords: ["KSCATEGORY_PREFERRED_MIDIOUT_DEVICE Device and Driver Installation"]
topic_type:
- apiref
api_name:
- KSCATEGORY_PREFERRED_MIDIOUT_DEVICE
api_location:
- Ksmedia.h
api_type:
- HeaderDef
---

# KSCATEGORY_PREFERRED_MIDIOUT_DEVICE


The KSCATEGORY_PREFERRED_MIDIOUT_DEVICE [device interface class](https://msdn.microsoft.com/library/windows/hardware/ff541339) is defined for the [kernel streaming](https://msdn.microsoft.com/library/windows/hardware/ff568277) (KS) functional category for the preferred MIDI output device.

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Attribute</th>
<th align="left">Setting</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><p>Identifier</p></td>
<td align="left"><p>KSCATEGORY_PREFERRED_WAVEOUT_DEVICE</p></td>
</tr>
<tr class="even">
<td align="left"><p>Class GUID</p></td>
<td align="left"><p>{D6C50674-72C1-11D2-9755-0000F8004788}</p></td>
</tr>
</tbody>
</table>

 

Remarks
-------

A user selects the preferred MIDI output device in the Multimedia property pages in the Control Panel.

This functional category is reserved for exclusive use by the system-supplied [WDM Audio Components](https://msdn.microsoft.com/library/windows/hardware/ff538905).

Requirements
------------

<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<tbody>
<tr class="odd">
<td align="left"><p>Version</p></td>
<td align="left"><p>Available in Windows Server 2003, Windows XP, Windows 2000 and later versions of Windows.</p></td>
</tr>
<tr class="even">
<td align="left"><p>Header</p></td>
<td align="left">Ksmedia.h (include Ksmedia.h)</td>
</tr>
</tbody>
</table>

 

 





