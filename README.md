# flexbox-gird-sample
flexboxを使ってグリッドレイアウトをするサンプルです。  
レスポンシブ対応として、横幅が768px未満の場合は全体を1カラムで表示します。

## Usage

次のようにして使います。

    <div class="container">
      <div class="row">
        <div class="col-4">
          <div class="content"></div>
        </div>
        <div class="col-8">
          <div class="content"></div>
        </div>
      </div>
      <div class="row">
        <div class="col-3">
          <div class="content"></div>
        </div>
        <div class="col-4">
          <div class="content"></div>
        </div>
        <div class="col-5">
          <div class="content"></div>
        </div>
      </div>
    </div>

※ 幅は12等分した内のどれぐらい使うかを `col-*` で指定します。

`pad` を付けると各コンテンツの間に20pxの余白が作られます。(参考: [demo.html](http://code.rlated.net/flexbox/demo.html))

    <div class="container pad">
      <div class="row">
        <div class="col-4">
          <div class="content"></div>
        </div>
        <div class="col-8">
          <div class="content"></div>
        </div>
      </div>
    </div>

## Demos

- [flexbox-grid-sample.cssを使ったデモ](http://code.rlated.net/flexbox/demo.html)
- [flexbox-grid-sample.cssを使った3カラムレイアウトのデモ](http://code.rlated.net/flexbox/demo-3column.html)

## License

- MIT license

- - -
ホームページの作り方  
<http://rlated.net/>
