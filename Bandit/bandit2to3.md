# Bandit2 -> Bandit3

![image](https://github.com/YbSain/KaliLinux/assets/108385276/e92476bd-a664-4cc5-aadd-431bf18b4756)

## Level Goal
**spaces in this filename** 즉 공백이 있는 파일 이름을 cat명령어로 읽어야 한다.

아무런 추가 없이 __cat spaces in this filename__ 을 입력해봤다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/43d4e60e-d4bb-4a18-b212-9e5f194a8a6c)

cat 명령어가 한 파일로 읽는 것이 아닌, 공백마다 하나 하나 따로 읽는 모습이다.

## How To Solve

이에 대한 해결 방법으로는 *""* *''* *\* 세가지가 있다.

이중에서 *backslash*는 공백마다 사용해야하는 불편함이 있다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/25af3022-8ae4-428c-86ca-07f2af1b62c9)

세가지 전부 cat명령어가 제대로 실행 되었고, 동일한 passward가 나왔다.
