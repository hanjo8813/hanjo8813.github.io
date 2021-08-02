# 나만의 개발일지 블로그 만들기~

> 블로그 링크 : https://hanjo8813.github.io

<br>

## 커스텀 메모

### 개발용 로컬 서버 실행

```
> bundle exec jekyll serve
```

<br>

### 카테고리 추가하기

1. `_pages/categories` : 이 폴더안에 만들고픈 카테고리를 md 파일로 생성
2. `_posts` : 이 폴더 안에서 카테고리의 폴더 구조를 그대로 따서 만들어준다.
3. 만든 폴더 내에서 md 파일을 생성. 파일명 규칙은 날짜-숫자임. (ex `2021-08-03-1.md`)
4. 이 md 생성 후 고유 카테고리를 지정해야 한번에 묶어줄 수 있다. (ex `categories: - BOJ`)
5. 생성했다면 `_includes/sidebar.html` 파일에서 링크를 해당 카테고리와 매핑해준다.

<br>

### _include 폴더
> _layout(골격)에서 참조해서 살을 붙이는 파일 모아놓는 폴더 (Liquid 언어로)

- `single.html` : 
- `archive-single.html` : 카테고리 클릭시, 해당 카테고리 내 게시글들 출력해주는 부분
- `sidebar.html` : 왼쪽 사이드바 출력 부분

<br>

### _sass 폴더
> css 모아놓는 폴더

- `하위폴더 skins` : 블로그 스킨 모아놓은 폴더. 나중에 내가 커스텀 스킨만들수도?
- `_variables.scss` : container 좌우 패딩 설정가능

<br>

## 참고 사이트

- https://hahafamilia.github.io/howto/jekyll-github-mistakes-blog/
- https://ansohxxn.github.io/blog/posting/
- https://devinlife.com/howto%20github%20pages/github-prepare/
- https://devinlife.com/howto%20github%20pages/blog-config/
- https://danggai.github.io/tags/#minimal-mistakes
- https://devinlife.com/howto%20github%20pages/blog-config/
