# bandit8 -> bandit9

![image](https://github.com/YbSain/KaliLinux/assets/108385276/43a6563b-4154-4c18-8e03-a40b37655976)

## Level Goal

이번 레벨의 목표는 수많은 문장들 중에서 중복되어있지않은 유일한 문장 하나가 password라고 한다..

## cat

cat으로 data.txt를 읽었더니 역시나 수많은 password 호소인들이 나오더라   

## uniq

처음 보니 생소해서 man uniq를 사용하여 uniq -u가 중복문자를 덜어주고 외의 문장만 읽어주는 명령어인것을 알아냄.

## sort
cat으로 계속 하였으나 결론이 나지않아 웹서핑을 해보니, 중복의 기준이 연달아 나와야 중복으로 여기는 듯 하다.

따라서 cat data | uniq -u 가 아닌, 내림차순으로 정렬해주는 sort 를 활용하여 sort data.txt | uniq -u 로 문제를 해결함

![image](https://github.com/YbSain/KaliLinux/assets/108385276/53966a68-d5de-4024-b113-cd85cc7ecdec)

## PAss word
EN632PlfYiZbn3PhVK3XOGSlNInNE00t
