---
title: SimpleMode
suite_name: IT Automation Ver.2
layout: common
language: ja
docs: ita
page_class: simple_mode
page_name: simple_mode
description: Exastro IT Automationが提供する機能のうちよく使う機能を自動構築ウィザードで簡単に設定できます。
---

<main id="main">
<article class="article">

<section id="" class="section">
    <p class="section-p">SimpleModeは、Exastro IT Automationの⼀部の機能を簡単に使⽤するためのラッパーツールです。</p>
</section>

<section id="" class="section">
    <h2 class="section-h2">インストール⽅法</h2>
    <p class="section-p">公開リポジトリのREADMEをご確認ください。<br>
    <a href="https://github.com/exastro-suite/exastro-it-automationsimplemode" class="touch">https://github.com/exastro-suite/exastro-it-automationsimplemode</a></p>
</section>

<section id="" class="section">
    <h2 class="section-h2">Exastro IT Automation SimpleModeとは︖</h2>
    <p class="section-p">Exastro IT Automationが提供する機能のうち、シンプルなユースケースに有⽤な機能を簡単に利⽤できるWebGUIを提供します。 ラッパーツールとしてExastro IT AutomationのREST APIと連携することで、⾃動構築をウィザード形式でサポートします。 また、SimpleMode特有の機能としてパラメータシート間でのデータコピー機能を提供し、例えば実環境から収集したパラメータを設定変更⽤のパラメータとして簡単に再利⽤することが可能です。</p>
    <h3 class="section-h3">機能</h3>
    <h4 class="section-h4">⾃動構築ウィザード機能</h4>
    <p class="section-p">ウィザード形式でAnsible Movementを実⾏できます。<br>
    ※ 実⾏するMovementは予めExastro IT Automationに設定しておく必要があります。</p>
    <h4 class="section-h4">スプレッドシート形式のパラメータ管理機能</h4>
    <p class="section-p">スプレッドシート形式で、パラメータの参照・編集が可能です。</p>
    <h4 class="section-h4">パラメータシート間のデータコピー機能</h4>
    <p class="section-p">異なるパラメータシート間で、データのコピーが可能です。<br>
    （パラメータシートのカラム構成が同じものが対象）</p>
    <h4 class="section-h4">⽐較ジョブ実⾏ウィザード機能</h4>
    <p class="section-p">パラメータ⽐較機能をウィザード機能で⼀括で実⾏できます。</p>
    <h3 class="section-h3">構成</h3>
</section>

<section id="" class="section">
    <h2 class="section-h2">ユースケース</h2>
    <h3 class="section-h3">Exastro IT Automationの⼊⾨⽤に</h3>
    <p class="section-p">Exastro IT Automationを初めて使⽤するユーザーが⾃動構築を始める際に、SimpleModeは有⽤です。 ⾃動化の担当者があらかじめ設定した⾃動化を、作業者がSimpleModeを通じてウィザード形式で実⾏できます。 初めての利⽤でも、パラメータの登録や再利⽤、Movement（作業パターン）の選択に際しての迷いが軽減されます。</p>
    <h3 class="section-h3">テンプレートを使ってOS構築から⾃動化をスタート</h3>
    <p class="section-p">繰り返し実⾏する機会の多いOSの設定作業をSimpleModeで⾃動化できます。 「Exastro Playbook Collection」として提供されるAnsible Role Templateをインポートすることで、サーバーOSのパラメータ収集、設定変更、パラメータ⽐較も可能な⾃動化を実現できます。</p>
    <h3 class="section-h3">構築済環境のOS設定確認に</h3>
    <p class="section-p">「Exastro Playbook Collection」のAnsible Role Template内の収集ジョブを使⽤することで、既に構築されている環境からパラメータを収集できます。 収集結果を基に設定ミスや漏れをチェックでき、⽐較機能を活⽤することで過去のパラメータとの差分抽出も⾏えます。</p>
    <p class="section-p">Exastro Playbook Collection はこちらからダウンロードいただけます。<br>
    <a herf="https://github.com/exastro-suite/playbook-collection-docs/blob/master/README.ja.md" class="touch">https://github.com/exastro-suite/playbook-collection-docs/blob/master/README.ja.md</a></p>
</section>

</article>
</main>