---
title: 1. Zsh 설명서
keywords: documentation theme, jekyll, technical writers, help authoring tools, hat replacements
last_updated: Dec 18, 2019
tags: [getting_started]
summary: "I have used this theme for projects that I've worked on as a professional technical writer."
sidebar: mydoc_sidebar
permalink: mydoc_zsh_manual.html
folder: mydoc
---
{::comment}{{ site.time | date: '%m %d %y' }}{:/comment}

이 문서(원본)는 Zsh 배포판 하위폴더 중 Doc에 들어있는 zsh.texi라는 texinfo 파일로부터 만들어졌습니다.

## 1. zsh.texi로 문서 만들기

### texinfo는 여러가지 다른 포맷으로 변환 할 수 있다.
[GNU Korea texinfo 페이지](http://korea.gnu.org/manual/release/texinfo/texinfo-ko_2.html)

### Info 파일
Info 형식은 찾기가 가능하고 `makeinfo zsh.texi`라는 명령으로 zsh.dvi로 변환되고 이것은 dvips 나 gs(Ghostscript)를 이용해서 인쇄용으로 만들 수 있다.

### The printed manual
- The command ‘texi2dvi zsh.texi’ will output zsh.dvi which can then be processed with dvips and optionally gs (Ghostscript) to produce a nicely formatted printed manual.

### The HTML manual
- An HTML version of this manual is available at the Zsh web site via:

  http://zsh.sourceforge.net/Doc/.

  (The HTML version is produced with texi2html, which may be obtained from http://www.nongnu.org/texi2html/. The command is ‘texi2html –output . –ifinfo –split=chapter –node-files zsh.texi’. If necessary, upgrade to version 1.78 of texi2html.)

- For those who do not have the necessary tools to process texinfo, precompiled documentation (PostScript, dvi, PDF, info and HTML formats) is available from the zsh archive site or its mirrors, in the file zsh-doc.tar.gz. (See Availability for a list of sites.)


{% include links.html %}
