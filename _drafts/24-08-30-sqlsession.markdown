---
layout: post
title:  "SqlSession"
date:   2024-07-27 15:37:39 +0900
categories: jekyll update
---

SqlSessionFactory를 통해
sqlsession을 사용할 수 있다.

session을 사용하는 이유 :
- 매핑 구문 실행
- 커밋, 롤백 수행
- 안쓰면 종료

= mybatis spring연동 모듈 사용 시, sqlsessionfactory 불필요
쓰레드에 안전한 sqlsession객체가 스프링 빈에 주입되기 때문


