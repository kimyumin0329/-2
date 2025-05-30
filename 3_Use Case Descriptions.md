# Use Case Descriptions – 공유 자전거 대여 시스템

| Use Case               | Actor Action                                                    | System Response                                                     |
|------------------------|------------------------------------------------------------------|----------------------------------------------------------------------|
| 회원 가입              | 사용자가 회원가입 화면에 접근한다.<br>필수 정보를 입력한다(ID, PW, 전화번호, 이메일) | 회원 정보를 저장하고 가입 완료 메시지를 표시한다.                     |
| 로그인                 | 관리자 또는 회원이 로그인 화면에 접근하여 ID, 비밀번호를 입력한다.       | 입력값 유효성 검사 후 성공 시 메인 화면을 표시하고, 실패 시 오류 메시지를 출력한다. |
| 로그아웃              | 로그인 상태에서 로그아웃 버튼을 클릭한다.                         | 세션 종료 후 로그인 화면으로 이동한다.                              |
| 자전거 등록            | 관리자가 자전거 등록 화면에 접근하여 정보를 입력한다(ID, 제품명, 유형, 대여소, 상태) | 입력값의 유효성을 검증하고 자전거 등록 완료 메시지를 표시한다.         |
| 자전거 대여            | 회원이 사용 가능한 자전거를 선택하여 대여 버튼을 클릭한다.             | 대여 처리 후 완료 메시지와 문자 알림을 전송한다.                     |
| 자전거 대여 정보 조회   | 회원이 현재 대여 중인 자전거 정보 메뉴에 접근한다.                   | 대여소, 자전거 ID, 제품명, 유형 등의 정보를 화면에 표시한다.          |
