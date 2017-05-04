---
layout: single
title:  "Spring boot 기반에서 jackson을 이용해서 LocalDateTime을 변환 시 특정 format으로 일괄 적용하기"
---
1. Introduction

기본적으로 Spring boot는 jackson과 통합이 되어 있어서 몇가지 설정을 하면 ISO 8601 포맷으로 LocalDateTime을 편하게 serialize할 수 있었다. 

