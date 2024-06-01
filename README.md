# 오픈소스 과제
## 명령어 조사하기

+ 20243048 이건영
+ 컴퓨터공학과 1학년
  

  
| 명령어 | 설명                                          | 주요 옵션                              |
|--------|---------------------------------------------|---------------------------------------|
| top  | 현재 실행중인 프로세스들을 실시간으로 보여줌               | -d (갱신 주기 초 단위 설정), -p (특정 PID만 보여줌), -u (특정 사용자만 보여줌) |
| ps   | 현재 실행 중인 프로세스들의 정보를 보여줌               | aux (모든 프로세스 상세정보), -e (모든 프로세스), -f (풀 포맷으로 출력), -u (특정 PID의 프로세스) |
| jobs | 현재 셸 세션의 백그라운드 작업 상태 보여줌     | -l (상세 정보), -n (가장 최근 작업), -p (각 작업의 PID만 출력) -r (실행중인 작업만) |
| kill | 특정 프로세스를 종료할 때 사용                        | -9 (강제 종료), -s (보낼 신호 지정), -l (신호 목록 보여줌) |

## 명령어 상세 설명

### 1. top 

#### 설명
`top` 은 현재 실행중인 프로세스를 실시간으로 보여주는 명령어다. CPU 사용률, 메모리 사용량, 실행 중인 프로세스의 상태 등을 한 눈에 볼 수 있다.

#### 사용법
```bash
top
```

### 2. ps

#### 설명
'ps' 는 현재 실행 중인 프로세스에 대한 정보를 보여준다. 기본적으로 프로세스 ID(PID), 터미널(TTY), CPU 사용 시간(TIME), 명령어(COMMAND) 등을 확인할 수 있다.

#### 사용법
```bash
ps
```

### 3. jobs

#### 설명
jobs 는 현재 셸 세션에서 백그라운드 작업의 상태를 표시한다. 각 작업에는 고유한 작업 ID를 가지고 있어 쉽게 관리가 가능합니다.

#### 사용법
```bash
jobs
```

### 4. kill

#### 설명
kill 명령어는 특정 프로세스를 종료할 떄 사용된다. 기본적으로 SIGTERM(15) 시그널을 보내는데, 필요하면 다른 신호를 지정할 수도 있다.

#### 사용법
```bash
kill [signal] PID
```

![그로밋](https://github.com/geonyeong26/igeonyeong/blob/main/OIP.jpeg)
