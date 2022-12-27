# 부록. 카카오워크 관리자 서비스

## 카카오워크 관리자 서비스

[[Admin 사이트\] 관리자 서비스](https://admin.kakaowork.com/)는 고객사가 업무 환경과 요구 사항에 맞게 카카오워크를 사용할 수 있도록 워크스페이스 설정, 커스텀 Bot 개발 및 수정 등의 다양한 기능을 제공합니다. 관리자 서비스는 슈퍼 관리자, 관리자 또는 Bot 개발자 권한을 부여받은 멤버만 접근할 수 있습니다.

{% hint style="info" %}
**안내**<br>
**카카오워크 관리자 서비스** 대표 기능
* [워크스페이스 환경 설정](https://www.notion.so/7218c86c7c6b4b829d924df5469adcda)
* [멤버 및 관리자 권한 설정](https://www.notion.so/40c226233dab4bfaa0675f12770f3540)
* [카카오워크 바로가기 관리](https://www.notion.so/22ebe24d47804be3ae0ba4d288b44c77)
* [커스텀 Bot 관리](https://www.notion.so/d17fc11a945a45129657371bdaa6cd33)
* [모바일 및 PC 보안 관리](https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f)
* [결제 관리](https://www.notion.so/b6fbd5a435ac402fac3ea0ab7b62e836)
* [통계 관리](https://www.notion.so/1674c398edcc4faaa26b94a76419373e) 
{% endhint %}

| 구분 | 접속 방법 |
| --- | --- |
| 바로가기 링크 | 카카오워크 관리자 서비스 링크(https://admin.kakaowork.com/)로 접속<br><br> - https://www.kakaowork.com/에서도 [관리자] 버튼을 클릭하여 https://admin.kakaowork.com/ 접속 가능 |
| 카카오워크 PC 앱 | 더보기 > 관리자 서비스 클릭  |

{% hint style="info" %}
**안내**<br>[카카오워크 관리자 서비스](https://admin.kakaowork.com/)는 Chrome 또는 IE11 이상의 브라우저 환경에 최적화되어 있습니다.

{% endhint %}

### 권한 정보

카카오워크의 권한은 크게 **관리자, Bot 개발자, 사용자**로 구분되며, **관리자**는 **슈퍼 관리자**와 **관리자**로 구분됩니다.

최초 워크스페이스를 생성하면 슈퍼 관리자 권한을 획득하며, 슈퍼 관리자는 워크스페이스에 한 명만 존재합니다. 슈퍼 관리자는 관리자 지정/워크스페이스 서비스 탈퇴/기기 인증/슈퍼 관리자 위임 등을 진행할 수 있습니다. 슈퍼 관리자로부터 지정된 관리자는 다른 멤버를 관리자로 추가할 수 있으며, 슈퍼 관리자가 위임한 일부 역할을 수행할 수 있습니다.

각 권한에 따라 카카오워크 관리자 서비스에서 수행할 수 있는 역할은 다음과 같습니다.

{% hint style="info" %}
**안내**\
커스텀 Bot을 개발하기 위해서는 슈퍼 관리자 또는 관리자로부터 Bot 개발자 권한을 부여받아야 합니다.
* 슈퍼 관리자 또는 관리자가 Bot 개발을 수행하는 경우에도 Bot 개발자 권한 등록이 필요합니다 {% endhint %}

| 권한 | 대상자 | 역할 |
| --- | --- | --- |
| 관리자  |  슈퍼 관리자와 관리자로 구분<br> - 자세한 사용 방법은 https://www.notion.so/abc6435cb3904902ae5496c66471497c 문서 참고 | 워크스페이스, 조직, 멤버 등 관리 책임자 |
|      슈퍼 관리자 | 워크스페이스를 최초 개설한 멤버로, 워크스페이스의 모든 권한을 관리<br> - 워크스페이스당 한 명의 슈퍼 관리자 존재 | 워크스페이스의 책임 관리<br> - 워크스페이스에 멤버 초대 및 관리<br> - 멤버에게 관리자, Bot 개발자 권한 부여<br> - 카카오워크 앱 내 Bot 노출 여부 설정 |
|      관리자 | 슈퍼 관리자 또는 기존 관리자로부터 권한을 부여받은 멤버<br> - 워크스페이스 별로 다수 관리자 지정 가능<br> - 별도로 관리자를 지정하지 않을 경우에는 존재하지 않을 수 있음 | 슈퍼 관리자가 위임한 일부 역할을 수행<br> - 워크스페이스에 멤버 초대 및 관리<br> - 멤버에게 관리자 또는 Bot 개발자 권한 부여<br> - 카카오워크 앱 내 Bot 노출 여부 설정 |
| 사용자 | 관리자나 Bot 개발자 권한 없이, 카카오워크만 사용하는 멤버<br> - 자세한 사용 방법은 https://www.notion.so/66999c5ad9d6492da7fa1aa44c255cd1 문서 참고 | 관리자 서비스에 접근 불가 |
| Bot 개발자 | 슈퍼관리자 또는 관리자로부터 개발자 권한을 부여받은 멤버 |  커스텀 Bot 생성, 개발한 Bot의 수정 및 관리<br> - 봇 관리 > Bot 개발 메뉴에만 접근 가능 |

### 메뉴 구성

[카카오워크 관리자 서비스](https://admin.kakaowork.com/)의 메뉴 구성은 다음과 같습니다.

![그림. 카카오워크 관리자 서비스](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e8bbfb80-215e-4315-b979-cc1aefa04485/%EC%B9%B4%EC%B9%B4%EC%98%A4%EC%9B%8C%ED%81%AC\_%EA%B4%80%EB%A6%AC%EC%9E%90\_%EC%84%9C%EB%B9%84%EC%8A%A4.png)

| 구분 | 설명 |
| --- | --- |
| https://www.notion.so/7218c86c7c6b4b829d924df5469adcda  | 워크스페이스의 기본 정보와 프로필 정보 설정  |
|      https://www.notion.so/7218c86c7c6b4b829d924df5469adcda | 워크스페이스 이름과 ID 등과 같은 기본 정보 설정 |
|      https://www.notion.so/7218c86c7c6b4b829d924df5469adcda | 프로필에 표시할 항목 변경 |
| https://www.notion.so/40c226233dab4bfaa0675f12770f3540  | 워크스페이스의 멤버, 조직도, 직책/직위, 관리자 설정, 계정 연동 등 수행 |
|      https://www.notion.so/40c226233dab4bfaa0675f12770f3540 | 워크스페이스에 새로운 멤버 등록 및 기존 멤버의 정보 조회 또는 변경 |
|      https://www.notion.so/40c226233dab4bfaa0675f12770f3540 | 조직도 구성 및 조직도 정보 생성/관리 |
|      https://www.notion.so/40c226233dab4bfaa0675f12770f3540 | 워크스페이스 멤버들의 직책 또는 직위 설정 |
|      https://www.notion.so/40c226233dab4bfaa0675f12770f3540 | 워크스페이스 관리자를 설정 및 관리자별 접근 가능 메뉴 제한 설정 |
|      https://www.notion.so/40c226233dab4bfaa0675f12770f3540 | 카카오워크 앱과 다양한 회사 시스템과 연동ㅊ상세 작업은 https://account.kakaoi.ai/login/form페이지에서 진행 |
| https://www.notion.so/6771ab948065447faa4da9ede653cfc7 | 카카오워크 앱의 바로가기에 기본으로 제공되는 워크 서비스의 노출 여부를 설정 |
| https://www.notion.so/15854aaf2a3147a5a41c54e254aef1fb | 워크스페이스 멤버들에게 전달할 공지 게시글 작성 및 관리 |
| https://www.notion.so/22ebe24d47804be3ae0ba4d288b44c77 | 카카오워크 앱의 바로가기 메뉴에서 제공하는 서비스를 등록 및 편집 |
| https://www.notion.so/d17fc11a945a45129657371bdaa6cd33  | 기존 Bot을 관리 및 신규 Bot을 개발/관리 |
|      https://www.notion.so/d17fc11a945a45129657371bdaa6cd33 | 워크스페이스에서 사용 중인 Bot 내역과 활성화 여부 설정 |
|      https://www.notion.so/d17fc11a945a45129657371bdaa6cd33 | 워크스페이스용 Bot을 생성할 수 있는 개발자 추가 및 관리 |
|      https://www.notion.so/d17fc11a945a45129657371bdaa6cd33https://www.notion.so/d17fc11a945a45129657371bdaa6cd33 | 워크스페이스의 커스텀 Bot을 생성 및 관리<br> -Bot 개발자로 지정된 멤버만 Bot 개발 가능 |
|      http://kko.to/4jaSAsafj | Bot 개발을 위한 기술 문서인 https://docs.kakaoi.ai/kakao_work/webapireference/ 가이드로 연결 |
|      http://kko.to/JbJZAstfT | Block Kit을 활용하여 커스텀 Bot을 구성해 볼 수 있는 https://www.kakaowork.com/block-kit-builder로 연결 <br> -자세한 내용은 https://docs.kakaoi.ai/kakao_work/blockkit/appdix_c/ 참고 |
|      QnA 데이터 관리↗︎ | Kakao i Kasper 지식 검색에서 활용할 서비스 데이터 등록/관리 |
| https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f  | 카카오워크의 PC 버전과 모바일 버전의 보안 관련 설정 관리 |
|      https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f | 카카오워크 사용과 관련된 보안 설정 가능 |
|      https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f | 카카오워크 PC 앱 사용과 관련된 보안 설정 관리 |
|      https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f | 카카오워크 모바일 앱 사용과 관련된 보안 설정 관리 |
|      https://www.notion.so/ff61cee4d0004b6b98f4cf757c8bb38f | 외부 카카오워크 워크스페이스 멤버와 대화 설정 가능 |
| https://www.notion.so/b6fbd5a435ac402fac3ea0ab7b62e836  | 월별 이용 내역과 납부 현황을 확인하고, 청구 정보를 조회 또는 변경 가능 |
|      https://www.notion.so/b6fbd5a435ac402fac3ea0ab7b62e836 | 카카오워크 이용과 관련된 청구현황 확인 |
| https://www.notion.so/1674c398edcc4faaa26b94a76419373e | 카카오워크 이용과 관련된 통계 분석 확인 |