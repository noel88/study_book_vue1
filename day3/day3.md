- 라우팅이란

웹 페이지 간의 이동 방법. 라우팅을 이용하면 화면 간의 전환이 매끄러울 뿐만 아니라 애플리케이션의 사용자 경험을 향상시킬 수 있음.

- 뷰 라우터

뷰 라우터는 뷰에서 라우팅 기능을 구현 할 수 있도록 지원하는 공식 라이브러리.

<router-link to="URL값"> : 페이지 이동 태그. 화면에서는 <a>로 표시되며 클릭하면  to에 지정한 URL로 이동.

<router-view> : 페이지 표시 태그. 변경되는 URL에 따라 해당 컴포넌트를 뿌려주는 영역.

<이미지 1>--------

- $mount() api

el 속성과 동일하게 인스턴스를 화면에 붙이는 역할. 인스턴스를 생성할 때 el 속성을 넣지 않았더라도 생성하고 나서 $mount()를 이용하면 강제로 인스턴스를 화면에 붙일 수가 있음.

- 네스티스 라우터

라우터로 페이지를 이동할 때 최소 2개 이상의 컴포넌트를 화면에 나타낼 수 있음. 상위 컴포넌트 1개에 하위 컴포넌트 1개를 포함하는 구조.

<이미지2>--------

- 네임드 뷰

특정 페이지로 이동했을때 여러개의 컴포넌트를 동시에 표시하는 라우팅 방식. 같은 레벨에서 여러 개의 컴포넌트를 한번에 표시.

<이미지3>--------

- 뷰 리소스

<이미지4>---------

- 엑시오스

뷰 커뮤니티에서 가장 많이 사용되는 HTTP통신 라이브러리

**액시오스 설치 및 사용하기**

```javascript
//HTTP get요청
axios.get('url 주소').then().catch();

//HTTP post 요청
axios.post('url 주소').then().catch();

//HTTP 요청에 대한 옵션 속성 정의
axios({
	method: 'get',
	url: 'url 주소',
	.....
});
```

<이미지5>-------
