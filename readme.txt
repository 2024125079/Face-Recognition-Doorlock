1. 문서 개요
1.1 목적
본 계획서는 'Face-Recognition-Doorlock' 프로젝트의 산출물을 체계적으로 관리하기 위해 작성함.

1.2 적용 범위
- 과제별 산출물(PDF, 문서)

2. 형상 항목 (파일 위치를 내 폴더 구조에 맞게 수정)
구분      형상 항목                    파일 위치
요구사항   과제1.프로젝트정의서         /docs/requirements
		과제3.요구사항정의서				/docs/requirements
		과제4.요구사항분석서				/docs/requirements
설계      	과제5.소프트웨어설계서       /docs/design
일정      	과제2.프로젝트관리계획서     /docs/plan
테스트	과제6.인스팩션예제				/docs/test
		과제7.테스트결과서				/docs/test

소스코드  소스코드             /src

3. 형상 식별 방법
3.1 버전 규칙: v1.0.0 (Major.Minor.Patch)
3.2 태그 전략: 각 과제 단계 완료 시 git tag 생성

4. 변경 관리 절차
4.1 절차: 변경 확인 -> draft 브랜치 작업 -> main 병합 -> CHANGELOG 기록
4.2 브랜치 전략: 
   - main: 최종 제출본
   - draft: 일상적인 과제 수행 및 문서 작업용

5. 형상 통제 방법
- 커밋 메시지 형식: [구분자] 내용 (예: [FEAT] 얼굴 인식 로직 추가)
- 구분자: [CR], [FEAT], [FIX], [DOCS] 활용

6. 형상 상태 기록
- CHANGELOG.md 파일을 별도로 운영하여 버전별 변경 사항 기록

7. 형상 감사
- 제출 전 모든 산출물의 Git 등록 여부 및 태그 확인

8. 백업 및 저장소 관리
- GitHub 원격 저장소: https://github.com/2024125079/Face-Recognition-Doorlock