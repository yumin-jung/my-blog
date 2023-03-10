## Designing for iOS

**사람들은 어디에서나 연결 상태를 유지하고, 게임을 하고, 미디어를 보고, 작업을 수행하고, 개인 데이터를 추적하는데 iPhone을 사용합니다.**

![ios-design](https://developer.apple.com/design/human-interface-guidelines/images/intro/platforms/platform-iOS-intro-dark_2x.png)

iOS에서 앱 또는 게임 디자인을 시작할 때, iOS 경험을 구별하기 위해 다음과 같은 기본적인 장치의 특성 및 패턴을 이해하는 것부터 시작해야 합니다.
이러한 특성 및 패턴을 사용하여 디자인을 결정하는 것은 iPhone 유저가 좋아하는 앱이나 게임을 제공하는 데 도움이 될 수 있습니다.

**Display.**
iPhone에는 중간 크기의 고해상도 디스플레이가 있습니다.

**Ergonomics.**
사람들은 일반적으로 필요에 따라 가로 방향과 세로 방향 사이를 전환하면서 상호작용할 때 한 손 또는 양손으로 iPhone을 잡습니다.
사람들이 장치와 상호작용하는 동안 시청 거리는 0.3~0.6미터를 넘지 않는 경향이 있습니다.

**Inputs.**
Multi-Touch 제스처, 온스크린 키보드 및 음성 제어를 통해 사람들은 이동 중에 의미 있는 작업을 수행할 수 있습니다.
또한 사람들은 종종 가속도계 및 자이로스코프를 통해 자신의 위치를 사용하기를 원하며 공간적 상호 작용에 참여하기를 원할 수도 있습니다.

**App interactions.**
때때로 사람들은 이벤트 또는 SNS 업데이트를 확인하거나 데이터를 추적하고 메시지를 보내는 데 1~2분 정도를 소비합니다.
다른 시간에는 웹브라우징 혹은 게임을 하거나 미디어를 즐기는 데 한 시간 이상을 보낼 수 있습니다.
사람들은 일반적으로 여러 개의 앱을 동시에 열어두고 자주 전환하며 사용하는 것을 좋아합니다.

**System features.**
iOS는 사용자가 익숙하고 일관된 방식으로 시스템 및 앱과 인터렉션할 수 있도록 몇 가지 기능을 제공합니다.
- Widgets
- Home Screen quick actions
- Spotlight
- Shortcuts
- Activity views

## Best practices
좋은 iPhone 경험은 사람들이 가장 중요하게 여기는 플랫폼과 기기의 기능을 통합합니다.
디자인이 iOS에서 편안하게 느껴지도록 하려면 다음 기능에 우선순위를 두어야 합니다.
- 최소한의 인터렉션으로 세부적인 정보 및 작업을 검색할 수 있도록 하면서 화면 컨트롤의 수를 제한하여
주요 작업 및 컨텐츠에 집중할 수 있도록 해야 합니다.
- 장치 방향, 다크 모드, 동적 유형(Dynamic Type)과 같은 변화에 원활하게 작동할 수 있도록 하여
사용자가 자신에게 가장 적합한 구성을 선택할 수 있도록 해야 합니다.
- 사람들이 일반적으로 장치를 잡는 방식을 지원하는 인터렉션을 활성화합니다.
예를 들어 디스플레이의 중간 또는 하단 영역에 버튼이 있는 경우 사용자가 버튼에 도달하는 것이 더 쉽고 편한 경향이 있으므로
사용자가 스와이프하여 뒤로 탐색하거나 목록 행에서 작업을 시작할 수 있도록 하는 것이 특히 중요합니다.
- 사용자의 허락을 받아 데이터 입력을 요구하지 않고 사용자 경험을 향상시키는 방식으로 플랫폼 기능을 통해 사용 가능한 정보를 통합합니다.
예를 들어 결제를 수락하거나, 생체 인증을 통해 보안을 제공하거나, 기기의 위치를 사용하는 기능을 제공할 수 있습니다.