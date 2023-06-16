# 작동 환경
Dressing Room Management System은 Java JDK 1.8 환경에서 작동한다.

# 프로그램 실행 가이드
소스코드를 동작시키면 가장 먼저 로그인 화면이 등장한다. 이때, profileList.txt 파일에 정보가 등록되지 않은 사용자는 로그인이 불가능하며 Join을 통해 회원가입을 할 수 있다.
로그인을 성공하면 Clothes List 화면으로 넘어가며 Add를 통해 옷을 clothesList.txt 파일에 저장할 수 있다. 옷을 추가하고 View를 누르면 콘솔창에 입력한 옷의 정보가 나타난다. 로그아웃은 언제든지 가능하며 Logout 버튼을 누르면 된다. 또, Change 버튼을 누르면 Outfit List로 이동한다.
Outfit List에서는 Add를 통해 원하는 옷의 코디를 지정할 수 있다. 그리고 Clothes List와 동일하게 View, Logout, Change 버튼이 동일하게 작동한다.