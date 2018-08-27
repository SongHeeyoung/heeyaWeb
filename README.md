# heeyaWeb 버전 업데이트 현황

#### 1.x Releases
- `1.0.x` Releases - [1.0.0],[1.0.1] 


---
## 1.0.1

업데이트 일시 : 2018-08-14

#### Updated
[1. 로그인 페이지 추가]
/styleWeb/login.html

---

---
## 1.0.0

업데이트 일시 : 2018-08-09

#### Updated

아주 단순하지만 꼭 필요한 폼스타일을 제공합니다.
화려하지는 않지만 가볍고 쉽습니다.


[1. input type="text" ]
1) input type="text" 또는 .dropDown 의 부모요소에 .formControl 클래스명이 있을 경우 기본적인  폼 스타일이 적용됩니다.
2) .selectControl 의 부모요소에 .formControl 클래스명이 있을 경우 기본적인  폼 스타일이 적용됩니다.
```
ex.
-   <div class="formControl">
        <div class="dropDown styleXSmall" style="border-color: rgb(88, 201, 185);"> ... </div>
        <input type="text" value="" name="" />
    </div>

ex.
-   <div class="selectControl styleXSmall">
        <div class="simple-select">
        ....
        </div>
    </div>
```    
3) 부모요소에 .formControl 클래스명이 부여되어있는 input type="text" 에 .simpleLine 클래스명 추가시 보더스타일이 하단에만 적용 되어있는 심플라인 스타일이 적용됩니다.

```
ex.
- <input class="styleSmall simpleLine" type="text" placeholder="">
```
[2. 폼 스타일 : xs,s,m 사이즈 정의]
1) .styleXSmall 
width:100px 고정 사이즈

2) .styleSmall
width:150px 고정 사이즈

3) .styleMedium
width:250px 고정 사이즈

```
ex.
- <span class="selectControl styleXSmall"> ... </span>
ex.
- <input class="styleSmall" type="text" placeholder="">
ex.
- <div class="dropDown styleMedium" style="border-color: rgb(88, 201, 185);"> ... </div>
```
[3. radio, check, button]
1) radiobox, checkbox 버튼 추가
- FontAwesome을 이용한 radiobox, checkbox 버튼 추가 
```
ex.
<div class="form_group">
    <div class="formControl">
        <input type="checkbox" id="c1" name="cc"/>
        <label for="c1"><span></span>옵션1</label>
        <input type="checkbox" id="c2" name="cc"/>
        <label for="c2"><span></span>옵션2</label>
    </div>
    <div class="formControl">
        <input type="radio" id="c3" name="rr"/>
        <label for="c3"><span></span>동의</label>
        <input type="radio" id="c4" name="rr"/>
        <label for="c4"><span></span>비동의</label>
    </div>
</div>
```
2) 기본 버튼스타일 추가
```
ex.
<button type="button" class="btn">기본1</button>
<button type="button" class="btn btn-basic2">기본2</button>
<button type="button" class="btn btn-warning">경고</button>
```
---


