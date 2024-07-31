# 동기부여 코치 AI-M

## 아이디어 기획
- 목표는 있지만 의욕이 없거나 꺾일 때 늘 다시 '동기부여'가 필요합니다.
- 스스로 동기부여를 낼 수 있으면 최고지만, 동기부여가 되는 말을 텍스트로 읽게 되면 마음을 다잡을 수 있게 됩니다.
- 목표를 상기시키고 마음을 다잡기 위해 목표와 현재 상태를 입력하고 그에 맞는 동기부여가 되는 말을 해주는 챗봇을 만들었습니다.

## WBS
```mermaid
gantt
    title Chat-GPT 연동 동기부여 서비스 WBS
    dateFormat YYYY-MM-DD
    axisFormat %Y-%m-%d
    section 프로젝트 준비
    아이디어 기획         :a1, 2023-07-29, 6h
    리포지토리 생성       :a2, after a1, 6h
    와이어 프레임         :a3, after a2, 6h
    기본 UI 구현          :a4, after a3, 6h
    section AI 연동 및 구현
    AI API 연동 (JS)      :b1, after a4, 12h
    결과 표시 기능 구현 (JS) :b2, after b1, 12h
    section 마무리
    공개 URL 생성         :c1, after b2, 6h
    README 파일 작성      :c2, after c1, 6h
    section 프로젝트 기한
    프로젝트 완료         :milestone, after c2, 0d
```

## 와이어프레임
<img width="911" alt="wireframe" src="https://github.com/user-attachments/assets/e39dd143-bf47-42e6-9825-f68a19d53aff">

[피그마 링크](https://www.figma.com/design/pJDMri393hCWavvNmTVN0E/AIM?node-id=0-1&t=GxYUCK5Ys65OCrY9-1)

## 구현
[프로그램 링크](https://donggyu-kim1.github.io/AI-motivation/)

## 시연 영상
![program-video](https://github.com/user-attachments/assets/ed346331-566e-4d94-b4b6-9b2e90e15407)
