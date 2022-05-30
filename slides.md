---
theme: seriph # https://sli.dev/themes/gallery.html
title: thanks-kunp-yan-slidev
download: false
lineNumbers: true
background: https://source.unsplash.com/collection/94734566/1920x1080
class: 'text-center'
---

# Thanks kunp-yan

10000leaves

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/10000leaves/thanks-kunp-yan-slidev" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---

# thanks-kunp-yan-slidev とは?
https://thanks-kunp-yan-slidev.netlify.app/  

watanabeさんの時で味を占め、また作成しました。

Slidev というスライドツールを使用して作成しています。

<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-square.png"
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-circle.png"
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>
  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }"
>
  <p>今回も、作成するにあたり様々な方からメッセージをいただきました。</p>
  <p>ご協力していただき、ありがとうございました。</p>
</div>
---
layout: intro
class: 'text-center'
---

# 使用した技術

<Decoration />

---

# 技術一覧

<div class="grid grid-cols-[30%,70%]"><div>

- Frontend
  - Slidev
  - Vue
  - Markdown
  - CSS
- Infrastructure
  - Netlify
- Code Management
  - GitHub
- Image editing
  - draw.io
  - undraw

</div><div>
  <img src="/drawio/systemConfiguration.drawio.png"/>
</div></div>

---

# Slidev とは?

公式サイト： https://sli.dev/

Slidev は開発者向けに設計されたスライドツールです。以下の機能で構成されています。

- 📝 **Text-based** - マークダウンを使用し、スタイルを設定出来ます
- 🎨 **Themable** - npm package を使用しテーマをシェア出来ます
- 🧑‍💻 **Developer Friendly** - コードハイライト, オートコンプリートを使用したライブコーディング
- 🤹 **Interactive** - Vue コンポーネントの埋め込みで表現を強化します
- 🎥 **Recording** - ビルトインの録画とカメラビューがあります
- 📤 **Portable** - PDF へのエクスポート, PNG, ホスティング可能な SPA
- 🛠 **Hackable** - Web ページで可能なことは何でも

<br>

Read more about [Why Slidev?](https://sli.dev/guide/why)

---
layout: intro
class: 'text-center'
---

# メッセージ

<Decoration />

---

# ka-horikawa

<div>

2年半お疲れ様でした！  
フロントにバック、AI、DevOps大活躍でしたね。  
仕事ではお互いに知らないことを教え合うなどして、スキルを高めることが出来ました。  
ありがとうございました。  
閻さんは何事も意欲的に取り組むので、どこでも活躍できると思っています。中国に帰ってからの活躍も応援しています。

仕事の話はここまでにして、、、

2年半、コロナで短いようで長かったですが、日本は漫喫できましたか？  
閻さんは旅行に行った際に、どこに行って何を見たなど色々教えてくださったので、聞いていて楽しかったです。  

</div>

<div class="grid grid-cols-[70%,30%]"><div>

コロナで飲みに行ったり、ご飯に行った回数は多くはありませんでしたが、  
その分よく覚えています。  

この前行った寿司美味しかったですね。（最近笑）  
また行きm、寿司より先に大宮でしたね。  

おでん行きましょう。

</div><div>
  <twemoji-oden class="text-10xl m-0"/>
</div></div>

---

# h-sutou

<div>

閻さんお疲れ様でした。  
担当システムはもちろんのこと、OJTを担当させてもらったり二人で新しい機能を作ってみたりと、  
いろいろ一緒に仕事をさせていただきました。  
正直仕事の中では教えることよりむしろ教えてもらうことが多かったです。  
改善案も反対意見もどんどん出してくれたので、とても勉強になりましたし自分たちなりのいいものを作ってこれたと思っています。  
今後も閻さんから学んだことを活かして頑張っていこうと思います。  

一緒に仕事が出来て楽しかったです。  
二年間ありがとうございました。帰国後も楽しくお過ごし下さい！  

</div>

---

# ke-kaneko

## 閻さん!!

我々のチームに配属されてから今日までずっと、プログラム開発の第一線で活躍いただきました。  
閻さんのスキルがあったからこそ胸を張ってお受けできた案件もあり（ポートフォリオとかね！）本当に感謝しています。  
目先の作業に追われて、閻さんのやりたかったことがあまりできなかったこと残念に思います。ほんとに申し訳ない。  

<div class="grid grid-cols-[75%,25%]"><div>

閻さん自身、柔軟に考えることができるので、きっとどんな分野でも活躍できると思います。  
これはOISを代表して金子が証言します、信じてください。  

もっとたくさんお話ししたかったですね！  
最後に私の好きな音楽を押し付けます。  
CDを渡そうか。。でも最近の若い子CD聞かないし。。データ？とか色々考えた結果、  
ジャケットだけを集めて乱暴に添付することにしました。  
既に知っていたらごめんね、知らなかったら頑張って探して聴いてみてください。笑

## 再見！！

</div><div>
  <img src="/drawio/cdJacket.drawio.png"/>
</div></div>

---

<div>
  <center>
    <img src="/cdJacket.png" width="500" />
  </center>
</div>

---

# tak-sakata

<div>

コロナがなければ、もっと一緒に居られると思うと  
非常に残念です。  

コナンの話とか、ドラマの話とか、Vlogの話とか盛り上がりましたね。  

<div class="grid grid-cols-[60%,40%]"><div>

アポトキシン4869を飲んで、また日本に遊びに来てください。  
A secret makes a woman woman.  

</div><div>
  <center>
    <img src="/aptx4869.png"/>
  </center>
</div></div>


</div>

---

# ta-imai

<div>

閻さんお疲れ様です！

バックエンドの開発では、いろいろ教えてもらってとても助けられました。  
高い技術力を持った上に春日部が大好きな閻さんがいなくなるのはとても寂しいですが、  
次の会社でもその技術力とコミュ力で頑張ってください。自分も頑張ります。  

今度日本に来るときは、また駒澤君誘って東武動物公園で飲みましょう。  
今井が中国遊びに行ったら案内してください。よろしくですm(_ _)m  

  <center>
    <img src="/logo_zoo_color.svg"/>
  </center>

</div>

---

# m-wada

<div>

お疲れさまでした。

カスタマーソリューション部で当初より証券システムよりはAIを中心に担当して頂くという、  
これまでのOISではあまりない形で対応を進めて頂きましたが、持ち前のスキルも含めて  
ファクターリターン算出やポートフォリオ提案システムなど活躍頂けた部分が大きかったと思います。  

今後は帰国ということで、次の会社も未定とのことですが、開発スキルや日本語ができるなど  
能力面では秀でている部分が大きいと思いますので、今後もお体に気をつけて頑張ってください。  

</div>

---

# tos-ishikawa

<div>

お話できたのが錦糸町に行った時の  
一度だけになってしまったのは残念ですが  
とてもいい思い出になってます！  

お世話になりました！  
BS部 石川  

</div>

---

# na-murakami

<div>

2年とちょっとという短い間だったけど、ドライブしたりご飯行ったりできて楽しかったです！

正直めちゃくちゃ寂しいですが、中国に帰っても閻さんらしく元気に頑張ってください。

日本に遊びに来たときは絶対連絡してね。また駒澤くんとの面白コンビが見られるのを楽しみにしてます。

我等友情永久不滅！！！！！！  
あ、お酒とタバコはほどほどにしてください。  

村上より

</div>

---

# m-iduka

<div>

閻さん

閻さんが帰国してしまうなんて…  
いまだにドッキリだといいな〜と思っています😂  

新人研修から始まり普段の生活でも閻さんにはとてもお世話になりました…ありがとう！💐  
面倒見のいい閻さんなら素敵な野原ひろしになれると思います。  
中国で頑張ってみさえゲットしてね！  

日本に遊びにくるときは連絡ください  
またみんなですみ屋いこうね〜！🐄  

井塚 未波

</div>

---

# y-inagi

<div>

2年間おつかれさまでした  

閻さんは2G内でよく先輩方から質問されているところを見かけるので、  
すごいなと思って見ていました  

コロナのせいであまり飲みに行けなかったことが残念です  
同期が辞めるのはさみしいですが中国でも頑張ってください！  

</div>

<br/>

# g-komazawa

<div>

プライベート、仕事中よく一緒にいたね！  
中国帰っても色々とがんばってください。  
今度、中国に行くことがあったら色んなところ紹介してね！  

また会う日前まで

</div>
