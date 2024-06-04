---
nav_title: 誘発された開封数
article_title: 誘発された開封数
page_order: 7
page_type: reference
description: "このリファレンス記事では、誘発された開封数と、それを追跡し、プッシュキャンペーンについて充実したレベルの詳細を提供する方法について説明します。"
channel: push

---

# 誘発された開封数

> プッシュ通知は、ユーザーの関心を喚起し、エンゲージメントを高める優れた方法です。多くの場合、このエンゲージメントはユーザーが通知をクリックする直接開封であり、この行動がアプリに送信されます。しかし、メッセージをクリックしないユーザーの行動も、プッシュキャンペーンに誘発される可能性があります。Braze は、プッシュキャンペーンの効果をより詳細に把握できるように、誘発された開封に関する充実したレベルの詳細を提供します。 

基本的に、誘発された開封数は、通知の受信後に通知をクリックせずにアプリを開いたユーザーの数です。通知をアプリの起動にリンクする直接的なアクションはないため、ユーザーがプッシュ通知を受信してから、アプリを開くまでの時間が 30 分以内か、ユーザーの最終セッションからの平均経過時間の半分未満の場合、誘発された開封だと見なされます。

たとえば、メッセージングアプリのユーザーにプッシュを送信するとします。また、通知をクリックしないユーザーのグループがあるとします。通常 1 日に 30 回アプリを開くユーザーが、プッシュを受信してから 6 時間後にアプリを開いた場合、プッシュが開封を誘発したと見なされることはほぼまったくありません。ただし、通常 1 か月に 1 回アプリを使用するユーザーがプッシュを受信してから 6 時間後にアプリを開いた場合、開封が誘発された開封数としてカウントされる可能性が高くなります。 

これは、プッシュキャンペーンのコンバージョンイベントとしてアプリ起動を設定することとは異なります。コンバージョンの場合、コンバージョン期間内のすべての開封がキャンペーンに起因すると見なされます。誘発された開封数では、個々のユーザーの行動に基づいて期間とアトリビューションクレジットを設定します。

## キャンペーンの詳細

誘発された開封数をキャンペーンの直接開封数に加えると合計開封数が得られます。これは、プッシュキャンペーンの [**詳細**] ページで確認できます。合計開封数と直接開封数は、[**メッセージのパフォーマンス**] セクションと [**過去のパフォーマンス**] セクションに表示されます。誘発された開封数は、この 2 つの値の差です。

![キャンペーンの [キャンペーンの詳細] ページに教示される誘発された開封数の統計情報][1]

開封数の追跡の詳細については、[プッシュ通知のベストプラクティス][bp]のコンバージョン追跡のセクションを参照してください。

[bp]: {{site.baseurl}}/user_guide/message_building_by_channel/push/best_practices/
[1]: {% image_buster /assets/img_archive/Influenced_Opens2.png %}