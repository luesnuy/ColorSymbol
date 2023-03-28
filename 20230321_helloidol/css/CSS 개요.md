selector {
     attribute: value;
}

* 
#id 
.class
TAG

/*주어진 값을 class 속성값으로 가진 html요소를 찾아 a selector1 selector2*/
/*하위(후손)선택자(descendant selector) : 지정된 모든 하위 요소에 스타일 적용*/
selector1>elector2 {}

/*자식 선택자(child selector) : 자식요소에만 스타일을 적용*/
selector1,
selector2 {}

/*인접 형제 선택자(adjacent selector) : 형제요소1과 가장 가까운(그중 첫번째) 형제 요소에 스타일 적용*/
selector1+selector2 {}

selector1~selector2 {}

selector:first-child() {}

selector:nth-child() {}

selector:hover {}

우선순위 1. !important 2. #id 3. .class 4. TAG 5. * 6. 같은 우선순위 일때,
나중에 쓴게 적용