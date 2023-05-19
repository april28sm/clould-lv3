![image](https://user-images.githubusercontent.com/487999/79708354-29074a80-82fa-11ea-80df-0db3962fb453.png)

# 예제 - 음식배달

배달의 민족 마이크로서비스 분석/설계, 구현, 배포/운영

# 서비스 시나리오

기능적 요구사항
• 고객이 메뉴를 선택하여 주문한다.
• 고객이 선택한 메뉴에 대해 결제한다.
• 주문이 되면 주문 내역이 입점상점주인에게 주문정보가 전달된다.
• 상점주는 주문을 수락하거나 거절할 수 있다.
• 상점주는 요리시작때와 완료 시점에 시스템에 상태를 입력한다.
• 고객은 아직 요리가 시작되지 않은 주문은 취소할 수 있다.
• 요리가 완료되면 고객의 지역 인근의 라이더들에 의해 배송건 조회가 가능하다.
• 라이더가 해당 요리를 Pick한 후, 앱을 통해 통보한다.
• 고객이 주문상태를 중간중간 조회한다.
• 라이더의 배달이 끝나면 배송확인 버튼으로 모든 거래가 완료된다.

# 체크포인트
1. Eventstorming Model

![이벤트스토밍](https://github.com/april28sm/clould-lv3/assets/94352502/c3dae2f8-c1c7-41ca-a3b9-aa7b1f95b5c4)

2. Saga (Pub / Sub) 확인 (클러스터에 Kafka 설치 후)

![subpub](https://github.com/april28sm/clould-lv3/assets/94352502/664d5cd2-0e7c-46ad-a589-9643cfa81031)

3. Service Router 설치

![serviceRouter](https://github.com/april28sm/clould-lv3/assets/94352502/83b94b59-e5dc-4718-aa8d-d944c396baff)

4. Zero downtime Deployment 

![zerodowntime](https://github.com/april28sm/clould-lv3/assets/94352502/b6d29fa2-9c23-4cd7-829f-89249adb040d)

