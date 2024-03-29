# J-TAG-SWD
> JTAG와 SWD는 MCU와 통신을 통해 디버깅과 플래시 프로그래밍을 도와주는 인터페이스이다.  
>
> JTAG는 여러 디바이스에 모두 사용할 수 있다는 장점이 있고, SWD는 핀 개수가 JTAG보다 적어 보다 간단한 구성을 가지고 있다는 장점이 있다.  
***
## JTAG 핀 연결 
- TCk (Test Clock): 클럭 신호 전송핀, 디버깅 장치와 타겟 사이의 동기화 역할을 한다.  
- TMS (Test Mode Select): 타겟 장치의 상태를 테스트 모드로 선택하는 데 사용되는 핀.  
- TDI (Test Data IN): 데이터 전송핀(디버깅 장치->타겟 장치). 프로그래밍 데이터나 디버깅 명령을 전송한다.  
- TDO (Test Data Out): 데이터 전송핀(타겟 장치->디버깅 장치) 디버깅 상태 또는 응답 데이터를 전송.  
- RESET : 타겟 초기화, 디버깅 세션을 초기 상태로 되돌린다.  
***
## SWD 핀 연결 
- SWDIO (Serial Wire Clock)
- SWCLK
- RESET
- SWO
***
