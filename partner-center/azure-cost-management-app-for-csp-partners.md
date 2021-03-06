---
title: CSP パートナー向けの Cloudyn 製 Azure Cost Management |パートナー センター
ms.topic: article
ms.date: 10/29/2018
description: Cloudyn が提供する Azure Cost Management を使用するには、パートナー センター API へのアクセスをプロビジョニングする必要があります。
author: Janet
ms.author: janet
Keywords: Azure コスト管理アプリでは、管理コストの削減、web アプリ
robots: ''
ms.localizationpriority: medium
ms.openlocfilehash: 586ec2936b8491e91b4f2a56cbc392e4dee350b3
ms.sourcegitcommit: 4c34d6fcaf020bcc53eaa5f0379011a56149a14f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2019
ms.locfileid: "57586085"
---
# <a name="azure-cost-management-app-for-azure-csp-partners"></a>Azure を販売する CSP パートナー様向けの Azure コスト管理アプリ  

**適用対象**

-  パートナー センター

[Azure Cost Management について詳細を取得します。](https://go.microsoft.com/fwlink/p/?linkid=857893)

## <a name="before-you-begin"></a>始める前に
Azure Cost Management を使用する前に、次の要件を満たしていることを確認してください。

- クラウド ソリューション プロバイダー プログラムのパートナー様であること。
- パートナー センター API Web アプリを作成できること。

## <a name="overview"></a>概要

Cloudyn が提供する Azure cost management は、お客様による Azure の使用量とその使用量に対応するコストを追跡、管理できる Web アプリです。 このアプリは、パートナー センター API 経由で使用します。

## <a name="register-your-web-app-in-the-partner-center"></a>パートナー センターで Web アプリを登録する
パートナー センターで Azure Active Directory Web アプリを登録すると、アプリがパートナー センター API にアクセスできるようになります。 
1.  [全体管理者または管理エージェント アカウント](create-user-accounts-and-set-permissions.md)を使って、[パートナー センター](https://partnercenter.microsoft.com/en-us/pcv/dashboard/overview)にサインインします。
2.  **パートナー センター**、**アカウント設定** &gt; **[アプリ管理](https://partnercenter.microsoft.com/en-us/pcv/apiintegration/appmanagement)** します。
3.  **[Web アプリ]** セクションで、**[新しいアプリの追加]** をクリックします。
<br> **注意**:Web アプリを作成していた場合は、手順 3. を省略できます。
4.  登録する Web アプリの **商取引 ID** GUID と **アプリ ID** GUID をコピーして保存します。 Azure cost management アプリの 30 日間無料試用版を利用するには、両方の ID が必要です。

## <a name="add-a-secret-key-to-your-app"></a>アプリへの秘密鍵の追加
1. **[キーの追加]** ボタンの横のドロップ ダウンで、1 年間または 2 年間の期間を選択します。
2. **[キーの追加]** をクリックします。 
3. 秘密キーの値を書き留めて保存します。 この値は、30 日間無料試用版の利用に必要です。<br>
   > [!NOTE]  
   > アプリケーションの秘密キーでは、パスワードより長い有効期限と同様です。 後日使用できるように、安全な場所にキーの値を保存してください。

## <a name="next-steps"></a>次のステップ
[30 日間無料試用版](https://go.microsoft.com/fwlink/?linkid=857895) をご利用ください。
試用を開始するには、次の情報が必要です。
- パートナー センターのログイン資格情報
- 商取引 ID GUID
- アプリ ID GUID
- アプリケーションの秘密キーの値
