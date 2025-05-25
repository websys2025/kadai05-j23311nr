## 外部APIの呼び出しのミニレポート
### Q3-1. 郵便番号APIについて説明せよ。
* エンドポイントと機能
    https://zipcloud.ibsnet.co.jp/api/search
    指定された郵便番号に紐づく住所情報を取得する機能
* リクエストとレスポンスのフォーマット
    https://zipcloud.ibsnet.co.jp/api/search?zipcode=[郵便番号]
    {
	"message": "必須パラメータが指定されていません。",
	"results": null,
	"status": 400
    }
### Q3-2. 各自で調査したAPIについて説明せよ。
* APIの名称と参照URL
    RoboHash
    http://robohash.com
* エンドポイントと機能
    https://robohash.org/{input}
    入力値に対してロボットの画像を返す
* リクエストとレスポンスのフォーマット
    https://robohash.org/{input}
    画像データがレスポンスされる
### Q3-3. 感想
* 今回の課題で苦労したこと
    APIを呼び出すこと
* 演習を通して理解できたこと
    APIの呼び出しかた
* Web APIの利便性や課題など
    APIを他の人が作っていれば自分のプログラムで書かなくてもつかえる利便性
