2021.11.21 (코딩중)
- BB15048, GT26CW, NJ2 끼리 중련구성 불가설정.
- 매개변수 : 유럽형 열차 사용여부 (열차 : E300, E320)
- 매개변수 : 중국형 열차 사용여부 (열차 : CRH380A, CRH380A Test)
- 열차별 숫자 ID 추가 적용중.

2021.11.20
[추가]
- 매개변수 : 중국형 열차 사용여부 (열차 : CHR1, CRH3)
- 매개변수 : 유럽형 열차 사용여부 (열차 : AGV, AVE, AVE Velaro, BB15048)
- 열차 : AGV-Cool (3002)

[변경]
- 열차별 숫자 ID 적용.
- 1층공통객차 (2001), 2층 공통객차 (2002) 숫자별 ID 적용.

[제거]
- AGV-Cool열차 가상열차로 분리되면서 기존 AGV 도색에서 제거됨.

2021.11.18
- makefile 코딩으로 ***.tar 파일생성완료 / 이제 이 파일로 공개합니다.

2021.11.17 (프리뷰 공개)
[추가]
- CR600 금색도색 추가

[변경]
- 승객차량 Passinger->Passenger 오타 수정.
- 코딩방식 Makefile 변경 (코딩방식으로 변경으로 기존 편성된 차량의 편성이 변경될 수 있습니다.
- 하나의 YST.pnml 세밀 분리 작업완료
- CR600 빨강도색 그래픽 디테일 업.
- CR600+CR600 끼리 중련구성가능.
- 이름변경 공통객차->1층공통객차
- 이름변경 Metro, HMX, NKX 2층 ->2층 공통객차
- 이제 2층형 차량은 2층 공통객차로 구성해야함. 예) KTX-N, TGV Duplex, TGV Old Duplex, 2층 객차 별도구성시 적용.
- TGV 2층형 차량과, 1층형 차량은 코드의 구성불가로 인해 중련구성은 불가능합니다.

[주의사항]
  대대적인 최신형 코딩방식 Makefile의 최신방식으로 코딩이 변경됨과, 열차별 분리 작업으로 열차 편성이 꼬임이 발생합니다.
  제작자 입장에서 열차의 편성이 바뀌는것에 대해선 반가운 입장은 아닙니다. 더 큰 발전과 편의를 위해 진행하기에 불가피한 선택임을 알려드립니다. 지속적으로 발전하기로 결심한 이후로 최신 NML과 최신방식의 코딩은 피할 수 없는 선택이자 필수입니다.

  이같은 불편과 불만은 달갑게 받겠습니다. 하지만, 롤백할 의사는 절대 없음을 알려드립니다. 최고의 자료를 위해선 기능적? 으로도 최신을 사용해야 한다는 것의 저의 생각이오니, 모두 양해바랍니다

  2021.11.13 (최종 공개)
  [추가]
- 홍콩 지하철 MTR CNR, CRRC, 현대로템-미쓰비시 차량추가

[변경]
- 홍콩지하철 MTR -> MTR 메트로카멜 직류형 전동차로 이름 변경
- 기존 홍콩지하철 MTR에 포함되어있는 CNR, CRRC, 현대로템 차량 제거
- MTR 메트로카멜 직류형 전동자 디즈니 팬터그래프 차량 추가
- MTR는 최소 3량부터 편성가능으로 변경.
- 승객이 없는 운전차량 유로스타E300, Gloroy600, Talgo, TGV 도색미적용 수정.

홍콩지하철 기존 도색이 제거됨으로 추가하셨던 차량은 기본도색으로 변경되어 있을겁니다. 열차 ID가 변경은 안되오니 참고하기 바랍니다.

2021.11.12
[추가]
- 평판 컨테이너 화차 20ft & 40ft 또는 트레일러형(#13), (#14), (#20)
- 평판 컨테이너 탱크 화차 (액체운반용) (#15)
- 미국 2층형 컨테이너 화차 (#16), (#17)
- MTR 홍콩지하철 추가 (#21)

[수정]
- YTRO200 빨강도색 운전차량 스프라이트 오류 수정 (#19)
- YTRO100, 200 속도 150->120 하향 조정
- YN01, YN01-Yellow 150->181 상향 조정

YST의 열차속도는 지하철 (120, 일반열차 181, 준고속 251, 고속열차 331, Cool도색&일부 고속열차 430, 초고속열차 & 시운전차량 600)

2021.11.8
추가열차
- EMD GT26CW (#9 ), NJ2 (#10 ), BB15048(#11 ) 추가
- 유조차 (#12 ) 추가

수정사항
- 열차별 전기, 디젤, 지하철 아이콘 추가
- 열차 무게 증가(#7 )
- NKX 열차속도 150->181증속
- 화물테이블 코드 4자리로 새로 코딩함.
- 승객이 없는 운전차량 승객없음으로 수정

2021.10.28
변경사항
- 깃허브 코드 소스 공개후 테스트 확인차 신규 GRF 적용

수정사항
- HMX 후미 운전차량 도색 오류 (#4 )
- TGV-Duplex & TGV Ouigo 수송량 수정 (#5 )
- 스프라이트 오류 수정 (#6 )
  - E300 3, 7번 연결부분스프라이트 오류
  - 타이완 고속열차 운전차량 3,7번 스프라이트 오류
  - Talgo250 Aprosiyob 객차 마지막 스프라이트 미적용
  - TGV Old Duplex & TGV Duplex 특실 객차 7번 스프라이트 연결부 미적용

2021.10.26
  Cool 도색 열차 : 최고속도 430km/h, Black 도색 열차 : 최고속도 600km/h 세팅으로 설정
추가열차
  - 대만고속철도, 닥터엘로우 추가
 
변경사항
  - N700 열차 스프라이트 디테일화
  - AGV 속도변수 삭제
  - 500-Cool 도색 변경시 430km/h로 변경됨. 도색메뉴에 속도안내추가
  - AGV-Cool 도색 변경시 430km/h로 변경됨. 도색메뉴에 속도안내추가
  - CRH380A-Cool 도색 변경시 430km/h 변경. 도색메뉴에 속도안내추가
  - CRH380A-Test 600km/h까지 증속
  - EMU 도색메뉴에서 EMU-300 차량 속도안내추가
  - 해무 600->430km/h 하향설정
  - YN02 도색변경시 메뉴에서 속도안내추가
  - ZEFIRO380-Cool 도색변경시 430km/h로 변경됨. 도색메뉴에 속도안내추가
  - ZEFIRO380-Black 도색변경시 600km/h로 변경됨. 도색메뉴에 속도안내추가

  2021.10.25
  - AGV-Cool (AGV 도색에서 변경가능) / 매겨변수로 600km/h까지 변경가능
  - YN (2020년등장/YN01, YN01-Yellow, YN02 3도색가능/ YN01(150km/h), YN02(251km/h) / YN01+YN02 중련구성시 150km/h고정적용
  - Metro ->YTRO 100 이름변경
  - YTRO 2F 그래픽 변경
  - YTRO 200 (10종 도색변경가능) / 스팩 YTRO 100과 동일하게 적용함.
 
주의사항
  - Metro 열차의 이름변경으로 기존에 추가한 열차의 편성이 꼬일 수도 있습니다.

자료제공 Det Tree님 감사합니다.
