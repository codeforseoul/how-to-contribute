코드포서울 시작하기
=================
코드포서울에서 시빅 해킹을 시작하기 위한 모든 것
Everything about Codeseouls Civic Hacking.

## 1. 목차
  * [목적](#2-목적)
  * [진행중인 프로젝트](#3-진행중인-프로젝트)
    * [a. Where Does My Money Go?](#a-where-does-my-money-go)
    * [b. 알뜰 서울의 발견](#b-알뜰-서울의-발견)
    * [c. 서울맑음](#c-서울-맑음)
    * [d. Hangul Romanization] (#d-hangul-romanization)
  * [새로 시작하기](#4-새로-시작하기)
    * [a. 도움이 필요한 문제들](#a-도움이-필요한-문제들바로가기---seoul-problems)
    * [b. 해외 오픈소스 사례들](#b-해외-오픈소스-사례들---overseas-opensource-examples)
    * [c. 나는 코드를 몰라요!](#c-나는-코드를-몰라요---i-dont-know-any-code)
  * [소통하기](#5-소통하기)
  * [라이선스](#6-라이선스)

## 2. 목적
아마도 여기까지 오게된 분들은 지금 **_어쩌다보니_** 핵나잇에 와서 뻘쭘히 자리에 앉으셨거나 **_어쩌다보니_** 링크를 잘못 눌러서 들어오셨거나 (~~아니면 구글 크롤러거나~~) 이겠죠? 누군가의 서버에 침투하기 위해서가 아니라 서울이 가진, 도시가 가진 문제를 해결하는데에 기여하기 위한 해킹을 하기위해 **_어쩌다보니_** 들어오게 되셨을 것이라고 생각합니다.

Those who have come so far have perhaps joined us at a hacker night or followed some wrong link? (Perhaps you are google crawler) . Our goal is not to hack some servers, but to use our coding skills to solve Seouls problem. Come hack with your friends and contribute solving some of our cities problems.

자, 그럼 지금부터 코드포서울에서 시빅 해커가 되기 위한 첫걸음을 돕기 위하여 지금 어떤 프로젝트가 진행되고 있는지(**참여하세요!**) 서울의 어떤 점을 시민들이 불편해하고 있는지(**새로 시작하세요!**) 그리고 다른 코드포서울 사람들과 어떻게하면 친해질 수 있는지 자세히 알려드립니다.

## 3. 진행중인 프로젝트

### a. [Where Does My Money Go?] (http://wheredoesmymoneygo.kr)
  * _1.0 공개 || 2.0 개발중_ (_1.0 released || 2.0 under development_)
  * **문제**: 우리가 내는 세금은 도대체 어떻게 사용되고 있을까요? 막연히 나의 세금이 좋은 곳에, 알맞는 곳에 쓰이겠지라는 믿음으로 꼬박꼬박 세금을 내고 있지만 (~~과연 그래서?~~) 잘 쓰이고 있는지 도통 알 길이 없죠.
  * **Problem**: How are our taxes being used? We believe ours taxes are being used for a good or right cause (do we?), but how can we be can not be sure about it.
  * **해결 방법**: 정부에서 공개하는 세금 데이터를 긁어 모아서 시민들이 이해하기 쉽게 보여주면 어떨까요? 전 세계 세금 데이터 플랫폼 [OpenSpending]()과 오픈소스 프로젝트 [WhereDoesMyMoneyGo?]()를 이용하여 시민들의 세금이 어떻게 쓰이고 있는지 보여주고자 만들었습니다.
  * **Solution**: What about summing up and showing our citizens in a easy and comprehensible way all the taxes information our government has made public? By benefiting from the OpenSpending tax platform and WhereDoesMyMoneyGo? open source project, we have created a project that helps our citizens by allowing them to easily understand where their taxes are going to.
  * **소스코드 / Repository** 
    * https://github.com/codeforseoul/wheredoesmymoneygo.kr
    * 세금 계산 알고리즘: https://github.com/codeforseoul/taxman
  * **슬랙 채널 / Slack channel**: #wheredoesmymoneygo

### b. 알뜰 서울의 발견
  * _개발중_ (_under development_)
  * **문제**: 우리가 살고 있는 도시에서, 자치구에서는 시민들을 위해 많은 서비스를 제공해주고 있습니다. 하지만 나에게 필요하고 내가 받을 수 있는 혜택들이 무엇이 있는지는 어디하나 정리된 곳이 없죠.
  * **Problem**: Within our city, there are many public services for each and every citizen. Still, there is no central place that shows what are the benefits of the services that I am entitled to.
  * **해결 방법**: 곳곳에 흩어진 데이터를 모아서 시민들이 받을 수 있는 혜택들을 일목요연하게 보여주고자 합니다. 나에게 딱 맞는 혜택만을 골라서 검색해볼 수 있을 것입니다. 알뜰한 서울을 발견하게 되는 것이죠!
  * **Solution**: Group all the scattered data on benefits that citizens can receive and display it in a central place. Allow the user to search for the benefits that best fits his need. A cheap way to get to know Seoul's benefits.
  * **소스코드 / Repository**
    * https://github.com/codeforseoul/FdAS
    * 데이터 스크래퍼: https://github.com/codeforseoul/FdAS_crawler
  * **슬랙 채널 / Slack channel**: #fdas

### c. 서울 맑음 (Seoul Serenity)
  * _개발중_ (_under development_)
  * **문제 / Problem**: 한 해 지방 정부에서 관리해야 하는 프로젝트가 200여개가 넘습니다. 도시의 시장님과 몇 분의 공무원분들이 모든 프로젝트를 관리하는데 어려움이 따를 수 밖에 없죠. 시정의 효율성이 떨어질 수 밖에 없습니다.
  * **해결 방법**: 어떤 프로젝트가 잘 진행되고 있고 어떤 프로젝트는 피드백이 필요한 상황인지 잘 구분해줄 수 있으면 어떨까요? 천둥부터 맑음까지 날씨 아이콘을 통해 바로 피드백이 필요한 프로젝트를 날씨로 표현해보고자 합니다.
  * **Solution**: What about letting us know which project is progressing and which one requires feedback? Let us know which project needs feedback by displaying the information in a weather way, from a thunderstorm to clear skies.
  * **소스코드 / Repository**
    * https://github.com/codeforseoul/seoul_serenity
  * **슬랙 채널 / Slack channel**: #seoul_serenity

### d. Hangul Romanization
  * _개발중_ (_under development_)
  * **문제**: 현재 사용되는 '국어의 로마자 표기법'은 영어권 사람들에게 많은 혼란이 있습니다. 강남스타일? 갱넴 스타일?
  * **Problem**: Most Westerners in English-speaking world often encounter discrepancy with the current Korean Romanization system for Hangul, due to several reasons including subtlety of specific vowels to the untrained ears, inconsistency within vowels in English language, and so on.
  * **해결 방법**: 영어권 사람들이 한글을 접할 때 쉽게 발음할 수 있도록 간단한 가이드라인을 제시하려고 합니다.
  * **Solution**: Our purpose is not to revise the current system but to offer a simple guideline to pronouncing Hangul.
  * **소스코드 / Repository**
    * https://github.com/codeforseoul/hangul 
  * **슬랙 채널 / Slack channel**: #hangul

## 4. 새로 시작하기 - Where to start

### a. 도움이 필요한 문제들([바로가기](https://github.com/codeforseoul/seoulproblems)) - Seoul Problems
IT기술로 서울을 변화시켜보고 싶다! 하지만 뭘 해야 할 지 모르겠다구요? 코드포서울에서는 서울에 어떤 문제들이 있는지 생각들을 모아보고 있습니다. 어떤 프로젝트를 해야할 지 망설여진다면 여기 적힌 문제들을 한 번 살펴보세요.

### b. 해외 오픈소스 사례들 - Overseas opensource examples
해외에서는 자기가 살고 있는 지역 사회를 위해 많은 오픈 소스 프로젝트들이 공개되어 있습니다. 코드포서울의 WhereDoesMyMoneyGo?도 오픈 소스 프로젝트를 우리나라에 맞게 활용한 것이죠. 오픈 소스 프로젝트야 말로 시빅 해킹을 쉽게 시작할 수 있는 한 방법입니다!

  * [Adopt a Hydrant](http://www.adoptahydrant.org/)

### c. 나는 코드를 몰라요! - I don't know any code!
코드를 몰라서 코드포서울에 참여하기 겁나신다구요? 코드가 아니여도 서울을 위해 기여할 수 있는 방법은 얼마든지 있습니다! 여러분의 능력을 보여주세요!
Are you scared of joining Code For Seoul since you don't know how to code ? Even if you are not a coder there are several ways to contribute with Seoul. Show us your skills!

  * 번역하기 (Help us translating the content)
  * 데이터 찾기 (Help us looking for data)

## 5. 소통하기 - Contact
  * [Slack](https://slack.com/): 슬랙은 별도로 초대를 받아야 가입할 수 있습니다. 참여를 원하시는 분은 codeforseoul@codenamu.org 로 메일을 보내주세요! You need an invitation to join us at slack. Send us an email at codeforseoul@codenamu.org!
  * Github: https://github.com/codeforseoul
  * 페이스북 그룹: https://facebook.com/groups/codenamu
  * 페이스북 페이지: https://facebook.com/codenamu
  * 트위터: https://twitter.com/codeforseoul_

## 6. 라이선스 - License
[CC0] (LICENSE)
