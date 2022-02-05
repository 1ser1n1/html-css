## 텍스트 스타일링

- **폰트 굵기**
   - `font-weight` 속성
   - 사용가능한 속성값: 100, 200, 300~900
   -  `font-weight: normal;`은 `font-weight: 400`과 똑같고, `font-weight: bold;`는 `font-weight: 700`과 똑같다!   
   
 - **텍스트 정렬**
   - `text-align` 속성
   - 사용가능 속성값: center, left, right
- **텍스트 꾸미기**
   - `text-decoration` 속성
   - 사용가능 속성값: underline, overline, line-through( 줄이 글자를 관통), None
   - `<a>` 태그에 밑줄을 없애기 위해 많이 사용
- **폰트 크기**
   - `font-size` 속성 사용   
   - | Absolute 절대적 | Relative(상대적)|
      |-|-|
      |px, pt| %, em|
   - `line-height` 속성: 각 줄이 실질적으로 차지하는 공간

- **폰트 설정**
   - | Serif| Sans-Serif | Monospace | Cursive(필기체) | Fantasy |
     |-|-|-|-|-|
     | "Time New Roman", times,  궁서체| Arial, 굴림체| Courier, Courier New | Cimic Sans MS, Monotype Corsiva| Iampact 등 특이한 글씨체|

- **폰트 파일 사용하기**
  - ````css
	   /* 폰트를 불러옴 */
    @font-face{
	    src: url("폰트위치");
	    font-family: "폰트이름"; /*폰트를 사용할때 적용할 폰트이름*/
	}
		/* 폰트를 사용 */
	p {
		font-family: "폰트이름";
    ````
