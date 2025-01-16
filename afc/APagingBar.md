# APagingBar
**Extends**: [`AView`](AView.html#aview)

APagingBar 컴포넌트.

<br/>


## Properties



## Instance Methods

 

### createElement(context)
이 함수가 실행된 이후에 init 함수가 실행된다.

### init(context, evtListener)

### clone(obj)
앏은 복사

return copy;

### isNumber(s)
	
### setReadOnly(isReadOnly)

### setDisabled(isDisabled)

### setTotalCount(cnt)

총 카운트 수

페이징뷰를 새로고침을 같이 진행케 한다.

* `cnt` \<Number> 총 카운트 수


### setPageIndex(idx)

현재 페이지 수

* `idx` \<Number> 현재 페이지 수


### setBlock(blk)

페이지당 레코드 수

* `blk` \<Number> 페이지당 레코드 수

총 카운트 수

### setPage(cnt, idx, per, blk)

기본 setter setting

* `cnt` \<Number> 총 카운트 수
* `idx` \<Number> 현재 페이지 수
* `per` \<Number> 페이지  수
* `blk` \<Number> 페이지당 레코드 수

### setIsCenter(bln)

가운데 유무(default: true)
* `bln` \<Boolean> 유무
	
 
### setParam(data)

전달할 정보 key/value setting

데이터를 세팅한다.

- `data` \<String> 데이터


### addParam(data)

데이터를 세팅한다.

- `data` \<String> 데이터

### getTotalCount()

총 카운트 수  리턴한다.

- **Returns** \<Number>
	 

### getTotalPage()

전체 페이지 수 리턴한다.

- **Returns** \<Number>
 

### getPageIndex()

현재 페이지 수 리턴한다.

- **Returns** \<Number>

### getPerPage()

페이지당 레코드 수 리턴한다

- **Returns** \<Number>


### getBlock()

총 카운트 수 리턴한다

- **Returns** \<Number>


### getPage()

기본 getter setting  리턴한다

- **Returns** \<Array>

 

### setComponent(acomp)

그리드, 리스트뷰 객체 


 
### setDelegator(delegator)
this 위임

 

 
### setPageView()

 
### getDroppable()

컴포넌트 내부에 드랍 가능여부 리턴

- **Returns**  `false`


