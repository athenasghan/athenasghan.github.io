---
layout: post
permalink: /google-seo-update-2021-search-console/
title: '구글 SEO 2021 업데이트: 구글 크롤링 통계보고서 사용하기'
date: 2020-12-02 22:00:00 +09:00
feature: '/img/posts/005/thumb5.jpg'
background: '/img/posts/005/thumb5.jpg'
categories:
  - digitalmarketing
tags:
  - SEO,GSC,digital,digitaladvertising,구글서치콘솔
description: '기존 구글 서치콘솔에서 새 버전의 크롤링 통계 보고서는 어떤게 달라졌을까?'
---
2020년 11월 24일 업데이트 – 기존 구글 서치콘솔에서 새 버전의 크롤링 통계 보고서 출시

기존에 볼 수 있었던 http 응답코드(response code) 상태 외에도 새로운 데이터들을 볼 수 있다.

### 크롤링 통계 보고서 보는 법:
1.	구글서치콘솔(https://search.google.com/search-console/)접속
2.  왼쪽 미리보기 중 보고싶은 사이트 속성을 선택 후 설정(Setting)을 클릭
3.	설정 중 크롤링 보고서(Crawl status)를 클릭한다
![Alt](/img/posts/005/0.jpg "google-search-console-crawl-status")

### 다른 방법:
1. https://search.google.com/search-console/settings/crawl-stats? 으로 접속후 보고싶은 사이트 속성 클릭
![Alt](/img/posts/005/1.jpg "google-search-console-crawl-status")

### 보고서 내용
1.	초과 근무 차트(Over-time chart): 총 크롤링 요청 수, 다운로드 크기, 평균 응답 시간에 대한 구글 크롤링 데이터를 볼 수 있음
![Alt](/img/posts/005/2.jpg "gsc-crawl-status-chart")

2. 그룹별로 크롤링 데이터 관찰 가능: 응답별, 파일 유형, 목표(발견/새로고침), 구글봇 기준 등 다양한 지표로 크롤링 상황을 볼 수 있음
![Alt](/img/posts/005/3.jpg "gsc-crawl-status-by-data")

  각 지표를 클릭하면 url 별로도 나눠서 보여준다:
  ![Alt](/img/posts/005/4.jpg "gsc-crawl-status-by-url")

3. 호스트 상태 체크: 지난 90일동안 내 사이트가 구글에 얼마만큼 정보를 제공하고, 가용성이 있었는지 알려준다.
![Alt](/img/posts/005/5.jpg "gsc-crawl-status-by-host")

  만일 호스트가 여러 개인 도메인 속성이라면, 상위 호스트들의 상태들도 한 곳에서 확인가능해 훨씬 편리해졌다
![Alt](/img/posts/005/6.jpg "gsc-crawl-status-by-host2")

### 총정리:

- 기존에도 응답코드(response code)를 체크할 수 있었지만, 지금은 크롤링 목적이나 Googlebot 유형대로도 크롤링 상태를 나눠 볼 수 있음
- 현재 호스트 상태에 관한 자세한 정보를 확인 가능하고 여러 호스트를 가진 속성 관련 요약 및 도메인 속성도 지원해준다
- 다수의 사이트요청(site request)이 발생한 위치를 url 로 표기

새롭게 업데이트된 구글 서치콘솔을 통해 구글 이외의 툴을 사용하지 않고도 구글봇들이 어떤 정보를 내 페이지에서 크롤링 하는지 자세하게 알게 되어서 더 세밀한 페이지 밸런싱과 업데이트가 가능해진다. 앞으로는 검색엔진별 크롤봇이 어떻게 페이지를 인식하는지도 세밀한 관찰이 필요해질 것 같다.
