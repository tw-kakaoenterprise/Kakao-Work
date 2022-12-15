---
description: 내 프로필을 설정하는 방법을 안내합니다.
---

# 확장서비스

카카오워크에서는 업무에 필요한 협업 서비스 및 사내 시스템을 카카오워크 Bot으로 연결하여, 중요한 알림을 빠르게 확인할 수 있습니다. 카카오워크의 모든 워크스페이스에서 기본으로 제공하는 기본 Bot 외에도 전사 공지, 장애 전파 등 사내 시스템과 연동한 우리 조직만의 Bot을 관리자가 직접 생성하여 멤버들에게 알림 메시지를 보낼 수도 있습니다.

**확장** 탭 > **확장 서비스** 메뉴에서 연동 가능한 서비스 목록을 확인할 수 있습니다. 각 서비스의 연동 및 Bot 설정 방법은 해당 서비스를 클릭하면 나타나는 상세 설명을 참고하시기 바랍니다.\
확장 서비스의 연동 유형은 계정 연동형과 Webhook형으로 구분할 수 있습니다. 본 가이드에서는 각 유형별 대표적인 연동 사례를 안내합니다. ![그림. 확장 탭 > 확장 서비스](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7d37a1d2-0229-4db5-9f72-032ba17443dc/%ED%99%95%EC%9E%A5\_%ED%83%AD\_\_\_%ED%99%95%EC%9E%A5\_%EC%84%9C%EB%B9%84%EC%8A%A4.png)

## 계정 연동형

계정 연동형이란 별도의 계정 체계가 있는 외부 서비스에서 사용자 가입한 계정을 기반으로 카카오워크 Bot을 이용하는 방식입니다. 서비스 연동을 위해 해당 서비스가 카카오워크 워크스페이스의 정보를 조회하고 Bot의 기능을 수행할 수 있도록 접근 권한 허용이 필요합니다.

### Google Calendar

사용자의 구글 캘린더 계정과 연동하면, 해당 Bot이 오늘/내일의 일정 알림, 새로운 일정 초대 알림, 10분 전 일정 알림 등을 1:1 채팅방으로 알려줍니다.

1. **확장** 탭 > **확장 서비스** 메뉴에서 **Google Calendar**를 클릭한 후, \[사용] 버튼을 클릭합니다. ![그림. Google Calendar 사용](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ba7866b2-b292-43e6-a833-f7b69e68c00b/Google\_Calendar\_%EC%82%AC%EC%9A%A9.png)
2. \[허용] 버튼을 클릭하여 구글 캘린더 권한 요청을 허용합니다. ![그림. 구글 캘린더 권한 허용](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/771146fe-8ee8-4f5d-95c6-bd9d4eff25d1/%E1%84%80%E1%85%AE%E1%84%80%E1%85%B3%E1%86%AF\_%E1%84%8F%E1%85%A2%E1%86%AF%E1%84%85%E1%85%B5%E1%86%AB%E1%84%83%E1%85%A5\_%E1%84%80%E1%85%AF%E1%86%AB%E1%84%92%E1%85%A1%E1%86%AB\_%E1%84%92%E1%85%A5%E1%84%8B%E1%85%AD%E1%86%BC.png)
3. 연동할 구글 계정을 입력하고 \[다음] 버튼을 클릭하여 로그인을 완료합니다. ![그림. 구글 계정 입력](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/78d9fc6d-f615-4878-9bfa-4f322b5ddeb9/%E1%84%80%E1%85%AE%E1%84%80%E1%85%B3%E1%86%AF\_%E1%84%80%E1%85%A8%E1%84%8C%E1%85%A5%E1%86%BC\_%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%85%E1%85%A7%E1%86%A8.png)
4. \[허용] 버튼을 클릭하여 구글 계정 액세스 권한을 허용합니다. ![그림. 구글 계정 액세스 허용](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5052ed4e-763d-408a-b353-ee726bca42e3/%E1%84%80%E1%85%AE%E1%84%80%E1%85%B3%E1%86%AF\_%E1%84%80%E1%85%A8%E1%84%8C%E1%85%A5%E1%86%BC\_%E1%84%8B%E1%85%A2%E1%86%A8%E1%84%89%E1%85%A6%E1%84%89%E1%85%B3\_%E1%84%92%E1%85%A5%E1%84%8B%E1%85%AD%E1%86%BC.png)
5.  Google Calendar 연동 완료 시 1:1 Bot 채팅방이 생성됩니다.

    * 최초로 수신하는 Bot 메시지에서 \[설정하기]를 클릭하면, Bot 알림 상세 설정 및 계정 연결 해제를 진행할 수 있습니다.

    ![그림. Google Calendar Bot 생성](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3663e51d-b3fb-49ef-ac91-0e9a6bac72d8/Google\_Calendar\_Bot\_%EC%83%9D%EC%84%B1.png)

## Webhook형

Webhook형이란 사용자의 계정 정보가 필요한 계정 연동 방식과는 달리, 사용자가 이용 중인 서비스에서 특정 이벤트가 발생하였을 때 카카오워크의 지정된 채팅방으로 알림을 보내는 방식입니다.

{% hint style="info" %}
**안내**\
Webhook은 클라이언트에서 제공하는 URL을 서버 측에 등록하면, 서버에서 특정 이벤트가 발생했을 때 클라이언트를 호출하는 기능입니다. Webhook 활용 시, 다른 애플리케이션과 연동하여 기능을 확장할 수 있습니다.

* Webhook형 Bot의 경우, 여러 개의 Bot을 각기 다른 이름으로 각기 다른 채팅방에 추가할 수 있으며 1인당 생성 개수 제한이 없습니다.
{% endhint %}

### Jira Enterprise

Jira Enterprise에서 특정 이벤트가 발생했을 때 Bot이 1:1 채팅방 또는 연동된 채팅방으로 알려줍니다.

{% hint style="info" %}
**안내**\


* 관리자 권한이 있는 프로젝트에 한해서만 Webhook URL 연동을 진행할 수 있습니다.
* Jira의 구축형 서비스를 이용하는 경우, **Project Automation**이라는 유료 플러그인을 사용하는 경우에만 설정이 가능합니다.
{% endhint %}

#### **카카오워크에서 Bot 생성하기**&#x20;

Jira Enterprise Bot을 연동하기 위해, 먼저 **확장 서비스** 메뉴에서 Jira Enterprise Bot을 생성합니다.

1.  **확장** 탭 > **확장 서비스** 메뉴에서 **Jira Enterprise**를 클릭 후, \[Bot 만들기]를 클릭합니다.

    ![그림. Jira Enterprise Bot 만들기](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5391cf36-a6c7-4b47-bae8-aeb88efe1850/Jira\_Enterprise\_Bot\_%EB%A7%8C%EB%93%A4%EA%B8%B0.png)
2.  Bot의 프로필 사진과 이름, 메시지를 받을 채팅방을 선택 후, \[Bot 만들기] 버튼을 클릭합니다.

    ![그림. Jira Enterprise Bot 이름 설정](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a74f51f-5cc2-4312-ab6e-ba2344cc183f/Jira\_Enterprise\_Bot\_%E1%84%8B%E1%85%B5%E1%84%85%E1%85%B3%E1%86%B7\_%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%BC.png)
3.  Bot이 정상적으로 추가되면 Webhook URL이 발급됩니다.

    ![그림. Jira Enterprise Webhook URL 발급](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/89df8fdd-5999-44da-b19d-719ab0be7a4a/Jira\_Enterprise\_Webhook\_URL\_%E1%84%87%E1%85%A1%E1%86%AF%E1%84%80%E1%85%B3%E1%86%B8.png)

{% hint style="info" %}
```
**안내**<br>
생성된 Webhook URL은 **확장 서비스** 메뉴 > **Jira Enterprise** Bot 프로필 > **나의 봇 관리** > **관리**에서 재설정 할 수 있습니다.
```
{% endhint %}

1.  \[채팅방 이동하기] 버튼을 클릭하면 Jira Enterprise Bot과의 1:1 대화방으로 이동합니다.

    ![그림. Jira Enterprise Bot 생성 완료](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/be68f591-bd6b-4965-8cc7-ea4d2e6128ff/%EA%B7%B8%EB%A6%BC.\_Jira\_Enterprise\_Bot\_%EC%83%9D%EC%84%B1\_%EC%99%84%EB%A3%8C.png)

#### **서비스 웹사이트에서 Webhook URL 등록하기**

발급받은 Webhook URL을 Jira 웹사이트에 등록하여, 특정 이벤트가 발생할 때마다 채팅방으로 메시지를 전송할 수 있습니다.

**\[Cloud형]**

1.  Jira Software 웹사이트에서 **설정 > Jira 설정 > 시스템** 메뉴로 이동합니다.

    ![그림. Jira Software 설정 > 시스템](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1c228a7d-e9e5-431a-93d3-f68142c26b2a/Jira\_Software\_%E1%84%89%E1%85%A5%E1%86%AF%E1%84%8C%E1%85%A5%E1%86%BC\_\_\_%E1%84%89%E1%85%B5%E1%84%89%E1%85%B3%E1%84%90%E1%85%A6%E1%86%B7.png)
2.  **웹후크** 메뉴에서 \[웹훅 만들기] 버튼을 클릭합니다.

    ![그림. Jira Software 웹훅 만들기](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5a619fb2-8ae5-496b-bee5-6f45edf97f90/Jira\_Software\_%E1%84%8B%E1%85%B0%E1%86%B8%E1%84%92%E1%85%AE%E1%86%A8\_%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%E1%86%AF%E1%84%80%E1%85%B5.png)
3.  URL란에 Jira Enterprise Bot에서 발급한 Webhook URL을 입력합니다.

    ![그림. Webhook URL 입력](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bd53cae3-2adb-44c3-9639-5628a6607ea8/Webhook\_URL\_%E1%84%8B%E1%85%B5%E1%86%B8%E1%84%85%E1%85%A7%E1%86%A8.png)
4.  알림을 수신할 이벤트 유형을 선택 후, \[만들기] 버튼을 클릭합니다.

    ![그림. Webhook 만들기](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fcb21137-b95f-41f2-be2f-9c7ecc115ba8/Webhook\_%E1%84%86%E1%85%A1%E1%86%AB%E1%84%83%E1%85%B3%E1%86%AF%E1%84%80%E1%85%B5.png)
5.  연동이 완료되면 다음과 같은 메시지를 수신할 수 있습니다.

    ![그림. Jira Bot 메시지 예시](https://t1.kakaocdn.net/service\_kep\_docpublish/service/9c3628af017c00001.png)

**\[구축형]**

1. 프로젝트 보드의 **Project settings** > **Project automation**으로 이동한 뒤, \[Create rule] 버튼을 클릭합니다. ![그림. Jira Create rule](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8cfec65b-1964-436d-ab58-9522b3d8d6e4/Untitled.png)
2. 지원하는 Trigger 중 하나를 선택한 후, \[Save] 버튼을 클릭합니다.
   * 지원하는 Trigger는 Issue created, Issue updated, Issue deleted, Issue commented입니다.
3. **Action**에서 \[Send web request] 버튼을 클릭합니다. ![그림. Jira Send web request](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5fa4c8b4-4c77-454e-bc7d-8d44793795e9/Untitled.png)
4.  Webhook URL에 발급받은 Webhook URL을 입력한 후, Headers 영역에 값을 입력합니다. 왼쪽 칸은 x-jira-event이고, 오른쪽 칸은 선택한 Trigger 이름입니다. ex) 왼쪽: x-jira-event, 오른쪽: issue created

    ![그림. Jira Webhook URL, Headers 입력](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6224c04a-4ef2-4870-8e22-43172f46790e/Untitled.png)
5. Webhook body는 `Issue data`를 선택한 뒤, \[Save] 버튼을 클릭하여 저장합니다. ![그림. Jira Webhook body](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/38df61bd-097b-467c-a5ab-f16b572ae024/Untitled.png)
6. **Project automation > automation** 리스트에서 **Enabled**가 활성화 상태이면 연동이 완료됩니다. ![그림. Jira 연동 완료](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3a894562-eefd-420e-8709-7be0ceb3b2c3/Untitled.png)
7. 연동이 완료되면 다음과 같은 메시지를 수신할 수 있습니다. \
   ![그림. Jira Bot 메시지 예시](https://t1.kakaocdn.net/service\_kep\_docpublish/service/9c3628af017c00001.png)



