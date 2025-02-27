---
title: WiiLink 음식 배달 채널 (도미노) 가이드
---

{% include toc title="Table of Contents" %}

이 자습서와 관련하여 도움이 필요하면 [WiiLink 디스코드 서버](https://discord.gg/wiilink-750581992223146074)에 가입하세요.
{: .notice--info}

더 이상 1달러를 지불하고 푸드 배달 채널 (도미노) 을 이용하지 않아도 됩니다. 이제 완전히 _무료_입니다!
{: .notice--info}

이 서비스는 도미노피자에 주문하는 것이므로 매장에서 결제해야 합니다. 배송 담당자가 신용/직불 카드기를 가지고 있는 경우 현금으로 결제할 수 있지만, 보통 현금으로 결제합니다.
{: .notice--info}

현재 미국과 캐나다만 지원됩니다.
{: .notice--warning}

이 서비스에서는 기본 Dolphin NAND는 사용할 수 없습니다. 본인의 NAND 덤프를 사용해야 합니다. 이 작업은 도구 모음에서 `도구 -> NAND 관리 -> BootMii NAND 백업 가져오기`를 클릭하여 Dolphin에서 수행할 수 있습니다.
{: .notice--warning}

#### 필요한 것

- SD 카드 및 USB 드라이브
- 인터넷에 연결되어 있는 Wii 콘솔
- 인터넷 연결이 활성화된 컴퓨터
- 디스코드 계정

#### 사용 방법

##### 섹션 I - 시작하기

1. 최신 버전의 WiiLink 패치 관리자를 [여기에서](https://github.com/WiiLink24/WiiLink24-Patcher/tree/csharp-ver) 다운로드할 수 있습니다.
2. 사용 중인 운영 체제에 맞는 버전을 사용 설명서에서 다운로드하세요.
3. 패치 관리자를 실행하고 설정 프로세스를 시작합니다.
4. 설정 화면이 표시되면 `1을 선택합니다. 영어 번역`를 입력하면 음식 배달 채널 (도미노) 채널에 접속할 수 있습니다.<br><br> ![빠른 설치](/images/Demae-Dominos/choose-core-channel.png)
5. 다음으로, 어떤 버전의 음식 배달 채널을 원하는지 묻는 이 화면이 표시되므로 `2를 선택해야 합니다. 도미노피자 (미국 및 캐나다만 해당)`<br><br> ![푸드 배달 채널 설정](/images/Demae-Dominos/choose-food-channel-ver.png)
6. 그 후 나머지 프로세스를 진행할 수 있지만, 이 단계에 도달하면 앱을 사용할 때 중요하므로 설치할 콘솔 플랫폼을 올바르게 선택해야 합니다.<br><br> ![콘솔 플랫폼](/images/Demae-Dominos/choose-console-platform.png)

##### 섹션 II - 콘솔 ID 등록하기

1. 설정 과정을 완료한 후 [**WiiLink 디스코드 서버**](https://discord.gg/wiilink-750581992223146074)로 이동하여 Wii의 콘솔 ID를 등록합니다.
2. 패처에서 제공한 `콘솔 ID 얻기` 홈브류 앱을 사용하여 시스템의 콘솔 ID를 검색합니다.
3. 디스코드 서버의 `#dominos-chat` 채널을 방문합니다.
4. 채팅에 `/dominos <your console ID>` 명령을 입력하고, `<your console ID>`을 실제 콘솔 ID로 바꿉니다. ID가 매개변수 상자에 있는지 확인하지 않으면 명령이 작동하지 않고 채널에 공개적으로 게시됩니다.
5. 콘솔 ID는 다시 등록할 수 없으므로 올바른 콘솔 ID를 입력했는지 다시 확인하세요. 재등록이 필요한 경우 서버 담당 직원에게 도움을 요청하세요.

##### 섹션 III - WAD 설치

이제 푸드 배달 채널과 개인 데이터 채널 설정을 설치합니다.

1. Wii에 SD 카드나 USB 드라이브를 연결합니다.
2. 콘솔 ID를 등록한 후 홈브류 채널로 이동하여 **Wii Mod Lite**를 실행합니다.
3. WAD 관리자 메뉴에서 `Food Channel (Domino's) (English).wad`를 찾습니다.
4. 또한 콘솔 플랫폼에 따라 `WiiLink_SPD (Wii).wad` 또는 `WiiLink_SPD (vWii).wad`을 찾습니다.
5. `+` 버튼을를 눌러 두 WAD를 모두 선택합니다.
6. `A` 버튼을 눌러 선택한 WAD를 설치합니다.

`Food Channel (Domino's) (English).wad` 설치 시 `Error -1022`가 발생하면 `-` 버튼으로 WAD를 선택하고 `A` 버튼을 눌러 채널을 제거합니다. 그런 다음 WAD를 다시 설치합니다.
{: .notice--warning}

##### 섹션 IV - 주소 정보 설정

WiiLink는 개인 데이터를 저장하지 않습니다. 사용되는 정보에 대한 자세한 내용은 [개인정보처리방침](https://www.wiilink24.com/privacy-policy)를 참조하세요.
{: .notice--info}

정확한 주소 정보를 입력할 책임은 본인에게 있습니다. 그렇게 하지 않으면 주문이 성공하지 못할 수 있습니다.
{: .notice--warning}

이 섹션에서는 주소 정보를 설정합니다. 이는 데매 도미노의 올바른 사용을 위해 필요합니다.

1. Wii 메뉴에서 푸드 배달 채널을 실행합니다.
2. 이전에 주소 정보를 설정하지 않은 경우 설정하라는 메시지가 표시됩니다. `주소 정보` 버튼을 누릅니다. 그렇지 않으면 메인 메뉴에서 `주소 정보 변경` 버튼을 클릭합니다.
3. 이제 주소 정보 메뉴로 이동했습니다. 화살표를 눌러 화면을 이동합니다. 여기에 데이터를 입력합니다. 완료되면 `완료` 버튼을 클릭한 다음 `데매`를 클릭합니다.<br><br> ![SPD 페이지 1](/images/Demae-Dominos/spd-1.png)<br><br> ![SPD 페이지 2](/images/Demae-Dominos/spd-2.png)

##### 섹션 V - 주문하기

이 섹션에서는 식사 비용을 현금으로 지불해야 합니다.
{: .notice--warning}

이전에 표준 버전의 푸드 배달 채널을 사용한 적이 있다면 <br>`Wii 메뉴 설정` -> `데이터 관리` -> `데이터 저장` -> `Wii`에서 <br>푸드 배달 채널 아이콘을 찾아 "지우기"를 클릭하여 기존 저장 데이터를 삭제합니다.
{: .notice--warning}

이전에 주문한 적이 있는 경우 4단계로 건너뛰세요.
{: .notice--info}

1. Wii 메뉴에서 푸드 배달 채널 (일명: 음식 채널) 실행
2. 화면의 안내에 따라 메인 메뉴에서 `주문`를 클릭합니다.<br><br> ![메인 메뉴](/images/Demae-Dominos/success.png)<br><br>
3. 이제 지역을 선택하라는 메시지가 표시됩니다. 거주 국가를 올바르게 선택해야 합니다. 그렇게 하지 않으면 레스토랑 불러오기에 실패하게 됩니다. 그러면 주/도를 선택한 다음 도시를 선택하라는 메시지가 표시됩니다. 해당 도시가 목록에 없는 경우, 아무 도시나 선택해도 상관없습니다.<br><br> ![메인 메뉴](/images/Demae-Dominos/country-setup.png)<br><br>
4. `피자` 버튼을 클릭합니다. 해당 지역의 모든 레스토랑이 로드됩니다. 목록의 첫 번째 레스토랑은 본인과 가장 가까운 레스토랑입니다.
5. `메뉴 보기`를 클릭하면 다양한 메뉴 카테고리가 나열됩니다. 원하는 카테고리를 클릭한 다음 식품 항목을 선택합니다. 아이템 화면에서 토핑을 추가하고 수량을 조정할 수 있습니다.
6. 식품을 추가하면 장바구니로 이동합니다. 음식 항목을 추가하려면 하단으로 스크롤하여 `주문 추가`를 선택합니다. 결제를 진행하려면 `다음`를 클릭합니다.
7. 주문하기 전에 주문을 꼼꼼히 검토하세요. 준비가 되면 큰 녹색 `주문` 버튼을 클릭합니다.<br><br> ![주문 전](/images/Demae-Dominos/order.png)<br><br>
8. 오류가 나타나지 않으면 주문이 성공적으로 완료된 것입니다! 주문을 추적하려면 해당 지역의 도미노 트래커를 방문하여 주소 정보 메뉴에 입력한 전화번호를 입력하면 됩니다.

**_행복한 주문 되세요!_**

[사이트 탐색 계속하기](site-navigation)<br> 여러분이 좋아할 만한 다른 자습서도 많이 있습니다.
{: .notice--info}
