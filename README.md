# JavaScript-jQuery
    with WebStorm, Atom

    Variable
    변수는 데이터를 저장하는 장소
    변수는 데이터를 읽고 쓰고 할 수 있는 장소
   
    How to use Variable
    특정 사이트의 로그인 상태 유무
    사용자가 선택한 메뉴항목
    사이트에 멋지게 출력돼 있는 메뉴 항목
    슈팅게임에서 현재 기록 중인 게임 점수
    슈팅게임에서 현재 남아있는 캐릭터의 에너지
    쇼핑몰 장바구니에 담겨 있는 상품목록
    화면 가특 출력된 게시물 목록
    
    Caution
    01_숫자로 시작 하면 안된다.
    var 1st = 10; // error
    02_대소문자 구분:name과 Name은 완전히 다른 변수.
    var name = "samara";
    var NAme = "samara";
    03_변수는 대문자가 아닌 소문자로 시작.
    var Name = "samara";
    대신
    var name = "samara";
    04_변하지 않는 환경 변수의 갑을 담는 상무 변수는 모두 대문자로 만든다.
    var DB_NAME = "samara";
    var ADMIN_ID = "samara";
    05_여러 단어가 조합되는 경우 다음과 같이 낙타 표기법(camelcase)으로 작선한다.
    var userName = "samara";
    var selectMenuIndex = "1";
    06_자바스크립트에서 이미 정의된 예약어(키워드)를 사용하면 안된다.
    break, case, catch, continue, default, do, else, finally, for, function, if, in
    instanceof, new, return, switch, this, throw, try, typeof, var, void, while, with
    
    var class = "test1";  //  error
    var for "test2";  //  error
    var if = "test3"; // error
    
    alert() 사용자에에 특정 정보를 팝업
    document.write() body 영역에 HTML 태그 정보를 출력
    console.log 전문 디버깅 함수 특정 변수 값 확인
    window.promp() 사용자로부터 값을 입력 받음
    
    변수 종류
    전역변수 전역에서 사용하는 데이터를 담는 변수 어디서든 접근 가능
    지역변수 특정 영역에서만 사용할 수 있는 변수 주로 함수 내부에 만들어지는 변수
    매개변수(파라미터) 함수 외부에서 함수 내부로 데이터를 전달하기 위한 용도로 사용하는 변수
    멤버변수(프로퍼티) 클래스 내부에 만들어지며 주로 객체에서 사용하는 정보를 담는 변수

    형변환 종류
    01. 암시적 형변환 
    자바스크립트 엔진이 필요에 의해 임시적으로 형을 자동으로 변환시키는 것
    02. 명시적 형변환
    개발자가 자바스크립트를 이용해서 직접 어떤 형으로 바꿀지 명시해주는 것
    
    암시적 형변환 종류
    숫자 형 + 문자 형 = 문자 형
    var a = 10+"10" = "1010"
    논리 형 + 문자 형 = 문자 형
    var a - true+"10" = "trye10"
    논리 형 + 숫자 형 = 숫자 형
    var a = true+10 = 11
