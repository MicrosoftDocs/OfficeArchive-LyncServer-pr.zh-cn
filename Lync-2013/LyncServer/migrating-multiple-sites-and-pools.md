---
title: 迁移多个站点和池
description: 迁移多个网站和池。
ms.reviewer: ''
ms.author: serdars
author: serdarsoysal
f1.keywords:
- NOCSH
TOCTitle: Migrating multiple sites and pools
ms:assetid: a6d726d2-564d-4b39-a97c-5656a673292a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ205165(v=OCS.15)
ms:contentKeyID: 48185079
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 7efaa6f038286ff9138e631f23da88bb445e20f1
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49440372"
---
# <a name="migrating-multiple-sites-and-pools"></a><span data-ttu-id="e31fc-103">迁移多个站点和池</span><span class="sxs-lookup"><span data-stu-id="e31fc-103">Migrating multiple sites and pools</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="e31fc-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="e31fc-104">

<span> </span></span></span>

<span data-ttu-id="e31fc-105">_**主题上次修改时间：** 2012-09-17_</span><span class="sxs-lookup"><span data-stu-id="e31fc-105">_**Topic Last Modified:** 2012-09-17_</span></span>

<span data-ttu-id="e31fc-106">Lync Server 2013 支持多站点和多池部署。</span><span class="sxs-lookup"><span data-stu-id="e31fc-106">Lync Server 2013 supports multi-site and multi-pool deployments.</span></span> <span data-ttu-id="e31fc-107">将多个池从 Lync Server 2010 迁移到 Lync Server 2013 的过程需要考虑下列事项：</span><span class="sxs-lookup"><span data-stu-id="e31fc-107">The process of migrating multiple pools from Lync Server 2010 to Lync Server 2013 requires the following considerations:</span></span>

1.  <span data-ttu-id="e31fc-108">部署 Lync Server 2013 试验池后，你需要定义将被移动到 Lync Server 2013 池的试点用户的子集，以及用于验证用户功能的方法。</span><span class="sxs-lookup"><span data-stu-id="e31fc-108">After deploying a Lync Server 2013 pilot pool, you need to define a subset of pilot users that will be moved to the Lync Server 2013 pool, and a methodology for validating the functionality of the users.</span></span> <span data-ttu-id="e31fc-109">例如，将用户移动到试验池后，请验证用户的会议策略是否已迁移到 Lync Server 2013。</span><span class="sxs-lookup"><span data-stu-id="e31fc-109">For example, after moving a user to the pilot pool, verify the user’s conference policy has moved to Lync Server 2013.</span></span>

2.  <span data-ttu-id="e31fc-110">在试验池中部署边缘服务器之后，你需要验证外部用户是否可以与 Lync Server 2013 池通信。</span><span class="sxs-lookup"><span data-stu-id="e31fc-110">After deploying an Edge Server in the pilot pool, you need to validate that external users can communicate with the Lync Server 2013 pool.</span></span>

3.  <span data-ttu-id="e31fc-111">将 Lync Server 2010 Edge 服务器中的联盟路由转换为试点 Lync Server 2013 Edge 服务器之后，你需要验证联盟用户是否可以与 Lync Server 2013 池通信。</span><span class="sxs-lookup"><span data-stu-id="e31fc-111">After transitioning the federated routes from Lync Server 2010 Edge Servers to the pilot Lync Server 2013 Edge Servers, you need to validate that federated users can communicate with the Lync Server 2013 pool.</span></span>

4.  <span data-ttu-id="e31fc-112">移动所有用户和非用户联系人对象后，需要验证 Lync Server 2010 池是否为空。</span><span class="sxs-lookup"><span data-stu-id="e31fc-112">After moving all the users and non-user contact objects, you need to validate that the Lync Server 2010 pool is empty.</span></span>

5.  <span data-ttu-id="e31fc-113">验证 Lync Server 2010 池是否为空后，您可以停用该池。</span><span class="sxs-lookup"><span data-stu-id="e31fc-113">After verifying that the Lync Server 2010 pool is empty, you can then deactivate the pool.</span></span>
    
    <span data-ttu-id="e31fc-114">有关如何停用旧版 Lync Server 2010 池和服务器的详细信息，请参阅 [第8阶段：解除旧版池](phase-8-decommission-legacy-pools.md)。</span><span class="sxs-lookup"><span data-stu-id="e31fc-114">For details about how to deactivate the legacy Lync Server 2010 pool and servers, see [Phase 8: Decommission legacy pools](phase-8-decommission-legacy-pools.md).</span></span>

<span data-ttu-id="e31fc-115"></div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="e31fc-115"></div>

<span> </span>

</div>

</div>

</span></span></div>

