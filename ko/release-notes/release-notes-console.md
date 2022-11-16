## Game > GameAnvil > 릴리스 노트 > Console

### 1.0.5 (2021.07.13)

#### Change

* 인스턴스 설정의 각 입력 값에 대한 가이드 문서를 최신화
* 인스턴스 중지 시 Kill로 강제종료 하지 않고 매니지먼트 노드를 통해 정상적으로 종료되도록 변경
* 인스턴스 설정 시 기본포트가 변경(신규 생성하는 인스턴스에 한함)

#### Fix

* 인증 필터의 순서가 명시적이지 않아 간헐적으로 오류 발생하는 현상 수정

---

### 1.0.4 (2021.06.15)

#### New

* 일문 번역 적용

#### Change

* 모니터링 시 오탐지를 줄이기 위해 모니터링 실행 주기와 에러 허용 횟수 변경

---

### 1.0.3 (2021.05.25)

#### New

* 서비스 생성만 가능하고 수정 및 삭제가 되지 않아 별도 관리 페이지 생성

#### Change

* 기존 인스턴스 설정을 노드 단위로 저장 및 관리하던 방식에서 인스턴스 단위로 저장 및 관리하도록 변경
* VM Option 입력 메시지를 10,240바이트까지 입력할 수 있도록 변경

#### Fix

* 인스턴스 설정 생성 시 각 노드의 사용자 가이드가 정상적인 가이드 페이지로 이동하도록 수정

---

### 1.0.2 (2021.04.27)

#### New

* 영문 번역 적용

#### Change

* VM Option 입력 메시지를 512바이트까지 입력할 수 있도록 변경
* Toast UI Chart Vue 버전 4.2.1로 적용

#### Fix

* 머신 설정 오류 발생 시 재시도 버튼을 누르면 무조건 Java 11로 셋팅되는 문제 수정
* 인스턴스 등록에서 머신 선택 시 필터링 된 상태의 전체선택 문제 수정

---

### 1.0.1 (2021.03.23)

#### Change

* 등록된 머신이 없을 때 인스턴스 등록화면 접근 시 머신등록 페이지를 안내하도록 변경
* 머신 파일 업로드 후 머신 목록 리스트로 이동하도록 변경
* 모니터링 대시보드 동시접속자 변화 그래프 데이터가 몇시 몇분 데이터인지 표시하도록 변경
* 인스턴스 등록 / 수정 화면에서 Port 입력란 아래 중복 체크 버튼을 Port 중복 체크로 문구 변경

#### Fix

* 노드 모니터링에서 선택 안하고 Resume / Pause 눌렀을 때 안내 팝업 나오도록 수정

---

### 1.0.0 (2021.02.23)

#### New

##### GameAnvil Console 출시

* 동시접속자 변화를 확인할 수 있으며 유저 분포를 모니터링 할 수 있습니다.
* GameAnvil 엔진 서버를 관리할 수 있습니다.
* 인스턴스, 노드에 발생 한 이벤트를 조회할 수 있습니다.