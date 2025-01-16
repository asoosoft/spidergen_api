# AVideo
**Extends**: [`AComponent`](./AComponent.md)

비디오 컴포넌트.

<br/>


## Properties



## Instance Methods


### init(context, evtListener)

비디오 컴포넌트를 생성하고 초기화 할 때 호출한다. <br/>동적으로 객체를 생성할 경우 파라미터를 생략하고 호출한다.

- `context` \<String> 컴포넌트 생성 및 초기화 정보
- `evtListener` \<String> context 에 매핑된 이벤트 수신자
 
<br/>


### setSource(url)

비디오 url를 지정한다.

- `url` \<String> url 경로

<br/>


### getSource()

비디오 url를 정보를 가져온다.

<br/>



### setData(data)

비디오 컴포넌트  저장된 value값과 같은경우 체크한다.

- `data` \<Any> 세팅할 데이터

<br/>

### getData()


컴포넌트에 세팅된 데이터를 추출한다.