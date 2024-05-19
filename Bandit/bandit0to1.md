# bandit0 -> bandit 1 문제

![image](https://github.com/YbSain/KaliLinux/assets/108385276/b3d89480-5d0d-439a-a02b-25ee9de59e54)

## Level Goal 
이 레벨에서는 home directory 내부에 있는 __readme__ 를 읽어 패스워드를 얻고 ssh를 이용하여 bandit 1로 접속하는 과정이다.

## Commands you may need to solve this level

ls, cd, cat, file, du, find  > 명령어들이 주어졌다.
이 중에서 **find** 는 이미 홈디렉터리 내부에 있다고 알려줘서 사용 할 일이 크게없어보임.
**du** 명령어는 용량을 알아내는 명령어이기에 사용할 일이 없다.
**ls** 명령어는 디렉토리 내부에 있는 파일을 알려주고 **cd** 명령어는 디렉토리를 오갈 때 쓰인다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/fdf2205b-3191-4c6b-aef1-8718c551e112)

**ls** 명령어를 사용해서 디렉토리 내부를 확인해보니 현재 위치가 __homedirectory__ 라서 바로 readme가 나옴.
따라서 __cd__ 명령어는 사용할 일이 없어졌다.

readme 파일을 읽는 역할은 __cat__ 이 한다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/70cad694-ae24-45ec-8b19-b9b97850e43e)

__cat__ 명령어 사용결과 무작위로 입력돼있는 패스워드가 나온다.

다음레벨로 들어가기 위해 로그아웃 후 ssh bandit1@bandit.labs.overthewire.org -p 2220 으로 접속하여 passward를 입력한다.

![image](https://github.com/YbSain/KaliLinux/assets/108385276/68b0ebae-c1d2-4080-ab55-15588e0fea47)

위는 1단계로 접속 완료한 모습이다.
