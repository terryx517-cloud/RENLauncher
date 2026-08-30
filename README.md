# REN Launcher

REN은 ELDEN RING의 지정 모드를 한 화면에서 설치·감지하고 켜고 끄고 실행하는 Windows 런처입니다.

- 런처 다운로드: [Releases](https://github.com/terryx517-cloud/RENLauncher/releases/latest)
- 모드 파일은 각 제작자의 공식 Nexus Mods 페이지에서 직접 다운로드합니다.
- 런처는 시작할 때 이 저장소의 `update.json`을 확인하고 새 버전이 있으면 자동 업데이트를 제안합니다.

현재 고정 구성은 Seamless Co-op, The Convergence, Convergence 한글패치, Better Camera입니다. 각 카드의 공식 Nexus Mods 설치 페이지에서 최신 ZIP을 받은 뒤 압축을 풀지 않고 런처의 `모드 적용`을 누르세요. 한글패치는 공식 `ConvergenceER KR v5.0` ZIP을 자동 식별해 별도 패키지로 설치하며, Convergence 뒤에서 로드되어 기존 모드 파일을 덮어쓰지 않습니다. ON 모드는 REN 런처의 `게임 실행`으로 로드되며, 모두 OFF면 Steam 순정 실행으로 전환됩니다.

RENLauncher.exe를 처음 실행하면 `%LOCALAPPDATA%\Programs\REN Launcher`에 자동 설치되고 바탕화면 바로가기가 생성됩니다. 이후 런처 자동 업데이트도 이 안정된 설치 경로의 EXE를 교체합니다.

새로 적용한 Seamless Co-op의 기본 세션 비밀번호는 `10301030`으로 자동 설정됩니다. 다만 2026년 8월 27일 배포된 ELDEN RING 1.17(실행 파일 2.7.0.0)과 공식 Seamless Co-op 1.9.9 조합에서는 월드 진입 크래시가 확인되었습니다. 런처 1.3.4는 해당 조합에서 `ersc.dll`을 안전하게 실행 대상에서 제외하고 정확한 상태를 표시합니다. 기존 Seamless-Convergence 세이브(`.cnv.co2`)는 원본을 보존한 채 Convergence 세이브(`.cnv`)로 한 번만 복사합니다. 공식 호환 버전이 설치되면 별도 REN 우회 DLL 없이 공식 `ersc.dll`을 다시 로드합니다.

1.3.3에 포함됐던 실험적 ELDEN RING 1.17 우회 DLL은 초기 검사만 통과시키고 월드 진입 접근 위반을 일으킬 수 있어 1.3.4에서 완전히 폐기했습니다. Seamless 기능이 반드시 필요한 경우에는 제작자의 ELDEN RING 1.17 호환 업데이트가 나올 때까지 기다려야 합니다.

모드 제작자와 각 모드의 배포 권한을 존중합니다. 이 저장소는 타인의 모드 파일을 재배포하지 않습니다. 실제 2인 접속은 각 사용자가 동일한 모드 버전과 비밀번호를 사용해 별도로 확인해야 합니다.
