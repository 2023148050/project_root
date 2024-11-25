# Project Root

## 개요
이 프로젝트는 부모 교육과 관련된 일기 작성 및 AI 상담 시스템을 제공합니다.

## 주요 기능
1. 부모가 일기를 작성하면 AI가 피드백을 제공합니다.
2. To-Do 리스트를 제안하고, 사용자가 선택한 리스트를 저장합니다.
3. 캘린더에서 일기와 To-Do 리스트를 확인할 수 있습니다.

## API 엔드포인트
- **POST /chat/**: AI와의 대화 및 To-Do 리스트 생성.
- **POST /todo/save/**: 선택한 To-Do 리스트 저장.
- **GET /calendar/<user_id>/<date>/**: 일기와 To-Do 리스트 데이터 반환.

## 실행 방법
1. `.env` 파일에 OpenAI API 키 추가:
