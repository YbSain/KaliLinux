# Bandit1 -> Bandit 2

![image](https://github.com/YbSain/KaliLinux/assets/108385276/73388ba5-9e4f-44b4-9d3a-205a7c2bd8e0)

## Level Goal
0에서 1레벨과 같이 홈디렉토리 내부에서 - 파일을 읽으면 된다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/f49f8cb3-4985-4bd9-9d6a-190e473e6eb7)

하지만 의도와 다르게 - 파일을 읽지 못하는 모습을 보여준다.

## Helpful Reading Material
### Google Search for "dashed filename"
dash filename에 대해 검색해보라고 한다.   
dash filename은 현재 디렉토리 위치를 가르키는 __./__ 를 사용하여 **./-** 를 사용해야 cat이 인식할 수 있다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/13de770d-d339-4bce-8029-06553a62b36d)

바로 **passward**가 나오는 모습을 볼 수 있다.

똑같이 bandit2레벨을 위에서 나온 passward를 사용해서 **ssh bandit2@bandit.labs.overthewire.org -p 2220** 을 사용하여 접속할 수 있다.

## Passward
rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
