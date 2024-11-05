# 吸血鬼生存猪
## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
* 主人公キャラクターをマウス操作により敵をにするゲームで，．．．
* 参考URL：[サイトタイトル](https://www.〇〇.com/)

## ゲームの遊び方
* 次々と現れる敵を避けながら戦い、強力な攻撃アイテムや特殊なスキルを獲得してキャラクターを強化
* 最終的に画面を埋め尽くすほどの敵を倒していく

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクターの描画
* プレイヤーのレベルアップ時に、強化するスキルを選択する画面表示

### 分担追加機能
* ステージ移動：移動方向とマウスの座標取得でキャラクターの移動
* 攻撃パターン：全キャラクターの攻撃方法とターゲットの決定
* スキル画面：どんなスキルを追加するのか、マウス押下でスキル選択できるUI画面
* レベルアップ：敵を倒した時に、その敵の種類に応じて経験値を決定
* 背景の表示：連続画像を100×100で表示

### ToDo
- [ ] 
- [ ] 

### メモ
* クラス内の変数は，すべて「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある
