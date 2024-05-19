# bandit0부터 시작

1. 문제

![image](https://github.com/YbSain/KaliLinux/assets/108385276/407736b2-0b66-4fe4-98d7-2581416af6a6)

위 문제는 맨 처음에 Command you may need to solve this level에 있는 ssh를 이용하여 linux에서 bandit Level 0겸 bandit 접속을 위한 기초적인 과정임.
접속 명령어는 아래와 같다.

      ssh bandit0@bandit.labs.overthewire.org -p 2220

ssh는 Secure Shell 이라고 부르며 이는 네트워크를 통해 안전하게 원격 시스템에 접속하고 명령을 실행할 수 있게 해주는 프로토콜이자 도구이다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/f7cfeff8-4e72-41e2-a60e-4b0e02ae92ea)

위 사진처럼 "bandit0@bandit.lab.overthewire.org's passward: "이 나오는데 문제에 passward는 bandit0으로 알려줬으니 입력하면 넘어가진다
(비밀번호를 입력할 때에는 눈으로 보이지 않기 때문에 입력이 안되나 생각하지 않아도된다.)

![image](https://github.com/YbSain/KaliLinux/assets/108385276/e8f09359-ef3e-46cb-b025-0236633ff6f5)

과정이 완료되면 root였던 쉘이 bandit0@bandit쉘로 바뀌게 된다.

이제 bandit0 -> bandit1 즉 다음 레벨을 위한 과정이자 bandit 모험의 시작이다.
