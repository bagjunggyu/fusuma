### 리눅스 민트 22.3 시나몬에서 단축키를 먼저 지정하고 설정한 fusuma의 confi.yml입니다.
##### alt + q - 창 닫기, 세 손가락 아래로
##### alt + w - 창 최대화 토글 , 세 손가락 위로
##### alt + e - 창 최소화
##### 우선 위의 단축키를 먼저 지정하고, 시나몬의 터치패드를 끕니다.
### fusuma 설치 
##### $ sudo gpasswd -a $USER input 
##### $ apt install libinput-tools ruby xdotool
##### $ sudo gem install fusuma 
##### $ mkdir -p .config/fusuma 
##### $ xed .config/fusuma/config.yml 
##### 또는, 이 설정 값을 다운로드해서 ~/.config/fusuma 폴더에 붙여 넣으면 됩니다.
### 시작 애플리케이션에 등록합니다.
##### https://blog.naver.com/bagjunggyu/224231202195
