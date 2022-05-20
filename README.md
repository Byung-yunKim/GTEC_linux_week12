# GTEC_linux_week12

2022.05.20

sudo useradd [유저명] -> 유저 생성    
sudo passwd [유저명] -> 유저 비밀번호 설정    
sudo usermod -aG sudo [유저명] -> 유저한테 sudo 권한 부여

sudo nano /etc/group    
sudo nano /etc/shadow    
sudo nano /etc/passwd

sudo adduser --home /gtechome gtec2 -> gtec2라는 유저의 홈 디렉토리를 gtechome으로 설정

sudo userdel -r [유저명] -> 유저 삭제

ln [원본파일명] [링크할 파일명] -> 하드링크    
ln -s [원본파일명] [링크할 파일명] -> 심볼릭링크
