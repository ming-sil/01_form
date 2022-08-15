# form, input 태그

## 01 text

### ```<input type="text" placeholder="검색어를 입력하세요.">```

- 입력란에 글자를 작성할 수 있는 태그
- 기본 인라인 블럭 요소로 크기값도 적용되며, 옆으로 정렬 됨
- placeholder는 input태그에 글자를 미리 적어둘 수 있음


## 02 button, submit

### ```<input type="button" value="검색">```

 - button 속성값에 value를 넣으면 원하는 글자를 적을 수 있음
 - (페이지 내에서)이벤트를 적용할 때 사용
 
### ```<button>```, ```<input type="submit" value="검색">```

- 폼에 작성한 내용을 전달할 때 사용
- 인풋태그에 담긴 내용을 폼태그에 전달함


## 03 checkbox, radio

### ``` <input type="checkbox" name="check" id="check_1">
        <label for="check_1">선택1</label>
        
        <input type="checkbox" name="check" id="check_2">
        <label for="check_2">선택2</label>```
        
- label 태그와 체크박스 연결할 때는 반드시 인풋태그에 id값을 정의하고, label태그의 for속성 안쪽으로 연결하고자 하는 id명을 넣어주면 됨
        
### ```<input type="radio" name="tab" id="tab_1">
       <label for="tab_1">선택1</label><br>
       
       <input type="radio" name="tab" id="tab_2">
       <label for="tab_2">선택2</label>```
       
- 중복체크 하지않을 때 사용
- name 사용으로 같은 그룹 속성으로 지정할 수 있음
   
   
## 04 password, date, time, color

### ```<input type="password">```
- 패스워드 입력

### ```<input type="date">```
- 달력(날짜) 선택

### ```<input type="time">```
- 시간 선택 
       
### ```<input type="color">```
- 컬러 선택
        
