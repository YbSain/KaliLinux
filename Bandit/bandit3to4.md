# Bandit3 -> Bandit4

![image](https://github.com/YbSain/KaliLinux/assets/108385276/0f371fc9-ccf0-47d8-b06c-c6204247ce57)

## Level Goal
이번 레벨의 목표는 inhere 디렉토리의 hidden file을 찾는 문제이다.

## How to Solve

### ls 사용

![image](https://github.com/YbSain/KaliLinux/assets/108385276/1ddd5019-8f6c-486e-8dc7-c1042bd267d7)

ls 사용결과 홈디렉토리 내부에 inhere 디렉토리가 있다.

### cd로 inhere 디렉토리에 진입 한 뒤, ls로 파일을 확인

![image](https://github.com/YbSain/KaliLinux/assets/108385276/699273ba-db13-4536-a436-9f92ee4f464f)

그냥 __ls__ 를 사용한 경우 _hidden_file_ 답게 나오지 않는 모습이다.

### ls 커맨드 중 -a를 사용

![image](https://github.com/YbSain/KaliLinux/assets/108385276/6f2a87bf-7bb1-42e8-a125-218e25d56ec9)

이전에는 보이지않았던 . .. 디렉토리와 __.hidden__ 파일이 보인다.

## ANS

![image](https://github.com/YbSain/KaliLinux/assets/108385276/8ed32479-a996-4f24-8527-46d6d1ee0605)


## Passward
