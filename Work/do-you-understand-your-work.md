## あなたが担う「部分」は「全体」の美に寄与しているか

自分が担当する仕事は自分の目の前にある。その仕事の範囲や要求される成果は分かっている。だが、自分の仕事はより大きな仕事の部分に過ぎない。自分の成果が全体の中でどう見えるか、全体の美しさに貢献しているか、となると分からなくなってくる。

　つまらない仕事だと思っていても全体の中に置いてみると相応の意義があるかもしれない。逆に自分としては最高の仕事をしたつもりでも全体としてぱっとしなければ良い仕事だったのかどうか怪しくなる。筆者の仕事は原稿を書くことだが、例えばある雑誌の特集記事を担当し、その第一部を書いたとする。面白いと自賛していても別の記者が書いた第二部と並べてみると特集全体として何が言いたいのか分かりにくくなってしまうかもしれない。

　当然、情報システムの仕事においても部分と全体の兼ね合いはある。あるプログラマーが書いたプログラムは単体で動くと同時にサブシステムの中で動く。サブシステムは他のサブシステムと連携し、一つのシステムは別システムとも連携する。システム群はそれらを使う企業の仕事に貢献するために作られている。一つのプログラムがそれを開発した人の前で動いたとしても、システムとして動かなかったり、システムが動いたとしてもそれを使う企業の仕事に役立たなかったりしたら、全体としては失敗である。

　真っ当な人なら自分が担当した部分についてきっちり仕事をしつつ、全体がどうなっているかを知ろうとする。真っ当な組織であれば取り組んでいる仕事の全体について部分を担当している人たちに説明する。

　つまり、何らかの仕事や企画を進めるにあたって、全体が備える要件と全体を構成する部分の要件をはっきりさせ、両者を整理して一つの体系にまとめておく必要がある。そうした体系があってこそ、全体の出来映えや美しさを担保できる。

### 何事にもアーキテクチャがある

　くどくど述べてきたが実はここまでの文章は「アーキテクチャ」の定義と意義の説明であった。アーキテクチャとは、構造を持つシステム全体の機能、パフォーマンス、実現可能性、コスト、美しさが最適になるように、構成要素を体系立てて整理したものである。この定義は『データマネジメント知識体系ガイド』から引用した。同書は“The DAMA Guide to The Data Management Body of Knowledge”の邦訳であり、Architectureの説明は原文では“an organized arrangement of component elements which optimizes the function,preformance,feasibility,cost,and/or aesthetics of the overall structure of system”となっている。

　労作と言える同書はDAMA（データマネジメントアソシエーション）と呼ぶ非営利団体に属するデータマネジメントの専門家が4年を費やして著したものだ。データマネジメントとはデータ資産および情報資産の価値を高めるために、計画作成、開発、統制をすることである。こうした活動も一つのシステムとみなせるから、データアーキテクチャが必要になる。

　聞かれたことがあるかどうか、「エンタープライズアーキテクチャ」という言葉がかつてあった。エンタープライズは大胆な企て、あるいは企業のことだから、エンタープライズアーキテクチャは企てあるいは企業の構成要素を体系立てて整理したものになる。「かつてあった」と書いたように、2003年11月に経済産業省が『EA策定ガイドライン』を公表し、エンタープライズアーキテクチャ（EA）は大いに話題になったものの、数年で静かになってしまった。

　長くなるが『データマネジメント知識体系ガイド』の説明を引用する。「エンタープライズアーキテクチャはエンタープライズの統一および標準化にまつわる要件を反映させた、ビジネスおよびITの仕様のモデルないし製作物を一つにまとめたものである」。原文は“Enterprise Architecture is an integrated set of　business and IT specification models and artifacts reflecting enterprise integration and standardization requirements”となっている。データアーキテクチャはエンタープライズアーキテクチャの重要な部分である。

　技術者の方はアーキテクチャと聞いてテクノロジーアーキテクチャを思い浮かべるかもしれない。企業の仕事を支援する情報システムを開発している人にとってはアプリケーションアーキテクチャがある。上記の定義に「ビジネスおよびITの仕様」とある通り、ビジネスアーキテクチャというものもあり、そこには企てや企業の目的、目標、戦略、規則などが記載される。ビジネス、アプリケーション、データ、テクノロジーの各アーキテクチャはエンタープライズアーキテクチャに包含される。

### 必要だが正面から取り組みにくいのはなぜか

　先に「エンタープライズアーキテクチャ（EA）は大いに話題になったものの、数年で静かになってしまった」と書いたがこれは日本の状況である。『手を動かさないと始まらないが動かすだけでは行き詰まる』に書いた通り、「2016年の今、日本においてはEAという言葉をあまり見聞きしない。日経BP社は2004年に『EA大全』という本を出し、EAのセミナーを開いたりしたが、最近は情報をほとんど発信していない」。
　
　のうのうと「情報をほとんど発信していない」と書いているが、エンタープライズアーキテクチャが不要になったわけではない。いや、必要か不要かを論じるのは意味がない。エンタープライズアーキテクチャは「ビジネスとITの仕様をまとめたもの」だから、本来すべての企てや企業が持っている。ビジネスを進め、ITを使っている以上、あまり整理されていないとしても、エンタープライズアーキテクチャとは呼んでいないとしても、何らかの仕様が企てや企業の中に必ずある。

　うまく行っているからエンタープライズアーキテクチャなど要らない、という訳にはいかない。「構成要素を体系立てて整理」せず、ビジネスやアプリケーションやデータやテクノロジーの仕様を埋もれたままにしておくと構造が段々分からなくなり、企てや企業に関わる人々が担う部分の活動がまとまらず、全体の「機能、パフォーマンス、実現可能性、コスト、美しさ」に悪影響を与えてしまう。実際、悪影響を受け、うまく行かなくなっている企てや企業が散見される。

　ただし、話を分かりにくくして恐縮だが、「日本企業はエンタープライズアーキテクチャに再度取り組もう」と呼びかけたいのかというと少し違う。繰り返しになるが企てや企業の構成要素の整理と各要素の見直しは不可欠であり、経済産業省や誰かに言われて取り組むことではない。人から言われてやろうとすると「エンタープライズアーキテクチャとは何か。それをどう作成するのか」が気になり、手法の勉強や人材育成へと話がそれていく。

　ご立派な『EA策定ガイドライン』や『EA大全』をひも解いただけに終わったのは手法の勉強で疲れてしまったからではないか。手法は整理の対象ごとに色々ある。片仮名を並べてしまうが例えばビジネスアナリシス、アプリケーションポートフォリオ、データモデリング、マスターデータマネジメントなどがある。テクノロジーを対象とする手法は沢山ある。すでに取り組んでいる手法があればそれを使って構成要素の整理をしていけばよい。

　エンタープライズの全体をいきなり整理しよう、アーキテクチャを完成させよう、と張り切って疲れてしまった企業もあるだろう。企業が抱えるビジネスやITの構成要素は膨大であり、整理には相当な時間がかかる。しかもビジネスや環境は変わっていくから、企てや企業というシステム全体の美を意識しつつ、アーキテクチャを常時見直していく。企てや企業が生きている限り、エンタープライズアーキテクチャは完成しない。完成しないけれども、それに近づくことを目指し、取り組みを続けることになる。
　
> Source: http://itpro.nikkeibp.co.jp/atcl/watcher/14/334361/082900648/
