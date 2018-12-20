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
      
![synology_2](/synology_2.PNG?raw=true)


   



7. 내PC 드라이브에서도 WebDAV가 생성되었습니다.

![synology_5](/synology_5.PNG?raw=true)


---  


# 드라이브 연결/끊기

- RaiDrive에서 연결된 스토리지를 손쉽게 연결/끊기가 가능합니다.

1. 연결 끊기 버튼을 클릭 시 사용 중이었던 스토리지 연결상태가 어두워지면서 연결이 끊기게 됩니다.

![webdav_play](/webdav_play.PNG?raw=true)

2. 연결 버튼 클릭 시 스토리지 연동 상태가 밝아지면서 연결이 시작됩니다.

![webdav_stop](/webdav_stop.PNG?raw=true)



# 드라이브 편집

- 드라이브를 생성한 후에도 연결 상태를 편집할 수 있습니다.

1. 연결된 스토리지를 정지 시킵니다.

- [드라이브 연결 끊기](https://github.com/bin1006/test/blob/master/WebDAV.md#%EB%93%9C%EB%9D%BC%EC%9D%B4%EB%B8%8C-%EC%97%B0%EA%B2%B0%EB%81%8A%EA%B8%B0)
  - 드라이브 연결 중에는 편집이 불가능합니다.

2. 스토리지 연결이 정지된 상태에서 설정 버튼을 클릭합니다.

![stop_setting](/stop_setting.png?raw=true)

3. 설정 버튼을 클릭하면 다음과 같은 화면이 출력됩니다.

![webdav_setting](/webdav_setting.PNG?raw=true)

4. 사용자가 원하는 연결 상태로 편집 할 수 있습니다.



# 드라이브 삭제

- 드라이브 생성 후 불필요한 스토리지를 손쉽게 삭제할 수 있습니다.

1. 스토리지를 삭제하려는 경우 먼저 드라이브 연결 정지 상태로 변환 후 휴지통 아이콘을 클릭합니다.

![webdav_delet1](/webdav_delet1.png?raw=true)

2. 휴지통 아이콘을 클릭하면 다음과 같은 화면이 출력됩니다.

![webdav_delet2](/webdav_delet2.PNG?raw=true)

3. 확인 버튼을 클릭하면 스토리지가 삭제됩니다.
