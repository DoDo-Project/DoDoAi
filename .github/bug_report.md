name: "🐞 Bug Report"
description: "버그 발생 시 보고하는 템플릿"
title: "[Bug] "
labels: ["bug"]
body:
  - type: textarea
    id: description
    attributes:
      label: "📄 버그 설명"
      description: "어떤 버그인지 명확하고 간결하게 설명해주세요."
      placeholder: "예: '로그인 버튼을 클릭해도 반응이 없습니다.'"
    validations:
      required: true

  - type: textarea
    id: reproduction
    attributes:
      label: "🐾 재현 방법"
      description: "다른 사람이 버그를 똑같이 재현할 수 있도록 순서대로 설명해주세요."
      placeholder: |
        1. '...' 페이지로 이동합니다.
        2. '....' 버튼을 클릭합니다.
        3. '....' 까지 스크롤합니다.
        4. 에러가 발생합니다.
    validations:
      required: true

  - type: textarea
    id: expected-behavior
    attributes:
      label: "🤔 예상 결과"
      description: "원래라면 어떻게 동작해야 했는지 설명해주세요."
      placeholder: "예: '로그인 버튼을 클릭하면 메인 페이지로 이동해야 합니다.'"
    validations:
      required: true

  - type: textarea
    id: environment
    attributes:
      label: "🖥️ 환경 정보"
      description: "버그가 발생한 환경을 알려주세요. (OS, 브라우저, 버전 등)"
      placeholder: |
        - OS: 
        - Browser: 
        - Version: 
    validations:
      required: false

  - type: textarea
    id: screenshots
    attributes:
      label: "📸 스크린샷 또는 로그"
      description: "문제 상황을 파악하는 데 도움이 되는 스크린샷, 비디오, 로그 등을 첨부해주세요."
    validations:
      required: false
