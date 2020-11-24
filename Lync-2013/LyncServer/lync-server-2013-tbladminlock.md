---
title: Lync Server 2013：tblAdminLock
description: Lync Server 2013： tblAdminLock。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: tblAdminLock
ms:assetid: 785a43c0-6892-474c-821c-fa9cdbeb99d8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg558665(v=OCS.15)
ms:contentKeyID: 48184560
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: c3313826b2c0d578c515fb25f83e713b8978ae63
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/24/2020
ms.locfileid: "49392009"
---
# <a name="tbladminlock-in-lync-server-2013"></a><span data-ttu-id="b1949-103">Lync Server 2013 中的 tblAdminLock</span><span class="sxs-lookup"><span data-stu-id="b1949-103">tblAdminLock in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="b1949-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="b1949-104">

<span> </span></span></span>

<span data-ttu-id="b1949-105">_**主题上次修改时间：** 2012-06-25_</span><span class="sxs-lookup"><span data-stu-id="b1949-105">_**Topic Last Modified:** 2012-06-25_</span></span>

<span data-ttu-id="b1949-106">tblAdminLock 包含运行某些管理员命令所需的管理员锁。</span><span class="sxs-lookup"><span data-stu-id="b1949-106">tblAdminLock contains the administrator lock that is needed to run some administrator commands.</span></span>

### <a name="columns"></a><span data-ttu-id="b1949-107">多</span><span class="sxs-lookup"><span data-stu-id="b1949-107">Columns</span></span>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="b1949-108">列</span><span class="sxs-lookup"><span data-stu-id="b1949-108">Column</span></span></th>
<th><span data-ttu-id="b1949-109">类型</span><span class="sxs-lookup"><span data-stu-id="b1949-109">Type</span></span></th>
<th><span data-ttu-id="b1949-110">说明</span><span class="sxs-lookup"><span data-stu-id="b1949-110">Description</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="b1949-111">lockExpiresTime</span><span class="sxs-lookup"><span data-stu-id="b1949-111">lockExpiresTime</span></span></p></td>
<td><p><span data-ttu-id="b1949-112">datetime，not null</span><span class="sxs-lookup"><span data-stu-id="b1949-112">datetime, not null</span></span></p></td>
<td><p><span data-ttu-id="b1949-113">锁定到期日期和时间。</span><span class="sxs-lookup"><span data-stu-id="b1949-113">Lock expiration date and time.</span></span> <span data-ttu-id="b1949-114">所有者可以定期延长此值。</span><span class="sxs-lookup"><span data-stu-id="b1949-114">The owner can extend this value periodically.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="b1949-115">lockServerID</span><span class="sxs-lookup"><span data-stu-id="b1949-115">lockServerID</span></span></p></td>
<td><p><span data-ttu-id="b1949-116">int，not null</span><span class="sxs-lookup"><span data-stu-id="b1949-116">int, not null</span></span></p></td>
<td><p><span data-ttu-id="b1949-117">拥有锁定的服务器的 ID。</span><span class="sxs-lookup"><span data-stu-id="b1949-117">ID of the server that owns the lock.</span></span></p></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="b1949-118">lockActorID</span><span class="sxs-lookup"><span data-stu-id="b1949-118">lockActorID</span></span></p></td>
<td><p><span data-ttu-id="b1949-119">int，not null</span><span class="sxs-lookup"><span data-stu-id="b1949-119">int, not null</span></span></p></td>
<td><p><span data-ttu-id="b1949-120">拥有锁定的主体的 ID。</span><span class="sxs-lookup"><span data-stu-id="b1949-120">ID of the principal that owns the lock.</span></span></p></td>
</tr>
</tbody>
</table><span data-ttu-id="b1949-121">


</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="b1949-121">


</div>

<span> </span>

</div>

</div>

</span></span></div>

