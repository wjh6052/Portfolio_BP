Description

-이동기-

걷기(Ctrl)

조깅(기본)

뛰기(w더블클릭)

구르기 (Shif)

벽타기 (Z)

Z클릭 시 캐릭터 앞으로 Line Trace로 확인 후 Climbing Start(State를 Climbing으로 교체, 중력 제거, Movement Mode Flying교체, 후 Line Trace에서 얻어온 위치로 이동)
이동 중 Capsule Trace로 갈수있는 곳이 없을경우 갈방향의 앞뒤로 확인후 SideTurn 또는 ForwradTurn가 나오도록함
위로 갈수없을경우 위와같은 방법으로 올라간 후 Climbing End(Start에서 교체한 값을 원래값대로 수정)


https://github.com/wjh6052/Portfolio_BP/assets/131844165/a2c48446-451e-4df7-9e10-a5b5a0bccf9f

점프(Space bar)

날기 (점프 중 Space bar)
![ScreenShot00008](https://github.com/wjh6052/Portfolio_BP/assets/131844165/cf4b9fb7-42a7-4c74-bd07-3e09b8c97b75)

대쉬중 바닥에 닿이면 착지하며 Flight를 끝냄
착지 애니메이션 중 바닥에 타입을 확인하여 타입에 맞는 나이아가라 효과가 나옴
![landing](https://github.com/wjh6052/Portfolio_BP/assets/131844165/2edbdc38-b5ac-44af-8a0a-4c3e0a440b2d)

대쉬중 바닥에 Line Trace로 바닥 타입을 확인하여 타입에 맞는 나이아가라 효과가 나옴
![ScreenShot00012](https://github.com/wjh6052/Portfolio_BP/assets/131844165/67cf6b06-ce89-4948-ad75-b0f6f7657e0c)



-Status 상태 관리-

Idling

Rolling

Battle

Attacking

Hitted

Dash

Groggy(제압됬을때)

Patrol (Enemy에만 사용할 용도 순찰, 대기)

Zom


-State 전투 관리-

Unarmed

Climbing

Swimming (추가예정)

Flight

Assassin

Bow (추가예정)

katana (추가예정)

window (추가예정)

Paladine (추가예정)

Magic (추가예정)



-공격-
일반 좌클릭 공격, 계속 좌클릭 콤보공격


https://github.com/wjh6052/Portfolio_BP/assets/131844165/494480f6-e381-4173-926a-5f46643c2965


우클릭 가드 또는 줌

Assassin

마우스 휠클릭 락온
![ScreenShot00002](https://github.com/wjh6052/Portfolio_BP/assets/131844165/89be1de2-6f90-4599-beab-6db7dfc9e10a)

쉬프트 이동중 좌클릭 대쉬공격

스킬1 1번


https://github.com/wjh6052/Portfolio_BP/assets/131844165/3a860aa3-6b42-4ebf-a88f-7235939fee12


스킬2 2번


https://github.com/wjh6052/Portfolio_BP/assets/131844165/a660374c-2264-41df-a6b4-443af9557a3f


스킬3 3번


https://github.com/wjh6052/Portfolio_BP/assets/131844165/bda054f4-7a9b-4af6-90d7-a4f945265724







-위젯-


디버그, HP창, 상호작용

![ScreenShot00000](https://github.com/wjh6052/Portfolio_BP/assets/131844165/e94b080b-c288-4e80-86d4-d656b6cfa80a)

무기 교체

![ScreenShot00001](https://github.com/wjh6052/Portfolio_BP/assets/131844165/6ad0a6bb-e15a-4ae2-bd03-207177538cd7)

스킬 아이콘 및 쿨타임

![ScreenShot00007](https://github.com/wjh6052/Portfolio_BP/assets/131844165/19b8f1e9-a3e0-4ac4-ae4c-2b403dbf1954)
