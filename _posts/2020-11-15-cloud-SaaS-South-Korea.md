---
layout: post
permalink: /cloud-SaaS-South-Korea/
title: '우리가 알게모르게 쓰는 SaaS 클라우드 서비스들'
date: 2020-11-15 20:26:00 +09:00
feature: '/img/posts/003/SaaS.JPG'
background: '/img/posts/003/spam.jpg'
categories:
  - cloud
tags:
  - cloud, SaaS, Kakao Works, Naver Works, 클라우드
description: '우리가 알게 모르게 쓰는 SaaS 들과 국내에서 이슈가 되고 있는 네이버웍스(Kakao Works),카카오웍스(Kakao Works)'
---
필자는 2016년 클라우드 서비스라는 생소한 단어를 아마존 웹서비스(AWS)의 EC2 (Amazon Elastic Computing Cloud) 라는 것으로 처음 접했다. 당시 데이터 분석을 배우며 단기 프로젝트를 진행하다가, 로컬 컴퓨터에서 진행하는 방법 외 강사님이 추천해주신 클라우드에서 EC2라는 가상 컴퓨팅 환경 (virtual computing environment, known as ‘instance’) 이라는 것을 처음 써보았다. 내 컴퓨터가 아닌 다른 저장소에서 내 프로젝트가 돌아가는 것을 보고 불안하지만 신기하다는 생각이 제일 처음 들었다.

Source: <ins>[아마존 – Amazon EC2이란 무엇입니까?](https://docs.aws.amazon.com/ko_akr/AWSEC2/latest/UserGuide/concepts.html)</ins>


사실, 클라우드 서비스라는 것은 2016년이 아닌 훨씬 전부터 쓰고 있었다. 우리가 쓰는 이메일, 드라이브, 웹 저장소 모두 클라우드 서비스의 일종이며, 단지 최근 클라우드 플랫폼, 클라우드 서비스 같은 키워드들이 급부상하면서 재조명 되는 것 뿐이였다. 2016년에 처음 클라우드를 접했던 것이 아니라, 사람들이 그동안 ‘클라우드’라고 부르지 않았던 서비스를 계속 써 왔던 것이다. 그동안 얼마나 많은 기술들이 이름도 불리지 못한 채 거쳐간 것인지 상상도 안 간다.

필자와 같이 클라우드를 쓰면서도 클라우드 서비스에는 어떤 것들이 있는지 궁금했던 사람들을 위해, 2020년도 들어 사람들이 지속적으로 쓰고 있고 사용이 가속화 된 클라우드 서비스 중 SaaS (Software as a Service) 타입의 클라우드 서비스를 정리해 보았다.


## SaaS(Software as a Service)란?
- 소프트웨어를 따로 설치할 필요 없이, 클라우드 기반으로 사용자가 필요한 것만 이용 가능한 소프트웨어 서비스

- 소프트웨어 기능을 인터넷으로 사용할 수 있도록 제공되며, 하나의 서버를 여럿이 공유 가능하지만 데이터 자체는 사용자별로 분류 가능하다

Source: <ins>[[클라우드] SaaS란? 소프트웨어의 기능을 서비스로 이용](https://blog.naver.com/ydot/222076883154)</ins>

- <strong>장점</strong>: 따로 소프트웨어를 PC에 설치할 필요가 없으며, 쓴 만큼 비용을 낼 수 있다. 웹 브라우저나 가벼운 사용자 어플리케이션으로도 이용이 가능하다

- <strong>단점</strong>: 서비스의 퀄리티가 브라우저, 인터넷 연결에 따라 좌우될수 있으며, 계약 조건이나 규정에 따라 조건에 맞춰 서비스가 업데이트 되거나 유지보수가 힘들 수 있다 (ex. SaaS 사용에 따라 제공되는 데이터가 규정에 맞춰서 전송, 사용 및 저장되는지)

  * Ex) 디아블로 같은 게임을 CD를 사서 컴퓨터에 설치: <br> SaaP (Softaware as a Product)

  * 디아블로 라이선스를 사서 컴퓨터로 다운로드: <br> SaaS(Software as a Service)

  Source:
  1. <ins>[Tackling compliance issues in software as a service by BoB Tarzey](https://www.computerweekly.com/feature/Tackling-compliance-issues-in-software-as-a-service)</ins>

  2. <ins>[Things SaaS Companies Need to Know About Regulatory Compliance by Benjamin Brandall](https://www.process.st/regulatory-compliance/)</ins>


## 대중적인 SaaS 제품 및 회사:

![Alt](/img/posts/003/Googleapps.jpg "googleapps")

1.	구글 드라이브, 구글 독스(Docs) : 넓게 나아가서는 구글 데이터스튜디오, 구글 마케팅 플랫폼. 사용자의 로그인/구독을 통해 이메일이나 소프트웨어를 다운받지 않고 어디서나 쓸 수 있다.

2.	Office 365: 브라우저 상에서 로그인만으로 엑셀,파워포인트, 저장소등 필요한 소프트웨어를 쓸 수 있다. 기존 오피스 제품을 라이선스로 다운받고 관리했던 것과 달리 로그인/구독을 통해 온라인에서 다운받을수 있는 소프트웨어를 제공하여 편리해짐

3.	Salesforce (SAP, Oracle): 마케팅과 CRM(고객관계 관리) 플랫폼을 클라우드로 옮긴 서비스. 주로 에이전시 마케터보다는 기업에서 기업데이터, 고객정보 관리 등에 많이 쓰인다.
  -	 예전에는 고객사나 고객 정보를 취합하여 엑셀로 분석하였지만, Salesforce는 그런 데이터와 분석하는 소프트웨어를 모두 클라우드 기반으로 바꾸었다

  - 	Ex) 페이스북이나 인스타그램에서 유저 통계를 보여주거나, 제품 유통 공급망이나 재고 관리 데이터를 저장하고 분석하는 것도 CRM에 범주에 든다

-	단순 소프트웨어를 사는게 아니라, 클라우드로 소프트웨어를 사고 파는 기업으로 원가의 90%를 절감하였다. 현재는 많은 기업용 앱 소프트웨어 스토어인 AppExchange을 운영하며 기업들이 상황에 맞게 소프트웨어를 플랫폼화 하게 도와주고 있다.

Source: <ins>[[글로벌 슈퍼스탁] 세일즈포스 (CRM US)](https://www.youtube.com/watch?v=KVGe4VF40jk)</ins>

## 최근 우리나라에서 뜨고 있는 SaaS:

##### 네이버 웍스 (Naver Works) vs. 카카오 웍스(Kakao Works)

-	둘다 업무용 메신저 협업툴의 성격을 띄고 있으며, 이미 슬랙이나 노션 같은 해외 업무용 툴로 활성화 된 우리나라에서 유저들에게 조금 더 친근한 서비스로 다가가려는 노력을 하고 있음

-	네이버 웍스는 기존 2016년 라인웍스 (B2B 업무용 협업툴)로 먼저 시장에 진출하였고, 일본에서는 슬랙 재팬을 제치고 4년동안 업계 1위를 차지한 전력이 있다. 현재는 네이버 웍스로 이름이 변경되었고, 메일, 메신저,캘린더,드라이브등을 클라우드에서 안전하게 제공하는 것을 경쟁력으로 삼는 다는 점에서 구글과 비슷한 전략을 보이고 있다.

-	카카오는 후발주자이기는 하지만 이미 국내에서는 많은 유저들이 카카오톡을 업무에도 활용중이고, 친숙한 UI/UX, 사용법이 유저들에게는 사용 장벽 없이 다가갈 수 있다는 장점이 있다. 카카오 100개 자회사 전반에 카카오워크를 도입할 전망으로, 파트너사인 HMM, 교보생명, NH 투자증권도 포함된다.

<ins>시장 경쟁력과 궁금증:</ins>
-	B2C의 측면으로는 메신저로서 어떻게 업무와 일상의 분리를 제대로 해내고, 업무 몰입도를 높이느냐가 시장 선점 우위가 될 것 같고,

-	B2B적인 관점에서는 툴이 기업 전체로 확장하여 활용할 수 있는 범용성이 존재하는지가(ex. 인프라서비스(IaaS), 플랫폼서비스(PaaS)를 함께 제공할 수 있는지) 시장 전체를 독점할 수 있는 키 포인트로 보인다

-	이미 슬랙과 노션이 국내에서 편리하게 대중화 되어 쓰이고 있는 시점에서, 과연 네이버와 카카오웍스는 자국민이 잘 사용하고 있는 메신저와 플랫폼이라는 장점을 업무용 플랫폼으로 확장할 수 있을까? 오히려 개인 생활에 밀착되어 접목시켜진 만큼 업무적으로 상용화 하였을 때 유저들의 거부감이 더 크지는 않을까??

Sources:
1. <ins>[협업툴 시장서 카카오-네이버 각축···“당분간 네이버 우세”](http://www.sisajournal-e.com/news/articleView.html?idxno=225596)</ins>
2. <ins>[[플랫폼] 라인웍스냐 카카오워크냐…대기업들의 선택은?](https://www.mk.co.kr/news/it/view/2020/10/1044998/)</ins>
