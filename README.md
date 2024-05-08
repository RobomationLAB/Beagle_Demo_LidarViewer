# LiDar Viewer

LiDar Viewer는 Beagle 로봇을 키보드로 직접 제어하고 LiDar 차트를 실시간으로 볼 수 있는 체험형 데모 프로그램입니다.

![비글배경](https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/c43bef77-3f7d-4ea6-b028-5d082e06cfc6)

아래 버튼을 눌러 실행 프로그램을 다운로드 받아 LiDar 센서를 직접 체험해보세요.

<br>

[LiDarViewer 설치하기](https://www.dropbox.com/scl/fo/cewii3qooqgvk1m7d503d/AAUPjnIgEuXjM0lyzdtEncg?rlkey=9kfnnz0lo7ign8yrgrtekgq9o&e=1&st=adw4n2dk&dl=0)

*( ※ LIDARVIEWER.exe는* **windows** *전용 프로그램입니다. )*

<details>

<summary>설치방법</summary>

위 링크로 들어가, 다음과 같이 **로그인하지 않은 상태**로 다운로드를 진행할 수 있습니다.<br>
[ 다운로드 ] → [ 또는 다운로드만 하고 계속 진행하세요. ] 순으로 클릭합니다.

<img src='https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/58e657db-f509-4161-b87c-52a5169434c0' width=600>

<br><br>

브라우저 우측 상단에 다운로드 버튼을 눌러 설치된 zip파일을 선택하고, 설치된 zip파일을 원하는 위치에 압축을 해제합니다.

<img src='https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/61b292b4-6a9a-46a9-bea9-3114823ff21f' width=600>


---

</details>


<br><br>

---

**LIDARVIEWER 실행파일을 시작하기 전에 로봇과 [PC를 연결](#pc-연결)하고 실행파일을 시작해 주시기 바랍니다.**


<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/23019638-98c0-44eb-922e-2d1eb365165e" alt="대체 텍스트" width=500>

---



*※해당 프로그램은 로보메이션의 제품을 활용해 대학생들이 개발하여 체험용으로 배포한 프로그램입니다.
<br>
따라서 <u>본 프로그램의 사용법이나 오류에 대한 문의는 받고 있지 않습니다.</u>*

---

<br><br><br><br>

 
## PC 연결

Beagle의 전원이 꺼져 있는 상태에서 **EXPRESS RECEIVER**를 PC의 USB단자에 꽂습니다.
<br>
**EXPRESS RECEIVER**의 연결 상태 표시등이 초록색으로 깜빡이면 연결 대기중인 상태로 정상입니다.



<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/48ad8216-8aaa-4bef-a428-17ae22e21141" alt="대체 텍스트" width=500>

<br><br>

Beagle로봇을 EXPRESS RECEIVER에 가까이 가져가 Beagle의 **전원 버튼**을 눌러 전원을 켭니다.
<br>
Beagle에서 **삑** 소리가 나고 **Beagle의 통신 상태 표시등**과 **EXPRESS RECEIVER의 연결상태 표시등**이 계속 켜져있거나 빠르게 깜빡이면 정상입니다.

<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/d013081b-4ba2-492f-a9ba-0a2ff76b02b6" width=350>


---




<br><br><br><br>











## LiDar Viewer 시작하기

- 우측 상단의 **CONNECT** 버튼을 클릭하여 연결을 시도합니다.

    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/535c77ba-5ef9-41a0-9561-cde6311f13c3" alt="대체 텍스트" width=400>

<br><br>

- 연결에 **성공**했다면 왼쪽 사진과 같이 초록 불이 들어오고, 
  
  연결에 **실패**했다면 초록 불이 들어오지 않습니다. 이때,  **Beagle의 전원**이 켜져 있는지 확인해봅니다.

    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/12892c1c-3c93-4167-a76f-1e5b684d37f8" alt='' width=800> 

<br><br>

- 좌측 상단의 **DISCONNECT** 버튼을 눌러서 Beagle과의 연결을 해제할 수 있습니다.

    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/1816c3cd-6fd5-41cb-8795-c583aa1bce4e" width=400>

<br><br>

- Beagle이 연결된 상태에서 프로그램을 실행하면 아래와 같이 프로그램 창이 나타납니다.

<img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/915acad3-c3aa-4a15-bed7-e04ee4dd5535" width=700>

<br><br>

### LiDar 뷰어 모드란?

**LiDar 뷰어 모드**에는 **두가지 모드**가 있습니다.


| 모드 | 설명 |
| --- | --- |
| Auto Scaling | [ 자동모드 ] LiDAR 센서가 수집한 데이터 중에서 가장 먼 거리의 정보를 기준으로 뷰어의 스케일을 자동으로 조정하여 시각적으로 나타내는 모드입니다. (뷰어의 수동조작 불가)|
| Mouse WheelScroll | [ 수동모드 ] 좌클릭 상태로 마우스를 움직여 화면상 Beagle의 위치를 자유롭게 이동시킬 수 있습니다. 휠 스크롤을 사용하여 화면 비율을 확대 또는 축소할 수 있습니다. |




---
<br><br><br><br>

# 방향키 주행

- 연결이 완료된 상태에서, 하단 **PLAY** 버튼을 누르면 다음과 같이 LiDar센서가 활성화되고, 키보드로 Beagle을 제어할 수 있는 상태가 됩니다.


    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/53e3c9e0-d8eb-4b2b-bfe5-648668a4c7f6" width=800>

<br>

| 입력 | 설명 |
| --- | --- |
| `↑` | 전진 |
| `↓` | 후진 |
| `←` | 제자리에서 왼쪽으로 회전 |
| `→` | 제자리에서 오른쪽으로 회전 |
| `↑` + `←` | 좌회전 |
| `↑` + `→` | 우회전 |
| `↓` + `←` | 왼쪽으로 후진 ( `↓`, `←` 순으로 입력 권장) |
| `↓` + `→` | 오른쪽으로 후진 ( `↓`, `→` 순으로 입력 권장) |


<br><br>

- **STOP** 버튼을 누르면 키보드와 LiDar센서가 비활성화 됩니다.

    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/a53b5c37-01e5-41d6-887c-7348962dc666" width=800>


<br><br>

- Beagle의 안정적인 종료를 위해 **DISCONNECT** 버튼을 클릭한 후 프로그램을 종료하는 것을 권장합니다.

    <img src="https://github.com/RobomationLAB/BeagleAPI_KR/assets/160319639/8747f380-2b53-4611-90ff-0b5a3d1f895a" width = 400>
