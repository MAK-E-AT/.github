
## 🧐 What is MAK-E-AT⁉️

<div style="display: flex; justify-content: space-between;">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/c4aed005-d8f0-4d80-8bc1-e7880a596f22" width="200" height="400">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/c334ab57-22f8-49ce-924b-bf74d494f08d" width="200" height="400">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/37765748-9513-45d5-b50c-6cff2baae6c5" width="200" height="400">
</div>

<div style="clear: both;"></div> 
<br></br> 
**(이미지 간격 조절 할꺼에요!)**

  🍴“Makeat” 프로젝트는, 인공지능 기술을 활용해 사용자가 섭취하게 될 음식의 영양성분과 칼로리를 분석하고, 목적에 따라 조절 가능하도록 돕기 위해 진행되었습니다.
  <br></br>
  
  📌 **Task**
> 모바일 애플리케이션 ‘MAK-E-AT’ 의 **사용자가 섭취할 음식을 촬영**하면, 촬영된 이미지 상에 존재하는 **음식들을 인식해 분류**하고, 각각의 음식에 포함되어 있는 **영양성분**(탄수화물, 단백질, 지방, 나트륨, 총 칼로리)**을 분석**해 시각화해 줌으로써 사용자가 원하는 **목적에 따라 음식의 특정 영양 성분 섭취 조절을 가능하게** 하는 것을 목표로 설정했습니다.

<br></br>
  🔧 **Main Features**
``` 
1️⃣ 소셜 로그인 기능을 활용한 사용자 정보 저장 기능
 ➜ 로그인 기능을 통해 구분된 사용자의 정보와 업로드 기록을 저장합니다.
    
2️⃣ 인공지능 모델 `yolov5s`를 활용한 음식 이미지 분석 기능
 ➜ 사용자가 촬영한 음식 이미지를 인식해 해당하는 음식에 대한 영양성분을 반환합니다.
    
3️⃣ 분석된 음식의 영양성분 시각화 기능
 ➜ 분석된 음식의 영양성분을 “탄수화물, 단백질, 지방, 나트륨, 총 섭취 열량” 으로 구분해 시각화한 화면을 제공합니다.
    
4️⃣ 식단 정보 기록 기능
 ➜ 사용자가 업로드한 음식 이미지를 일일/ 주간/ 월간 식단 기록 정보로 저장한 내용을 제공합니다.
```
<br></br>
## 🗓️ How to manage MAK-E-AT
  ⏱️ **Agile**
  
기존의 `요구사항 분석` ➜ `기획` ➜ `디자인` ➜ `개발` ➜ `테스트` ➜ `출시` 의 순서대로 한번에 프로젝트를 진행하는 방식을 개선(프로젝트가 진행되면 수정이 어려움)한 방법인 Agile로 프로젝트 관리를 진행했습니다.

✅ 기능 단위의 prototype을 기반으로 프로젝트를 진행

✅ 실행 방법 : `Scrum`과 `Kanban` 방식을 결합 
  > - `Scrum` : __개발 주기인 sprint__ 를 설정하고, 그 일정에 맞춰 개발을 진행/ 해당 sprint 기간 내에 할당된 기능 개발이 완료돼야 함 종료일 iteration이 정해져 있음
  > - `Kanban` : sprint 기간 없이, __일의 진행을 진행사항에 따라 나누고__ 작업흐름을 확인하며 진행
  > `NEW` ➜ `Backlog` ➜ `Todo` ➜ `In Progress` ➜ `In Review` ➜ `Done`
 <br></br>
 
  🌿 **Branch를 활용한 협업** 
  
  각각의 `feature/ 기능명` 브랜치에서 __독립적으로 개발__ 을 완료한 후, Pull Request(develop <- feature)하여 develop 브랜치에 완성된 기능들을 __병합__ 해 전체 기능을 완성했습니다.
  > - **develop** (default) : 개발이 완성된 기능들을 병합하기 위해 생성한 브랜치 (배포준비 전 단계를 총괄)
> - **feature** : 개발이 필요한 기능들을 구분해 놓은 브랜치

👀 Branch를 활용한 협업 방법에 대한 자세한 설명은 [Discussion_Branch](https://gifted-antler-fe6.notion.site/MAK-E-AT-7f61599c851247a7ab4b3c1c21034295) 를 참고해주세요!

<br></br>


## 🙋 Who made MAK-E-AT
⇒ 멤버별로 구분, 기능 구현시 사용한 프로그램& 라이브러리 등 정리 필요!
- 사용된 인공지능 모델 및 프로그램 : 주요 기능 구현 과정에서 사용된 프로그램을 간단하게 표기  

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://kentcdodds.com"><img src="https://avatars.githubusercontent.com/u/1500684?v=3?s=100" width="100px;" alt="Hyeonho_Shin"/><br /><sub><b>Hyeonho_Shin</b></sub></a><br /><a href="#question-kentcdodds" title="Answering Questions">💬</a> <a href="https://github.com/all-contributors/all-contributors/commits?author=kentcdodds" title="Documentation">📖</a> <a href="https://github.com/all-contributors/all-contributors/pulls?q=is%3Apr+reviewed-by%3Akentcdodds" title="Reviewed Pull Requests">👀</a> <a href="#talk-kentcdodds" title="Talks">📢</a></td>
      <td align="center"><a href="https://github.com/jfmengels"><img src="https://avatars.githubusercontent.com/u/3869412?v=3?s=100" width="100px;" alt="Sungmin_Ha"/><br /><sub><b>Sungmin_Ha</b></sub></a><br /><a href="https://github.com/all-contributors/all-contributors/commits?author=jfmengels" title="Documentation">📖</a> <a href="https://github.com/all-contributors/all-contributors/pulls?q=is%3Apr+reviewed-by%3Ajfmengels" title="Reviewed Pull Requests">👀</a> <a href="#tool-jfmengels" title="Tools">🔧</a></td>
      <td align="center"><a href="https://jakebolam.com"><img src="https://avatars2.githubusercontent.com/u/3534236?v=4?s=100" width="100px;" alt="Eunjung_Lee"/><br /><sub><b>Eunjung_Lee</b></sub></a><br /><a href="https://github.com/all-contributors/all-contributors/commits?author=jakebolam" title="Documentation">📖</a> <a href="#tool-jakebolam" title="Tools">🔧</a> <a href="#infra-jakebolam" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="#maintenance-jakebolam" title="Maintenance">🚧</a> <a href="https://github.com/all-contributors/all-contributors/pulls?q=is%3Apr+reviewed-by%3Ajakebolam" title="Reviewed Pull Requests">👀</a> <a href="#question-jakebolam" title="Answering Questions">💬</a></td>
    </tr>
    <tr>
      <td align="center"><a href="https://robertlluberes.com"><img src="https://avatars1.githubusercontent.com/u/13991439?v=4?s=100" width="100px;" alt="Seonghyeon_Lee"/><br /><sub><b>Seonghyeon_Lee</b></sub></a><br /><a href="#translation-robertlluberes" title="Translation">🌍</a></td>
      <td align="center"><a href="https://jongjineee.github.io"><img src="https://avatars2.githubusercontent.com/u/26620470?v=4?s=100" width="100px;" alt="Jaegyeong_Han"/><br /><sub><b>Jaegyeong_Han</b></sub></a><br /><a href="https://github.com/all-contributors/all-contributors/commits?author=Jongjineee" title="Documentation">📖</a> <a href="#translation-Jongjineee" title="Translation">🌍</a></td>
      <td align="center"><a href="http://marsx.vip"><img src="https://avatars2.githubusercontent.com/u/21303543?v=4?s=100" width="100px;" alt="Jaehyeong_Park"/><br /><sub><b>Jaehyeong_Park</b></sub></a><br /><a href="#translation-MarsXue" title="Translation">🌍</a></td>
    </tr>

  </tbody>
</table>
<br></br>

## 4️⃣ Storyboard
(Adobe XD 화면구성 이미지로 첨부)
<br></br>

## 5️⃣ Prototype
<br></br>

## 6️⃣ Start using MAK-E-AT
- 설치 경로 (이동 링크 제공)
- 간단한 사용 방법 설명  
  ⇒ 첨부한 Prototype에 기반한 전체적인 앱 사용 흐름을 간단하게 설명 
  <br></br>

## 8️⃣ License
- 저작물의 수정, 배포에 대한 권한이나 저작권에 대한 조항 표기
<br></br>

## 9️⃣ References
- (외부 리소스 정보) 개발에 사용된 참고 코드 출처 표기
<br></br>

 
