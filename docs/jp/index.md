![PagerDutyの障害対応](./assets/img/headers/pagerduty_ir.jpg)

このドキュメントは、PagerDutyの障害対応手順の一部を扱っています。PagerDutyが重大障害やオンコール対応をする新しい従業員の準備用に使用する内部ドキュメントの一部省略版です。障害への備え方だけでなく、その前後で何をすべきかについての情報も提供します。オンコール対応者や障害対応者（または司式な障害対応手順の実施を希望する人）が使用することを想定しています。このドキュメントが何で、何故存在しているのかについては、[このページについて](about.md) を参照してください。



!!! tip "どこから始めたらいいのかわからない？"
    もし新たに障害対応をしようとしていたり、組織内に正式な手順がないのでしたら、まず着手すると良い一覧である[入門](getting_started.md) を見ることをお勧めします。

## オンコールを始める

以前にオンコールをしたことがない場合は、それが何か不思議に思うかもしれません。あなたに役立ついくつかの資料とオンコールで何を期待するのかについて説明します。

* [オンコールを始める](oncall/being_oncall.md) - _オンコールを始めるガイド、責任範囲と責任範囲外について_
* [アラートの原則](oncall/alerting_principles.md) - _どのようなものでエンジニアを呼び出し、いつ呼び出すのかを判断するために使用する原則_

## 障害発生前

障害発生前にあなたが恐らく読みたいと思うであろう資料を読んでください。実際の障害中には読みたいとは思わないでしょう。

* [What is an Incident?](before/what_is_an_incident.md) - _招待対応について話す前に、障害とは何かを定義する必要があります。_
* [Severity Levels](before/severity_levels.md) - _重大度レベルの分類に関する情報。SEV-3 と SEV-1の構成要素は何でしょうか？ どう対応しますか？_
* [Different Roles for Incidents](before/different_roles.md) - _障害対応中の役割についての情報。 障害指揮者、書記など_
* [Incident Call Etiquette](before/call_etiquette.md) - _障害オンコールの礼儀指針_
* [Complex Incidents](before/complex_incidents.md) - _大規模で複雑な障害を扱うための指針_

## 障害発生中

重大障害中の情報と手順

* [During an Incident](during/during_an_incident.md) - _障害中に何をするべきか、前向きに貢献する方法についての情報_
* [Security Incident Response](during/security_incident_response.md) - _セキュリティインシデントは通常の障害対応とは異なる方法で取り扱います。_

## 障害発生後

フォローアップ手順は、私たちは失敗を繰り返さず、常に改善していることを確認する方法です。

* [After an Incident](after/after_an_incident.md) - _障害解決後に何をするかについての情報_
* [Post-Mortem Process](after/post_mortem_process.md) - _事後分析手順についての情報。事後分析を書いたり実行するためにどのようなことが関係しているか。_
* [Post-Mortem Template](after/post_mortem_template.md) - _重大障害についての事後分析を書くのに使用するテンプレート。_
* [Effective Post-Mortems](after/effective_post_mortems.md) - _効果的な事後分析を書く指針_

## トレーニング

障害対応について学びたいですか？正しい場所に行くべきです。

* [Training Overview](training/overview.md) - _トレーニング指針の概要と外部の追加のトレーニング資料_
* [Incident Commander Training](training/incident_commander.md) - _次の障害指揮者になるための指針_
* [Deputy Training](training/deputy.md) - _代理をしたり、障害指揮者のバックアップになる方法_
* [Scribe Training](training/scribe.md) - _書記のための指針_
* [Subject Matter Expert Training](training/subject_matter_expert.md) - _重大障害における参加者全員の行動と責任に関する指針_
* [Customer Liaison Training](training/customer_liaison.md) - _障害中の公衆の代理人として行動する方法に関する指針_
* [Internal Liaison Training](training/internal_liaison.md) - _障害発生中に社内チームと連絡を取る方法についての指針_
* [Glossary of Incident Response Terms](training/glossary.md) - _使用していると聞く可能性の用語集と定義_

## 補足資料

障害対応に関する外部の有益な資料やリソースです。

* [Reading](resources/reading.md) - _障害対応に関連する推薦資料_
* [ChatOps](resources/chatops.md) - _このドキュメントで参照しているチャットボットの説明_
* [Anti-Patterns](resources/anti_patterns.md) - _試行し取りやめた一覧、私たちの過ちから学びます。_
