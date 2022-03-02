
### 깃허브에 올리는 법 
> *ctrl+s  > add > commit > push*
- git add
- git commit -m "0000"
- git push origin master

#### 상태확인
- git status
- git log --oneline

#### .gitignore

touch .gitignore
touch a.txt b.txt c.txt

.gitignore 에 a.txt 추가 후 저장하면 무시 

[ignore 찾기](www.total.com)
- python, jupyternotebooks 입력 후 생성 
- gitignore에 붙여넣기



### 목차만들기 
- GitHub에 보이는 목차는 링크를 상대경로로 지정하는 것 

#### 개념 
- 마크다운 링크 문법 
```
[내용 작성](링크)
```
- 절대경로와 상대경로 
```
c/
 TIL/
  Python/
   algorithms/
```
- 절대경로 : c:/TIL/python
- 상대경로 
    - TIL 폴더 입장에서 python 폴더 : ./python
    - python 폴더 입장에서 TIL 폴더 : ../
    - python 폴더 입장에서 algorithms 폴더 : ../algorithms/

### 예시
#### 동일 페이지에서 이동 
> 동일 페이지에서는 Heading을 기준으로 할 수 있습니다. 
- 링크 작성하실 때 #의 갯수는 반드시 하나입니다. 
    - Heading Level이랑 상관 없음

```
* [python](#python)
* [algorithms](#algorithms)

## python
### algorithms
```
#### 상대경로 이동 
> 상대 경로로 파일이나 폴더를 링크 걸 수 있습니다. 
```
[python](./python)
[algorithms](./algorithms)
```
- 파이썬(./python)


