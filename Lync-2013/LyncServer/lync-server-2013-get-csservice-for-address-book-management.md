---
title: Lync Server 2013：用于通讯簿管理的 Get-CsService
description: Lync Server 2013：用于通讯簿管理的 Get-CsService。
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Get-CsService for Address Book management
ms:assetid: 373b717d-5efa-4c36-a899-a23a5bd922b4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg429698(v=OCS.15)
ms:contentKeyID: 48183853
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 5e46173429988d87022c13fab33e3778279dd0e9
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 11/26/2020
ms.locfileid: "49427983"
---
# <a name="get-csservice-for-address-book-management-in-lync-server-2013"></a>Lync Server 2013 中的通讯簿管理 Get-CsService

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody">

<span> </span>

_**主题上次修改时间：** 2012-11-01_

哪些人可以运行此 cmdlet：默认情况下，授权以下组的成员在本地运行 Get-CsService cmdlet： RTCUniversalUserAdmins、RTCUniversalServerAdmins。 若要返回所有基于角色的访问控制列表 (RBAC) 角色已将此 cmdlet 分配给 (包括你自己创建的任何自定义 RBAC 角色) ，请从 Windows PowerShell 提示符处运行以下命令：

    Get-CsAdminRole | Where-Object {$_.Cmdlets -match "Get-CsService"}

Get-CsService 可检索和显示基础结构的已定义 Web 服务的当前配置非常有用。 通过定义池的完全限定的域名 (FQDN) 和参数 Web 服务器，cmdlet 将返回由服务器提供的基于 web 的服务，包括通讯簿处理程序和通讯组列表扩展 Uri。

例如：

    Get-CsService -PoolFqdn "fe01.contoso.net" -WebServer

此 cmdlet 返回以下内容：

标识： Web 站点:pool01

:Dc01：

UserServer： UserServer:pool01

PrimaryHttpPort：80

PrimaryHttpsPort：443

ExternalHttpPort：8080

ExternalHttpsPort：4443

PublishedPrimaryHttpPort：80

PublishedPrimaryHttpsPort：443

PublishedExternalHttpPort：80

PublishedExternalHttpsPort：443

ReachPrimaryPsomServerPort：8060

ReachExternalPsomServerPort：8061

AppSharingPortStart：49152

AppSharingPortCount：16383

LIServiceInternalUri : https://internalweb.contoso.net/locationinformation/liservice.svc

ABHandlerInternalUri : https://internalweb.contoso.net/abs/handler

ABHandlerExternalUri : https://csweb.contoso.com/abs/handler

DLExpansionInternalUri : https://internalweb.contoso.net/groupexpansion/service.svc

DLExpansionExternalUri : https://csweb.contoso.com/groupexpansion/service.svc

CAHandlerInternalUri : https://internalweb.contoso.net/CertProv/CertProvisioningService.svc

CAHandlerInternalAnonUri : http://internalweb.contoso.net/CertProv/CertProvisioningService.svc

CollabContentInternalUri : https://internalweb.contoso.net/CollabContent

CollabContentExternalUri : https://csweb.contoso.com/CollabContent

CAHandlerExternalUri : https://csweb.contoso.com/CertProv/CertProvisioningService.svc

DeviceUpdateDownloadInternalUri : https://internalweb.contoso.net/RequestHandler/ucdevice.upx

DeviceUpdateDownloadExternalUri : https://csweb.contoso.com/RequestHandlerExt/ucdevice.upx

DeviceUpdateStoreInternalUri : http://internalweb.contoso.net/RequestHandler/Files

DeviceUpdateStoreExternalUri : https://csweb.contoso.com/RequestHandlerExt/Files

RgsAgentServiceInternalUri : https://internalweb.contoso.net/RgsClients/AgentService.svc

RgsAgentServiceExternalUri : https://csweb.contoso.com/RgsClients/AgentService.svc

MeetExternalUri : https://csweb.contoso.com/Meet

DialinExternalUri : https://csweb.contoso.com/Dialin

CscpInternalUri : https://internalweb.contoso.net/Cscp

ReachExternalUri : https://csweb.contoso.com/Reach

ReachInternalUri : https://internalweb.contoso.net/Reach

WebTicketExternalUri : https://csweb.contoso.com/WebTicket/WebTicketService.svc

WebTicketInternalUri : https://internalweb.contoso.net/WebTicket/WebTicketService.svc

ExternalFqdn： csweb.contoso.com

InternalFqdn： internalweb.contoso.net

DependentServiceList： {注册:pool01，ConferencingServer:pool01}

ServiceId： 1-WebServices-1

SiteId：网站：雷德蒙

PoolFqdn： pool01.contoso.net

版本：5

角色： Web 还是 Web

<div>

## <a name="see-also"></a>另请参阅


[CsService](https://docs.microsoft.com/powershell/module/skype/Get-CsService)  
  

</div>

</div>

<span> </span>

</div>

</div>

</div>

