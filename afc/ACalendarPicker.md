# ACalendarPicker
**Extends**: [`AView`](AView.html#AView)

캘린더 피커

## Properties



## Instance Methods

 
### createElement(context)

이 함수가 실행된 이후에 init 함수가 실행된다.

### init(context, evtListener)

컴포넌트 객체를 생성한 후 초기화 할 때 호출한다. 코딩을 이용하여 동적으로 객체를 생성할 경우 사용한다. 일반적으로 파라미터를 생략하여 기본값으로 생성 되도록 해준다.

- `context` \<String> 컴포넌트 생성 정보
- `evtListener` \<String> 이벤트 발생 시 수신할 객체

### getDate()
 
### getDateString()
 
### getDiffDate(gap)
 
### setDate(date)

### setCalendarIconLeft()
 defailt Calendar Icon - Left
  
### setCalendarIconRight()
 defailt Calendar Icon - Right

### setCalendarIconImage(img)
 
### setCalendarPickerStyle\<Object>
 
### setCalendarPickerSelectedStyle\<Object>
 
### setCalendarIconStyle\<Object>
 
### setCalendarInputStyle\<Object>
 
### openPopup()
 
### setPartner(type, cal)

### setReadOnly(isReadOnly)
 
### setDisabled(isDisabled)
 
### getPartner()
 
### getMode()
 
### setQueryData(dataArr, keyArr, queryData)

### setData(data)
 
### getQueryData(dataArr, keyArr, queryData)
 
### updatePosition(pWidth, pHeight)

- `pWidth` \<Number>
- `pHeight` \<Number>
- **Returns** \<HTMLObject>

### getMappingCount()

   매핑가능한 개수를 리턴한다.

### getDroppable()

   컴포넌트 내부에 드랍 가능여부 리턴 

### setCalendarViewStyle\<Object>

  CalendarView Style

### setHeadViewStyle\<Object>

  HeadView Style

### setYearMonthBtnStyle\<Object>

  YearMonthBtn Style

### setLLeftArrowBtnStyle\<Object>

  LeftLeftArrowBtn Style

### setLeftArrowBtnStyle\<Object>

  LeftArrowBtn Style
 
### setRRightArrowBtnStyle\<Object>

  RightRightArrowBtn Style
 
### setRightArrowBtnStyle\<Object>

  RightArrowBtn Style

### setHeadGridStyle\<Object>

  HeadGrid Style

### setListGridStyle\<Object>
 
  ListGrid Style

### setHeadGridTdStyle\<Object>

  HeadGrid Td Style

### setHeadGridTdFirstStyle\<Object>

  HeadGrid Td(firstChild - Sunday) Style

### setHeadGridTdLastStyle\<Object>

  HeadGrid Td(lastChild - Saturday) Style

### setListGridTdStyle\<Object>

  ListGrid Td Style

### setListGridTdFirstStyle\<Object>

  ListGrid Td(firstChild - Sunday) Style

### setListGridTdLastStyle\<Object>

  ListGrid Td(lastChild - Saturday) Style

### setListGridTdSelectedStyle\<Object>

  ListGrid Td selected Style
