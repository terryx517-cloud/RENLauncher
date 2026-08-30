# REN Launcher

REN은 ELDEN RING의 지정 모드를 한 화면에서 설치·감지하고 켜고 끄고 실행하는 Windows 런처입니다.

- 런처 다운로드: [Releases](https://github.com/terryx517-cloud/RENLauncher/releases/latest)
- 모드 파일은 각 제작자의 공식 Nexus Mods 페이지에서 직접 다운로드합니다.
- 런처는 시작할 때 이 저장소의 `update.json`을 확인하고 새 버전이 있으면 자동 업데이트를 제안합니다.

현재 고정 구성은 Seamless Co-op, The Convergence, Better Camera입니다. 각 카드의 공식 Nexus Mods 설치 페이지에서 최신 ZIP을 받은 뒤 압축을 풀지 않고 런처의 `모드 적용`을 누르세요. ON 모드는 REN 런처의 `게임 실행`으로 로드되며, 모두 OFF면 Steam 순정 실행으로 전환됩니다.

RENLauncher.exe를 처음 실행하면 `%LOCALAPPDATA%\Programs\REN Launcher`에 자동 설치되고 바탕화면 바로가기가 생성됩니다. 이후 런처 자동 업데이트도 이 안정된 설치 경로의 EXE를 교체합니다.

새로 적용한 Seamless Co-op의 기본 세션 비밀번호는 `10301030`으로 자동 설정됩니다. 런처 1.3.2에는 ELDEN RING 1.17 + Seamless Co-op 1.9.9 전용 REN 호환 패치가 포함되어 있습니다. 공식 Seamless 설치가 감지된 경우에만 별도 REN DLL을 배치하고 실행 순서에 추가하며, 공식 `ersc.dll` 자체는 변경하거나 재배포하지 않습니다. 공식 Seamless가 더 새 버전으로 바뀌면 이 패치는 자동으로 로드 대상에서 제외됩니다.

모드 제작자와 각 모드의 배포 권한을 존중합니다. 이 저장소는 타인의 모드 파일을 재배포하지 않습니다. 실제 2인 접속은 각 사용자가 동일한 모드 버전과 비밀번호를 사용해 별도로 확인해야 합니다.
