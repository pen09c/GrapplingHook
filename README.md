# ⛓️ Minecraft Advanced Grappling Hook

하이픽셀(Hypixel) 로비 가젯인 그레플링 훅을 Skript로 구현한 프로젝트입니다.

## ✨ Key Features
- **Instant Retraction Pull**: 낚시찌가 살아있는 동안 다시 우클릭하면 해당 지점으로 즉시 도약합니다.
- **Dynamic Vector Physics**: 거리와 방향을 계산하여 자연스러운 포물선 가속도를 제공합니다.

## 🛠️ Technical Insights
- **Heuristic Entity Capture**: `wait 1 tick`과 `radius loop`를 사용하여 서버 엔진에 구애받지 않고 낚시찌를 정확히 타겟팅합니다.
- **Velocity Control**: 마인크래프트의 기본 물리 엔진을 `vector` 연산으로 재정의하여 공중 기동을 구현했습니다.

## 🚀 How to use
1. 서버에 `Skript` 플러그인을 설치합니다.
2. `plugins/Skript/scripts` 폴더에 이 파일을 넣습니다.
3. `/sk reload PrecisionChainClimber`를 입력합니다.
4. 낚싯대를 던지고, 원하는 타이밍에 한 번 더 우클릭하여 날아가세요!
