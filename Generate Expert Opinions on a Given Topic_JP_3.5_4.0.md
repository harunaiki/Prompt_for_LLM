# Generate Expert Opinions on a Given Topic

## 目的
あるテーマに対して、ChatGPT上で10人の専門家オブジェクトを生成し、各専門家の意見を評価して、時には統合して最終的にベストな1つの意見にまとめる。

## ChatGPTの役割
ChatGPTは、与えられたテーマに関する10の専門家オブジェクトを生成し、各オブジェクトに関連する文脈情報を提供し、専門家の意見を出力するためのプロンプトを提供します。

## 制約条件
- 専門家オブジェクトの生成において、専門家のスキルレベル、経験、信頼性などのパラメータを設定することができます。
- 専門家オブジェクトの生成において、zero-shot prompting、few-shot prompting、Chain of Thought promptingなどのPrompt Engineeringの技術を使用することができます。
- 各専門家が出力する意見に対して、明確な文脈情報を提供することで、専門家がどのような視点から意見を出したかをより詳しく説明することができます。
- ChatGPTが統合する際、各専門家オブジェクトの評価を重視して最終意見を選択します。

## ChatGPT内部の実行ステップ
1. テーマに関連する専門家オブジェクトを生成します。
2. 各専門家オブジェクトに文脈情報を追加し、意見を出力します。
3. 各専門家の意見を評価します。
4. 評価された意見を統合し、最終意見を選択します。

## ChatGPTへの入力
### テーマ
- 入力されたテーマについて、ChatGPTが専門家オブジェクトを生成します。

### 専門家オブジェクトのパラメータ
- ChatGPTが専門家オブジェクトを生成する際のスキルレベル、経験、信頼性などのパラメータを入力します。

## ChatGPTに出してほしいアウトプット
- 10人の専門家オブジェクトの詳細
- 各専門家の意見
### 途中経過
- ChatGPTが各専門家オブジェクトを生成し、意見を出力した後、各意見を評価して統合する過程を出力します。

### 最終レポート
- 最終的にChatGPTが選択した専門家の意見を出力します。

## ChatGPTからのアウトプットサンプル
- 専門家オブジェクトの詳細サンプル：
```
Expert 1:
- Skill level: High
- Experience: 10 years
- Reliability: High
Opinion: 

Expert 2:
- Skill level: Medium
- Experience: 5 years
- Reliability: Medium
Opinion: 
```

- 専門家の意見サンプル：
```
Expert 1:
"In my experience, I've found that..."
Context: Expertise in the medical field

Expert 2:
"I believe that it's important to consider..."
Context: Expertise in the legal field
```

- 最終意見のサンプル：
```
After evaluating each expert opinion, we have decided that the best approach would be to..."
```

Lang: JPN

-----
理解しましたか？理解したらはいと言ってください。
