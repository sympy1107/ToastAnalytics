## 시작하기
#### 공통
##### 1.SDK에서 수집하는 개인정보가 있나요?
 

SDK는 개인 식별이 가능한 정보는 수집하지 않습니다. 다만 통계를 위해서 단말기 정보 일부를 수집하고 있습니다.
현재 수집하고 있는 정보는 아래와 같습니다.
* iOS, Android 공통 : 단말 기종, 단말 제조사, 디바이스 해상도, 언어설정, Carrier(이통사),Time Zone, OS Version, App Version 

* OS : Language, Device Vendor ID, Device Token(APNS), Wifi MAC Address(수집 가능한 경우), IDFA

* Android : Android Device ID, Registration ID(GCM), 광고 ID, WiFi MAC Address (권한이 있는 경우만) 

<BR>


#####2. 로그 데이터를 전송 중 앱이 종료되면 어떻게 되나요?

모든 로그는 내부에 백업되어 있기 때문에 앱이 종료되어 전송에 실패한 로그는 다음에 앱이 실행되면 자동으로
재전송되게 됩니다. 단, 24시간이 지난 로그는 자동 폐기되게 됩니다.


<BR>

#####3. 안드로이드의 경우 앱의 종료 시점을 명확히 알기 어려운데 앱의 종료 로그 수집에 문제 없나요?

안드로이드에서 앱의 종료 로그가 명확하지 않아도 다른 로그들의 전송 패턴을 분석하여 앱의 종료 시점을 합리적으로 추론하여 분석에 반영하고 있습니다.

<BR>

#####4. SDK 에서 기본적으로 수집하는 데이터 이외에 사용자 정의 데이터도 수집 가능한가요?
<BR>


####계정 및 권한
#####1.컴퍼니란 무엇이며 어디에 사용되는 건가요?
#####2.컴퍼니 생성은 아무나 할 수 있나요?
#####3.컴퍼니 생성자 권한을 다른 사람에게 이양할 수 있나요?


## SDK적용
#### SDK연동전 고려사항
#####1.앱 실행 직후 부터 지표가 추적되나요?
#####2.InitializeSDK 는 어느 시점에 해야 하나요? 지표추적시점과 연관이 있나요?
#####3.사용자 구분 설정(use logging userid flag)은 반드시 사업 담당자와 논의해주세요.

#### 지원환경
#####1.SDK를 사용할 수 있는 최소 OS Version은 무엇인가요?


## 분석/지표
#### 공통
#####1.국가의 기준은 무엇인가요?
#####2.글로벌 서비스를 하고 있습니다. Analytics 에서 보여주는 환율 계산의 기준은 어떻게 되나요?


#### 커스텀이벤트
#####1.커스텀 이벤트 로그 수집을 위해 어떤 작업을 해야 하나요?
#####2.커스텀 이벤트 기능은 언제 사용하나요?