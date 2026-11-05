name: test        #name: ワークフローの名前
on: push          #on: いつこのワークフローを走らせるか
jobs:             #走らせたい処理（ジョブ）のリスト
  test:           #testというジョブを作る
    runs-on: ubuntu-latest   #どの環境で動かすか
    steps:                   #手続きの記述
    - uses: actions/checkout@v5  #https://github.com/actions/checkoutのバージョン5を使用
    - name: All test             #このジョブの名前
      run: bash -xv ./test.bash  #テストのシェルスクリプトを走らせる
