---
UID: NF:wdfpdo.WdfPdoClearEjectionRelationsDevices
title: WdfPdoClearEjectionRelationsDevices function (wdfpdo.h)
description: The WdfPdoClearEjectionRelationsDevices method removes all devices from the list of devices that must be ejected when a specified device is ejected.
old-location: wdf\wdfpdoclearejectionrelationsdevices.htm
tech.root: wdf
ms.assetid: 09154884-130d-47aa-be00-08a3a4da6f22
ms.date: 02/26/2018
ms.keywords: DFDeviceObjectFdoPdoRef_ddbc7fa5-d0c0-4074-901e-bc7a8ea50fa4.xml, WdfPdoClearEjectionRelationsDevices, WdfPdoClearEjectionRelationsDevices method, kmdf.wdfpdoclearejectionrelationsdevices, wdf.wdfpdoclearejectionrelationsdevices, wdfpdo/WdfPdoClearEjectionRelationsDevices
ms.topic: function
f1_keywords:
 - "wdfpdo/WdfPdoClearEjectionRelationsDevices"
req.header: wdfpdo.h
req.include-header: Wdf.h
req.target-type: Universal
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 1.0
req.umdf-ver: 
req.ddi-compliance: DriverCreate, KmdfIrql, KmdfIrql2
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Wdf01000.sys (see Framework Library Versioning.)
req.dll: 
req.irql: <= DISPATCH_LEVEL
topic_type:
- APIRef
- kbSyntax
api_type:
- LibDef
api_location:
- Wdf01000.sys
- Wdf01000.sys.dll
api_name:
- WdfPdoClearEjectionRelationsDevices
product:
- Windows
targetos: Windows
req.typenames: 
---

# WdfPdoClearEjectionRelationsDevices function


## -description


<p class="CCE_Message">[Applies to KMDF only]</p>

The <b>WdfPdoClearEjectionRelationsDevices</b> method removes all devices from the list of devices that must be ejected when a specified device is ejected. 


## -parameters




### -param Device [in]

A handle to a framework device object.


## -returns



None.

A system bug check occurs if the driver supplies an invalid object handle.




## -remarks



For more information, see <a href="https://docs.microsoft.com/windows-hardware/drivers/wdf/supporting-ejectable-devices">Supporting Ejectable Devices</a>.


#### Examples

The following code example clears the specified device's list of ejection relations.

<div class="code"><span codelanguage=""><table>
<tr>
<th></th>
</tr>
<tr>
<td>
<pre>WdfPdoClearEjectionRelationsDevices(device); </pre>
</td>
</tr>
</table></span></div>



## -see-also




<a href="https://docs.microsoft.com/windows-hardware/drivers/ddi/content/wdfpdo/nf-wdfpdo-wdfpdoaddejectionrelationsphysicaldevice">WdfPdoAddEjectionRelationsPhysicalDevice</a>



<a href="https://docs.microsoft.com/windows-hardware/drivers/ddi/content/wdfpdo/nf-wdfpdo-wdfpdoremoveejectionrelationsphysicaldevice">WdfPdoRemoveEjectionRelationsPhysicalDevice</a>
 

 

