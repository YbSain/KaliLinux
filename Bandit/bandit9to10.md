# bandit 9 - > bandit 10

![image](https://github.com/YbSain/KaliLinux/assets/108385276/0dd52025-14ee-47ee-9ba8-a1831232f674)

## Level Goal
위 문제는 data.txt에서 여러개의 등호를 포함한 몇개 없는 human-readable 문자열이 있다고한다

### cat
cat 명령어를 사용해봤더니, 애초에 ASCII text파일 조차도 아니다.

## Commands you may need to solve this level
여기 항목에서 제공하는 명령어를 봤더니 생소하지만 위의 문제와 동일한 strings라는 것이 있음.
## Strings
![image](https://github.com/YbSain/KaliLinux/assets/108385276/78228c68-cfc8-4745-a672-7070409688e1)
strings를 사용한 결과, 이상한 기호들은 전부 사라져있고, 사람이 읽을만한 정도의 기호와 알파벳 그리고 숫자의 형태로 바뀐모습이다

## grep
이제 문제에서 힌트로 알려준 여러개의 등호에 password에 대한 단서가 있다고 했으니 두가지를 함께 사용해보았다

## Solve
![image](https://github.com/YbSain/KaliLinux/assets/108385276/c42f9e5c-00a5-46cf-b321-7ecb69ea1c47)
아주 친절하게 The Password Is 하면서 알려주었다

## Password
G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
