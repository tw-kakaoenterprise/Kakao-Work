# 메시지 암호화

## 메시지 암호화 설정

카카오워크는 메시지 수발신 전체 과정에서 암호화 상태를 유지하는 종단간 암호화를 기반으로 한 보호체계를 구축하고 있습니다. 이를 바탕으로 사용자의 메시지를 높은 보안 수준으로 보호하고 관리합니다.

2022년 12월 업데이트 이후 가입한 워크스페이스에서는 각 워크스페이스에 맞는 메시지 암호화 정책을 설정할 수 있습니다.

### 메시지 암호화 모드 유형

카카오워크 메시지 암호화 모드는 총 2가지가 제공됩니다.

| 구분             | 설명                                                                                                                                                                                |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 일반 암호화 모드(기본값) | <p>별도 설정 없이 기본 적용되는 강력한 메시지 암호화<br>- 메시지는 사용자의 기기에서 암호화되어 서버로 전송 및 저장<br>- 새로운 기기에서 로그인 시 별도의 기기 인증 절차 없이 간편하게 로그인</p>                                                            |
| 고급 암호화 모드      | <p>Standard 이상 플랜에서 사용할 수 있는 보안이 강화된 메시지 암호화 모드<br>- 메시지는 사용자의 기기에서 암호화되어 서버로 전송 및 저장<br>- 새로운 기기 로그인 시 기기 인증 절차 필요(인증되지 않은 기기에서는 워크스페이스 진입 불가)<br>- 슈퍼 관리자에게 인증을 위한 ‘인증키’ 제공</p> |

### 메시지 암호화 모드 변경

PC 혹은 Mobile 카카오워크 앱에서 메시지 암호화 모드를 변경할 수 있습니다.

{% hint style="info" %}
**안내**\
**슈퍼 관리자만 접근 가능합니다.**
{% endhint %}

{% hint style="info" %}
**안내**\
Standard 이상의 [플랜](https://www.kakaowork.com/pricing)에서만 메시지 암호화 모드를 변경할 수 있습니다.

* 암호화 모드 변경 후 1시간 동안은 설정을 변경할 수 없습니다.
{% endhint %}

#### 고급 암호화 모드로 변경하기

일반 암호화 모드를 고급 암호화 모드로 변경하면 강화된 보안 체계를 바탕으로 카카오워크를 이용할 수 있습니다.

고급 암호화 모드에서 모든 멤버는 새로운 기기로 로그인 시 [기기 인증](https://www.notion.so/e058b8ddd43b42b297b72e5cf128456f) 절차를 거치게 됩니다. 슈퍼 관리자는 자동 인증 이외에도 인증키를 활용해 기기 인증을 수행할 수 있습니다. 인증키는 고급 암호화 모드로 변경 시 슈퍼 관리자에게 발급됩니다.

{% hint style="danger" %}
**주의**\
인증키를 분실할 경우, 워크스페이스 사용이 불가능할 수 있습니다. 슈퍼 관리자는 인증키 보관에 유의하시기 바랍니다.

* 인증키를 분실하여 재발급이 필요하다면, [인증키 재발급](https://www.notion.so/3682c3bd61314b4090e104eecec2070a) 문서를 참고하시기 바랍니다.
{% endhint %}

**PC 버전**

1.  **더보기** 탭 **> 관리자 메뉴 > 메시지 암호화 설정** 메뉴를 클릭합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 설정 메뉴(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%A9%94%EC%8B%9C%EC%A7%80%20%EC%95%94%ED%98%B8%ED%99%94%20%EC%84%A4%EC%A0%95%20%EB%A9%94%EB%89%B4pc.png)


2.  [모드 설정] 버튼을 클릭합니다.

    ![그림. 모드 설정(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%AA%A8%EB%93%9C%EC%84%A4%EC%A0%95pc.png)


3.  **메시지 암호화 모드 설정** 팝업창에서 **고급 암호화 모드**를 선택하고, \[설정] 버튼을 클릭합니다.

    ![그림. 고급 암호화 모드 선택(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%84%A0%ED%83%9Dpc.png)


4.  기기 인증 관련 안내를 확인하고, \[다음] 버튼을 클릭합니다.

    ![그림. 기기 인증 안내(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B8%B0%EA%B8%B0%EC%9D%B8%EC%A6%9D%20%EC%95%88%EB%82%B4pc.png)


5.  인증키 관련 안내를 확인하고, \[고급 암호화 모드 적용] 버튼을 클릭합니다.

    ![그림. 인증키 안내(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%B8%EC%A6%9D%ED%82%A4%20%EC%95%88%EB%82%B4pc.png)


6.  **고급 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 클릭합니다.

    ![그림. 고급 암호화 모드 적용](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9.png)


7.  고급 암호화 모드 적용이 완료되어 인증키가 발급됩니다.

    * 인증키는 슈퍼관리자 메일로 발송되며, 복사하여 다른 멤버에게 공유하거나 별도로 보관할 수 있습니다.

    ![그림. 고급 암호화 모드 적용 완료(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9%20%EC%99%84%EB%A3%8Cpc.png)

**Mobile 버전**

1.  **더보기** 탭 **> 관리자 > 메시지 암호화** 메뉴를 선택합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 메뉴(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%A9%94%EC%8B%9C%EC%A7%80%20%EC%95%94%ED%98%B8%ED%99%94%EB%A9%94%EB%89%B4mobile.png)


2.  **고급 암호화 모드**를 선택하고, \[설정] 버튼을 누릅니다.

    ![그림. 고급 암호화 모드 선택(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%84%A0%ED%83%9Dmobile.png)


3.  기기 인증 관련 안내를 확인하고, \[다음] 버튼을 선택합니다.

    ![그림. 기기 인증 안내(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B8%B0%EA%B8%B0%EC%9D%B8%EC%A6%9D%20%EC%95%88%EB%82%B4mobile.png)


4.  인증키 관련 안내를 확인하고, \[고급 암호화 모드 적용] 버튼을 선택합니다.

    ![그림. 인증키 안내(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%B8%EC%A6%9D%ED%82%A4%20%EC%95%88%EB%82%B4mobile.png)


5.  **고급 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 선택합니다.

    ![그림. 고급 암호화 모드 적용(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%20%EC%95%94%ED%98%B8%ED%99%94%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9mobile.png)


6.  고급 암호화 모드 적용이 완료되어 인증키가 발급됩니다.

    * 발급된 인증키는 슈퍼 관리자 메일로 발송되며, **인증키 보관하기** 메뉴를 통해 별도로 보관할 수도 있습니다.

    ![그림. 고급 암호화 모드 적용 완료(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B3%A0%EA%B8%89%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9%20%EC%99%84%EB%A3%8Cmobile.png)

#### 일반 암호화 모드로 변경하기

고급 암호화 모드에서 일반 암호화 모드로 변경할 수 있습니다.

일반 암호화 모드에서는 새로운 기기에서 로그인 시 추가 인증 과정이 생략되어, 간편하게 워크스페이스에 로그인할 수 있습니다.

**PC 버전**

1.  **더보기** 탭 **> 관리자 메뉴 > 메시지 암호화 설정** 메뉴를 클릭합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 설정 메뉴(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%A9%94%EC%8B%9C%EC%A7%80%20%EC%95%94%ED%98%B8%ED%99%94%20%EC%84%A4%EC%A0%95%20%EB%A9%94%EB%89%B4pc.png)


2.  \[모드 설정] 버튼을 클릭합니다.

    ![그림. 모드 설정(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%AA%A8%EB%93%9C%EC%84%A4%EC%A0%95pc.png)


3.  **메시지 암호화 모드 설정** 팝업창에서 **일반 암호화 모드**를 선택하고, \[설정] 버튼을 클릭합니다.

    ![그림. 일반 암호화 모드 선택(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%EB%AA%A8%EB%93%9C%20%EC%84%A0%ED%83%9Dpc.png)


4.  **일반 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 클릭합니다.

    ![그림. 일반 암호화 모드 적용(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9pc.png)


5.  일반 암호화 모드 적용이 완료됩니다.

    ![그림. 일반 암호화 모드 적용 완료(PC)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9%20%EC%99%84%EB%A3%8Cpc.png)

**Mobile 버전**

1.  **더보기** 탭 **> 관리자 > 메시지 암호화** 메뉴를 선택합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 메뉴(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%A9%94%EC%8B%9C%EC%A7%80%20%EC%95%94%ED%98%B8%ED%99%94%EB%A9%94%EB%89%B4mobile.png)


2.  **일반 암호화 모드**를 선택하고, \[설정] 버튼을 누릅니다.

    ![그림. 일반 암호화 모드 선택(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%84%A0%ED%83%9Dmobile.png)


3.  **일반 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 선택합니다.

    ![그림. 일반 암호화 모드 적용(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9mobile.png)


4.  일반 암호화 모드 적용이 완료됩니다.

    ![그림. 일반 암호화 모드 적용 완료(Mobile)](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9D%BC%EB%B0%98%20%EC%95%94%ED%98%B8%ED%99%94%20%EB%AA%A8%EB%93%9C%20%EC%A0%81%EC%9A%A9%20%EC%99%84%EB%A3%8Cmobile.png)
