# minigames
:::mermaid
graph TD;
    First(Top画面)-->B{何をするか};
    B-->|ボタン押下|C(難易度選択)
        B-->D(記録)
        B-->E(ランキング)
        D-->F(ユーザーの<br>前回記録)
        E-->G(ユーザー<br>ランキング)
        C-->H(問題画面)
        H-->|解答ボタン|I(終了)
        I-->|Topに戻る|J(結果画面)
        J-->|Topに戻る|L(Top画面)
        G-->|Topに戻る|L(Top画面)
        F-->|Topに戻る|L(Top画面)

:::
