# アノテーションスキーマ

## 有害レベル

文章の有害さを4段階で評価したスキーマ（[参考](https://developers.perspectiveapi.com/s/about-the-api-training-data?language=en_US)）。

<table>
    <tr>
        <td>レベル</td>
        <td>定義</td>
    </tr>
    <tr>
        <td>Not Toxic</td>
        <td>有害ではない文章</td>
    </tr>
    <tr>
        <td>Hard to Say</td>
        <td>有害かどうか分からない、有害かどうかを決めるために前後の文脈が必要な文章</td>
    </tr>
    <tr>
        <td>Toxic</td>
        <td>失礼、無礼、理不尽な表現で、見た人が議論を放棄したり、自分の意見を述べることを諦める可能性がある文書</td>
    </tr>
    <tr>
        <td>Very Toxic</td>
        <td>非常に憎悪的、攻撃的な、あるいは軽蔑的な表現を含み、見た人が議論を放棄したり、自分の意見を伝えることを諦める可能性が非常に高い文章</td>
    </tr>
</table>

## 有害カテゴリ

有害さの種類を7つのメインカテゴリと41つのサブカテゴリで表現した階層的なスキーマ。

<table>
    <tr>
        <td>メインカテゴリ</td>
        <td>倫理観</td>
        <td>サブカテゴリ</td>
        <td>例文</td>
    </tr>
    <tr>
        <td >卑語</td>
        <td>他者への配慮</td>
        <td>卑語</td>
        <td>うんこ！うんこ！うんこ！</td>
    </tr>
    <tr>
        <td rowspan="13">差別</td>
        <td rowspan="13">公正性</td>
        <td>人種差別</td>
        <td>バカチョンイライラ</td>
    </tr>
    <tr>
        <td>性別差別</td>
        <td>男はATM</td>
    </tr>
    <tr>
        <td>性的指向差別</td>
        <td>レズビアンは受け付けない</td>
    </tr>
    <tr>
        <td>職業差別</td>
        <td>トラック運転手に低学歴が多いのはなぜ?</td>
    </tr>
    <tr>
        <td>外見差別</td>
        <td>ブスには犯罪者が多い</td>
    </tr>
    <tr>
        <td>宗教差別</td>
        <td>XXX教徒は頭おかしい</td>
    </tr>
    <tr>
        <td>政治差別</td>
        <td>XXX党の支持者は白髪のジジババしか居ない</td>
    </tr>
    <tr>
        <td>地域差別</td>
        <td>XX人が一番嫌いだわ。頭が全員悪いから。</td>
    </tr>
    <tr>
        <td>国籍差別</td>
        <td>移民のくせに偉そうなんだよ</td>
    </tr>
    <tr>
        <td>年齢差別</td>
        <td>ジジイババアは早く死ね</td>
    </tr>
    <tr>
        <td>市民権差別</td>
        <td>在留資格も無い、体調も悪いのになぜ帰らない</td>
    </tr>
    <tr>
        <td>障がい・病気差別</td>
        <td>障害者は死ね</td>
    </tr>
    <tr>
        <td>その他</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="9">迷惑行為</td>
        <td rowspan="9">他者の尊重</td>
        <td>侮辱・誹謗中傷（個人攻撃）</td>
        <td>早く死ね</td>
    </tr>
    <tr>
        <td>侮辱・誹謗中傷（集団・その他）</td>
        <td>お前ら全員気持ち悪い。</td>
    </tr>
    <tr>
        <td>暴力・脅し</td>
        <td>てめえぶち殺してやる</td>
    </tr>
    <tr>
        <td>自殺・自害</td>
        <td>今から自殺する。</td>
    </tr>
    <tr>
        <td>非文・繰り返し</td>
        <td>ｇじょいあｇじおらｊごいあ</td>
    </tr>
    <tr>
        <td>扇動的行為</td>
        <td>負け組乙</td>
    </tr>
    <tr>
        <td>嫌悪</td>
        <td>ハムスターを飲み込む</td>
    </tr>
    <tr>
        <td>宣伝行為</td>
        <td>起動するだけで1万円配布します</td>
    </tr>
    <tr>
        <td>その他</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="4">わいせつ</td>
        <td rowspan="4">法規制の遵守・有害コンテンツからの保護</td>
        <td>卑猥表現</td>
        <td>SEX 大歓迎</td>
    </tr>
    <tr>
        <td>性売買・風俗系</td>
        <td>本日22時からです♪会いに来てね #セクキャバ</td>
    </tr>
    <tr>
        <td>成人用品系</td>
        <td>中年に効く激安精力剤はこれ！</td>
    </tr>
    <tr>
        <td>その他</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="4">出会い・プライバシー侵害</td>
        <td rowspan="4">他者のプライバシーの尊重</td>
    </tr>
    <tr>
        <td>個人情報</td>
        <td>電話番号はXX-XXXXです</td>
    </tr>
    <tr>
        <td>出会い</td>
        <td>彼女募集中です！</td>
    </tr>
    <tr>
        <td>その他</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="6">違法行為</td>
        <td rowspan="6">法規制の遵守</td>
        <td>違法薬物</td>
        <td>大麻売ります。</td>
    </tr>
    <tr>
        <td>模造品系</td>
        <td>当店はブランド用品のコピーを販売しております</td>
    </tr>
    <tr>
        <td>金融系</td>
        <td>FX コピートレードは何もしません、口座開設するだけです！</td>
    </tr>
    <tr>
        <td>児童ポルノ</td>
        <td>児童ポルノ作品を売ります</td>
    </tr>
    <tr>
        <td>権利侵害</td>
        <td></td>
    </tr>
    <tr>
        <td>その他</td>
        <td>副作用のない薬を販売してます。</td>
    </tr>
    <tr>
        <td rowspan="4">偏向表現</td>
        <td rowspan="4">多様性の尊重・公正性</td>
        <td>政治</td>
        <td>XX党が絶対正しい！</td>
    </tr>
    <tr>
        <td>宗教</td>
        <td>XXX教は正しかった。</td>
    </tr>
    <tr>
        <td>専門予測（医療・法律・金融）</td>
        <td></td>
    </tr>
    <tr>
        <td>その他</td>
        <td></td>
    </tr>
</table>