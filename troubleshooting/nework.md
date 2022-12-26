# nework
- nscd

  - name server cache domain

- ipconfig/flushdns

  - DNS 초기화

- route print / netstat -r

  - 라우팅 테이블 확인

- netstat

  - -l (listen) : 연결 가능한 상태
  - -n (number port) : 포트 넘버
  - -t (tcp) : tcp
  - -u (udp) : udp
  - -p : 프로그램 이름 / PID
  - -a : 모두
  - -i : 이더넷 카드별 정상/에러/드랍 송수신 패킷 수 확인
  - -r : 라우팅 테이블
  - -s : 네트워크 통계

- ifconfig

  - **[flags] :** 네트워크 카드의 상태 표시
  - **[mtu] :** 네트워크 인터페이스의 최대 전송 단위(Maximum Transfer Unit)
  - **[inet] :** 네트워크 인터페이스에 할당된 IP 주소
  - **[netmask] :** 네트워크 인터페이스에 할당된 넷마스크 주소
  - **[broadcast] :** 네트워크 인터페이스에 할당된 브로드캐스트 주소
  - **[inet6] :** 네트워크 인터페이스에 할당된 IPv6 주소
  - **[prefixlen] :** IP 주소에서 서브 넷 마스크로 사용될 비트 수
  - **[scopeid] :** IPv6의 범위. LOOPBACK / LINKLOCAL / SITELOCAL / COMPATv4 / GLOBAL
  - **[ether] :** 네트워크 인터페이스의 하드웨어 주소
  - **[RX packets] :** 받은 패킷 정보
  - **[TX packets] :** 보낸 패킷 정보
  - **[collision] :** 충돌된 패킷 수
  - **[Interrupt] :** 네트워크 인터페이스가 사용하는 인터럽트 번호

- ping

- nmap

  - 포트 스캐닝 툴
  - 호스트나 네트워크를 스캐닝할 때 사용
  - 방화벽 안쪽의 네트워크도 스캔할 수 있음

- iptables

  - 방화벽을 설정하는 도구

    ![img](https://t1.daumcdn.net/cfile/tistory/2773BA3354A9D63327)

- AB

  - 아파치의 HTTP 서버의 성능을 검사하는 도구
  - 현재 아파치가 어떻게 동작하는지 알려준다.
  - 현재 토당 몇개의 요청을 서비스 하는지 알려줌

- nGrinder

  - 애플리케이션 부하테스트 툴
  - 스크립트를 작성하여 애플리케이션의 부하를 테스트하는 용도

- nalookup

  - 도메인의 IP정보 조회
  - -type=레코드종류 옵션을 통해 다양한 레코드 파악 가능

- web service monitoring service(WMS)

  - 웹 서비스 모니터링 서비스(ncloud)
  - 시나리오 기반 모니터링
  - 시나리오에 작성도니 기능이 잘 수행되는지 확인
  - 필터링 가능을 통해 예외처리 혹은 특정 url을 제외시키는 것이 가능

- pinpoint

  - 자바 분산 서비스 및 시스템의 지속적인 성능 분석 지원
  - 오류 발생 가능성에 대한 진단과 추적 제공
  - 접속 안되면 ACG 확인

- tcpdump

  - 주어진 조건을 만족하는 네트워크 인터페이스를 거치는 패킷들의 헤더를 출력
    - 트래픽 모니터링
  - tcpdump로 패킷을 파일로 저장한 후 wireshark로 읽어서 분석하면 됨
  - NCP내에서 LB로 연결된 구조에는 부적합

- ethtool

  - NIC정보 파악

- netconfig

  - 네트워크 환경을 설정하는데 사용

- virtual private agateway

  - 

- route 

  - 운영중인 시스템의 라우팅 경로 설정