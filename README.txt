口コミ・アンケートQRシステム 更新版

【反映済み】
LINE友だち追加URL:
https://lin.ee/npg2S7P

回答フォームURL:
https://docs.google.com/forms/d/e/1FAIpQLSdnRG0Eeu9Q5OIFD3rfV1oj0PYPzopv1lt3DOuifyn30CAU0w/viewform?usp=publish-editor

【未設定】
Googleクチコミ投稿用URL:
まだ未設定です。

現在は、Google口コミボタンが「Googleクチコミは準備中」と表示されるようにしています。
Googleクチコミ投稿用URLが入手できたら、index.html の下記部分を差し替えてください。

const GOOGLE_REVIEW_URL = "";

↓ 例

const GOOGLE_REVIEW_URL = "https://g.page/r/xxxxxxxx/review";

【導線】
QRコード
↓
満足度アンケート
↓
満足した
→ Googleクチコミ ※現在は準備中
→ LINE友だち追加 5%OFF
→ ご意見・ご要望フォーム

普通
→ ご意見・ご要望フォーム
→ Googleクチコミ ※現在は準備中
→ LINE友だち追加 5%OFF

不満があった
→ 改善フォーム
→ Googleクチコミ ※現在は準備中
→ LINE友だち追加 5%OFF

【公開方法】
1. index.html をGitHub Pagesにアップロードします。
2. 公開されたURLを qr_generator.html に入力します。
3. 表示されたQRコードを保存して、店頭POPに配置します。

【Google口コミURLについて】
管理者権限がない場合でも、後日正式URLが取得できたら1行差し替えるだけで使えるようにしてあります。
