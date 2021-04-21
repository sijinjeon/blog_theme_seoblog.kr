---
layout: post
permalink: /posts/yoast-onpage-seo/
title: 'Yoast 플러그인을 통해 온페이지 SEO를 해보자'
date: 2021-04-21 20:57:00 +09:00
feature: '/img/posts/10/blog_post_header10.jpeg'
background: '/img/posts/10/blog_post_thumbnail10.png'
categories:
  - basic
tags:
  - 워드프레스
  - 마케팅
  - 디지털 마케팅
  - SEO
  - 구글
  - 네이버
  - 검색
  - Yoast
  - plugin
description: Yoast 플러그인을 설치하면 페이지에서 작성 중인 글에 대한 SEO를 적용할 수 있습니다. SEO 최적화 글을 많이 작성하신 분은 이미 머릿속에 힌트를 가지고 바로 작성할 수 있지만 대부분의 사람들은 그렇지 않죠. 그래서 이번에는 Yoast 플러그인을 설치하면 나타나는 힌트로 온페이지 SEO에 대해 알아보겠습니다. 
---
이번 시간에는 워드프레스의 SEO 최적화로 유명한 <bold>'Yoast 플러그인'</bold>을 통해 온페이지 SEO에 대해 알아보겠습니다. 온페이지 SEO는 글을 작성할 때 필요한 SEO기술입니다. 예를 들어 HTML에 흔히 말하는 "title", "h1", "h2", "h3"가 구조에 알맞게 배치된 문서거나, 문서에서 가장 중요한 키워드가 문서 내에 얼마나 적절히 배치됐는지 가독성은 얼마나 좋은지 등을 말하죠. 워드프레스에서 한 문단 정도의 글을 써보니 아래 7가지의 문제점이 발견됐는데요. 어떤 문제점인지 살펴보고, 하나씩 해결해보겠습니다.

## Outbound links: No outbound links appear in this page. Add some!

페이지 내에 아웃바운드 링크가 없으니 아웃바운드 링크를 넣어야 합니다. 아웃바운드 링크는 우리 블로그나 웹사이트 말고도 외부의 웹사이트로 보내는 걸 말하는데요, 우리 웹사이트에서 최대한 붙잡아 두어야 할 글인데 외부로 보내는게 이상하죠? 웹크롤러는 각기 다른 사이트들끼리 거미줄을 치면서 돌아다니는데, 우리 웹사이트에 들어왔는데 외부로 나가는 링크가 없다면 웹크롤러가 우리 웹사이트에서 작동을 멈추게 됩니다. 그렇게 되면 웹크롤러가 다른 곳으로 빠져나가지 못하고 사라지기 때문에 웹사이트 생태계를 구축하는데 어려움이 따르죠. 그래서 하나의 페이지는 꼭 외부로 빠져나가는 길을 최소한 하나는 만들어줘야 합니다. [전시진 워드프레스 블로그](https://sijinii.com)

## Internal links: No internal links appear in this page, make sure to add some!

내부 페이지로 연결되는 링크를 넣어야 합니다. Internal links는 내부 페이지 링크를 말해요. 제 블로그 내에 다른 글을 말하는거죠. 예를 들면 현재 글은 'Yoast 플러그인 을 통해 글 내에 있는 SEO를 기능을 맞춰보자'인데, 이 페이지에서 관련 페이지로 [UTM에 대해 알아보자](https://seoblog.kr/posts/what-is-utm/)를 넣어주는 겁니다. 그러면 글을 읽는 독자가 해당 글을 다 읽다가 또는 다 읽고 나면 관련된 다른 글을 보러가서 웹사이트의 체류 시간을 올려주는 역할을 합니다. 최대한 블로그 내에 체류 시간을 높이는게 목적이므로, 글마다 관련 포스트 링크를 달아두어 우리 사이트 내에 오랫동안 머물게 하는게 중요합니다.

## Keyphrase in introduction: Your keyphrase or its synonyms do not appear in the first paragraph. Make sure the topic is clear immediately.

핵심 키워드가 첫번째 문단에 들어가야 합니다. 이 글에서 가장 중요한 핵심 키워드를 선정했으면, 그 키워드가 첫 번째 문단에 들어가 처음 들어오는 독자가 이 문서는 어떤 목적으로 쓰여진 글인지, 어떤 키워드에 관한 글인지 쉽게 이해할 수 있게 만들어주는 겁니다. 잘 쓰여진 글을 보면 문단의 핵심 문장이 항상 첫번째 문장 속에 있는 것과 같은 맥락이죠. 웹크롤러도 핵심 키워드를 쉽게 찾을 수 있고, 글을 읽는 독자도 쉽게 핵심 키워드를 찾을 수 있으므로 SEO에 중요한 요소로 작용합니다.

![first paragraph](/img/posts/10/01.png)

## Image alt attributes: No images appear on this page. Add some!

이미지를 넣고, 이미지에 대체 텍스트를 넣어야 합니다. 블로그 글에 이미지가 하나도 없으면 문서를 읽는데 쉽게 지루해져서 사람들이 나가기도 합니다. 또한 이미지가 있지만 대체 텍스트가 없다면 웹크롤러가 이미지가 있는지 파악할 수도 없죠. 웹크롤러는 이미지를 넣을 때 들어가는 alt 속성을 통해 어떤 이미지가 들어있는 지 파악하는데, 이미지가 있지만 alt 속성이 없다면 이 페이지는 글만 있는 지루한 페이지라고 파악할 수 있습니다. 따라서 글이 쉽게 지루해지지 않도록 적정한 이미지와 함께 alt 태그를 삽입해야 합니다.

![first paragraph](/img/posts/10/02.png)

## Text length: The text contains 22 words. This is far below the recommended minimum of 300 words. Add more content.

문단의 길이가 짧습니다. 영어 단어 기준으로 한 문단에 최소 300단어 이상이 들어가야 좋은 글이라고 파악하는데, 제가 썼던 문장은 22단어 정도 밖에 없었어요. 따라서 문단에 내용을 더 채워넣고 글자수를 늘려야 합니다. 너무 짧은 글을 문단으로 만들어서 쓴다면 너무 가벼운 형태의 글로 보일 수 있습니다.

## SEO title width: The SEO title is wider than the viewable limit. Try to make it shorter.

제목의 길이를 줄여야 합니다. Yoast 플러그인을 설치하면 모바일 또는 PC에서 제 글이 검색되었을 때 어떤 형태로 미리보기가 나타나는지 볼 수 있습니다. 미리보기로 제가 잠깐 작성했던 아래의 글을 보면 파란색 큰 글씨가 제목부분인데 '생산성, ...'하고 글자가 짤린 모습을 볼 수 있습니다. 모바일에서 미리 볼 때는 제가 작성한 제목이 구글에서 보여주는 모습보다 길기 때문에 제목이 잘려 확실하게 제출되지 않을 수 있어 제목의 길이를 줄이라는 문구가 보이고 있습니다.

![first paragraph](/img/posts/10/03.png)