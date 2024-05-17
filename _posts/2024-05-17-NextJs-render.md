---
title: NextJs가 사전 렌더링하는 방식
date: 2024-05-17 03:49:00 +0900
categories: [NextJs]
tags: [NextJs, 웹개발] # TAG names should always be lowercase
---

# 들어가기 앞서 사전렌더링(Pre-rendering)이란?

사전렌더링이란 서버에서 HTML을 렌더링하고 클라이언트에게 보내주는 과정이다  
NextJs는 기본적으로 사전렌더링을 한다

## 왜 필요한가?

1. 클라이언트의 부담을 덜기 위해서  
   기존의 방식은 서버에서 HTML, JS를 클라이언트에게 전송하고 클라이언트에서 렌더링하는 방식입니다.

# SSG(Static Site Generation)와 SSR(Server Side Rendering)

NextJs에서 두가지의 사전렌더링 방식을 지원한다
