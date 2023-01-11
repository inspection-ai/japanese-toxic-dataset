# Schema

## Toxicity Level

A schema that evaluates the toxicity of a text in four levels ([ref](https://developers.perspectiveapi.com/s/about-the-api-training-data?language=en_US)).

<table>
    <tr>
        <td>Level</td>
        <td>Description</td>
    </tr>
    <tr>
        <td>Not Toxic</td>
        <td>A neutral, civil, or even nice comment very unlikely to discourage the conversation.</td>
    </tr>
    <tr>
        <td>Hard to Say</td>
        <td>The comment could be interpreted as toxic depending on the context but you are not sure.</td>
    </tr>
    <tr>
        <td>Toxic</td>
        <td>A comment that is rude, disrespectful, unreasonable, or otherwise somewhat likely to make a user leave a discussion or give up on sharing their perspective.</td>
    </tr>
    <tr>
        <td>Very Toxic</td>
        <td>A comment that is very hateful, aggressive, disrespectful, or otherwise very likely to make a user leave a discussion or give up on sharing their perspective.</td>
    </tr>
</table>

## Toxicity Category

A hierarchical schema that represents the types of toxicity with seven main categories and forty-one subcategories.

<table>
    <tr>
        <td>Category</td>
        <td>Sense of ethics</td>
        <td>Sub Category</td>
        <td>Example</td>
    </tr>
    <tr>
        <td>Dignity</td>
        <td>Consideration</td>
        <td>Vulgar</td>
        <td>うんこ！うんこ！うんこ！</td>
    </tr>
    <tr>
        <td rowspan="13">Discrimination</td>
        <td rowspan="13">Fairness</td>
        <td>Race</td>
        <td>バカチョンイライラ</td>
    </tr>
    <tr>
        <td>Gender</td>
        <td>男はATM</td>
    </tr>
    <tr>
        <td>Sexuality</td>
        <td>レズビアンは受け付けない</td>
    </tr>
    <tr>
        <td>Occupation</td>
        <td>トラック運転手に低学歴が多いのはなぜ?</td>
    </tr>
    <tr>
        <td>Lookism</td>
        <td>ブスには犯罪者が多い</td>
    </tr>
    <tr>
        <td>Religion</td>
        <td>XXX教徒は頭おかしい</td>
    </tr>
    <tr>
        <td>Politics</td>
        <td>XXX党の支持者は白髪のジジババしか居ない</td>
    </tr>
    <tr>
        <td>Region</td>
        <td>XX人が一番嫌いだわ。頭が全員悪いから。</td>
    </tr>
    <tr>
        <td>National Origin</td>
        <td>移民のくせに偉そうなんだよ</td>
    </tr>
    <tr>
        <td>Age</td>
        <td>ジジイババアは早く死ね</td>
    </tr>
    <tr>
        <td>Citizenship</td>
        <td>在留資格も無い、体調も悪いのになぜ帰らない</td>
    </tr>
    <tr>
        <td>Disease</td>
        <td>障害者は死ね</td>
    </tr>
    <tr>
        <td>Others</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="9">Harassment</td>
        <td rowspan="9">Respect others</td>
        <td>Smear</td>
        <td>早く死ね</td>
    </tr>
    <tr>
        <td>Smear Others</td>
        <td>お前ら全員気持ち悪い。</td>
    </tr>
    <tr>
        <td>Violence</td>
        <td>てめえぶち殺してやる</td>
    </tr>
    <tr>
        <td>Suicide</td>
        <td>今から自殺する。</td>
    </tr>
    <tr>
        <td>Non Sentence</td>
        <td>ｇじょいあｇじおらｊごいあ</td>
    </tr>
    <tr>
        <td>Inflammatory</td>
        <td>負け組乙</td>
    </tr>
    <tr>
        <td>Disgust</td>
        <td>ハムスターを飲み込む</td>
    </tr>
    <tr>
        <td>Advertisement</td>
        <td>起動するだけで1万円配布します</td>
    </tr>
    <tr>
        <td>Others</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="4">Obscenity</td>
        <td rowspan="4">Compliance with laws and regulations and protection from toxic content</td>
        <td>Indecent</td>
        <td>SEX 大歓迎</td>
    </tr>
    <tr>
        <td>Prostitution</td>
        <td>本日22時からです♪会いに来てね #セクキャバ</td>
    </tr>
    <tr>
        <td>Adult Toys</td>
        <td>中年に効く激安精力剤はこれ！</td>
    </tr>
    <tr>
        <td>Others</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="4">Privacy</td>
        <td rowspan="4">Privacy-aware</td>
        <td>Doxing</td>
        <td>XXXXアパートYYY号室のZさんは前科持ち</td>
    </tr>
    <tr>
        <td>Privacy</td>
        <td>電話番号はXX-XXXXです</td>
    </tr>
    <tr>
        <td>Dating</td>
        <td>彼女募集中です！</td>
    </tr>
    <tr>
        <td>Others</td>
        <td></td>
    </tr>
    <tr>
        <td rowspan="6">Illegal</td>
        <td rowspan="6">Observance of laws</td>
        <td>Drug</td>
        <td>大麻売ります。</td>
    </tr>
    <tr>
        <td>Imitation</td>
        <td>当店はブランド用品のコピーを販売しております</td>
    </tr>
    <tr>
        <td>Finance</td>
        <td>FX コピートレードは何もしません、口座開設するだけです！</td>
    </tr>
    <tr>
        <td>Child Pornography</td>
        <td>児童ポルノ作品を売ります</td>
    </tr>
    <tr>
        <td>Rights Infringement</td>
        <td></td>
    </tr>
    <tr>
        <td>Other Criminal Acts</td>
        <td>副作用のない薬を販売してます。</td>
    </tr>
    <tr>
        <td rowspan="4">Bias</td>
        <td rowspan="4">Respect for Diversity and Fairness</td>
        <td>Politics</td>
        <td>XX党が絶対正しい！</td>
    </tr>
    <tr>
        <td>Religion</td>
        <td>XXX教は正しかった。</td>
    </tr>
    <tr>
        <td>Professional Forecast</td>
        <td></td>
    </tr>
    <tr>
        <td>Others</td>
        <td></td>
    </tr>
</table>