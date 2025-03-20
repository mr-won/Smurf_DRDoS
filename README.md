# Smurf_DRDoS
Smurf_DRDoS

Distributed(분배) Reflection(반사) DoS 

공격자가 출발지 IP를 공격 대상 IP로 위조한 후 증폭 네트워크로 ICMP Echo Request 메시지를 브로드캐스팅으로 전송
타켓 IP로 대량의 ICMP Echo Reply 메시지 전송

## DRDoS and DDoS 's Difference? 
- DRDoS는 증폭을 활용하기 때문에 공격효과가 증가
- DRDoS는 직접 공격을 수행하지 않고 반사 서버(Reflected Server)를 이용하여 역추적이 어렵다.
