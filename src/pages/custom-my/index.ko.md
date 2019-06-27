---
title: JS 문장
date: '2019-06-28'
spoiler: Label 대해 알아보자.
---

# JS 문장

### Label

→ label 문은 break 문, continue 문에서 반복을 벗어날 때 연결용으로 사용합니다. break 문, continue 문에서 레이블을 사용하지 않아도 됩니다.

**문법**
```js
    // 식별자: 문장
    L: function F() {}
```

식별자(Idenitifier)는 식별할 수 있는 이름을 의미하며 유일한 이름을 사용합니다. 자바스크립트에서 사용하는 키워드,  예약어를 제외한 이름을 사용할 수 있습니다. 문장을 생략할 수 있지만, 콜론(:)은 작성 해야합니다. label 문과 continue 문에서 같이 다룹니다.

[https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Statements/label#레이블_continue문_사용하기](https://developer.mozilla.org/ko/docs/Web/JavaScript/Reference/Statements/label#%EB%A0%88%EC%9D%B4%EB%B8%94_continue%EB%AC%B8_%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0)

### return

→ return 문은 함수(function)에서 사용하며 return 문의 표현식 평가 결과를 반환합니다.

[문법]
```js
    //형태
    return;
    return 표현식;
```