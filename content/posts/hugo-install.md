+++
date = '2026-03-26T15:41:49+09:00'
draft = false
title = 'Windows 11에서 Hugo 설치'
tags  = ["hugo", "install"]
+++
Hugo Install(Windows 11에서)


$ Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

$ irm get.scoop.sh | iex

$ scoop install hugo-extended

$ hugo version
