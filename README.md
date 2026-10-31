<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>【一口1万円〜】最先端の創造力を、社会の火種に。｜UNLEARNING PORTLAND クラウドファンディング</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@600;800;900&family=Zen+Kaku+Gothic+New:wght@500;700;900&family=Syne:wght@700;800&display=swap" rel="stylesheet">
<style>
  :root {
    /* プロのUI/UXデザイナーが使用する「スマート＆インパクト」カラーパレット */
    --primary: #0F172A;       /* ディープスレート（知的で重厚なメインカラー） */
    --accent-orange: hsl(0, 97%, 58%); /* テラコッタ・ポートランドオレンジ（火種と情熱） */
    --accent-teal: #0dd906d5;   /* ディープティール（探求と持続可能性） */
    --accent-gold: #0dd906d5;   /* ウォームアンバー（上質なトーン） */
    --cream: #F8F9FA;        /* クリーンなオフホワイト */
    --charcoal: #4c4c4c;      /* 引き締め用スレート */
    --white: #ffffff;
    
    /* 互換用変数マッピング */
    --lime: hsl(0, 97%, 58%);
    --orange: ##0dd906d5;
    --cobalt: #4c4c4c;
    --magenta: #d91806;
    
    --border-dark: 2px solid #0F172A;
    --shadow-pop: 4px 4px 0px #0F172A;
    --shadow-pop-lg: 6px 6px 0px #0F172A;
  }

  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'Zen Kaku Gothic New', -apple-system, BlinkMacSystemFont, sans-serif;
    background-color: var(--cream);
    color: var(--charcoal);
    line-height: 1.7;
    overflow-x: hidden;
  }

  /* Layout Utility */
  .container { max-width: 1080px; margin: 0 auto; padding: 0 24px; }
  .tag {
    display: inline-block;
    background: var(--accent-orange);
    color: #fff;
    border: var(--border-dark);
    box-shadow: 3px 3px 0px var(--primary);
    font-size: 13px;
    font-weight: 900;
    letter-spacing: 0.06em;
    padding: 6px 16px;
    text-transform: uppercase;
    transform: rotate(-1deg);
  }
  .tag.orange { background: var(--accent-teal); color: #fff; }
  .tag.blue { background: var(--primary); color: #fff; }
  .tag.magenta { background: var(--accent-gold); color: #fff; }

  /* Hero Section */
  header.hero {
    background: var(--primary);
    border-bottom: var(--border-dark);
    color: #fff;
    padding: 90px 0 80px;
    position: relative;
    overflow: hidden;
  }
  .hero-grid {
    display: grid;
    grid-template-columns: 1.2fr 0.8fr;
    gap: 40px;
    align-items: center;
  }
  .hero-title {
    font-family: 'Syne', 'Zen Kaku Gothic New', sans-serif;
    font-size: clamp(32px, 5vw, 56px);
    font-weight: 900;
    line-height: 1.15;
    color: #fff;
    margin: 20px 0 24px;
    text-transform: uppercase;
    letter-spacing: -0.02em;
  }
  .hero-title span {
    background: var(--accent-orange);
    color: #fff;
    padding: 0 10px;
    display: inline-block;
    box-shadow: 4px 4px 0px var(--accent-gold);
  }
  .hero-lead {
    font-size: 16px;
    font-weight: 700;
    line-height: 1.8;
    background: rgba(255, 255, 255, 0.08);
    padding: 20px;
    border: 1px solid rgba(255,255,255,0.2);
    border-radius: 8px;
    margin-bottom: 28px;
  }
  .hero-meta-badges {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
  }
  .meta-badge {
    background: var(--white);
    color: var(--primary);
    border: var(--border-dark);
    box-shadow: var(--shadow-pop);
    padding: 8px 16px;
    font-weight: 900;
    font-size: 14px;
  }
  .hero-img-box {
    position: relative;
  }
  .hero-img {
    width: 100%;
    height: 380px;
    object-fit: cover;
    border: var(--border-dark);
    box-shadow: var(--shadow-pop-lg);
    border-radius: 12px;
    transform: rotate(1.5deg);
  }
  .hero-sticker {
    position: absolute;
    bottom: -15px;
    left: -15px;
    background: var(--accent-teal);
    color: #fff;
    border: var(--border-dark);
    box-shadow: 4px 4px 0 var(--primary);
    padding: 12px 20px;
    font-weight: 900;
    font-size: 16px;
    transform: rotate(-3deg);
  }

  /* Marquee */
  .marquee {
    background: var(--accent-orange);
    border-bottom: var(--border-dark);
    padding: 12px 0;
    overflow: hidden;
    white-space: nowrap;
    display: flex;
  }
  .marquee-content {
    display: inline-block;
    font-family: 'Outfit', sans-serif;
    font-size: 18px;
    font-weight: 900;
    color: #fff;
    letter-spacing: 0.1em;
    animation: scrollText 22s linear infinite;
  }
  @keyframes scrollText {
    from { transform: translateX(0%); }
    to { transform: translateX(-50%); }
  }

  /* Section Common */
  section { padding: 80px 0; border-bottom: var(--border-dark); }
  .sec-header {
    text-align: center;
    margin-bottom: 50px;
  }
  .sec-title {
    font-size: clamp(28px, 4vw, 42px);
    font-weight: 900;
    letter-spacing: -0.02em;
    margin-top: 10px;
    color: var(--primary);
  }

  /* Pop Cards */
  .grid-3 { display: grid; grid-template-columns: repeat(3, 1fr); gap: 24px; }
  .grid-2 { display: grid; grid-template-columns: repeat(2, 1fr); gap: 28px; }
  .pop-card {
    background: var(--white);
    border: var(--border-dark);
    box-shadow: var(--shadow-pop);
    border-radius: 12px;
    padding: 30px 24px;
    position: relative;
    transition: transform 0.15s ease;
  }
  .pop-card:hover {
    transform: translate(-3px, -3px);
    box-shadow: var(--shadow-pop-lg);
  }

  /* Visual Photo Section */
  .photo-card {
    background: var(--white);
    border: var(--border-dark);
    box-shadow: var(--shadow-pop);
    border-radius: 12px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
  }
  .photo-wrap {
    width: 100%;
    height: 240px;
    overflow: hidden;
    position: relative;
    border-bottom: var(--border-dark);
  }
  .photo-wrap img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.4s ease;
  }
  .photo-card:hover .photo-wrap img {
    transform: scale(1.05);
  }
  .photo-body {
    padding: 24px;
    flex: 1;
    display: flex;
    flex-direction: column;
  }
  .photo-badge {
    align-self: flex-start;
    background: var(--primary);
    color: #fff;
    font-size: 11px;
    font-weight: 900;
    padding: 3px 8px;
    margin-bottom: 10px;
    border-radius: 3px;
  }

  /* Impact Box */
  .impact-box {
    background: var(--accent-teal);
    color: #fff;
    border: var(--border-dark);
    box-shadow: var(--shadow-pop-lg);
    border-radius: 14px;
    padding: 40px;
    margin: 40px 0;
  }
  .impact-grid {
    display: grid;
    grid-template-columns: 1.2fr 1fr;
    gap: 30px;
    align-items: center;
  }

  /* Timeline */
  .timeline-step {
    display: flex;
    gap: 20px;
    margin-bottom: 20px;
    background: var(--white);
    border: var(--border-dark);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 4px 4px 0 var(--primary);
    align-items: center;
  }
  .step-date {
    font-family: 'Outfit', sans-serif;
    font-size: 18px;
    font-weight: 900;
    background: var(--primary);
    color: #fff;
    padding: 8px 14px;
    border-radius: 6px;
    flex-shrink: 0;
  }

  /* Return & Plan Box */
  .return-card {
    background: var(--white);
    border: var(--border-dark);
    box-shadow: var(--shadow-pop-lg);
    border-radius: 12px;
    padding: 32px;
    margin-bottom: 24px;
  }
  .return-price {
    font-family: 'Outfit', sans-serif;
    font-size: 36px;
    font-weight: 900;
    color: var(--accent-orange);
    margin-bottom: 12px;
  }

  /* CTA Button & Bank Info */
  .cta-block {
    background: var(--primary);
    color: #fff;
    text-align: center;
    padding: 80px 24px;
    border-top: var(--border-dark);
    position: relative;
  }
  .bank-box {
    background: var(--white);
    color: var(--charcoal);
    border: var(--border-dark);
    box-shadow: 6px 6px 0 var(--accent-gold);
    border-radius: 12px;
    padding: 28px;
    max-width: 640px;
    margin: 30px auto;
    text-align: left;
  }
  .btn-entry {
    display: inline-block;
    background: var(--accent-orange);
    color: #fff;
    font-size: 22px;
    font-weight: 900;
    text-decoration: none;
    padding: 20px 40px;
    border: var(--border-dark);
    box-shadow: 6px 6px 0 var(--accent-gold);
    border-radius: 12px;
    margin-top: 16px;
    transition: all 0.15s ease;
    cursor: pointer;
  }
  .btn-entry:hover {
    transform: translate(-3px, -3px);
    box-shadow: 9px 9px 0 var(--accent-gold);
    background: #c84428;
  }

  @media (max-width: 860px) {
    .hero-grid, .grid-3, .grid-2, .impact-grid { grid-template-columns: 1fr; }
    .hero-img { height: 260px; }
  }
</style>
</head>
<body>

<!-- Hero Header -->
<header class="hero">
  <div class="container">
    <div class="hero-grid">
      <div>
        <div class="tag">クラファン挑戦中｜1口1万円から応援募集</div>
        <h1 class="hero-title">
          最先端の創造力を、<br>
        　若者の未来へ。<br>
          <span>UNLEARNING PORTLAND</span>
        </h1>
        <p class="hero-lead">
          世界が注目するクリエイティブ都市・ポートランドへ。<br>
          東北芸術工科大学の学生有志6名が現地リサーチを敢行し、得られた知見と熱量を地域社会へ還元するエコシステムをつくります！
        </p>
        <div class="hero-meta-badges">
          <div class="meta-badge"> 渡航：2027年2月下旬〜3月上旬（5泊7日）</div>
          <div class="meta-badge" style="background: var(--accent-gold); color: #fff;"> 目標金額：80万円（1口 10,000円〜）</div>
          <div class="meta-badge">成果還元：ZINE100部発行＆報告会開催</div>
        </div>
      </div>
      <div class="hero-img-box">
        <img class="hero-img" src="https://images.unsplash.com/photo-1502175353174-a7a70e73b362?auto=format&fit=crop&w=1000&q=80" alt="Portland Oregon USA Cityscape">
        <div class="hero-sticker">SUPPORT OUR VISION!</div>
      </div>
    </div>
  </div>
</header>

<!-- Marquee Strip -->
<div class="marquee">
  <div class="marquee-content">
    SUPPORT UNLEARNING PORTLAND ★ CROWDFUNDING ★ 1口10,000円 ★ SUPPORT YOUNG CREATORS ★ PORTLAND RESEARCH 2027 ★ COMMUNITY DESIGN ★ SUSTAINABLE ARCHITECTURE ★
    SUPPORT UNLEARNING PORTLAND ★ CROWDFUNDING ★ 1口10,000円 ★ SUPPORT YOUNG CREATORS ★ PORTLAND RESEARCH 2027 ★ COMMUNITY DESIGN ★ SUSTAINABLE ARCHITECTURE ★
  </div>
</div>

<div class="container">

  <!-- マニフェスト -->
  <section>
    <div class="sec-header">
      <div class="tag orange">MANIFESTO</div>
      <h2 class="sec-title">マニフェスト</h2>
      <p style="font-size: 24px; color: var(--accent-orange); margin-top: 15px; font-weight: 900;">私たちは、この世界の火種となれるだろうか。</p>
    </div>
    <div style="max-width: 800px; margin: 0 auto; font-size: 16px; line-height: 2;">
      本プロジェクト「UNLEARNING PORTLAND」は、東北芸術工科大学の多岐にわたる専門分野を持つ学生5名を公募選抜し、米国ポートランドでの一週間の滞在を通してその知見を地域社会に還元するプロジェクトです。<br><br>


このプロジェクト発足に至ったきっかけは、私自身が4年間オーストラリア タスマニア島での正規留学を経験し、そこでの体験が今の私の目標や夢の根幹になっているところから始まります。私は留学当初英語が思ったように上達せず、言語の壁によって人と人の間に大きな隔たりを感じていました。どう頑張っても私の伝えたいことは伝わらず、自分のことは自分として理解されない。<br>
その経験から私は非言語的なコミュニケーションとしてのアートに興味を持ち始めました。アートの場を創ることで、どんな感じ方、世界の捉え方をしていてもあなたは美しいという世界を表現したいと思っています。そこから私は現在の美術大学を進路に選び、「対話を生み出すアートの場を創る」という私の根幹となる情熱が芽生えました。<br><br>

そんな私の経験から、若者の主体性はその個人の特異な体験から生まれるのではないかと考えています。<br>

しかし、現代においてその個人の特異な体験の機会は多くにとって狭まっています。私はその課題を、山形の大学に行ったことで目の当たりにしました。<br>

それは主に二つの理由があり、経済・機会格差の広がりと情報の安易な取得にあります。<br><br>

物価高や円安によって資本は都市圏に集中し、地方の若者にとっては東京に行くことさえ難しい人もいます。海外、特に西洋圏に行くことのハードルは、かつての１ドル100円程度の時代とは全く違うと言えるでしょう。<br>
私の大学は私立ですが、奨学金で生活している人、最低賃金で働き毎晩深夜にバイトから帰ってくる生活を繰り返している人ばかりで、彼らにとって学生の間に海外に行くなど夢物語のように感じられるといっても過言ではないようです。<br>
その事実を目の当たりにして、恵まれた環境にいた自分自身を省みると同時に、挑戦したくても機会に恵まれない仲間たちの現状に強い歯がゆさを感じました。だからこそ、ただ現状を嘆くのではなく、自らの手で挑戦の機会を作り出し、共に世界へ飛び出す仕組みを作りたいと決意しました。<br><br>

二つ目の理由である情報の安易な取得においては、AIの台頭やSNSが身近になっている現代において、私たちはその答えを知るだけで体験した気になってしまうということが課題です。「ポートランド」と検索すればいくらでもブログや街並みの写真、都市の特徴などの情報を得ることができます。「へー、ポートランドってこんなところなんだ」と、誰もが画面越しに知った気になれてしまうのです。<br>
この事実は、私たちクリエイティブ大学の学生にとっては特に大きな隠れた損失であると考えます。私たちがどんな分野を学んでいるにせよ、いくら画面上の情報を見て知った気になっても、それは私たちの新たな発見や私たちの創造性、イノベーションには繋がらないからです。事実として出力されるその情報を答えとして受け取って、誰がそこから誰も予想だにしなかったアイデアを生み出せるのでしょうか？クリエイティビティとは、自身の体験とその個人の独自の視点や発見、つまり「見てみなくちゃわからない」精神から生まれると私は思うのです。<br><br>

今回のプロジェクトで13名の応募から選抜した５名も、みんなそれぞれが確かな問いや専門分野、そして純粋な「見てみたい」というワクワク感を持っています。そして彼らは副リーダーを除いてほとんどか全く海外渡航経験がありません。<br>
例えば、建築環境デザインを学ぶメンバーの一人は、多くの建築が外側だけを設計し、そこで生まれるコミュニティや持続可能性について考えない姿勢に違和感を持っていると言っていました。ただ外側の綺麗なデザインを考えるだけではなく、ソフトな面までを包括して考えられる建築デザインができる人になりたいとのこと。ポートランドは、世界初のLEED認証という厳格なサステナブル建築の基準を満たしたリノベーション商業施設があったり、空き倉庫街をアーティストの居住区としてクリエイティブ都市を形成していったという歴史があります。ハードとソフトの両面から街全体をクリエイティブに組み上げてきたポートランドでの体験は、彼女の建築観を大きく広げる絶好の機会になると確信しています。<br>
他のメンバーも含めて、私はこの渡航をただの楽しい旅行ではなく、彼らと繋がっていく社会の可能性が最大限開かれるものにするために厳正な選抜を行い、彼らを信頼しています。<br><br>

現代社会は、若者の創造性を要求しています。<br>
人口減少や環境問題、広がっていく格差。個人ではどうしようもないと無力感にかられるこの社会において、唯一の希望は誰かのそれでも新しい火種を社会に生み出したいと感じるその主体性と彼らの新しいアイデアです。<br>
若者一人一人の社会に対する責任が重くなることが確定しているこの日本社会において、これからの社会のクリエイティブを担うべくして美術大学に通っている私たちは、「見てみなくちゃわからない」を最大化する必要性があります。<br>
学生時代にそのワクワク感という原動力を特異な体験に変え、新たな発見をし、社会にとっての新しい可能性を芽吹かせる。そして、その姿勢はきっと、私たちが大人になり、次世代を培っていく時にまた彼らへの希望として手渡せる。<br>

世界一周とか、大それたことじゃなくていいのです。たった一週間、みなさんからの応援を糧にしてクリエイティブ先端都市と言われるポートランドに行き、思う存分みたことのないものを見る。そして、これをどう持ち帰り、自分の創造性を使って料理しようかとみんなで考えてみる。報告会やZINEの制作によって、しっかりとステークホルダーの記憶と記録に残る形でこのプロジェクトも発信し、残していきます。これらのアウトプットも、メンバー全員の専門分野を最大限活かし、クリエイティブ大学の学生としてしっかりと質の高いものにします。<br>
彼らのたった一回の大学生時代に、こうして海外に行き、その体験を社会に共有する体験は、どれほど今後の可能性に繋がっていくでしょうか。<br><br>

これを読んでくださっているみなさんは、次の世代にどんな未来や希望を渡したいと考えていらっしゃるでしょうか。<br>
その大きな力と愛を、私たちに少しだけ、分けて欲しいのです。<br>
私たちは、若者として、この世界の火種となり、これからもずっとこの世界に生まれてくる人々がワクワクと共に生きられる社会のために学びたい。<br>
たった一人の特異な体験から生まれる新しい視点と創造性が、どこまでこれからの社会を豊かにしうるのか、探求してみたい。<br><br>

そのために、私たちはまず、ポートランドに行き、それを小さくてもしっかりと社会に還元するまでの循環を起こしたいのです。<br>
ぜひ、あなたの力を貸してください。<br>
    </div>
  </section>

  <!-- 課題意識：なぜ若者に体験が必要なのか -->
  <section>
    <div class="sec-header">
      <div class="tag magenta">WHY WE NEED THIS</div>
      <h2 class="sec-title">私たちが直面している2つの課題</h2>
      <p style="font-size: 15px; color: #555; margin-top: 8px;">受け身の時代を打破し、若者の創造性を地域へ循環させるために。</p>
    </div>

    <div class="grid-2">
      <div class="pop-card">
        <div style="font-size: 14px; font-weight: 900; color: var(--accent-gold); margin-bottom: 6px;">課題 01</div>
        <h3 style="font-size: 20px; font-weight: 900; margin-bottom: 12px;">経済・機会格差と「海外体験」の激減</h3>
        <p style="font-size: 14px; color: #444;">
          物価高や円安、ネットで体験した気になれる環境により、20代の出国者数はピーク時（1996年）比で<strong>53%減少</strong>。20代の約60%が海外未経験という現実があります。創造性を育む根幹である「海外での直接的な原体験」が得にくくなっています。
        </p>
      </div>
      <div class="pop-card">
        <div style="font-size: 14px; font-weight: 900; color: var(--accent-gold); margin-bottom: 6px;">課題 02</div>
        <h3 style="font-size: 20px; font-weight: 900; margin-bottom: 12px;">正解主義と受け身な姿勢の定着</h3>
        <p style="font-size: 14px; color: #444;">
          気候変動や人口減少など答えのない大きな課題に直面する中で、就活の早期化や情報の氾濫により若者の保守化が進んでいます。既存の構造を問い直し、自ら新しい変化を起こす「主体性・創造性」を育む場の創出が急務です。
        </p>
      </div>
    </div>
  </section>

  <!-- なぜポートランドなのか？ 3つの探求軸 -->
  <section>
    <div class="sec-header">
      <div class="tag orange">WHY PORTLAND?</div>
      <h2 class="sec-title">ポートランドに学ぶ「3つの探求軸」</h2>
      <p style="font-size: 15px; color: #555; margin-top: 8px;">山形・東北の課題解決へと接続する実践的リサーチテーマ。</p>
    </div>

    <div class="grid-3">
      <div class="pop-card">
        <div style="font-size: 36px; margin-bottom: 12px;">🎨</div>
        <div style="font-size: 12px; font-weight: 900; color: var(--accent-teal); margin-bottom: 4px;">クラフト × 伝統工芸</div>
        <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 10px;">クリエイティブ経済の循環</h3>
        <p style="font-size: 13.5px; color: #444;">
          個人の作り手が自立し、地域内でお金が循環するマーケット（サタデーマーケット）やDIY出版・コミューン拠点（IPRC）のエコシステムを解剖します。
        </p>
      </div>
      <div class="pop-card">
        <div style="font-size: 36px; margin-bottom: 12px;">🤝</div>
        <div style="font-size: 12px; font-weight: 900; color: var(--accent-teal); margin-bottom: 4px;">市民自治 × 相互扶助</div>
        <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 10px;">住民主体の自治・まちづくり</h3>
        <p style="font-size: 13.5px; color: #444;">
          市民が「街の共作者」として機能する仕組み。流域評議会や地域芸術文化評議会など、草の根団体が行政や地域社会に強い影響力を持つ自治の形を探求。
        </p>
      </div>
      <div class="pop-card">
        <div style="font-size: 36px; margin-bottom: 12px;">🌱</div>
        <div style="font-size: 12px; font-weight: 900; color: var(--accent-teal); margin-bottom: 4px;">倉庫再生 × 遊休不動産</div>
        <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 10px;">空間・資源の再生循環</h3>
        <p style="font-size: 13.5px; color: #444;">
          築100年を超える倉庫を最先端の環境共生型オフィスへ変貌させたパール地区やエコトラストビル等、建築とコミュニティのリノベーション実践を体感。
        </p>
      </div>
    </div>
  </section>

  <!-- 現地視察スポット -->
  <section>
    <div class="sec-header">
      <div class="tag blue">FIELDWORK SITES</div>
      <h2 class="sec-title">五感をフル稼働させるリサーチ拠点（候補）</h2>
    </div>

    <div class="grid-2">
      <!-- Spot 1 -->
      <div class="photo-card">
        <div class="photo-wrap">
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEh8QNJQqWfEohtCw3PbSjC7UsfHY65jAPX5Il0kNwrAEHE1qHJMeWUNvwzceK6KMt3sQcdNCmjf67ItvQ4OuE_uT6FqcJjKPzwkvBo5f83sCr_gd2otoOeX8fcn-tP46_atK_FtZsE5HOgi/s960/IMG_4248.jpg" alt="Pearl District Warehouse Renovation">
        </div>
        <div class="photo-body">
          <div class="photo-badge">建築・環境 / 空間再生</div>
          <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 6px;">エコトラスト・ビル ＆ パール地区</h3>
          <p style="font-size: 13px; color: #555;">
            1895年の倉庫をLEEDゴールド認証の環境配慮型建築へリノベーション。社会的企業が集まり経済が回り続ける空間再生の実態を調査！
          </p>
        </div>
      </div>

      <!-- Spot 2 -->
      <div class="photo-card">
        <div class="photo-wrap">
          <img src="https://res.cloudinary.com/dragonspell/images/w_1440,h_864,c_fill,dpr_auto,fl_progressive:steep,f_auto/w_1440,h_864/v1634240655/www.travelportland.com/cropped-PSU_FarmersMarket_Leah-Nash/cropped-PSU_FarmersMarket_Leah-Nash.jpg" alt="Outdoor Craft Market">
        </div>
        <div class="photo-body">
          <div class="photo-badge">企画構想 / コミュニティ</div>
          <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 6px;">ポートランド・サタデー・マーケット</h3>
          <p style="font-size: 13px; color: #555;">
            全米最長級の常設アウトドアマーケット。個人クラフト作家が継続して収益を生み出せる出店エコシステムの秘密に迫る！
          </p>
        </div>
      </div>

      <!-- Spot 3 -->
      <div class="photo-card">
        <div class="photo-wrap">
          <img src="https://images.unsplash.com/photo-1547890316-3bb90edb9004?q=80&w=870&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Street Art and Murals">
        </div>
        <div class="photo-body">
          <div class="photo-badge">美術 / パブリックアート</div>
          <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 6px;">アルバータ・アート地区 ＆ 壁画群</h3>
          <p style="font-size: 13px; color: #555;">
            ストリートがアートの介入でどう再生したのか？合法的な壁画カルチャーと地域コミュニティの共存を体感！
          </p>
        </div>
      </div>

      <!-- Spot 4 -->
      <div class="photo-card">
        <div class="photo-wrap">
          <img src="https://assets.st-note.com/production/uploads/images/195054/picture_pc_c80d857a6771486bd499d7d51ac95a83.jpg?width=2000&height=2000&fit=bounds&quality=85" alt="Independent Bookstore and Zine Culture">
        </div>
        <div class="photo-body">
          <div class="photo-badge">グラフィック / 出版</div>
          <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 6px;">IPRC ＆ パウエルズ・ブックス</h3>
          <p style="font-size: 13px; color: #555;">
            リソグラフや活版印刷の共有工房「IPRC」でDIY出版文化を直撃！ 帰国後に制作するリサーチZINEのインスピレーション源に。
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- 地域還元と支援リターン -->
  <section>
    <div class="sec-header">
      <div class="tag magenta">RETURN & OUTCOME</div>
      <h2 class="sec-title">学びを地域へ還元するリターン</h2>
      <p style="font-size: 15px; color: #555; margin-top: 8px;">一回限りの渡航で終わらせず、成果を形にして皆様にお届けします。</p>
    </div>

    <div class="return-card">
      <div class="return-price">一口 10,000円〜 <span style="font-size: 16px; color: #555; font-weight: bold;">（複数口のご支援も大歓迎です！）</span></div>
      <h3 style="font-size: 22px; font-weight: 900; margin-bottom: 16px;">ご支援者様への4つの還元・お礼</h3>
      <ul style="font-size: 15px; line-height: 2; padding-left: 20px; color: #333;">
        <li><strong>① 学生特製「ポートランド・リサーチZINE」（100部限定発行・実物提供）</strong><br>各専門分野（企画・建築・デザイン・美術）の視点を網羅したコラムや現地インタビューを掲載したレポート冊子をお届け。</li>
        <li><strong>② リサーチZINE ＆ 報告会エンドロールにお名前クレジット掲載</strong><br>感謝を込めて、ご支援いただいた個人様・企業様のお名前（ロゴ）を掲載いたします。</li>
        <li><strong>③ 現地からのデジタルリサーチNote配信</strong><br>渡航期間中、現地での生の気づきや写真をメールマガジン形式でお届けします。</li>
      </ul>
    </div>
  </section>

  <!-- 収支計画 & ガバナンス -->
  <section>
    <div class="sec-header">
      <div class="tag">BUDGET & TRANSPARENCY</div>
      <h2 class="sec-title">収支計画・ガバナンス体制</h2>
    </div>

    <div class="grid-2">
      <div class="pop-card">
        <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 14px;">収支計画（6名分）</h3>
        <p style="font-size: 13.5px; color: #333; margin-bottom: 10px;">
          渡航コスト総額：<strong>1,424,000円</strong><br>
          うち自己負担額：<strong>660,000円</strong>（1人あたり11万円）<br>
          <span style="color: var(--accent-orange); font-weight: bold;">クラファン・企業協賛目標：800,000円</span>
        </p>
        <div style="font-size: 12.5px; background: var(--cream); padding: 12px; border-radius: 6px; border: 1px solid var(--primary);">
          ・往復航空券：810,000円<br>
          ・滞在費（Airbnb 5泊自炊）：200,000円<br>
          ・現地食費：150,000円<br>
          ・保険・通信費・予備費等：264,000円
        </div>
      </div>

      <div class="pop-card">
        <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 14px;">🛡️ 安心のガバナンス体制</h3>
        <ul style="font-size: 13px; padding-left: 16px; line-height: 1.8; color: #333;">
          <li><strong>専用口座運用：</strong>私的入出金を遮断した「プロジェクト専用口座」で厳格管理。</li>
          <li><strong>明細開示：</strong>教員アドバイザーへの定期収支報告および明細常時開示。</li>
          <li><strong>安全管理：</strong>全員海外保険加入、外務省たびレジ登録、夜間単独行動禁止。</li>
          <li><strong>返金保証：</strong>達成率70%未満でプロジェクト中止となった場合は、迅速に全額返金手続きを行います。</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- 企画者・チーム紹介 -->
  <section>
    <div class="sec-header">
      <div class="tag orange">TEAM & PROFILE</div>
      <h2 class="sec-title">プロジェクトチーム紹介</h2>
    </div>

    <div class="impact-box" style="background: #fff; color: var(--charcoal); border: 2px solid var(--primary);">
      <div class="impact-grid">
        <div>
          <div class="tag blue" style="margin-bottom: 12px;">代表責任者 / 全体統括</div>
          <h3 style="font-size: 26px; font-weight: 900; margin-bottom: 6px;">中土井 陽太</h3>
          <p style="font-size: 13px; font-weight: 700; color: #555; margin-bottom: 12px;">東北芸術工科大学 企画構想学科2年</p>
          <p style="font-size: 13.5px; color: #333; line-height: 1.7;">
            2005年東京都生まれ。2020年〜2023年にオーストラリア・タスマニア州の現地高校へ正規留学。2024年にクラファンを活用した「じぶんを投稿する写真展」（神田）、2026年に寒河江市の空き家で展覧会「田代百年区域」を主催。英検準一級 / TOEIC 920点 / IELTS overall 7.5。
          </p>
        </div>
        <div style="text-align: center;">
          <img src="IMG_0491.jpeg" alt="中土井陽太">
        </div>
      </div>
    </div>

    <div style="margin-top: 30px;">
      <h3 style="font-size: 20px; font-weight: 900; text-align: center; margin-bottom: 20px;">専門領域を融合させた学生5名の選抜チーム</h3>
      <div class="grid-3">
        <div class="pop-card" style="padding: 20px;">
          <div style="font-weight: 900; color: var(--accent-orange);">01 副リーダー / 進行</div>
          <div style="font-size: 13px; color: #555;">進捗管理・経理・レポート編集統括</div>
        </div>
        <div class="pop-card" style="padding: 20px;">
          <div style="font-weight: 900; color: var(--accent-orange);">02 企画構想・コミュニティ</div>
          <div style="font-size: 13px; color: #555;">現地ヒアリング・提案ドラフト作成</div>
        </div>
        <div class="pop-card" style="padding: 20px;">
          <div style="font-weight: 900; color: var(--accent-orange);">03 建築環境デザイン</div>
          <div style="font-size: 13px; color: #555;">空間分析・建築図面ダイアグラム作成</div>
        </div>
        <div class="pop-card" style="padding: 20px;">
          <div style="font-weight: 900; color: var(--accent-orange);">04 グラフィックデザイン</div>
          <div style="font-size: 13px; color: #555;">リサーチZINEの誌面デザイン・入稿</div>
        </div>
        <div class="pop-card" style="padding: 20px;">
          <div style="font-weight: 900; color: var(--accent-orange);">05 美術・映像アーカイブ</div>
          <div style="font-size: 13px; color: #555;">写真撮影・報告映像制作</div>
        </div>
        <div class="pop-card" style="padding: 20px; background: var(--accent-orange); color: #fff;">
          <div style="font-weight: 900; color: #fff;">06 プロジェクト代表</div>
          <div style="font-size: 13px; color: #fff;">全体統括・中土井 陽太</div>
        </div>
      </div>
    </div>
  </section>

 <div style="position: relative; width: 100%; padding-top: 56.25%; border: 2px solid #0F172A; border-radius: 12px; box-shadow: 4px 4px 0px #0F172A; overflow: hidden; background: #000; margin: 30px 0;">
  <iframe 
    style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" 
    src="https://www.youtube.com/embed/2DwdTh0Gqlc" 
    title="メンバー紹介動画" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; webshare" 
    allowfullscreen>
  </iframe>
</div>

  <!-- スケジュール -->
  <section>
    <div class="sec-header">
      <div class="tag">ROADMAP</div>
      <h2 class="sec-title">プロジェクト実行スケジュール</h2>
    </div>

    <div style="max-width: 720px; margin: 0 auto;">
      <div class="timeline-step">
        <div class="step-date">2026.09-10</div>
        <div>
          <h4 style="font-size: 16px; font-weight: 900;">公募・メンバー選抜 ＆ 協賛・クラファンアプローチ</h4>
        </div>
      </div>
      <div class="timeline-step" style="border-color: var(--accent-orange);">
        <div class="step-date" style="background: var(--accent-orange);">2026.11.30</div>
        <div>
          <h4 style="font-size: 16px; font-weight: 900;">【目標達成判定デッドライン】</h4>
          <p style="font-size: 13px; color: #555;">目標達成を確認し、渡航手続き・宿泊予約を正式決定！</p>
        </div>
      </div>
      <div class="timeline-step">
        <div class="step-date">2026.12-2027.02</div>
        <div>
          <h4 style="font-size: 16px; font-weight: 900;">全4回の事前勉強会 ＆ 現地取材アポ入れ</h4>
        </div>
      </div>
      <div class="timeline-step" style="background: var(--accent-teal); color: #fff;">
        <div class="step-date" style="background: var(--primary);">2027.02下-03上</div>
        <div>
          <h4 style="font-size: 18px; font-weight: 900; color: #fff;">✈️ ポートランド現地渡航リサーチ（5泊7日）</h4>
        </div>
      </div>
      <div class="timeline-step">
        <div class="step-date">2027.04</div>
        <div>
          <h4 style="font-size: 16px; font-weight: 900;">リサーチZINE発行 ＆ 成果報告会（全リターン納品完了）</h4>
        </div>
      </div>
    </div>
  </section>

</div>

<!-- CTA Support Section -->
<div class="cta-block">
  <div class="container">
    <div class="tag orange" style="margin-bottom: 16px;">JOIN OUR JOURNEY</div>
    <h2 style="font-size: clamp(28px, 5vw, 44px); font-weight: 900; color: #fff; line-height: 1.2; margin-bottom: 16px;">
      若者の挑戦に、あたたかいご支援をお願いいたします。
    </h2>
    <p style="font-size: 15px; max-width: 680px; margin: 0 auto 20px; opacity: 0.9;">
      皆様からいただいたご支援が、若者の視野を広げ、東北から社会の未来を照らす火種となります。
    </p>

    <!-- 振込先情報ボックス -->
    <div class="bank-box">
      <h3 style="font-size: 18px; font-weight: 900; margin-bottom: 12px; color: var(--accent-orange); border-bottom: 2px solid var(--primary); padding-bottom: 6px;">
         振込口座（プロジェクト専用口座）
      </h3>
      <p style="font-size: 14px; line-height: 1.8; font-weight: bold;">
        金融機関：三井住友銀行　普通　8368478 ナカドイヨウタ
