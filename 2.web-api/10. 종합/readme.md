
\\<!-- 주석입니다. -->  

# 제목 1 (h1)
## 제목 2 (h2)
### 제목3 (h3)
#### 제목3 (h4)
##### 제목3 (h5)
###### 제목3 (h6)

이탤릭체는 *별표(asterisks)* 혹은_언더바(underscore)_
두꺼운 글씨는 **별 두개** 혹은 __언더바 두개__ 로 표기.
취소선은 ~~ 물결 두개~~ 를 사용.
<u>밑줄</u>긋기.



1.순서가 필요한 목록
1. 순서가 필요한 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브)


- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록(서브)
    - 순서가 필요하지 않은 목록(서브)

1. 순서가 필요한 목록
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)
    1. 순서가 필요한 목록(서브)



[NAVER](https://www.naver.com)
[GOOGLE](https://www.google.com "링크 설명(title) 작성")


[GITHUB][1]

문서 안에서 [참조 링크] 를 그대로 사용하는 것도 가능합니다.

[1]: https://github.com/woozz12
[참조 링크]: https://www.naver.com


![대체 텍스트를 작성합니다!](https://image.fmkorea.com/files/attach/new2/20210302/486616/3130483644/3426504955/856ae366223ed926c3a9541c771a149b.jpg "그림 설명입니다.")








```javascript
 for(let i=gameData.min; i<=gameData.max; i++) {
        const $icon = document.createElement('div');
        $icon.classList.add('icon');
        $icon.textContent = i;
        $frag.appendChild($icon);
    }

    $numbers.appendChild($frag);
    return $numbers;
}
```

```css
.list > li {
    position:absolute;
    top: 40px;
}
```

```html
<a href="http://www.naver.com">네이버로 가자</a>
```




















