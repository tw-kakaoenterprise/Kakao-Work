# Bot(봇) 관리하기

[카카오워크 관리자 서비스](https://admin.kakaowork.com/) **봇 관리** 메뉴에서는 업무에 활용할 Bot을 개발하고, 카카오 i 캐스퍼 지식 검색 서비스의 데이터를 등록 및 관리할 수 있습니다.

Bot(봇)이란 특정 작업을 자동으로 수행하도록 프로그래밍된 응용 프로그램입니다. 카카오워크에서는 업무에 필요한 서비스를 연결한 Bot을 개발 및 관리하는 기능을 제공합니다. 워크스페이스 멤버들은 Bot을 통해 관련 알림을 채팅방 메시지로 빠르게 확인할 수 있습니다. **봇 관리 > 워크스페이스 봇 관리, Bot 개발자 관리, Bot 개발** 메뉴에서는 Bot 관리자를 지정하거나 Bot을 생성 및 관리할 수 있고, **API 가이드**와 **Block Kit Builder**를 Bot 개발에 활용할 수 있습니다.

카카오 i 캐스퍼 지식 검색 서비스는 카카오워크 채팅방 내 AI 어시스턴트인 카카오 i 캐스퍼를 활용한 사내 지식 정보 서비스입니다. 카카오 i 캐스퍼 지식 검색 서비스를 제공하기 위해서는 사내 지식 데이터를 직접 등록해야 합니다. **봇 관리 > QnA 데이터 관리** 메뉴에서 서비스에 활용할 사내 지식 데이터를 등록 및 관리할 수 있습니다.

### 워크스페이스 봇 관리하기

[카카오워크 관리자 서비스](https://admin.kakaowork.com/) **봇 관리 > 워크스페이스 봇 관리** 메뉴에서 워크스페이스에서 사용 중인 Bot 내역과 활성화 여부를 설정할 수 있습니다.

![그림. 워크스페이스 봇 관리](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/44b6aa04-4792-477f-bafd-50ff6a19e63f/%EC%B9%B4%EC%B9%B4%EC%98%A4%EC%9B%8C%ED%81%AC\_%EA%B4%80%EB%A6%AC%EC%9E%90\_%EC%84%9C%EB%B9%84%EC%8A%A4\_\(1\).png)

| 구분               | 설명                                                            |
| ---------------- | ------------------------------------------------------------- |
| ⓵ 사용 중인 기본 Bot   | <p>워크스페이스 기본 Bot 중 활성화된 Bot<br>- 활성화된 Bot만 사용 개수에 포함</p>      |
| ⓶ 등록된 개발자 생성 Bot | <p>워크스페이스 개발자가 직접 개발한 Bot<br>- 개발자가 직접 등록한 Bot이 사용 개수에 포함</p> |

### Bot 개발자 관리하기

[카카오워크 관리자 서비스](https://admin.kakaowork.com/) > **봇 관리 > Bot 개발자 관리** 메뉴에서는 워크스페이스용 Bot을 생성할 수 있는 개발자를 추가하고 관리할 수 있습니다.

![그림. Bot 개발자 관리](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e2b98ed0-7f59-46da-86f5-5bbad8ca800f/Untitled.png)

| 구분            | 설명                                      |
| ------------- | --------------------------------------- |
| ⓵ 개발자 추가 등록   | 클릭 시 워크스페이스용 Bot을 생성할 수 있는 개발자 추가 등록 가능 |
| ⓶ Bot 개발자 리스트 | 현재 등록된 개발자 목록                           |
|      개발자      | Bot을 개발할 개발자                            |
|      등록자      | Bot 개발자를 지정한 관리자                        |
|      등록일      | 해당 Bot 개발자를 등록한 날짜                      |
|      권한 해제    | 멤버의 개발자 권한을 해제<br>- 사전에 Bot 개발자로 등록되어 있을 경우, 권한을 해제할 수 없으며 [Bot 개발](https://www.notion.so/d17fc11a945a45129657371bdaa6cd33) 메뉴에서 해당 Bot을 삭제 후 가능 |                          |



### 개발자 등록하기

개발자를 신규 등록하는 방법은 다음과 같습니다.

1.  **봇 관리 > Bot 개발자 관리** 화면으로 이동하여 \[개발자 추가 등록] 버튼을 클릭합니다.

    ![그림. 개발자 추가 등록](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3124d2dd-1761-49b4-bf6b-8d120435f99d/Untitled.png)


2.  개발자로 등록할 멤버 이름 검색 후, \[추가] 버튼을 클릭합니다.

    ![그림. 개발자 등록 팝업창](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f362ac75-40a5-4520-9ace-0b580597f797/Untitled.png)



**안내**\
관리자 권한이 없는 사용자가 개발자로 지정될 경우, [카카오워크 관리자 서비스](https://admin.kakaowork.com/)의 **봇 관리** 메뉴에만 접근할 수 있습니다.

#### 권한 해제하기

**봇 관리 > Bot 개발자 관리**에서 \[권한 해제] 버튼을 클릭하여 개발자 권한을 해제할 수 있습니다.

![그림. 개발자 권한 해제](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f01b3c13-6822-40fb-961c-059eaf0fbd8d/Untitled.png)



### Bot 개발하기

[카카오워크 관리자 서비스](https://admin.kakaowork.com/) **봇 관리 > Bot 개발** 메뉴에서는 워크스페이스의 커스텀 Bot을 생성하고 관리할 수 있습니다. Bot 개발은 개발자 권한으로 지정된 멤버만 개발할 수 있습니다.

* 관리자도 Bot 개발을 하기 위해서는 먼저 [개발자 등록](https://www.notion.so/d17fc11a945a45129657371bdaa6cd33)을 완료해야 합니다.

{% hint style="info" %}
**안내**\
 Bot 개발 서비스는 현재(22년 11월 기준) Beta 버전으로 제공됩니다.
{% endhint %}

![그림. Bot 개발 화면](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f067f9c-b071-4dbe-ac15-3cc28d03a6e4/Untitled.png)

| 구분             | 설명                                                                      |
| -------------- | ----------------------------------------------------------------------- |
| ⓵ Bot 생성하기     | 커스텀 Bot 생성                                                              |
| ⓶ Bot 리스트      | <p>현재 등록된 Bot의 리스트<br>- 카카오워크 앱에 Bot 노출 여부 설정은 관리자만 설정 가능</p>           |
|      Bot 아이콘   | Bot 아이콘 이미지                                                             |
|      이름        | Bot 이름                                                                  |
|      개발자       | Bot을 개발한 개발자                                                            |
|      등록일       | Bot 최초 등록일                                                              |
|      수정일       | Bot 최신 수정 날짜                                                            |
|      Bot 목록 노출 | <p>슬라이드 버튼을 ON/OFF 하여 멤버의 카카오워크 앱에 Bot 노출 여부를 설정<br>- 관리자만 설정 가능</p>    |
|      관리        | <p>Bot을 수정 및 삭제<br>- [수정] 아이콘: Bot 정보 및 기능 수정<br>- [삭제] 아이콘: Bot 삭제</p> |

### Bot 생성하기

신규 Bot을 생성하는 방법은 다음과 같습니다.

1.  **봇 관리 > Bot 개발** 화면에서 \[Bot 생성하기] 버튼을 클릭합니다.

    ![그림. Bot 생성](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6e184269-2923-4b69-b947-db33075215cd/Untitled.png)
2.  Bot 정보를 입력한 후, \[생성] 버튼을 클릭합니다.

    ![그림. Bot 정보 입력 팝업창](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ab6e135c-ba6f-4d2b-b12b-4a3146bcf0b1/Untitled.png)

    | 구분     | 필수 여부 | 설명                    |
    | ------ | ----- | --------------------- |
    | 이름     | 필수    | Bot의 이름               |
    | 한 줄 설명 | 필수    | Bot 목록에 표시할 문구        |
    | 문의     | 필수    | Bot 담당자 정보(아이디, 메일 등) |

#### Bot 수정하기

Bot의 정보를 수정하는 방법은 다음과 같습니다.

1.  **봇 관리 > Bot 개발자 관리** 메뉴에서 \[수정] 아이콘을 클릭합니다.

    ![그림. 생성된 Bot 수정](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/761e5368-20c0-4c76-8694-53d1e41577e7/Untitled.png)
2.  제작된 Bot의 기본 정보와 권한 등을 설정합니다.

    1.  **Bot 기본 정보 탭**에서 정보 수정 후 \[저장] 버튼을 클릭합니다.

        * **App Key**는 Bot 생성 시 자동으로 부여되며, Bot 인증 시 Request 파라미터에 입력하는 값입니다.

        ![그림. Bot 기본 정보 수정](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/550a2946-b02c-4920-b1b5-3ca874a91bc6/Untitled.png)

    | 구분 | 필수 여부 | 설명 |
    | --- | --- | --- |
    | Bot 기본 정보 탭 ▼ |  | Bot의 권한과 기능을 수정할 수 있는 탭 |
    |      제작사 | 필수 | Bot 제작사<br>- 제작사는 해당 워크스페이스명으로 고정 |
    |      아이콘 | 선택 | Bot의 아이콘 이미지 |
    |      이름 | 필수 | Bot의 이름 |
    |      한 줄 설명 | 필수 | Bot 목록에 표시할 문구 |
    |      소개 | 선택 | Bot의 역할 또는 알림 상황 설명 문구 |
    |      App Key | 필수 | Bot 생성 시 자동으로 부여되는 값<br>- Bot 인증 시 Request 파라미터에 App Key를 이용하여 인증 요청 |
    |      문의 | 필수 | Bot 담당자 정보<br>- 아이디, 메일 등 |

    2.  **Bot 권한 및 기능 탭**에서 정보 수정 후 \[저장] 버튼을 클릭합니다.

        ![그림. Bot 권한 및 기능 설정](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/618f8520-5317-4dae-b13b-3a94c93cb6b1/Untitled.png)

    | 구분 | 필수 여부 | 설명 |
    | --- | --- | --- |
    | Bot 권한 및 기능 탭 ▼ |  | Bot의 권한과 기능을 수정할 수 있는 탭 |
    |      Bot 권한 선택 ▼ | 선택 | Bot 제작에 필요한 API 권한 선택 가능<br>- 자세한 설명은 [Web API 가이드](https://docs.kakaoi.ai/kakao_work/webapireference/) 참고 |
    |          멤버 조회 | 선택 | 사용자 정보를 다루는 [멤버 조회](https://docs.kakaoi.ai/kakao_work/webapireference/users/) API |
    |          채팅방 조회 | 선택 | 채팅방을 조회하는 [채팅방 조회](https://docs.kakaoi.ai/kakao_work/webapireference/conversations/) API |
    |          메시지 발송 | 선택 | 메시지를 다루는 [메시지 발송](https://docs.kakaoi.ai/kakao_work/webapireference/messages/) API |
    |          부서, 조직도 조회 | 선택 | 특정 워크스페이스에 속한 부서 정보를 조회하는 [부서, 조직도 조회](https://docs.kakaoi.ai/kakao_work/webapireference/departments/) API |
    |          채팅방 개설 | 선택 | 채팅방을 개설하는 [채팅방 개설](https://docs.kakaoi.ai/kakao_work/webapireference/conversations/) API |
    |      URL 등록 ▼ | 선택 | Bot이 동작하는데 필요한 URL 등록 가능<br>- URL 등록 후 교육용 카카오워크 담당자가 해당 정보 확인 후 등록 완료 메일 발신<br>- Request URL과 Callback URL의 활용 시점에 관한 부분은 [Bot 시작 가이드](https://docs.kakaoi.ai/kakao_work/botdevguide/)의 반응형 시나리오 참고 |
    |          Request URL | 선택 | 메시지의 Button(Button Block, Action Block) 블록을 눌렀을 때, 모달 블록 구성을 호출할 수 있는 URL |
    |          Callback URL | 선택 | Request URL에서 받은 모달 화면에서 사용자가 입력하거나 선택한 정보를 POST 요청으로 보내기 위한 URL |

{% hint style="info" %}
**안내**\
자세한 Bot 개발 방법은 \[[카카오 i 기술문서\] Bot 개발 가이드](https://docs.kakaoi.ai/kakao\_work/botdevguide/)와 \[[카카오 i 기술문서\] Web API 레퍼런스](https://docs.kakaoi.ai/kakao\_work/webapireference/) 문서를 참고하시기 바랍니다.
{% endhint %}
