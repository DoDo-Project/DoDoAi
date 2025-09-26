name: "✨ Feature"
description: "새로운 기능 추가"
title: "[Feature] "
labels: ["feature"]
body:
  - type: textarea
    id: description
    attributes:
      label: "📄 설명"
      description: "새로운 기능에 대한 설명을 작성해 주세요."
      placeholder: "자세히 적을수록 좋습니다!"
    validations:
      required: true

  - type: textarea
    id: tasks
    attributes:
      label: "✅ 작업할 내용"
      description: "이 기능을 구현하기 위해 할 일을 체크박스 형태로 작성해주세요."
      placeholder: |
        - [ ] 기능 A 개발
        - [ ] 기능 B UI 디자인
        - [ ] 기능 C 테스트 코드 작성
      render: markdown
    validations:
      required: true

  - type: textarea
    id: references
    attributes:
      label: "🙋🏻 참고 자료"
      description: "참고 자료가 있다면 작성해 주세요."
      placeholder: |
        - 관련 링크:
        - 참고 문서:
    validations:
      required: false
