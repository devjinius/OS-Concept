# OS-Concept
운영체제 스터디 내용을 공유합니다.
개념 위주로 작성합니다. 필요시 코드를 첨부합니다.

# 목차
1. Abstract
  1. About OS
  2. 컴퓨터 시스템 구조
    - 저장장치 계층 구조
    - Device Contoroller
    - Program Counter
    - Mode Bit
    - Timer
    - Interrupt
    - DMA
    
  3. 프로세스 - 소개
    - About Process
    - Process Execution
    - Process Memory Structure
    - Process State
    
  4. 커널 - 소개
    - Kernel Memory Structure
    - Process Control Block
    - Context Switch
    - System Call
    
  5. CPU 스케줄링
    5.1 선점과 비선점 preemptive vs non-preemptive
    5.2 Scheduling Criteria
      - CPU bound, IO bound
      - CPU Utilization
      - Throughput
      - Turnaround Time
      - Waiting Time
      - Response Time
    5.3 스케줄링 종류
      - FCFS
      - SJF
      - Priority
      - Round Robin (RR)
      - Multilevel Queue
      - Multilevel Feedback Queue
      
   6. 프로세스 - 동기화
      6.1 다중작업
          - MutiProcess (IPC)
            - Message Passing
            - Shared Memory
          - MultiThread
      6.2 문제
          - Race Condition
          - Critical Section
          - Kernel Race Condition
          
 ...
