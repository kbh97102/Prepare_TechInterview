# 목차
1. [Coroutine](#1.-Coroutine-정리)
2. [Data Binding](#2.-DataBiding-정리)
3. [Jetpack Library](#3.-Jetpack-Library-정리)

## 1. Coroutine 정리
### 코루틴은 경량 스레드다
Coroutine은 단독으론 실행 될 수 없다. 스레드에서 실행이 된다. 여러 개의 코루틴을 한 스레드에서 실행 시킬 수는 있지만,
한번에 한 개씩 실행되며 코루틴 내부에서 Suspend Point에 달하면 resume 가능한 다른 코루틴으로 넘어간다. 
이때문에 Context switch 의 오버헤드가 없고 많은 동시성 작업을 처리 가능하다.
### 코루틴에서 중요 키워드 3가지
1. CoroutineScope == launch or async를 사용해서 만든 코루틴 추적
   1. 실행중인 코루틴 취소 가능
   2. 수명주기를 제어 가능함
   3. 특정 주기 클래스 (ViewModel, LifeCycle)같은 경우 자체 Scope가지고 있음
2. dispatcher == 실행 할 수 있는 위치
   1. Main -> UI 작업이 가능한 메인 스레드 당연히 오랜 시간이 걸리는 작업은 하면 안됨
   2. IO -> 디스크 또는 네트워크 IO에 최적화되어있음
   3. Default -> Cpu많이 먹는 작업에 최적화
3. yield
   1. 말 그대로 자신이 하던 일을 멈추고 다른 스레드가 돌아가게끔 양보
    


## 2. DataBiding 정리


## 3. Jetpack Library 정리