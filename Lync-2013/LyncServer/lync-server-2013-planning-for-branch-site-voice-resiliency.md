---
title: Lync Server 2013：规划分支站点语音恢复能力
description: Lync Server 2013：规划分支站点语音复原。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Planning for branch-site voice resiliency
ms:assetid: 67713f57-3ded-4127-ac37-57d8099bf384
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg398477(v=OCS.15)
ms:contentKeyID: 48184351
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 9ce7eb25e1d3078cd2114fc26428f4c8c2ff6508
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/24/2020
ms.locfileid: "49392281"
---
# <a name="planning-for-branch-site-voice-resiliency-in-lync-server-2013"></a><span data-ttu-id="dd2d2-103">在 Lync Server 2013 中规划分支站点语音恢复能力</span><span class="sxs-lookup"><span data-stu-id="dd2d2-103">Planning for branch-site voice resiliency in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="dd2d2-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="dd2d2-104">

<span> </span></span></span>

<span data-ttu-id="dd2d2-105">_**主题上次修改时间：** 2012-09-21_</span><span class="sxs-lookup"><span data-stu-id="dd2d2-105">_**Topic Last Modified:** 2012-09-21_</span></span>

<span data-ttu-id="dd2d2-106">如果你想要提供分支站点弹性（即高可用性企业语音服务），你有三种方法可用于执行此操作：</span><span class="sxs-lookup"><span data-stu-id="dd2d2-106">If you want to provide branch-site resiliency, that is, high-availability Enterprise Voice service, you have three options for doing so:</span></span>

  - <span data-ttu-id="dd2d2-107">Survivable Branch Appliance</span><span class="sxs-lookup"><span data-stu-id="dd2d2-107">Survivable Branch Appliance</span></span>

  - <span data-ttu-id="dd2d2-108">Survivable Branch Server</span><span class="sxs-lookup"><span data-stu-id="dd2d2-108">Survivable Branch Server</span></span>

  - <span data-ttu-id="dd2d2-109">分支站点上的完整 Lync 服务器部署</span><span class="sxs-lookup"><span data-stu-id="dd2d2-109">A full Lync Server deployment at the branch site</span></span>

<span data-ttu-id="dd2d2-p101">本指南将帮助您评估最适合组织的恢复能力解决方案，并基于您的恢复能力解决方案选择要使用的 PSTN 连接解决方案。还将通过介绍先决条件和其他规划注意事项来帮助您准备部署所选择的解决方案。</span><span class="sxs-lookup"><span data-stu-id="dd2d2-p101">This guide will help you evaluate which resiliency solution is best for your organization and, based on your resiliency solution, which PSTN-connectivity solution to use. It will also help you prepare to deploy the solution that you choose by describing prerequisites and other planning considerations.</span></span>

<div>

## <a name="in-this-section"></a><span data-ttu-id="dd2d2-112">本节内容</span><span class="sxs-lookup"><span data-stu-id="dd2d2-112">In This Section</span></span>

  - [<span data-ttu-id="dd2d2-113">Lync Server 2013 中的分支站点恢复能力功能</span><span class="sxs-lookup"><span data-stu-id="dd2d2-113">Branch-site resiliency features in Lync Server 2013</span></span>](lync-server-2013-branch-site-resiliency-features.md)

  - [<span data-ttu-id="dd2d2-114">Lync Server 2013 中的分支站点恢复能力解决方案</span><span class="sxs-lookup"><span data-stu-id="dd2d2-114">Branch-site resiliency solutions in Lync Server 2013</span></span>](lync-server-2013-branch-site-resiliency-solutions.md)

  - [<span data-ttu-id="dd2d2-115">Lync Server 2013 的分支站点恢复能力要求</span><span class="sxs-lookup"><span data-stu-id="dd2d2-115">Branch-site resiliency requirements for Lync Server 2013</span></span>](lync-server-2013-branch-site-resiliency-requirements.md)

<span data-ttu-id="dd2d2-116"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="dd2d2-116"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

