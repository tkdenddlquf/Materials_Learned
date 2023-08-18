# VendingMachine
자판기를 Text와 GUI 모드로 나누어 제작, 하단의 기본 데이터를 정해진 경로에 미리 만들어 둔 뒤 진행한다.

## 기본 데이터(C:\Temp\menu.txt)
5  
1 물 1500 20  
2 밥 1000 30  
3 고기 1700 10  
4 커피 2000 20  
5 된장 3000 5  

## 기본 순서
- 돈 10000(만원)을 입력하고 된장을 구매한다.
- 돈 입력창에 -999를 입력한다.
- 관리자 메뉴에서 기존메뉴 수정을 클릭한다.
- 기존메뉴 수정에서 메뉴 5번을 선택한뒤 된장의 수량을 다시 5개로 변경한뒤 저장을 누른다.
- 기존메뉴 수정에서 메뉴 1번을 선택한뒤 삭제한다.
- 기존메뉴 수정에서 메뉴 3번을 선택한뒤 가격을 8000원으로 수정한뒤 저장을 누른다.
- 기존메뉴 수정에서 메뉴 2번을 선택한뒤 이름을 동전으로 바꾼다.
- 확인 버튼을 누르고 돈 입력창의 -999를 다시 입력시킨다.
- C:\Temp 경로로 들어가 Log.txt 파일을 확인한다.
- 끝

## 기본 기능
- 잔돈이 물건 각각의 물건 가격보다 높아지면 버튼이 활성화된다.
- 돈 입력창에 돈을 입력하고 입력 버튼을 누르면 잔돈이 올라간다.
- 잔돈 반환 버튼을 누르면 잔돈이 반환된다.
- 물건의 갯수가 0개가 되면 수량이 적힌 텍스트가 품절로 바뀐다

## 특수 기능
- 숫자 입력창에는 숫자가 아닌 다른 형식에 경고 문구가 뜬다.
- 돈 입력창에 -999를 입력하면 메뉴바가 활성화된다.
- 창의 크기는 버튼의 갯수에 따라 변한다.
