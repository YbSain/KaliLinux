# bandit4 -> bandit5
![image](https://github.com/YbSain/KaliLinux/assets/108385276/7a456202-cd84-419a-823b-afc2e1fb869b)

## level Goal

inhere 디렉토리 내부에서 사람이 읽을 수 있는 파일을 찾는 것이 이번 단계의 목표임

## How to solve

### ls
![image](https://github.com/YbSain/KaliLinux/assets/108385276/706ce95e-ceff-4aad-b4f3-cf2c0a609bb5)
inhere 디렉토리는 현재 홈디렉토리에 있음을 알게되었다   

### cd
![image](https://github.com/YbSain/KaliLinux/assets/108385276/2b8e6b65-a43e-4839-b563-5360d61e091c)

inhere 디렉토리로 위치를 이동시킴   

### ls(한번 더)

ls를 사용해서 현재 디렉토리에 어떤 파일들이 있는지 확인함.

### file
![image](https://github.com/YbSain/KaliLinux/assets/108385276/718852e3-eacb-4f5a-838a-e0f14b54560e)

위의 file 명령어를 사용할 시 파일들의 타입을 확인 할 수 있음   
숫자끝에 __*__ 는 오름차순으로 파일을 읽어준다.

## Solved
![image](https://github.com/YbSain/KaliLinux/assets/108385276/52939e07-8570-4585-8670-d4e21afef722)
여러 파일들 중에서 유일하게 ASCII text 파일이 존재함   
따라서 cat ./-file07로 해당 파일을 읽었다.

## Passward
lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
