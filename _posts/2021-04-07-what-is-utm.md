---
layout: post
permalink: /posts/what-is-utm/
title: 'UTM에 대해 알아보자'
date: 2021-04-07 16:36:00 +09:00
feature: '/img/posts/09/blog_post_thumbnail9.png'
background: '/img/posts/09/blog_post_header9.jpg'
categories:
  - basic
tags:
  - URL
  - 마케팅
  - 디지털 마케팅
  - UTM
  - 구글
  - 네이버
  - 검색
description: 디지털 마케팅은 데이터 수집, 분석, 결과, 개선, 다시 수집 순으로 진행됩니다. 이들은 동시에 진행되는게 아니라 순서대로 진행되는 만큼 데이터 수집을 명확하게 하지 않으면 다른 순서들도 엉망이 되어버리죠. 이번 시간에는 데이터 수집에 필요한 UTM에 대해 알아보겠습니다. 
---
### **디지털 마케팅에서의 측정**

디지털 마케팅은 데이터 수집 → 분석 → 결과 → 개선 → 수집 순으로 돌아가게 됩니다. 동시에 진행되는 것이 아니라 순서대로 진행되기 때문에 수집이 잘못되면 분석도 잘못된 결과를 도출할 수 밖에 없고, 문제와 다른 개선 방향이 나올 수 밖에 없죠. 따라서 여기서 가장 중요한 것은 `수집`입니다. 수집은 `측정`이라고 말하기도 하는데, 바로 고객의 행동 데이터를 가져오는 것이죠. 디지털 마케팅에서 가장 중요한 것입니다.

![digital marketing](/img/posts/09/01.png)

우리는 수집하는 방법 중 가장 기본적인 방법인 UTM에 대해서 배워볼 거예요. 우리 웹사이트에 들어오는 고객들이 어떤 코스를 이용해서 우리 웹사이트에 알아보는 것과 같죠. 예를 들면 우리 매장에 방문하는 고객님이 지인 소개로 왔는지, 지나가다가 간판 보고 들어왔는지, 전단지를 보고 왔는지, 내 SNS를 보고 들어왔는지 파악하는 것입니다. 오프라인 매장에서는 모든 고객님에게 일일이 물어보긴 힘들지만, 디지털에서는 대부분 파악할 수 있습니다. 바로 Referrer이라고 불리는 URL을 통해서죠. 

![referrer](/img/posts/09/02.png)

우리 웹사이트에 들어오기 전에 어떤 URL을 보고 있었는지 파악할 수 있습니다. 예를 들면 페이스북에서 우리 웹사이트로 들어오는 링크를 클릭했다면. facebook이라고 나타나고, 인스타그램이라면 instagram.com이라고 나타나죠. 한가지 아쉬운 점은 카카오톡과 같은 일반 메신저에서는 kakaotalk이라고 나타나지 않는다는 점입니다. 하지만 이것조차도 수동으로 파악할 수 있게 만들어주는게 바로 UTM입니다. 우리가 이 링크는 이제부터 kakaotalk에서만 공유할거야~ 하며 kakaotalk 이란 키워드를 링크에 넣어서 전달해주면 그 링크를 클릭한 사람은  카카오톡에서 우리 웹사이트로 접속한 상태가 되는거죠.

![utm](/img/posts/09/03.png)

### **URL의 구조**

이렇게 링크를 UTM으로 만들기 위해서는 URL의 구조에 대해서 어느정도 알 필요가 있습니다. 완전히 알아야 하는건 아니지만 이해하고 있으면, 이제 다른 마케터들이 어떻게 UTM을 사용하고 이 웹사이트는 어떻게 URL이 만들어져 있는지 쉽게 파악하실 수 있을거예요.

![url structure](/img/posts/09/04.png)

`레어케어`라고 검색했을 때 나오는 네이버의 URL입니다. 이를 위와 같은 형태로 나눠보죠

https : https 입니다. ssl 보안인증서가 붙어있습니다.
://search.naver.com : 도메인 입니다. 
/search.naver : /로 이어져있는 패스입니다.
?where=nexearch : ?로 이어져있는 파라미터입니다. 파라미터에서 where라고 되어있는 곳은 탭이 변경될때마다 바뀌는 걸 볼 수 있습니다.
&sm=tab_jum : ?
&query=레어케어 : 검색 결과입니다. `레어케어`라고 검색해서 쿼리에 `레어케어`라고 나왔으니, 이 부분만 단어를 바꿔준다면? 검색 결과가 바뀌게 됩니다.

![utm example](/img/posts/09/05.png)

### **UTM이란?**

UTM이란 GA에서 유입된 곳을 확인하기 위한 추적 기능입니다. 돼지 농장에 가면 우리가 보기엔 다 똑같이 생긴 돼지들인데 언제 어디서 태어났고, 몇살이나 됐는지 태그를 붙이는 것처럼 어떤 사이트에서 우리 사이트에 들어왔는지 성과가 얼마나 났는지 파악할 수 있죠.

![what is utm](/img/posts/09/06.png)

### **UTM의 구조?**

![utm structure](/img/posts/09/07.png)

### **UTM 만들기**

UTM을 만드는 곳은 여러 사이트가 있습니다. 구글 애널리틱스 도움말에 들어가면 아래 사이트를 추천해주고 있습니다.

![Url builder1](/img/posts/09/08.png)

[https://ga-dev-tools.appspot.com/campaign-url-builder/](https://ga-dev-tools.appspot.com/campaign-url-builder/)

또는 규칙을 지정해야하니 버튼 형식으로 클릭하면 UTM을 생성할 수 있는 아래 사이트도 있습니다.

![Url builder2](/img/posts/09/09.png)

[https://www.ttmkt.com/tools/google-utm-builder/](https://www.ttmkt.com/tools/google-utm-builder/)

UTM을 만들 때는 캠페인, 소스, 미디움, 콘텐츠 등 하나의 캠페인에 여러 이름을 사용해선 안됩니다. 하나의 캠페인에 여러 소스가 찍히면 데이터 측정이 불편하기 때문이죠. 따라서 꼭 규칙을 만들어서 적용할 하고 링크를 명확하게 관리하셔야 합니다.