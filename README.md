# styleWeb 버전 업데이트 현황

#### 1.x Releases
- `1.0.x` Releases - [1.0.0] | [1.0.1] | [1.0.2]| [1.0.3]| [1.0.4]| [1.0.4_1]

---
## 1.0.4_1

업데이트 일시 : 2018-08-16

#### Updated
[1. 폼스타일 모음 페이지 추가]
/styleWeb/formStyle.html

[2. 셀렉트 플러그인 변경]
'Searchable-Dropdown-Select-jQuery-Selectstyle' 플러그인으로 변경
이전에 사용했던 검색창 셀렉트박스는 한페이지내에서 여러개를 사용할 경우 스크립트 오류발생.
변경된 플러그인에서는 옵션 변경이 html 페이지에서 가능하며, theme 설정 기능이 있음.
```
ex.
<span class="formControl">
<div class="selectControl styleXSmall">
    <select placeholder="select search XSmall" data-search="true">
        <option value="">select search XSmall</option>
    </select>
</div>

```
[3. 폼스타일 추가 - radio, check, button]
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
## 1.0.4

업데이트 일시 : 2018-08-14

#### Updated
[1. 로그인 페이지 추가]
/styleWeb/login.html

---
## 1.0.3

업데이트 일시 : 2018-08-13

#### Updated
[1. 폼 스타일 : 모듈화 진행]
- active, focus 컬러 통일 
$beforeActive-color: #8c8c8c;


---

## 1.0.2

업데이트 일시 : 2018-08-10

#### Updated
1) font-family 업데이트 
NanumGothic 폰트에서 Poppins 폰트로 우선순위 높임
```
font-family: Poppins,sans-serif,'Nanum Gothic', sans-serif, 'Source Sans Pro';
```
2) 폰트 우선순위 변경으로 아이콘과 폰트간의 line-height 수정
3) nav 폰트 투뎁스 hover 색상 지정, 아이콘 색상 톤다운
---

## 1.0.1

업데이트 일시 : 2018-08-09

#### Updated
[1. 폼 스타일 : 모듈화 진행]
1) input type="text" 또는 .dropDown 의 부모요소에 .formControl 클래스명이 있을 경우 기본적인  폼 스타일이 적용됩니다.
2) .simple-select 의 부모요소에 .formControl 클래스명이 있을 경우 기본적인  폼 스타일이 적용됩니다.
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

[3. 폼 스타일 : input type="text" 스타일 추가]
1) 부모요소에 .formControl 클래스명이 부여되어있는 input type="text" 에 .simpleLine 클래스명 추가시 보더스타일이 하단에만 적용 되어있는 심플라인 스타일이 적용됩니다.

```
ex.
- <input class="styleSmall simpleLine" type="text" placeholder="">
```


---
## 1.0.0

업데이트 일시 : 2018-08-09

#### Updated
styleWeb layout 업데이트 

---
