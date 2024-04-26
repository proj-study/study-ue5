# 1
ThirdPersonTemplateで始める.  
プレイヤーの制御はBP_ThirdPersonCharacterがほぼ答えなので参考程度に.  
c++ or BP慣れている方で

## 0. log
  - ゲーム画面上に文字列を表示する(表示時間、位置、文字色の指定も)
  - コンソールにログを表示する(log, info, warn, error)
## 1. UE system
  - character, actor, pawn, objectなど、それぞれの特徴と使い分けを知る
  - gameModeの概念
  - gameMode, gameState, PlayerControllerなどの理解と、指定方法
  - actorのスポーン方法
## 2. ユーザー入力
  - 直接keyCodeで入力を受け付ける.
  - start, finished, cancelなどがいつ呼ばれるかをそれぞれ把握する
  - enhanced inputを使って入力を制御する(unityでいうinputsystem)
