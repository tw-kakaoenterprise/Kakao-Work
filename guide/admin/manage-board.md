# 게시판 관리하기

[카카오워크 관리자 서비스](https://admin.kakaowork.com/) **게시판** 메뉴에서는 워크스페이스 멤버들에게 전달할 공지 게시글을 작성하고, 카카오워크 채팅방에 공지 게시글 관련 Bot 알림 메시지를 발송할 수 있습니다. 멤버들은 관리자가 발송한 Bot 메시지 또는 웹 게시판([https://noticeboard.kakaowork.com](https://noticeboard.kakaowork.com))에서 상세한 공지 내용을 확인할 수 있습니다. 게시판 메뉴는 접근 권한이 있는 관리자만 접근하고, 공지 게시글을 작성할 수 있습니다.

**게시판 화면 구성**

| 구분           | 설명                                                                                                     |
| ------------ | ------------------------------------------------------------------------------------------------------ |
| ⓵ 새 게시글 작성   | 새로운 게시글 생성                                                                                             |
| ⓶ 웹 게시판 바로가기 | 게시글을 열람할 수 있는 웹사이트(https://noticeboard.kakaowork.com/)로 이동                                             |
| ⓷ 게시글 리스트    | 현재 등록되어 있는 게시글 리스트                                                                                     |
|      제목      | 게시글 제목                                                                                                 |
|      추가 일시   | 게시글을 최초 생성한 일시                                                                                         |
|      수정 일시   | 게시글을 마지막으로 수정한 일시                                                                                      |
|      게시 상태   | <p>게시글의 현재 노출 상태 표시<br>- [정상]: 게시글이 웹 게시판에 정상 노출된 기본 상태<br>- [미노출]: 게시글이 작성되었으나, 웹 게시판에 노출되지 않은 상태</p> |
|      작성자     | <p>게시글을 작성한 관리자의 정보<br>- 게시글이 수정된 경우, 최종 수정자의 정보를 표시</p>                                               |

### 새 게시글 작성하기

워크스페이스 멤버들에게 전달할 공지 게시글을 작성하고, 이를 Bot 메시지로 발송할 수 있습니다.

1.  **게시판** 메뉴에서 \[새 게시글 작성] 버튼을 클릭합니다.

    ![그림. 새 게시글 작성](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B2%8C%EC%8B%9C%EA%B8%80_%EC%9E%91%EC%84%B1.png)


2.  제목과 본문을 작성하고, \[등록] 버튼을 클릭합니다.

    * 각 첨부 파일은 100MB 이하여야 하며, 총 300MB 까지 첨부할 수 있습니다.
    * 첨부 파일 확장자가 `.bmp`, `.png`, `.jpeg`, `.gif`인 경우, 하단에 썸네일이 생성됩니다. 썸네일에서 **본문 삽입**을 클릭하면 본문 내에 해당 이미지를 삽입할 수 있습니다.

    ![그림. 게시글 작성](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B2%8C%EC%8B%9C%EA%B8%80_%EC%9E%91%EC%84%B1.png)


3.  Bot 메시지 발송 여부를 선택합니다.

    | 버튼        | 설명                                    |
    | --------- | ------------------------------------- |
    | 게시글만 등록하기 | 게시글만 등록하고 Bot 메시지는 발송하지 않음            |
    | 발송하기      | 게시글을 등록한 후, 워크스페이스 전체 멤버에게 Bot 메시지 발송 |

    ![그림. Bot 메시지 발송 여부 확인](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EB%B4%87_%EB%A9%94%EC%8B%9C%EC%A7%80_%EB%B0%9C%EC%86%A1_%EC%97%AC%EB%B6%80_%ED%99%95%EC%9D%B8.png)

    {% hint style="info" %}
    **안내**\
    Bot 메시지는 게시글을 작성할 경우에만 발송할 수 있습니다.
    {% endhint %}

**게시판 알림 Bot**

Bot 메시지 발송 시, 워크스페이스 멤버들은 게시판 알림 메시지를 수신합니다. 멤버가 Bot 메시지에서 \[게시글 보기] 버튼 클릭하면, 상세 게시글을 확인할 수 있습니다.

![그림. 게시판 알림 Bot 메시지](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B2%8C%EC%8B%9C%ED%8C%90%20%EC%95%8C%EB%A6%BC%20%EB%B4%87%20%EB%A9%94%EC%8B%9C%EC%A7%80.png)

### 게시글 수정 및 삭제하기

업로드한 게시글의 내용 혹은 게시 상태를 수정하거나, 게시글을 삭제하는 방법은 다음과 같습니다.

1.  게시글 리스트에서 수정할 게시글을 클릭합니다.

    ![그림. 수정할 게시글 선택](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%88%98%EC%A0%95%ED%95%A0_%EA%B2%8C%EC%8B%9C%EA%B8%80_%EC%84%A0%ED%83%9D.png)


2.  게시글을 수정하고 \[적용] 버튼을 클릭하거나, \[삭제하기] 버튼을 클릭하여 게시글을 삭제합니다.

    * **게시 상태**를 **미노출**로 변경 시, 해당 게시글이 웹 게시판에 노출되지 않습니다.

    ![그림. 게시글 수정 및 삭제](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EA%B2%8C%EC%8B%9C%EA%B8%80_%EC%88%98%EC%A0%95_%EB%B0%8F_%EC%82%AD%EC%A0%9C.png)

### 웹 게시판 바로가기

실제 멤버들이 보게되는 웹 게시판([https://noticeboard.kakaowork.com](https://noticeboard.kakaowork.com))으로 이동하여 공개된 게시글 목록을 확인하는 방법은 다음과 같습니다.

1.  **게시판** 메뉴에서 \[웹 게시판 바로가기] 버튼을 클릭합니다.

    ![그림. 웹 게시판 바로가기](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9B%B9_%EA%B2%8C%EC%8B%9C%ED%8C%90_%EB%B0%94%EB%A1%9C%EA%B0%80%EA%B8%B0.png)


2.  작성한 게시글을 확인합니다.

    ![그림. 웹 게시판](https://t1.kakaocdn.net/service_kep_docpublish/Figma/%5B%EA%B4%80%EB%A6%AC%EC%9E%90%20%EA%B0%80%EC%9D%B4%EB%93%9C%5D%20Kakao%20Work/%EC%9B%B9_%EA%B2%8C%EC%8B%9C%ED%8C%90.png)
