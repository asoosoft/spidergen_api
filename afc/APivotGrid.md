# APivotGrid
**Extends**: [`AView`](AView.html#aview)

APivotGrid 컴포넌트.

<br/>
  
## Properties



## Instance Methods


### init(context, evtListener)
 

### _initEx()

//Ex 관련 초기화


### _qryLoadDone(aquery)

//pivot scroll 그리드에 매핑정보를 전달하는 함수
//로드시점에 pivotGrid 즉 하위 컴포넌트가 초기화되기 전인 경우에는 무시한다.
//현재 컴포넌트의 init 시점에도 호출하여 지금까지 로드된 매핑정보를 전달한다.

### _setChildQueryInfo(aquery)
 
### getPivotGrid()
 

### _applyOptionToChild()
 
### calcHeight()
 

### setMainGridWidth(width)
 

### getMainGridWidth()
 

### setPivotGridWidth(width)
 

### getPivotGridWidth()
 
### _getDataStyleObj()
 
### _setDataStyleObj(styleObj)

// object 형식의 css class 값을 컴포넌트에 셋팅한다.
// default style 값만 셋팅한다.



### getMappingCount()

// 매핑가능한 개수를 리턴한다.


### showHeader()
 
### hideHeader()
 
### showFooter()
 
### hideFooter()
 
### enableScrollIndicator()
 
//APivotGrid 가 스크롤 가능 영역에 추가되어져 있을 경우
//APivotGrid 스크롤이 끝나고(ex, scrollBottom) 상위 스크롤이 연속적으로 발생되도록 하려면
//상위 스크롤은 enableScrlManager 가 호출되어져야 하고 자신은 overscrollBehavior 함수를 호출해야 한다.


### overscrollBehavior(disableScrlManager)


### lockScrollView()


### unlockScrollView()
 

### scrollViewLeft()
 
### setData(pivotData, scrollData)
 

### addRow(pivotData, scrollData)

//하나의 row 를 추가한다.
 

### addRows(pivotInfoArr2, scrollInfoArr2, pivotRowData2, scrollRowData2)
 
//데이터가 많은 경우 addRow 를 여러번 호출하는 것보다
//addRows 로 한번에 추가하는 것이 성능적으로 유리하다. 


### prependRow(pivotData, scrollData)
 

### setRow(rowInx, pivotData, scrollData, start, end)
 
### removeRow(rowIdx)
 
### removeFirst()
 
### removeLast()

### removeAll()
 
### createBackup(maxRow, restoreCount)
 
### destroyBackup()
 
### setDirectBackup(isDirect)

//추가되는 순간 화면에 표시되지 않고 바로 백업되도록 한다. append 인 경우만 유효


### applyBackupScroll()
 
### getSelectedCells()

//isFullRowSelect 가 참이면 선택된 row 가 리턴된다.

### selectRows(startIdx, endIdx)

//endInx 가 생략되면 1개 선택


### _setAllGridSelect()
	
	//----------------------------------------------------------------
	//   select cell  
	//----------------------------------------------------------------
	//	isFullRowSelect 가 참이면 cellArr 은 tr element 의 array or jQuery 집합.
	//	rowSet 이 여러개인 경우 인 경우 여러개의 row 객체들을 가지고 있다.
	//	cellArr 는 element 를 담고 있는 배열이거나 jQuery 집합 객체이다.
	//	그룹지어야 할 cell 이나 row 들을 배열이나 jQuery 집합으로 모아서 넘긴다.
	//	※ 주의, cellArr 는 특정 cell 이나 row 를 그룹짓고 있는 배열이나 집합이므로 
	//	동등 비교를 할 경우 this.selectedCells[i][0] === cellArr[0] 과 같이 해야 함.
	//	그룹지어져 있는 경우 첫번째 원소의 주소만 비교하면 같은 그룹임


### _onGridSelect(acomp, info, e)
 
### _onGridScroll(acomp, info, e)
 
### _onGridScrollTop(acomp, info, e)
 
### _onGridScrollBottom(acomp, info, e)
 
### _onGridDblclick(acomp, info, e)

### setScrollComp(acomp)
 
### _onGridActionDown(comp, info, e)
 

### _onGridActionMove(comp, info, e)
 

### _onGridActionUp(comp, info, e)
 
### scrollTo(pos)
 
### scrollOffset(offset)
 
### scrollIntoArea(row, isAlignTop)

### scrollToTop()
 
### scrollToBottom()
 
### scrollToCenter()
 
### setUpdateType(updateType)
 
### setQueryData(dataArr, keyArr, queryData)
 
### getQueryData(dataArr, keyArr, queryData)
 