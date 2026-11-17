# 클로드 입문서 실습 플러그인

책 3장 실습에서 만든 예시 스킬 3개를 플러그인 하나로 묶었습니다. 스킬을 직접 만들어 보기 전에 완성된 모양을 확인하거나, 직접 만든 스킬과 비교할 때 사용합니다.

| 스킬 | 하는 일 |
|---|---|
| sample-bakery-post | 빵 이름과 나오는 시간을 주면 가게 말투로 인스타그램 게시글을 씁니다. |
| sample-blog-to-sns | 블로그 글 한 편으로 인스타그램 게시글과 뉴스레터 소개 글을 함께 만듭니다. |
| sample-meeting-minutes | 회의 메모를 단톡방에 붙여 넣을 짧은 회의록으로 정리합니다. |

## 설치하기 (claude.ai)

1. 왼쪽 사이드바에서 [플러그인]을 누릅니다.
2. [추가] → [마켓플레이스 추가]를 누르고 `dingcodingco/dingco-book-practice`를 입력합니다.
3. 목록에 나온 dingco-book-practice 플러그인을 설치합니다.

## 예제 파일

`examples/ch03/` 폴더에 3장 실습에 쓰는 블로그 글, 회의 메모, 회비 내역이 들어 있습니다. 예제 속 가게와 동호회는 실습을 위해 만든 것입니다.

## 클로드 코드에서 설치하기

```
/plugin install dingco-book-practice --marketplace dingcodingco/dingco-book-practice
```
