# bandit7 -> bandit8
![image](https://github.com/YbSain/KaliLinux/assets/108385276/68dad35b-dce6-4f34-948a-a17eb7f73b50)

이번문제는 매우 간단했다

data.txt 파일에서 millionth 단어 옆에 있는 문장이 password임

## cat & grep
초기에 아무 조건없이 cat data.txt 만 사용할 경우 
![image](https://github.com/YbSain/KaliLinux/assets/108385276/db8ce3e5-2aa5-43ef-8608-974d419ac2b7)
위와 같이 수많은 키워드와 복잡한 문자열이 나오는데, 이중 millionth만 추려내면 되는것이다

   cat data.txt | grep 'millionth'

## Solve

위의 명령어를 사용할 경우
![image](https://github.com/YbSain/KaliLinux/assets/108385276/5e75dce5-1b86-488f-9019-b49f46c5d57d)
하나의 문장만 나오게 되는것을 알 수있다

## Password
