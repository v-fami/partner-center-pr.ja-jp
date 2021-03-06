---
title: Power BI 用パートナー センター分析アプリ | パートナー センター
ms.topic: article
ms.date: 10/29/2018
description: Power BI 用パートナー センター分析アプリ (CSP の直接パートナー向け) の使用方法を説明します。
fwlink: https://go.microsoft.com/fwlink/?linkid=852581
author: LauraBrenner
ms.author: labrenne
ms.localizationpriority: medium
ms.openlocfilehash: 59e5ce944429a74ab9090952eb877187b169ce08
ms.sourcegitcommit: 4c34d6fcaf020bcc53eaa5f0379011a56149a14f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2019
ms.locfileid: "57587485"
---
# <a name="view-your-business-data-with-the-partner-center-analytics-app-for-microsoft-power-bi"></a>Microsoft Power BI 用パートナー センター分析アプリでビジネス データを表示する

**適用対象**

-   パートナー センター

## <a name="view-your-business-data"></a>ビジネス データを表示する

Power BI 用パートナー センター分析アプリでは、ビジネス データの視覚表現を利用できます。以下に例を示します。

- 顧客数、サブスクリプション数、ライセンス数の増加

- Office 365、Microsoft Dynamics、Microsoft Azure の製品の使用量

- 過去 60 日間の各 Azure サブスクリプションにおける従量制課金リソースごとの 1 日当たりの消費単位

- (最新の価格カードに基づく) 推定コスト

- データセットのエクスポートおよびカスタム レポート作成 (顧客別など) の機能 

### <a name="about-the-partner-center-analytics-app-preview-release"></a>パートナー センターの分析のアプリのプレビュー リリースについて

 - このアプリは、クラウド ソリューション プロバイダー プログラムの直接パートナーのみを対象としています。 CSP の他のパートナー (間接リセラーなど) はログインできません。

- 見積もりコストはすべて税抜きの請求データであり、法的拘束力を持ちません。 推定コストは、データ インサイトの目的のみで使用することを想定しています。

- 顧客情報は、サブスクリプションに基づきます。 最近、アカウントを作成し、まだサブスクリプションがない顧客はカウントされません。 

- 推定コストは、最新の価格カード (CSP 価格に基づく) を使って算出されます。 

- 日数は暦日です。 


### <a name="business-insights-report"></a>ビジネス インサイト レポート

-  **顧客テナント**:個別の Azure のサブスクリプションを購入した顧客の AD テナント

-  **新しい (過去 30 日)**:新しい顧客が過去 30 日間に少なくとも 1 つのサブスクリプションの購入

-  **(過去 30 日間) のチャーン**:お客様を"active"、"で猶予"または"disabled"サブスクリプション

- **新しい (過去 24 時間)**:新しい顧客が過去 24 時間に少なくとも 1 つのサブスクリプションの購入

- **過去 12 か月間の推定月間コスト**:推定税引き前の請求金額の傾向を 1 か月の前月が過去 12 か月間の期間の月単位で集計

- **製品で過去 12 か月間の推定コスト**:推定税引き前の請求金額を並べ替えて販売されている製品は、過去 12 か月間の期間にわたって集計されます。 これにより、収益性の高い主力製品が明確になります。

- **過去 12 か月間以上の顧客**:過去 12 か月間の期間の月単位の新規の顧客や顧客のチャーンか月ごとの傾向を 1 か月の集計

- **過去 12 か月間の推定コストを顧客が**:顧客の過去 12 か月間の期間にわたって集計された推定税引き前の請求金額で並べ替えられます。 これにより、収益性の高い主要顧客が明確になります。

- **製品別の顧客数**:製品は販売関連付けられている顧客によって並べ替えられています。 これにより、多くの顧客が購入した主力製品が明らかになります。 


### <a name="subscription-insights-report"></a>サブスクリプション インサイト レポート 

- **Subscription status** (サブスクリプションの状態): 

    - アクティブ:サブスクリプションの"猶予"または「アクティブ」に属する状態

    - 中断。「無効」状態に属するサブスクリプション

    - プロビジョニング解除します。属するサブスクリプションが「プロビジョニング解除」または「期限切れ」の状態

- **Expiry status** (有効期限の状態): 

    - ［有効期限切れ］:既に有効期限の切れたサブスクリプション (サブスクリプションの終了日が、これまで)

    - 30 日後に期限切れになりません。(サブスクリプションの終了日は、次の 30 日後に)、30 日後に期限切れサブスクリプション

    - 30 日以内に期限切れになりません。サブスクリプション (サブスクリプションの終了日は現在および今後 30 日間)、[次へ] の 30 日以内に切れる

-  **サブスクリプションの合計**:「アクティブ」でのサブスクリプションの"猶予"または「無効」の状態

- **新しい (過去 30 日)**:過去 30 日以内に顧客が購入した新しいサブスクリプション

- **新しい (過去 24 時間)**:過去 24 時間以内に顧客が購入した新しいサブスクリプション

- **30 日以内に期限切れにならない**:次の 30 日以内の有効期限のサブスクリプション

- **(過去 30 日間) のチャーン**:逆にプロビジョニングされたサブスクリプションまたは Suspended の過去 30 日以内には、(無効)

- **Distribution by subscription types** (サブスクリプションの種類別分布率): 全サブスクリプションのライセンス ベースと利用量ベースのサブスクリプションの種類別分布率

- **製品別のアクティブなサブスクリプション数**:アクティブなサブスクリプションの数によって並べ替えられて販売されている製品

- **過去 12 か月間のサブスクリプション**:過去 12 か月間の期間の月単位の新規のサブスクリプションとサブスクリプションの変更頻度か月ごとの傾向を 1 か月の集計

- **顧客サブスクリプションの詳細**:顧客、サブスクリプション プランの詳細の表示 


### <a name="license-insights-report"></a>ライセンス インサイト レポート:

- **ライセンスの合計**:ライセンス ベースのライセンスのすべてのサブスクリプションにわたって集計の合計数

- **新しい (過去 30 日)**:過去 30 日以内のライセンスの追加

- **(過去 30 日間) のチャーン**:過去 30 日間でのライセンスの削減

- **新しい (過去 24 時間)**:過去 24 時間以内にライセンスの追加

- **過去 90 日間ライセンス**:前月のライセンスの追加や過去 90 日間の期間の月単位で集計の削減か月ごとの傾向

- **製品別のアクティブなライセンス数**:アクティブなライセンスの数によって並べ替えられて販売されている製品

- **お客様によってアクティブなライセンス数**:アクティブなライセンス数の順で顧客が並べ替えられます

- **過去 90 日間ライセンスのイベントの詳細を顧客**:サブスクリプション イベントのイベントなどの日付、イベント名、数量と数量の変更および顧客のサブスクリプション ビューの詳細。


### <a name="licenses-usage-report"></a>ライセンス使用状況レポート:

- **割り当てられている製品ライセンス**:ライセンス割り当ての数によって並べ替えられて販売されている製品

- **製品で使用中のライセンス**:ライセンスの使用率カウントで並べ替えられた販売されている製品

- **Customer distribution of licenses assigned** (割り当て済みライセンスの顧客分布): 全顧客を 20% 刻みのライセンス割り当て率の範囲ごとに分割した分布率

- **Customer distribution of licenses in use** (使用中ライセンスの顧客分布): すべての顧客を 20% 刻みの使用中ライセンス率の範囲ごとに分割した分布率

- **顧客が割り当てられているライセンス**:ライセンスの詳細ビューの販売し、顧客と製品ライセンスを割り当てる

- **お客様が使用中のライセンス**:ライセンスの販売と顧客と製品で使用中のライセンスの詳細ビュー


### <a name="azure-insights-report"></a>Azure インサイト レポート:

- **過去 12 か月間使用量ベースの顧客**:新しい使用状況の傾向を 1 か月の前月の顧客をベースし、過去 12 か月間の期間の月単位で集計使用法に基づく顧客を頻繁

- **過去 12 か月間のサブスクリプションが使用法に基づく**:新しい使用状況の傾向を 1 か月の前月のサブスクリプションをベースし、過去 12 か月間の期間の月単位で集計使用法に基づくサブスクリプションを頻繁

- **過去 60 日間の顧客による使用量のコストの見積もり**:使用法に基づくお客様の推定税引き前の請求金額で並べ替えられますが、過去 60 日間の期間にわたって集計されます。 これにより、収益性の高い使用量ベースの主要顧客が明確になります。

- **カテゴリ別過去 60 日間使用量のコストの見積もり**:使用状況測定のカテゴリに分類ベースのサブスクリプションを過去 60 日間の期間にわたって集計された推定税引き前の請求金額で並べ替えられます。

- **過去 60 日間のサブスクリプションによって使用量のコストの見積もり**:推定税引き前の請求金額での使用法に基づくサブスクリプションは、過去 60 日間の期間にわたって集計されます。

- **支出予算を推定使用量のコストを顧客**:顧客の支出予算超過しきい値 (100%)、現在の使用量の割合で並べ替えられます。


### <a name="azure-resource-usage-report"></a>Azure リソース使用状況レポート:

- **選択した期間の日別の Azure リソースの使用量**:過去 60 日間内で選択した期間中のサブスクリプションを従量制課金の各リソースごとの使用状況での毎日の消費量単位に基づいています。

- **選択した期間の Azure リソースの使用量のコストの見積もり**:過去 60 日間内で選択した期間の各使用法に基づくサブスクリプションで従量制のリソースごとに最新の価格カードに基づく推定コスト。 

## <a name="see-also"></a>関連項目

[パートナー センターの Analytics の Power BI アプリの概要](power-bi-app-for-direct-partners.md)


[インストールし、Microsoft Power BI 用のパートナー センターの分析アプリのプレビュー](power-bi-app-for-direct-partners-install.md)
