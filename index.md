---
title: Home
suite_name: IT Automation Ver.2
layout: common
language: ja
docs: ita
page_class: home
page_name: index
description: Exastro IT Automationはシステム設定をデジタル化して一元管理するためのオープンソースのフレームワークです。
---
<link rel="stylesheet" href="assets/css/software_home.css?v=3">
<!--
##################################################
   Header
##################################################
-->
<header id="header">
<div class="header-container">
    <div class="header-main">
        <div class="header-main-specialized"><span>システム<strong>構築・運用</strong>に特化</span></div>
        <h1 class="header-main-title">
            <span class="header-main-exastro">Exastro</span>
            <span class="header-main-software">IT Automation <span style="font-size: 50%">Ver.</span>2</span>
        </h1>
        <p class="header-main-description">Exastro IT Automation はシステム設定をデジタル化して一元管理するためのオープンソースのフレームワークです。</p>
        <div class="install-command-block">
          <p class="install-command-title"><i class="fas fa-download"></i> Easy to install...</p>
          <div class="install-command-wrap clipboard-copy"><pre class="install-command ">sh &lt;(curl -sf {{ site.url }}{{ site.baseurl }}/setup) install<i class="fa-regular fa-copy"></i></pre></div>
          <p class="install-command-note">インストールの詳細については、<a class="install-command-link touch" href="https://ita-docs.exastro.org/ja/2.4/installation/index.html">ドキュメント</a>を参照してください。</p><br>
          <p class="install-command-note">旧バージョン（ Exastro IT Automation Ver.1 は、<a class="install-command-link touch" href="https://exastro-suite.github.io/it-automation-docs/index_ja.html">こちら</a> ）</p>
          <p class="install-command-note">旧バージョン（ Exastro OASE は、<a class="install-command-link touch" href="https://exastro-suite.github.io/oase-docs/index_ja.html">こちら</a> ）</p>
        </div>
    </div>
    <div class="header-menu">
        <ul class="header-menu-list">
            <li class="header-menu-item"><a href="https://ita-docs.exastro.org/ja/2.4/installation/" class="header-link touch">
                <i class="fas fa-download"></i>
                <span class="header-link-sub">Documents</span>
                <span class="header-link-main">Install</span>
            </a></li>
            <li class="header-menu-item"><a href="https://ita-docs.exastro.org/ja/2.4/manuals/" class="header-link touch">
                <i class="fas fa-file-alt"></i>
                <span class="header-link-sub">Documents</span>
                <span class="header-link-main">Manual</span>
            </a></li>
            <li class="header-menu-item"><a href="https://ita-docs.exastro.org/ja/2.4/learn/quickstart/index.html" class="header-link touch">
                <i class="fa-solid fa-jet-fighter"></i>
                <span class="header-link-sub">Learn</span>
                <span class="header-link-main">Quickstart</span>
            </a></li>
            <li class="header-menu-item"><a href="https://ita-docs.exastro.org/ja/2.4/learn/" class="header-link touch">
                <i class="fas fa-school"></i>
                <span class="header-link-sub">Documents</span>
                <span class="header-link-main">Learn</span>
            </a></li>
            <li class="header-menu-item"><a href="https://ita-docs.exastro.org/ja/2.4/templates/index.html" class="header-link touch">
                <i class="fas fa-cog"></i>
                <span class="header-link-sub">Documents</span>
                <span class="header-link-main">Templates</span>
            </a></li>
            <li class="header-menu-item"><a href="https://www.exastro.org/index.html#handout" class="header-link touch">
                <i class="fas fa-toolbox"></i>
                <span class="header-link-sub">Hand out</span>
                <span class="header-link-main">PSSO method</span>
            </a></li>
            <li class="header-menu-item"><span class="header-nolink">
                <i class="fas fa-video"></i>
                <span class="header-link-main">Webinar</span>
                <span class="header-link-coming-soon">Coming Soon...</span>
            </span></li>
            <li class="header-menu-item"><span class="header-nolink">
                <i class="fas fa-question-circle"></i>
                <span class="header-link-main">FAQ</span>
                <span class="header-link-coming-soon">Coming Soon...</span>
            </span></li>
        </ul>
    </div>
</div>


</header>

<main id="main" style="overflow:hidden">
<article class="article">

<section id="overview" class="section">

<div class="section-container">
<div class="section-main">
    <h2 class="section-h2"><strong class="software-name">Exastro IT Automation</strong>とは？</h2>
    <p class="section-p">Exastro IT Automation は、システム構築や運用業務の自動化/効率化/省力化を目的としたシステムの構成管理およびシステム設定のためのフレームワークです。</p>
    <h3 class="section-h3">システム構築/運用は情報の一元管理が要！</h3>
    <p class="section-p">Exastro IT Automation は、情報連携のミスやチーム間の情報伝達のコストを抑えるために、システムの構成情報であるパラメータや手順(IaC)を一元的に管理する仕組みを提供します。また、CMDB 上にシステムの過去・現在・未来のパラメータ情報を格納でき、作業手順書である IaC にパラメータを連携することで IaC の再利用性を高めることができます。</p>
</div>

<div class="section-image">
    <figure class="loupe touch"><img src="assets/img/ita_overview.png" alt="概要イメージ"></figure>
</div>

</div>
</section>

<hr class="section-hr">

<section id="version-update" class="section">

<div class="section-container">
<div class="section-main">
    <h2 class="section-h2">Ver. 2 で何が変わったのか？</h2>
    <h3 class="section-h3">マルチテナンシー対応</h3>
    <p class="section-p">複数の組織やプロジェクトを1つの Exastro IT Automation 上にテナントとして管理できるため、コンピュータリソースを効率的に利用できます。また、データ領域はテナント毎に隔離されているため情報の機密性が保たれています。</p>
    <h3 class="section-h3">ワークスペース機能</h3>
    <p class="section-p">システムのパラメータ、設定ファイル、自動化ソフトウェアの IaC といった、システムを構成・管理・維持するための作業領域としてワークスペース機能を提供しています。このワークスペース機能を利用することで複数のシステム、または環境を容易に管理できます。</p>
    <h3 class="section-h3">Restful API</h3>
    <p class="section-p">すべての操作を Restful API で操作可能で周辺システムとの連携が容易です。</p>
</div>

<div class="section-image">
    <figure class="loupe touch"><img src="assets/img/exastro-it-automation.gif" alt="Exastro IT Automation"></figure>
</div>

</div>
</section>


<section id="resolve" class="section">
<div class="resolve-container">
<h2 class="resolve-title"><span><strong class="software-name">Exastro IT Automation</strong>は<br>システムの管理を取り巻く3つの問題を解決します</span></h2>

<ul class="resolve-problem-list">
    <li class="resolve-problem-item">
        <dl class="problem-list">
            <dt class="problem-title"><i class="fa-solid fa-xmark"></i>データ多重管理による<br class="problem-br">設計ミス</dt>
            <dd class="problem-resolve"><i class="fas fa-check-circle"></i>データを一括で管理、二重管理による設計ミスを防ぎます。</dd>
            <dd class="problem-image"><figure class="loupe touch"><img src="assets/img/parameter_sheet_for_input_2.gif" alt=""></figure></dd>
        </dl>
    </li>
    <li class="resolve-problem-item">
        <dl class="problem-list">
            <dt class="problem-title"><i class="fa-solid fa-xmark"></i>複雑な人手作業による<br class="problem-br">オペレーションミス</dt>
            <dd class="problem-resolve"><i class="fas fa-check-circle"></i>構築作業は自動実行、実行状況をわかりやすく表示します。</dd>
            <dd class="problem-image"><figure class="loupe touch"><img src="assets/img/excute_conductor.gif" alt=""></figure></dd>
        </dl>
    </li>
    <li class="resolve-problem-item">
        <dl class="problem-list">
            <dt class="problem-title"><i class="fa-solid fa-xmark"></i>作業記録不足による<br class="problem-br">障害対応遅延</dt>
            <dd class="problem-resolve"><i class="fas fa-check-circle"></i>作業記録をしっかりと管理、作業の成否をレポートします。</dd>
            <dd class="problem-image"><figure class="loupe touch"><img src="assets/img/job_detail.gif" alt=""></figure></dd>
        </dl>
    </li>
</ul>

</div>

<script>
/*
$("document").on('click','img',function () {
    $("#grayBack").html($(this).prop("outerHTML"));
    $("#grayBack").fadeIn(200);
    return false;
});

$("document").on('click','#grayBack',function () {
    $("#grayBack").fadeOut(200);
    return false;
});
*/
</script>
</section>

<!--<section id="features" class="section">

<div class="features-container">
    <h2 class="features-h2"><span><strong>７</strong>つの特徴</span></h2>
    <div class="features-main">
        <div class="features-slide">
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">マルチテナントの実現</div>
                    <div class="features-body">
                        <div class="features-paragraph">各メニューやレコード単位のRBACを活用することで、<em>マルチテナント</em>として活用いただくことが可能です。パラメータシートやJobFlowの<em>１つ１つに対して権限付与が可能</em>です。</div>
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image1.png" | relative_url }}" alt="マルチテナントの実現"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">NoCodeでCMDBを定義</div>
                    <div class="features-body">
                        <div class="features-paragraph">パラメータシートを<em>グラフィカル</em>に定義可能<br>
                        作成した<em>パラメータシートの関連性を可視化</em>できます。</div>
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image2.png" | relative_url }}" alt="NoCodeでCMDBを定義"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">パラメータのライフサイクルを管理</div>
                    <div class="features-body">
                        <div class="features-paragraph">収集⇒変更⇒収集⇒比較を一連のライフサイクルとして整備することで、変更すべき箇所が正しく変更できていることを確認することができる。</div>
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image3.png" | relative_url }}" alt="パラメータのライフサイクルを管理"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">IaCのCI/CDの実現</div>
                    <div class="features-body">
                        <div class="features-paragraph">PlaybookやTFファイル等のIaCのCI/CDを実現する機能を具備。<br>
                        GitにIaCをコミットすることでMovement実行までを自動化することができる。</div>
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image4.png" | relative_url }}" alt="IaCのCI/CDの実現"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">IaCをモジュール管理して再利用性を向上</div>
                    <div class="features-body">
                        <div class="features-paragraph">作成するIaCはなるべく使いまわせる粒度で作成することがIaC作成コストを低減させることにつながる。</div>
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image5.png" | relative_url }}" alt="IaCをモジュール管理して再利用性を向上"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">複数の自動化ソフトウェアを繋げて実行</div>
                    <div class="features-body">
                        <div class="features-paragraph"><figure class="loupe touch"><img src="{{ "/exastro-it-automation-docs/assets/img/features_image6.png" | relative_url }}" alt="複数の自動化ソフトウェアを繋げて実行"></figure></div>
                    </div>
                </div>
            </div>
            <div class="features-block">
                <div class="features-block-inner">
                    <div class="features-title">実行状況をリアルタイムでモニタリング</div>
                    <div class="features-body">
                        <div class="features-paragraph"><em>手動作業と比較して遜色なく実行状況をリアルタイム把握</em>することを重視<br>
                        また<em>実行記録（作業エビデンス）を管理</em>し欲しい時にダウンロード可能</div>
                        <div class="features-paragraph"></div>
                    </div>
                </div>
            </div>
        </div>
        <div class="features-menu">
            <ol class="features-list">
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>マルチテナントの実現</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>NoCodeでCMDBを定義</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>パラメータのライフサイクルを管理</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>IaCのCI/CDを実現</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>IaCをモジュール管理して再利用性を向上</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>複数の自動化ソフトウェアを繋げて実行</div></li>
                <li class="features-item touch"><div class="features-item-inner"><i class="fas fa-cog"></i>実行状況をリアルタイムでモニタリング</div></li>
            </ol>
        </div>
    </div>
</div>
</section>

<script>
$(function(){
    const $features = $('#features'),
          $slide = $features.find('.features-block'),
          $item = $features.find('.features-item');
    
    $slide.eq(0).add( $item.eq(0) ).addClass('open');
    
    $item.on('click', function(){
        const $item = $( this ),
              $list = $item.closest('.features-list'),
              index = $list.find('.features-item').index( $item );
        
        $features.find('.open').removeClass('open');
        $slide.eq( index ).add( $item ).addClass('open');
    });
});
</script>


<section id="applied" class="section">

<div class="section-container">

<div class="section-main">
    <div class="section-subTitle"><span>Exastro IT Automation 応用1</span></div>
    <h2 class="section-h2"><strong class="software-name">Exastro IT Automation</strong>が目指す<br>システムライフサイクル</h2>
    <h3 class="section-h3">システムのインベントリ情報の取得と収集</h3>
    <p class="section-p">自動化ソフトウェアの構築コードでインベントリ情報を取得すれば、それらのインベントリ情報はIT Automationに自動収集できます。IT資産管理にも活用して頂くことができます。</p>
    <h3 class="section-h3">システムのインベントリ情報の妥当性をチェック</h3>
    <p class="section-p">IT Automationはシステムに投入予定のパラメータを世代管理できます。そのため現時点でシステムに設定されているべきパラメータの期待値をパラメータの履歴から抽出が可能です。</p>
    <p class="section-p"><img src="https://exastro-suite.github.io/it-automation-docs/asset/img/system_check.png" alt="チェック" style="max-width: 50%;"></p>
    <p class="section-p">現時点でシステムに設定されているべきパラメータの期待値と、システムから収集したインベントリ情報とを比較することで、システムのインベントリ情報の妥当性をチェックできます。</p>
</div>

<div class="section-image">
    <figure class="loupe touch"><img src="https://exastro-suite.github.io/it-automation-docs/asset/img/system.png" alt="システムライフサイクルサポート"></figure>
</div>

</div>
</section>

<hr class="section-hr">

<section id="cloudnative" class="section">

<div class="section-container">

<div class="section-main">
    <div class="section-subTitle"><span>Exastro IT Automation 応用2</span></div>
    <h2 class="section-h2">クラウドネイティブでの活用</h2>
    <h3 class="section-h3">あああああああああああああああああああああああ</h3>
    <p class="section-p">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</p>
    <h3 class="section-h3">あああああああああああああああああああああああ</h3>
    <p class="section-p">あああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああああ</p>
</div>

<div class="section-image">
    <figure class="loupe touch"><img src="https://exastro-suite.github.io/it-automation-docs/asset/img/cloud_native.png" alt="クラウドネイティブでのCI/CD：kubernetesの場合"></figure>
</div>

</div>
</section>-->
<div id="overlay"></div>
<div id="grayBack"></div>
</article>
</main>
