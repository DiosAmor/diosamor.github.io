# 홈페이지 프로젝트 지침

## News

- 홈, News 목록, 개별 뉴스 페이지에는 월과 연도만 표시한다. 원자료의 날짜는 정렬을 위해 각 뉴스의 `date`에 보존한다.

## Publications

- 인용 수 배지는 홈페이지와 미리보기 모두에서 페이지를 열 때 Dimensions에서 조회한 값을 표시한다.

## CV 수정

- CV의 편집 원본은 [_cv/cv_changmin_mcx.tex](_cv/cv_changmin_mcx.tex)이다. 경력, 논문, 학술 활동을 갱신할 때는 이 파일을 수정한다. 이전에 만든 Word 파일과 PDF는 비교용으로만 사용한다.
- 기존 LaTeX 서식과 저자 기호를 유지하고, 내용이 바뀌면 문서 상단의 `Last update` 날짜도 갱신한다. 논문이 `Selected Publications`와 전체 논문 목록에 모두 있으면 두 곳의 서지정보를 함께 확인한다.
- Overleaf에서는 `cv_changmin_mcx.tex`를 메인 문서로 선택한다. 기존 공개 PDF의 서식을 재현할 때는 같은 엔진인 pdfLaTeX를 사용한다.
- 수정한 TeX를 PDF로 컴파일해 페이지 나눔, 잘린 문장, 링크를 확인한다. 홈페이지에 반영할 때는 이 PDF를 `assets/pdf/CV_changminlee_YYMMDD.pdf`로 저장하고, [_pages/cv.md](_pages/cv.md)의 `cv_pdf`가 해당 파일을 가리키도록 한다.
- 배포 전 미리보기에서는 `/cv/`를 직접 열어 검토한 PDF가 표시되는지 확인한다.
