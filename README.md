<div align="center">

# 김준규 · Mobile App Developer

사용자의 일상에 가까운 앱을 만듭니다.

**Android · Flutter · Unity**

Kotlin과 Jetpack Compose를 중심으로, Flutter와 Unity까지 앱 개발 경험을 넓혀왔습니다.

</div>

---

## Projects

| 프로젝트 | 소개 | 기술 |
| :--- | :--- | :--- |
| [🍕 PizzaEatHo](#pizzaeatho) | 메뉴 탐색부터 주문과 리뷰까지, 피자 주문 앱 | Flutter · Dart · Provider |
| [📱 싸브리타임](#ssabreetime) | 교육생의 소통과 활동을 연결하는 커뮤니티 앱 | Android · Kotlin |
| [📈 What's Your ETF](#whats-your-etf) | ETF 탐색과 관심 목록, 투자 전략을 돕는 앱 | Kotlin · Jetpack Compose · Hilt |
| [📚 Dot Shelf](#dot-shelf) | 책장과 책의 상호작용을 구현한 앱 | Unity · C# |

> 현재 프로젝트 서버 운영은 종료되었습니다. 프로젝트 소개와 개발 경험을 정리한 페이지이며, 소스코드는 공개하지 않습니다.

---

<a id="pizzaeatho"></a>
## 🍕 PizzaEatHo · 피짜잇호

**Flutter 기반 피자 주문 앱**

메뉴를 고르고 장바구니에 담은 뒤, 주문 내역과 리뷰까지 확인하는 서비스입니다.

- **서비스 기능**: 메뉴 조회, 장바구니, 주문 및 주문 내역, 리뷰, 매장 찾기, 관리자 주문 관리
- **기술 구성**: Flutter · Dart · Provider · HTTP · Firebase Cloud Messaging
- **구조**: 화면과 ViewModel, Repository, 데이터 소스를 구분한 구성

---

<a id="ssabreetime"></a>
## 📱 싸브리타임

**교육생을 위한 Android 커뮤니티 앱**

게시판과 그룹, 개인 포트폴리오를 한곳에 모아 소통과 활동을 연결합니다.

- **역할**: 6인 팀의 Android 개발 및 Android 리딩
- **담당 기능**: 앱 구조와 인증, 홈과 내비게이션, 게시판, 그룹 관리, 마이페이지와 포트폴리오, D-Day, 다크 모드
- **개발 과정**: 기능 구현부터 QA와 APK 배포까지 참여

여러 기능을 하나의 앱 흐름으로 연결하고, 실제 사용 과정에서의 완성도를 높이는 데 집중했습니다.

---

<a id="whats-your-etf"></a>
## 📈 What's Your ETF

**ETF 탐색과 투자 전략을 돕는 Android 앱**

- **담당 기능**: ETF 상세 및 관심 목록, 마이페이지, 투자 전략, 뉴스, 푸시 알림, 온보딩
- **기술 구성**: Kotlin · Jetpack Compose · MVVM / Clean Architecture · Retrofit · Hilt · Room · DataStore · FCM

### 중복 네트워크 요청 개선

목록을 표시할 때 종목마다 관심 등록 여부를 개별 조회하던 흐름을 개선했습니다. 목록 응답의 `isFavorite` 값을 활용해 **기본 20개 목록에서 발생하던 20회의 추가 요청을 제거**했습니다.

---

<a id="dot-shelf"></a>
## 📚 Dot Shelf

**책장과 책의 상호작용을 구현한 Unity 프로젝트**

- **담당 기능**: 책장과 책의 상호작용, 드래그 물리 처리, API 연동과 데이터 동기화
- **품질 개선**: 저장 실패 시 재시도 큐, 입력 검증, 로딩 피드백
- **개발 환경**: Unity · C# · Unity CI 구성 참여

### 저장 실패 이후의 처리

저장 요청이 실패했을 때 다시 시도할 수 있도록 재시도 큐를 구현했습니다. 입력 검증과 로딩 피드백을 함께 다듬어 사용자가 앱 상태를 이해할 수 있도록 했습니다.

---

<div align="center">
<sub>화면 구현부터 데이터 흐름과 사용 경험까지 고민합니다.</sub>
</div>
