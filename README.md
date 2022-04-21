# SCV Team
![Untitled](https://user-images.githubusercontent.com/82289435/155078196-a7fc6036-283a-4319-a404-c7e16906c4d8.png)

- 2022.02.23 ~ 2022.04.07
- 네이버 커넥트 재단 및 Upstage에서 주관하는 비공개 대회
- 마스크 착용 상태 Image Classification
- Public 12위, Private 14위

## MEMBERS
- 김찬혁
- 문태진
- 박정재
- 임종현
- 정다운

## 문제 정의(대회 소개) & Project Overview
COVID-19의 확산으로 우리나라는 물론 전 세계 사람들은 경제적, 생산적인 활동에 많은 제약을 가지게 되었습니다. 우리나라는 COVID-19 확산 방지를 위해 사회적 거리 두기를 단계적으로 시행하는 등의 많은 노력을 하고 있습니다. 과거 높은 사망률을 가진 사스(SARS)나 에볼라(Ebola)와는 달리 COVID-19의 치사율은 오히려 비교적 낮은 편에 속합니다. 그럼에도 불구하고, 이렇게 오랜 기간 동안 우리를 괴롭히고 있는 근본적인 이유는 바로 COVID-19의 강력한 전염력 때문입니다.

감염자의 입, 호흡기로부터 나오는 비말, 침 등으로 인해 다른 사람에게 쉽게 전파가 될 수 있기 때문에 감염 확산 방지를 위해 무엇보다 중요한 것은 모든 사람이 마스크로 코와 입을 가려서 혹시 모를 감염자로부터의 전파 경로를 원천 차단하는 것입니다. 이를 위해 공공 장소에 있는 사람들은 반드시 마스크를 착용해야 할 필요가 있으며, 무엇 보다도 코와 입을 완전히 가릴 수 있도록 올바르게 착용하는 것이 중요합니다. 하지만 넓은 공공장소에서 모든 사람들의 올바른 마스크 착용 상태를 검사하기 위해서는 추가적인 인적자원이 필요할 것입니다.

따라서, 우리는 카메라로 비춰진 사람 얼굴 이미지 만으로 이 사람이 마스크를 쓰고 있는지, 쓰지 않았는지, 정확히 쓴 것이 맞는지 자동으로 가려낼 수 있는 시스템이 필요합니다. 이 시스템이 공공장소 입구에 갖춰져 있다면 적은 인적자원으로도 충분히 검사가 가능할 것입니다.

## Dataset
- 데이터
    - 데이터 특징
    - 아시아인 남녀
    - 나이 20대 ~ 70대
    - 사람 명 수 : 4,500
    - 이미지 크기 : (384, 512)
    - 색이 다른 마스크 착용 사진
    - 마스크를 정확하게 착용하지 않는 사진 포함
    - 마스크 미착용 사진

- 데이터 분류(18개 클래스)

![Untitled (1)](https://user-images.githubusercontent.com/82289435/155078245-c7cc8e8f-a835-4d35-adfb-e2233fa03d86.png)

## Metrics
- F1 Score
![Untitled (1)](https://user-images.githubusercontent.com/76461625/164366119-47403e07-c246-43cf-b848-8bf7246e453f.png)
In "macro" F1, a separate F1 score is calculated for each classes value and then averaged.

### LB Score
![Untitled](https://user-images.githubusercontent.com/76461625/164366510-454a6139-81cd-4a3a-ae5f-f6f366acf7d6.png)
![Untitled1](https://user-images.githubusercontent.com/76461625/164366508-c27d243a-0fc6-4f20-a030-86d34626dfbb.png)

### Tools
- Github (Custom Git-flow Branching, Issue, PR)
- Notion
- Slack
