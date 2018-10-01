<img width="150" height="150" style="float:left" alt="MS-DOS logo" src="https://github.com/Microsoft/MS-DOS/blob/master/msdos-logo.png">   
> 출처 : 나무위키

# 개요
마이크로소프트에서 사서 개발한 OS이자 마이크로소프트의 운영체제 업계 데뷔작. 일반적으로 '엠에스 도스'라고 읽는다. 'DOS'란 원래 System/360이나 PDP-11 같은 메인프레임 시절부터 사용되던 일반명사였고 애플 II의 운영체제도 DOS라는 이름을 사용하나[2] 이 MS-DOS가 워낙 대박을 쳐서 DOS라고만 하면 문맥상 이 MS-DOS를 가리키는 경우가 대부분이다. 처음에는 IBM에 납품하기 위해 개발했으나 이후 IBM이 PC 관련 기술을 공개하면서 우후죽순처럼 생겨난 PC 제조사들이 전부 MS-DOS를 사용하게 되면서 마이크로소프트를 지금의 공룡기업으로 성장시켜준 1등 공신. 윈도우에게 자리를 물려주기 전까지 IBM PC와 그 호환 기종의 OS 시장을 가히 점령하고 있었다. 초기에는 CP/M 86, 나중에는 DR-DOS 같은 경쟁자가 있기는 했지만 큰 의미는 없었다.

# 역사

* 1980년, IBM이 최초의 IBM PC Model 5150을 개발하면서 IBM은 이 새로운 16비트 시스템의 운영체제를 자체개발하는 것이 아닌 외주를 통해 개발하는 것으로 결정했다.[3]

* 이미 이전에 IBM 방식(관료제)로 개인 목적 컴퓨터를 내놓았다가 시원하게 말아먹은 IBM은 이번엔 독립된 그룹을 조직해서 아웃소싱과 개방형 구조를 채택하기로 결정했다. IBM 대표단은 마이크로소프트와 처음 접촉했으나[4][5] 당시의 마이크로소프트는 베이직 인터프리터 및 소프트웨어를 주력으로 하는 회사였고[6], (자사 베이직을 얹어 돌리기 위한) CP/M 운영체제 개발사인 디지털 리서치를 IBM 담당자들과 연결시켜 줬다.

* 그러나 전형적인 실리콘 밸리 개척자였던 킬달에게 IBM의 제안과 협상에 임하는 딱딱한 태도는 별 흥미를 끌지 못했고, 첫 대응을 부사장인 아내에게 맡겼다가 (대기업이 으레 첫 단계로 진행하는) NDA(비밀보호계약)에 먼저 사인할 것인지 여부를 두고 시작부터 충돌을 일으켰다. 보통 NDA에는 정보 함구에 대한 의무를 어겼을 때 몇배까지 탈탈 털어먹을 것인지에 대한 대기업측의 무시무시한 계약사항들이 가득하다. 그 이후에도 IBM과 디지털 리서치는 마이크로소프트를 중재자로 해서 수차례 접촉을 가지긴 했지만 이미 디지털 리서치는 이미 큰 성공을 거두어서 성장세가 무시무시했기 때문에 IBM측의 무시무시한 요구에 마냥 고개를 조아릴 필요가 없었다.

* 이때, 8086 기반으로 '시애틀 컴퓨터' 社의 프로그래머였던 팀 패터슨(Tim Paterson)이 제작한 CP/M의 클론 OS인 '86-DOS', 통칭 'Q-DOS'(Quick and Dirty Operating System)라는 운영체제가 시장에 나와있었다. IBM-PC용으로 나왔던 것은 아니고 8086 기반의 DIY 컴퓨터 키트[7]용으로 나왔던 운영체제였는데 디지털 리서치와 IBM의 계약이 결렬된 것을 알아챈 빌 게이츠는 잽싸게 팀 패터슨으로부터 Q-DOS 1.10을 75,000달러에 구입하여 이름을 MS-DOS로 바꿔달고[8] IBM과 계약을 체결했다고. 이 때문에 MS-DOS도 초기 릴리즈 버전이 1.0이 아니라 1.10이다. 최근 세 OS의 소스코드를 분석하여 연구한 결과, Q-DOS는 CP/M을 베낀 것이 아니며, MS-DOS도 Q-DOS와는 다른 것이었다는 주장이 나오기도 했으나 이는 저자의 사업을 홍보하기 위한 수단이라고 비난받고 있으며 편집자 역시 저자가 마이크로소프트사의 지원을 받고 있음을 명시하고 있다. 링크된 글의 댓글을 참고. MS-DOS를 만든 빌 게이츠가 자신의 저서인 '미래로 가는 길'에 MS-DOS를 사서 개발했다고 써놨다. 사실 당시 빌게이츠는 IBM에게 OS파는것은 별로 중요하게 생각하지 않았다. 하지만 IBM에게 베이직을 팔아야만 했으며, 그 베이직을 구동하기위해서는 CP/M이건 Q-DOS건 해당 OS를 어떻게든 IBM이 쓰게 만들어야 했고, 이에 CP/M이 협상결렬로 판매되지 않은이상 Q-DOS를 자신이 사서라도 IBM에 납품해야 했던것.... 결국 처음 계약시에는 MS-DOS가 별로 중요한것도 아니었고, MS-DOS는 어디까지나 베이직을 팔기위한 도구에 불과했던것.

* 그러나 이 Q-DOS의 일부에 CP/M의 지적 재산권을 침해하는 부분이 있음을 파악한 IBM에서는 디지털 리서치와 재접촉, 결국 IBM-PC의 공식 운영체제는 마이크로소프트의 MS-DOS와 디지털 리서치의 CP/M 86을 둘 다 사용하는 것으로 결정되었다. 실제로 PC와 도스는 세트가 아니었으며 구매자가 둘 중 하나를 선택하는 방식이었고, IBM에서도"PC에는 운영체제가 세가지나 된다" 는 점을 세일즈 포인트로 삼았다.[9] 당연히 언론과 기술업계 측에서도 완성도 높고 고오급인 CP/M을 높게 쳤으며, 기존 킬러앱을 개발하던 업체들도 CP/M-86용 버전을 앞다퉈서 출시했기에 초반엔 CP/M이 잘 나갔다. 문제는 가격이었는데 CP/M 86의 가격은 250달러, MS-DOS는 40달러로 책정되었고 결국 CP/M 86은 8비트 시장에서의 대성공과 달리 IBM PC에서는 그다지 팔리지 않았다. 원체 잘나갔던 CP/M이었던지라 콧대를 좀 세웠던 모양이다. 이후 킬달은 가격차이를 IBM의 정책 탓으로 돌렸으나 실제로는 자신들의 제품을 '엔터프라이즈' 용으로 여겼으며, 1983년 CP/M 이스트 컨퍼런스에서도 가격 정책에 의문을 제기하는 참석자들에게 킬달이 직접 '제 값이다' 라고 주장한 것으로 볼 때 디지털 리서치는 프리미엄을 놓칠 생각이 없었던 것으로 보인다. 심지어는 킬달이 개인용 경비행기 타고 놀러가느라(!) IBM과의 계약현장에 안나타났다는 루머까지 있었는데 이건 사실이 아니라고 한다.

* 어쨌거나 시애틀 컴퓨터의 Q-DOS 1.10은 MS-DOS 1.10 이라는 이름으로 리테일 시장에 공급되었고 이는 다시 IBM에 OEM으로 공급되면서 PC-DOS라는 이름으로 들어가게 되었다. 그런데 IBM과의 계약에서 마이크로소프트가 'OS에 관한 모든 권리는 마이크로소프트가 가짐'이라는 조항을 계약서에 집어넣었고, 이 덕분에 IBM의 PC 기술 공개가 PC 산업은 크게 흥하게 했지만 정작 IBM의 하드웨어 매출은 급감시킨 반면 마이크로소프트는 크게 성장시켰고 이로 인한 이익은 IBM에겐 단 한 푼도 돌아가지 않았다. 그때서야 후회한 IBM이었지만 이미 OS 시장은 마이크로소프트에게 점령당한 상태였고, OS/2로 운영체제 시장을 되찾기 위해 노력하였지만 결국 완전히 윈도우에게 밀려 OS/2는 사라지고 말았다. 현재 IBM은 PC 부문을 정리하고 서버 시장 및 기업 컨설팅, 통합 솔루션으로 먹고 살고 있다. 이 아픈 과거 때문에 IBM의 노트북 ThinkPad에는 윈도우 키가 없었다. 일종의 자존심이랄까. 그러나 중국의 레노버에 IBM의 노트북 사업이 팔린 후에는 윈도우 키가 달려 나온다. 두 번 가슴 아픈 일이다.

* 이후 MS-DOS는 확대되는 IBM PC 시장의 주력 OS로서 계속해서 버전업을 해 나갔고 1994년 버전 6.22를 끝으로 주력 운영체제의 자리를 이듬해에 나온 Windows 95에 넘겨주었다.

# MSDOS의 종류
1. 1.0 1981년 - 최초의 IBM PC에 탑재된 첫 버전(PC-DOS).
2. 1.25 1982년 - MS-DOS라는 이름으로 출시된 IBM PC 호환기종용 첫 버전.
3. 2.0 1983년 - 하위 디렉토리, 핸들 기반 파일 운용, 명령어 입출력 리다이렉션, 파이프 등을 지원. 마이크로소프트는 경로명 구분 문자를 대부분의 도스나 CP/M 프로그램에서 명령 스위치로 사용하고 있는 슬래시(/) 대신 역슬래시(\)로 사용하기로 함. 하드 디스크와 360KB 플로피 디스크 드라이브 지원.
4. 2.01 1983년
5. 2.11 1983년 - 영어 이외의 언어와 날짜 형식 지원.
6. 2.25 1985년 - 한글과 일본어 한자 지원 확대. 동아시아 나라에만 출시됨.
7. 3.0 1984년 - PC AT를 지원함. 1.2MB 플로피 디스크 및 최대 32 메가바이트의 하드 디스크 파티션 지원(한 개의 기본 파티션과 한 개의 논리 드라이브 지원).
8. 3.1 1984년 - 마이크로소프트 네트워킹 지원.
9. 3.2 1986년 - 3.5 인치 720KB 플로피 디스크 드라이브 지원.
10. 3.3 1987년 - 여러 개의 논리 드라이브 지원.
11. 3.31 1987년 -
12. 4.0 1988년 - 도스 셸 제공.
13. 5.0 1991년 - 메모리 관리, 전체 화면 편집기, QBasic 프로그래밍 언어, 온라인 도움말, 작업 전환 기능이 추가된 도스 셸 등 제공.
14. 6.00 1993년 - 더블스페이스, 영문 사용자 메시지 지원(한글판), 조합형 한글 코드 페이지(1361) 지원(한글판).
15. 6.20 1993년 -
16. 6.21 1994년 - 스택 일렉트로닉스와의 소송으로 인해 더블스페이스 기능이 제외됨.
17. 6.22 1994년 - 단일 제품으로는 마지막 버전. 더블스페이스 대신 동일한 기능의 드라이브스페이스 제공.
18. (7.0) 1995년 - 윈도 95에 내장됨. MSDOS.SYS의 기능이 IO.SYS에 통합되어, MSDOS.SYS에는 참고용 텍스트만이 들어있다. LBA(논리 블록 어드레싱) 지원. DOSLFN 등의 별도 드라이버를 이용하면 긴 파일 이름을 사용할 수 있다.
19. (7.1) 1998년 - 윈도 95 OSR2와 그 이후 버전 및 윈도 98, 윈도 98 SE에 내장됨. FAT32 파일 시스템 지원.
20. (8.0) 2000년 - 윈도 Me에 내장됨. 또한 윈도 XP, 윈도 비스타, 윈도 7에서 플로피 디스크를 포맷할 때 'MS-DOS 시동 디스크 만들기'를 선택하면 이 버전의 최소한의 파일을 포함한 MS-DOS가 디스크에 설치된다. 

## 마지막
* 윈도우 95의 출시와 함께, MS-DOS의 통합 버전은 부트스트래핑, 문제 해결, 특히 게임 및 더 이상 출시되지 않는 독립 제품과 같은 오래된 도스 소프트웨어와의 하위 호환성을 위해 사용되었다. 윈도우 95에서 MS-DOS 7이라는 이름의 도스는 윈도우 GUI 없이 별도로 부팅이 가능하다. 이 기능은 윈도우 98 SE에도 포함되었다. 윈도우 ME에서는 이 기능을 제거하였으나, 기반이 되는 도스 MS-DOS 8.0으로 직접 접근할 수 있도록 해킹이 가능하다.

# 번외

## Mdir

* 한국에서 개발된 MS-DOS용 파일관리 셸 프로그램. 아래아 한글, 이야기와 더불어 국산 소프트 3대 천왕이라고 할 만한 존재. V3까지 합쳐서 4대 천왕이라는 말도 있다. 보통 실행파일 이름을 따서 간단히 M, 혹은 M방이라고 불렸다.

* 도스셸에 속한다. 원류인 노턴 유틸리티와 PC Tools 같은 프로그램과 비슷한 기능을 가지고 있다. 한국에서는 한글이라는 장점과 강력한 사용자 커스텀 기능 때문에 가장 널리 쓰이는 도스셸이 되었다. 비슷하기로 따지면 ls++와 가장 유사하다. 당시 PC 통신에는 노턴 커맨더 이후 도스셸 프로그램들이 여럿 제작되어 올라왔는데, 그 중에 가장 인터페이스가 직관적이고 기능도 충실했기에 인기를 끌게 된 것. 초기의 윈도우즈보다 편리하다(…)는 평도 있다.

* 개발자는 최정한씨로, 컴퓨터를 다루기 어려워하는 여친을 위해서 개발했다고 한다. Mdir 개발 이후 여친과 헤어졌다는 후문이 돌았지만 사실 그 여친과 현재 결혼까지 해서 살고 있다고 하며 현재는 컴퓨터 관련 일에서 손을 떼었다고 전해진다. 당시에 통신망이나 카피를 통해 널리 퍼져서 곧 국내의 거의 모든 컴퓨터에 퍼지게 되었다. 일부에서는 DOS 기본 명령어인 줄 알고 있었다는 이야기도 있을 정도. 심지어 운영체제로 알고 있는 사람들도 있다. 그래서 프로그램의 유명세로 인해 세무서에서 세금 6억을 고지받기도 하였다;;전국민이 쓰는 프로그램인데 많은 돈을 벌지 않았겠냐고 어림짐작으로 과세한 것. 하지만 확인해 보니 막상 매출은 크지 않아서 국세청이 머쓱해진 해프닝으로 끝났다. 

* 개발자 최정한 씨가 한빛인포텍에 입사한 후 코드의 저작권이 어떤 경위에서인지 회사로 넘어갔고, 퇴사에 따라 저작권 문제로 업데이트가 어렵게 되었다는 이야기가 전해진다. 이후 한빛인포텍은 폐업폐업과 동시에 2002년 퇴사, 이후 곧바로 프로그래머 최종테크 - 치킨집을 개업하시고 얼마 전에는 포항에서 돼지갈비집을 오픈하신다는 이야기가 있는 듯. 마소 최근호에 소개된 폐절제 후 수당 미지급 문제로 소송중인 개발자란 이야기가 있으나 그 분은 양모 씨다. 그러나 2003년에 만났다는 사람이 단 댓글을 보면 그마저도 사장이 아닌 지배인이라고 했다. 그래도 긍정적인 영향이 된 것인지 2013년에 달린 댓글에 따르면 조카분 역시 개발자의 길로 들어섰다고 한다. 2016년 현재는 갈비집을 그만두시고 다른 일을 한다고 한다.

* 그리고 트위터에서 개발자의 따님 분이 "기억해주셔서 정말 감사합니다"며 인증하셨다. 따님에게 간 트윗 중에 꽤나 인상깊었던 것 중 하나는 "그러니까 춘부장께서는 대략 산신령이라든가 잊혀진 옛 기억의 대마법사라든가 멋 옛날 홀연히 자취를 감춘 드래곤 슬레이어쯤 되는 분이십니다."

# MS-DOS v1.25 and v2.0 Source Code
This repo contains the original source-code and compiled binaries for MS-DOS 1.25 and MS-DOS 2.0.

These are the same files [originally shared at the Computer History Museum on March 25th 2014]( http://www.computerhistory.org/atchm/microsoft-ms-dos-early-source-code/) and are being (re)published in this repo to make them easier to find, reference-to in external writing and works, and to allow exploration and experimentation for those interested in early PC Operating Systems.  

# License
All files within this repo are released under the [MIT (OSI) License]( https://en.wikipedia.org/wiki/MIT_License) as per the [LICENSE file](https://githib.com/microsoft/msdos/license.txt) stored in the root of this repo.

# Contribute!
The source files in this repo are for historical reference and will be kept static, so please don’t send Pull Requests suggesting any modifications to the source files, but feel free to fork this repo and experiment 😊.  

If, however, you’d like to submit additional non-source content or modifications to non-source files (e.g. this README), please submit via PR and we’ll review and consider.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).  For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
