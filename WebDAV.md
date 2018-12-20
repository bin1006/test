# WebDAV 연결

## 드라이브 추가
  
1. 스토리지에서 WebDAV를 선택합니다.

2. 수정이 필요한 옵션을 변경합니다.
  - 드라이브 문자 및 이름 [자세히보기](https://github.com/bin1006/test/blob/master/drive_name.md)
  - 프로그램이 시작될 때 자동 연결 [자세히보기](https://github.com/bin1006/test/blob/master/automatic.md)
  - 연결할 때마다 로그인 [자세히보기](https://github.com/bin1006/test/blob/master/connection_login.md#webdav-%EB%A1%9C%EA%B7%B8%EC%9D%B8)
  - 프록시 [자세히보기](https://github.com/bin1006/test/blob/master/proxy.md#%ED%94%84%EB%A1%9D%EC%8B%9C-%EC%82%AC%EC%9A%A9)
  - 읽기 전용 [자세히보기](https://github.com/bin1006/test/blob/master/read.md)

3. 먼저 NAS의 WebDAV 서버가 활성화 되어야 합니다.
  - [Synology](https://www.synology.com/ko-kr/knowledgebase/DSM/tutorial/File_Sharing/How_to_access_files_on_Synology_NAS_with_WebDAV)
  - [QNAP](https://www.qnap.com/ko-kr/how-to/tutorial/article/webdav%EB%A5%BC-%EC%9D%B4%EC%9A%A9%ED%95%9C-qnap-%EC%9B%90%EA%B2%A9-%EC%95%A1%EC%84%B8%EC%8A%A4)
  - [ipTIME](http://iptime.com/iptime/?page_id=67&pageid=1&mod=document&keyword=raidrive&x=22&y=15&uid=18934)
   
![synology1](/synology1.png?raw=true)


4. 주소 라벨 오른쪽의 체크박스로 스킴(http/https)을 선택합니다.
  - 서버 주소와 포트번호를 입력합니다.
  - 최상위 폴더로 출력될 서버의 경로를 입력합니다. (선택사항)
  
  
5. 사용자 비밀번호를 입력후 확인 버튼을 클릭합니다.
  - 익명 계정을 사용한다면 익명 체크박스를 클릭합니다.
      
![synology2](/synology2.PNG?raw=true)


6. 내PC 드라이브에서도 WebDAV가 생성되었습니다.

![synology3](/synology3.PNG?raw=true)


---  


# 드라이브 연결/끊기

1. 끊기 버튼(![stop](/stop_icon1.png?raw=true)) 을 클릭하면 연결한 WebDAV가 파일 탐색기에서 제거됩니다.

![webdav_play](/webdav_play.PNG?raw=true)

2. 연결 버튼(![play](/play.png?raw=true)) 을 클릭하면 WebDAV가 파일 탐색기의 네트워크 드라이브로 생성됩니다.

![webdav_stop](/webdav_stop.PNG?raw=true)



# 드라이브 편집

1. 드라이브가 연결되어 있다면, 끊기 버튼(![stop](/stop_icon1.png?raw=true)) 을 클릭합니다.

2. 편집 버튼(![setting](/setting_icon.png?raw=true)) 을 클릭합니다.

![stop_setting](/stop_setting.png?raw=true)

3. 수정이 필요한 옵션을 변경한 후, 확인 또는 적용 버튼을 클릭합니다.

  - 드라이브 문자 및 이름 [자세히보기](https://github.com/bin1006/test/blob/master/drive_name.md)
  - 프로그램이 시작될 때 자동 연결 [자세히보기](https://github.com/bin1006/test/blob/master/automatic.md)
  - 연결할 때마다 로그인 [자세히보기](https://github.com/bin1006/test/blob/master/connection_login.md)
  - 프록시 [자세히보기](https://github.com/bin1006/test/blob/master/proxy.md#%ED%94%84%EB%A1%9D%EC%8B%9C-%EC%82%AC%EC%9A%A9)
  - 읽기 전용 [자세히보기](https://github.com/bin1006/test/blob/master/read.md)

![webdav_setting](/webdav_setting.PNG?raw=true)




# 드라이브 삭제

1. 드라이브가 연결되어 있다면, 끊기 버튼(![stop](/stop_icon1.png?raw=true)) 을 클릭한 후 삭제 버튼(![delete](/delete_icon1.png?raw=true)) 을 클릭합니다.

![webdav_delet1](/webdav_delet1.png?raw=true)

2. 확인 버튼을 클릭하면 드라이브가 연결 목록에서 삭제됩니다.

![webdav_delet2](/webdav_delet2.PNG?raw=true)
