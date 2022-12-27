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

    ![그림. 메시지 암호화 설정 메뉴(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fd1926dc-13a5-44dd-8b38-5ff3e97788bd/%EB%A9%94%EC%8B%9C%EC%A7%80\_%EC%95%94%ED%98%B8%ED%99%94\_%EC%84%A4%EC%A0%95\_%EB%A9%94%EB%89%B4.png)
2.  \[모드 설정] 버튼을 클릭합니다.

    ![그림. 모드 설정(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/84d9f5a4-7dd8-43f2-92e5-b2a58d798c68/%EB%AA%A8%EB%93%9C\_%EC%84%A4%EC%A0%95.png)
3.  **메시지 암호화 모드 설정** 팝업창에서 **고급 암호화 모드**를 선택하고, \[설정] 버튼을 클릭합니다.

    ![그림. 고급 암호화 모드 선택(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f231d72d-420a-48e9-9bbc-3733f23f10b8/%EA%B3%A0%EA%B8%89\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%84%A0%ED%83%9D.png)
4.  기기 인증 관련 안내를 확인하고, \[다음] 버튼을 클릭합니다.

    ![그림. 기기 인증 안내(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f8d30526-c00f-445c-b71c-cc887fa58475/%EA%B8%B0%EA%B8%B0\_%EC%9D%B8%EC%A6%9D\_%EC%95%88%EB%82%B4.png)
5.  인증키 관련 안내를 확인하고, \[고급 암호화 모드 적용] 버튼을 클릭합니다.

    ![그림. 인증키 안내(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/56bf304b-0554-4102-b38d-ae1f45be968f/%EC%9D%B8%EC%A6%9D%ED%82%A4\_%EC%95%88%EB%82%B4.png)
6.  **고급 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 클릭합니다.

    ![그림. 고급 암호화 모드 적용](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a5ce619-062c-44cf-a489-7cf8bb3840df/%EA%B3%A0%EA%B8%89\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%A0%81%EC%9A%A9.png)
7.  고급 암호화 모드 적용이 완료되어 인증키가 발급됩니다.

    * 인증키는 슈퍼관리자 메일로 발송되며, 복사하여 다른 멤버에게 공유하거나 별도로 보관할 수 있습니다.

    ![그림. 고급 암호화 모드 적용 완료(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/025b0120-1f29-4ced-b187-bb70ef40eb54/%EC%9D%B8%EC%A6%9D%ED%82%A4\_%EB%B0%9C%EA%B8%89.png)

**Mobile 버전**

1.  **더보기** 탭 **> 관리자 > 메시지 암호화** 메뉴를 선택합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 메뉴(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/df76e7d7-8f82-4718-bd0c-a082f1d64b1f/%EB%A9%94%EC%8B%9C%EC%A7%80\_%EC%95%94%ED%98%B8%ED%99%94.png)
2.  **고급 암호화 모드**를 선택하고, \[설정] 버튼을 누릅니다.

    ![그림. 고급 암호화 모드 선택(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e545104e-3acb-42b2-bc97-1d0c914c015f/%E1%84%80%E1%85%A9%E1%84%80%E1%85%B3%E1%86%B8\_%E1%84%8B%E1%85%A1%E1%86%B7%E1%84%92%E1%85%A9%E1%84%92%E1%85%AA\_%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3\_%E1%84%89%E1%85%A5%E1%86%AB%E1%84%90%E1%85%A2%E1%86%A8.png)
3.  기기 인증 관련 안내를 확인하고, \[다음] 버튼을 선택합니다.

    ![그림. 기기 인증 안내(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c1377034-a40a-49c8-97e5-8856f2ed8acc/%E1%84%80%E1%85%B5%E1%84%80%E1%85%B5\_%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%8C%E1%85%B3%E1%86%BC\_%E1%84%8B%E1%85%A1%E1%86%AB%E1%84%82%E1%85%A2.png)
4.  인증키 관련 안내를 확인하고, \[고급 암호화 모드 적용] 버튼을 선택합니다.

    ![그림. 인증키 안내(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/71a5d488-79c9-48a5-ada3-1846b8a83881/%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%8C%E1%85%B3%E1%86%BC%E1%84%8F%E1%85%B5\_%E1%84%8B%E1%85%A1%E1%86%AB%E1%84%82%E1%85%A2.png)
5.  **고급 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 선택합니다.

    ![그림. 고급 암호화 모드 적용(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/0075d504-07a7-4c3f-8ce9-e04aacb378f0/%EA%B3%A0%EA%B8%89\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%A0%81%EC%9A%A9\_\(1\).png)
6.  고급 암호화 모드 적용이 완료되어 인증키가 발급됩니다.

    * 발급된 인증키는 슈퍼 관리자 메일로 발송되며, **인증키 보관하기** 메뉴를 통해 별도로 보관할 수도 있습니다.

    ![그림. 고급 암호화 모드 적용 완료(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2b223482-17f0-464a-925e-be8f9a91fea5/%EC%9D%B8%EC%A6%9D%ED%82%A4\_%EB%B0%9C%EA%B8%89\_\(1\).png)

#### 일반 암호화 모드로 변경하기

고급 암호화 모드에서 일반 암호화 모드로 변경할 수 있습니다.

일반 암호화 모드에서는 새로운 기기에서 로그인 시 추가 인증 과정이 생략되어, 간편하게 워크스페이스에 로그인할 수 있습니다.

**PC 버전**

1.  **더보기** 탭 **> 관리자 메뉴 > 메시지 암호화 설정** 메뉴를 클릭합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 설정 메뉴(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fd1926dc-13a5-44dd-8b38-5ff3e97788bd/%EB%A9%94%EC%8B%9C%EC%A7%80\_%EC%95%94%ED%98%B8%ED%99%94\_%EC%84%A4%EC%A0%95\_%EB%A9%94%EB%89%B4.png)
2.  \[모드 설정] 버튼을 클릭합니다.

    ![그림. 모드 설정(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5d007ee7-db4a-45cb-910b-2b43f93955ad/%EB%AA%A8%EB%93%9C\_%EC%84%A4%EC%A0%95.png)
3.  **메시지 암호화 모드 설정** 팝업창에서 **일반 암호화 모드**를 선택하고, \[설정] 버튼을 클릭합니다.

    ![그림. 일반 암호화 모드 선택(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1a12c981-8620-4dca-9899-6b7ce833ceed/%EC%9D%BC%EB%B0%98\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%84%A0%ED%83%9D.png)
4.  **일반 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 클릭합니다.

    ![그림. 일반 암호화 모드 적용(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f60700d-f605-40cb-b9d9-32684b999534/%EC%9D%BC%EB%B0%98\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%A0%81%EC%9A%A9.png)
5.  일반 암호화 모드 적용이 완료됩니다.

    ![그림. 일반 암호화 모드 적용 완료(PC)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/592c4aef-4ef7-431f-ae10-1aacdb8861c6/%EC%9D%BC%EB%B0%98\_%EC%95%94%ED%98%B8%ED%99%94\_%EB%AA%A8%EB%93%9C\_%EC%A0%81%EC%9A%A9\_%EC%99%84%EB%A3%8C.png)

**Mobile 버전**

1.  **더보기** 탭 **> 관리자 > 메시지 암호화** 메뉴를 선택합니다.

    * 현재 설정된 암호화 모드를 확인할 수 있습니다.

    ![그림. 메시지 암호화 메뉴(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/df76e7d7-8f82-4718-bd0c-a082f1d64b1f/%EB%A9%94%EC%8B%9C%EC%A7%80\_%EC%95%94%ED%98%B8%ED%99%94.png)
2.  **일반 암호화 모드**를 선택하고, \[설정] 버튼을 누릅니다.

    ![그림. 일반 암호화 모드 선택(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d7a86f7a-82fd-4b49-93f5-734d72309437/%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%87%E1%85%A1%E1%86%AB\_%E1%84%8B%E1%85%A1%E1%86%B7%E1%84%92%E1%85%A9%E1%84%92%E1%85%AA\_%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3\_%E1%84%89%E1%85%A5%E1%86%AB%E1%84%90%E1%85%A2%E1%86%A8.png)
3.  **일반 암호화 모드 적용** 팝업창에서 \[적용] 버튼을 선택합니다.

    ![그림. 일반 암호화 모드 적용(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/27c3d927-4446-4582-ab70-babc5e966303/%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%87%E1%85%A1%E1%86%AB\_%E1%84%8B%E1%85%A1%E1%86%B7%E1%84%92%E1%85%A9%E1%84%92%E1%85%AA\_%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3\_%E1%84%8C%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%AD%E1%86%BC.png)
4.  일반 암호화 모드 적용이 완료됩니다.

    ![그림. 일반 암호화 모드 적용 완료(Mobile)](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/9f4316b1-0d03-45e4-9457-1edf587e426c/%E1%84%8B%E1%85%B5%E1%86%AF%E1%84%87%E1%85%A1%E1%86%AB\_%E1%84%8B%E1%85%A1%E1%86%B7%E1%84%92%E1%85%A9%E1%84%92%E1%85%AA\_%E1%84%86%E1%85%A9%E1%84%83%E1%85%B3\_%E1%84%8C%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%AD%E1%86%BC\_%E1%84%8B%E1%85%AA%E1%86%AB%E1%84%85%E1%85%AD.png)
