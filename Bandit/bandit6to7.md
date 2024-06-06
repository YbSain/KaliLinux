# bandit6 - > bandit 7

![image](https://github.com/YbSain/KaliLinux/assets/108385276/2675074c-6a9a-48b2-bf92-3f1d73874c28)

이 문제도 어딘가에 있는 파일의 위치를 찾는것이다.   

find 명렁어를 사용할듯 싶음
## find

위 문제에 해당하는 조건을 그대로 다 기입해주었다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/37e9a328-4ceb-494e-9180-ae39f0ee284b)

여기서 -user 는 유저 이름, -group은 그룹, 33bytes 짜리기때문에 -size 33c 를 사용하였고, 마지막에 2>dev/null 을 사용해서 Permission denied된 파일들은 표시되지 않게 하였음   

## Solve
![image](https://github.com/YbSain/KaliLinux/assets/108385276/d7bfe3f0-1056-4fd1-a4f8-f598534d2d28)
해당 위치의 파일만 찾아내었다.

## Passward
z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
