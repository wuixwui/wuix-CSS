# Prettier

---

정해진 규칙에 따라 자동으로 코드 스타일을 정리해 준다.

설정 파일을 수정하면 규칙도 커스터 마이징이 가능하다.

## 설치방법

1. vscode에서 prettier 확장자를 설치해준다.

2. 확장자가 enable인지 확인한다.

3. 기본 설정을 하기 위해 설정창에 들어간다.

4. editor farmat on save 체크박스를 체크해준다.

5. json을 검색해서 Edit in setting.json 안의 editor.formatOnSave 값이 true 인지 확인해준다.

6. 그리고 다시 default formatter를 검색하고 null값을 prettier로 바꿔준다.

7. 이후 저장을 해보면 setting 값에 맞춰서 설정되는 것을 볼 수 있다.

> 보통 Prettier은 tab size가 2로 설정되어 있기 때문에 vscode의 tab 인덱스도 맞춰두는 것이 좋다.

## 설정 적용 순서

> settings.json -> .editorconfig -> .prettierrc
> 해당 설정 세팅파일들 순서에 따라서 적용된다.

## 설정방법

[관련 블로그](https://uxgjs.tistory.com/150)
