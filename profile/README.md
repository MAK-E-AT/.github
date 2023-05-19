
## 🧐 What is MAK-E-AT⁉️

<p align="center">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/c4aed005-d8f0-4d80-8bc1-e7880a596f22" width="200" height="400" hspace="30"> 
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/c334ab57-22f8-49ce-924b-bf74d494f08d" width="200" height="400" hspace="30">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/37765748-9513-45d5-b50c-6cff2baae6c5" width="200" height="400" hspace="30">
</p>

<div style="clear: both;"></div> 
<br></br> 

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
  
<p align="center">
  <img src="https://github.com/MAK-E-AT/.github/assets/102943250/d6c2bec8-9737-4625-8ef3-98a368a9d674" width="800" height="400">
</p>
  
 ♾️ 프로젝트를 순차적으로 한번에 진행하는 **Waterfall model 을 개선**(프로젝트가 진행되면 수정이 어려움)한 방법인 **Agile**로 프로젝트 관리를 진행했습니다.

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
</br>

<table align="center">
  <tbody>
    <tr>
      <!--신현호 / hardy716 -->
      <td align="center">
        <a href="https://github.com/hardy716">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239111507-0dc7d584-a661-4d12-8f4c-af910e20e313.PNG"    
               width="150px;"
               height="150px;"
               alt="Hyeonho_Shin"
           />
        </a>
        <br />
        <sub><b>Hyeonho_Shin</b></sub>
        <br /> 
        <a href="https://github.com/hardy716">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href="https://hardy716.github.io" title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto:dev.hardy716@gmail.com">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
      <--!성민-->
      <td align="center">
            <a href="https://github.com/xman227">
          <img src="https://github.com/MAK-E-AT/.github/assets/102943250/ab1cea70-5b3c-4daf-b244-4f0c78f3e86a" 
               width=" " 
               height="150px;"
               alt="Sungmin_Ha"/>
        </a>
        <br />
        <sub><b>Sungmin_Ha</b></sub>
        <br /> 
        <a href="https://github.com/xman227">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href="https://blog.naver.com/bulkup-star_maybe" title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto:dev.woodspace7@gmail.com">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
      <!-- 은정 -->
      <td align="center">
        <a href="https://github.com/eunjung0301">
          <img src="https://github.com/MAK-E-AT/.github/assets/102943250/ba045935-9c9a-4a4c-8e50-677ee1428511"
                width="150px;"
               height="150px;"
               alt="Eunjung_Lee"/>
        </a>
        <br />
        <sub><b>Eunjung_Lee</b></sub>
        <br /> 
        <a href="https://github.com/eunjung0301">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href="https://deadpan-map-562.notion.site/Welcome-to-notion_LEE-EUNJUNG-251367bb154e4a33a464a7e022e78a1c" title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto:english0301@naver.com">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
    </tr>
    <!--백엔드 팀-->
    <!-- 승현 -->
    <tr>
            <td align="center">
        <a href="https://github.com/cookie0010">
          <img src="https://github.com/MAK-E-AT/.github/assets/102943250/46a95518-c039-47b2-bfdb-cb79bd4f5a1f" width="200px;" alt=" "/>
        </a>
        <br />
        <sub><b>Seonghyeon_Lee</b></sub>
        <br /> 
        <a href="https://github.com/cookie0010">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href="https://jmcsoft.tistory.com/2" title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto:">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
      <!-- 재경 -->
           <td align="center">
        <a href="https://github.com/hanjaegyeong">
          <img src="https://github.com/MAK-E-AT/.github/assets/102943250/46a95518-c039-47b2-bfdb-cb79bd4f5a1f" width="200px;" alt=" "/>
        </a>
        <br />
        <sub><b>Jaegyeong_Han</b></sub>
        <br /> 
        <a href="https://github.com/hanjaegyeong">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href=" " title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto: ">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
      <!-- 재형 -->
      <td align="center">
        <a href="https://github.com/hyeong0917">
          <img src="https://github.com/MAK-E-AT/.github/assets/102943250/46a95518-c039-47b2-bfdb-cb79bd4f5a1f" width="200px;" alt="Jaehyeong_Park"/>
        </a>
        <br />
        <sub><b>Jaehyeong_Park</b></sub>
        <br /> 
        <a href="https://github.com/hyeong0917">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117067-43cb7344-e4f3-469d-8fc6-3587be22c1ad.png"    
               width="24px;"
               height="24px;"
               onclick="null"
           />
        </a> 
        <a href=" " title="Documentation">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239116990-3e2fc917-34d7-49ed-a811-dc804c379de8.png"    
               width="24px;"
               height="24px;"
           />
        </a> 
        <a href="mailto: ">
          <img 
               src="https://github-production-user-asset-6210df.s3.amazonaws.com/101140679/239117133-6d40683c-93a0-40c0-a383-1365b4c22f2c.png"    
               width="24px;"
               height="24px;"
           />
        </a>
      </td>
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

 
