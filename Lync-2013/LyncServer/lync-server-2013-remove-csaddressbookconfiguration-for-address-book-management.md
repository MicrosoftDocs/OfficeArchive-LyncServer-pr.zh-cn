---
title: 通讯簿管理 Remove-CsAddressBookConfiguration
description: 为通讯簿管理 Remove-CsAddressBookConfiguration。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Remove-CsAddressBookConfiguration for Address Book management
ms:assetid: 5d173ebe-ec4d-4640-8432-a25071ea9cc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg429705(v=OCS.15)
ms:contentKeyID: 48184258
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: d513c128dfe87c5a6e92b66a6ba4e1dbdfbfb651
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49436438"
---
# <a name="remove-csaddressbookconfiguration-for-address-book-management-in-lync-server-2013"></a><span data-ttu-id="eb39d-103">Lync Server 2013 中的通讯簿管理 Remove-CsAddressBookConfiguration</span><span class="sxs-lookup"><span data-stu-id="eb39d-103">Remove-CsAddressBookConfiguration for Address Book management in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="eb39d-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="eb39d-104">

<span> </span></span></span>

<span data-ttu-id="eb39d-105">_**主题上次修改时间：** 2012-11-01_</span><span class="sxs-lookup"><span data-stu-id="eb39d-105">_**Topic Last Modified:** 2012-11-01_</span></span>

<span data-ttu-id="eb39d-106">哪些人可以运行此 cmdlet：默认情况下，已授权以下组的成员在本地运行 Remove-CsAddressBookConfiguration cmdlet： RTCUniversalServerAdmins。</span><span class="sxs-lookup"><span data-stu-id="eb39d-106">Who can run this cmdlet: By default, members of the following groups are authorized to run the Remove-CsAddressBookConfiguration cmdlet locally: RTCUniversalServerAdmins.</span></span> <span data-ttu-id="eb39d-107">若要返回所有基于角色的访问控制列表 (RBAC) 角色已将此 cmdlet 分配给 (包括你自己创建的任何自定义 RBAC 角色) ，请从 Windows PowerShell 提示符处运行以下命令：</span><span class="sxs-lookup"><span data-stu-id="eb39d-107">To return a list of all the role-based access control (RBAC) roles this cmdlet has been assigned to (including any custom RBAC roles you have created yourself), run the following command from the Windows PowerShell prompt:</span></span>

    Get-CsAdminRole | Where-Object {$_.Cmdlets -match "Remove-CsAddressBookConfiguration"}

<span data-ttu-id="eb39d-108">顾名思义，Remove-CsAddressBookConfiguration 将根据定义的网站标识删除配置。</span><span class="sxs-lookup"><span data-stu-id="eb39d-108">As the name implies, Remove-CsAddressBookConfiguration will remove the configuration based on the defined Site Identity.</span></span>

<span data-ttu-id="eb39d-109">例如：</span><span class="sxs-lookup"><span data-stu-id="eb39d-109">For example:</span></span>

    Remove-CsAddressBookConfiguration -Identity site:Redmond

<div>

## <a name="see-also"></a><span data-ttu-id="eb39d-110">另请参阅</span><span class="sxs-lookup"><span data-stu-id="eb39d-110">See Also</span></span>


<span data-ttu-id="eb39d-111">[Remove-CsAddressBookConfiguration](https://technet.microsoft.com/library/Gg398934(v=OCS.15))</span><span class="sxs-lookup"><span data-stu-id="eb39d-111">[Remove-CsAddressBookConfiguration](https://technet.microsoft.com/library/Gg398934(v=OCS.15))</span></span>  
  

<span data-ttu-id="eb39d-112"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="eb39d-112"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

