+++
title = 'GitHub と Claude の親和性について'
date = 2025-01-15
description = '実装から学んだ GitHub Issues と Claude の使い方'
tags = ['GitHub', 'Claude', 'AI']
categories = ['開発手法']
draft = false
+++

## はじめに

Hongo Kogyo のウェブサイト更新プロジェクトを通じて、GitHub Issues と Claude を組み合わせた開発フローの効率性に気づきました。単なる「版管理ツール」「AI チャット」として見ていたものが、実は相互補完できる関係だったんです。

## GitHub Issues を使う理由

最初は「Issues って、バグ報告用では？」と思っていました。でも実装が進むにつれて、これが プロジェクト管理の中心 になることに気づきました。

- 記事企画の一覧管理
- 進捗状況の可視化（label）
- Claude への指示書として機能

すべてが GitHub 内で一元管理できるってすごい。

## Claude との相性

Claude に GitHub Issues のリンクを貼って「この Issue の内容をもとに実装プランを立ててほしい」と指示すると、Issues の文脈をそのまま使って、具体的な実装手順が帰ってくる。

試行錯誤がローカルファイルの更新履歴として残るから、「何をどう変更したか」が GitHub で追跡できる。

## これからの可能性

GitHub Actions を使えば、記事公開時に自動で SNS 告知とか、RSS フィード生成とか、いろいろできそう。今回のプロジェクトで得た知見は、会社のメインサイト更新にも応用できる気がします。
