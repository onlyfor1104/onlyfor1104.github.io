---
layout: post
title: Sangria
subtitle: 샹그리아
gh-repo: onlyfor1104/onlyfor1104.github.io
gh-badge: [star, fork, follow]
cover-img: /assets/img/12.jpg
tags: [Website, Blog, GitHub, Guide, How to, Seokho Son, Open source]
comments: true
---

## 개요

Granada, Spain

- Drunk man, Sunset, Red

{: .box-note}
연습 차원에서, **동휘** 를 위해 게시하였습니다. &#128525;


<br>

## 다른 사진

동휘 웹사이트 확인: [https://onlyfor1104.github.io](https://onlyfor1104.github.io)

<br>

## 기존 양식

여기가 대분류

### 동영상

[이걸로 동영상 링크](https://www.youtube.com/watch?v=a2jcJuxxiFQ&list=PL0NUN1E_oXsyfQZ5H6rFXJHLyQts1-8v_)

<iframe width="770" height="432" src="https://www.youtube.com/embed/a2jcJuxxiFQ" frameborder="0" allowfullscreen></iframe>

<br>

### 간단 GIF 가이드

GIF 짤 입력 방법

![짤이름? 느낌표는 무엇?](../assets/img/simple-guide.gif)

<br>

### 상세 설명

1. GitHub 계정이 없는 경우, GitHub 계정을 생성하고 이메일 인증을 수행합니다.

   1. GitHub 계정 생성
      ![GitHub 계정 생성](../assets/img/githubpage-guide/p1.jpg)

   1. GitHub 계정 이메일 인증
      ![GitHub 계정 이메일 인증](../assets/img/githubpage-guide/p2.jpg)

1. 웹사이트의 기본 소스를 제공하는 GitHub 저장소에 접속하고, `Fork` 를 통해 해당 저장소를 본인의 GitHub 계정으로 복제합니다.

    1. [https://github.com/seokho-son/seokho-son.github.io](https://github.com/seokho-son/seokho-son.github.io) 저장소에 접속
       ![GitHub 저장소 접속](../assets/img/githubpage-guide/g2.jpg)

    1. [https://seokho-son.github.io](https://seokho-son.github.io) 접속을 통해 데모 웹사이트 확인
       ![GitHub Page 접속](../assets/img/githubpage-guide/g1.jpg)

    1. GitHub의 `Fork` 기능을 통해 저장소를 본인의 GitHub 계정으로 복제
       ![GitHub 포크](../assets/img/githubpage-guide/g3.jpg)

       `Fork` 는 Git 저장소를 복제 및 기존 저장소와 연계시키는 기능 (보통 공동 작업을 위한 방법)

    1. 본인 계정에 복제된 저장소 확인
       ![GitHub 포크 확인](../assets/img/githubpage-guide/g5.jpg)

1. GitHub Page 활성화를 위해 저장소 명칭 변경

    1. `Settings` 탭을 선택하고 `Repository name` 을 `계정이름.github.io` 로 변경
        ![저장소 이름 변경](../assets/img/githubpage-guide/g7.jpg)

    GitHub는 `계정이름.github.io` 인 저장소에 대해 자동으로 소스코드 빌드 및 호스팅을 수행함

    1. 자동 생성된 웹사이트 확인
        ![자동 생성 웹사이트 확인](../assets/img/githubpage-guide/g8.jpg)


1. 자신의 웹사이트로 내용 커스터마이징

    1. `_config.yml` 파일을 선택하여 내용 수정 및 저장소에 수정 사항 반영

        `_config.yml` 파일은 웹사이트의 설정 정보가 포함되어 있음. `수정필요` 로 코멘트된 사항에 대해 커스터마이징 진행.

        ![컨피그 확인](../assets/img/githubpage-guide/g9.jpg)

        ![컨피그 수정](../assets/img/githubpage-guide/g10.jpg)

        ![컨피그 수정2](../assets/img/githubpage-guide/g11.jpg)

        ![컨피그 커밋](../assets/img/githubpage-guide/g12.jpg)

        `Commit` (`git commit`)은 어려가지 변경 사항에 대한 스넵샷을 제공하는 기능임. 수정 사항을 저장소에 반영하기 위해서는 `Commit` 이라는 행위를 필수적으로 수행해야 함.

    1. `index.md` 파일을 선택하여 내용 수정 및 저장소에 수정 사항 반영

        ![인덱스 확인](../assets/img/githubpage-guide/g13.jpg)

        ![인덱스 수정](../assets/img/githubpage-guide/g14.jpg)

        ![인덱스 커밋](../assets/img/githubpage-guide/g15.jpg)

        `index.md` 는 웹사이트에서 첫 페이지(`home`)의 소스 파일임. 커스터마이징 진행.

        `.md` 파일은 [마크다운 언어](https://ko.wikipedia.org/wiki/마크다운)으로 작성되는 것을 의미함.

    1. `carrer.md` , `publication.md` 등 `*.md` 에 대해서도 커스터마이징 진행


1. 내용이 업데이트된 웹사이트 최종 확인
    ![업데이트된 웹사이트](../assets/img/githubpage-guide/g17.jpg)

끝.
