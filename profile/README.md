# 한신대학교 알림마당

## 기간
24.03 - 24.06

## 기획 배경

## 팀원
|![](https://avatars.githubusercontent.com/u/92840513?v=4)|![](https://avatars.githubusercontent.com/u/114846624?v=4)|
|:---:|:---:|
|[정보통신학부 유희준](https://github.com/UHeeJoon)|[정보통신학부 신민섭](https://github.com/ShinminSub6)|
|백엔드|백엔드 + 프론트 엔드|






## 흐름도
![image](https://github.com/HS-Notification-Field/.github/assets/92840513/9584f105-94f0-4aec-b360-531844317c99)

## 아키텍쳐
![image](https://github.com/HS-Notification-Field/.github/assets/92840513/03eb602c-5b17-46ca-a82a-837144a3f29e)

## 기술스택
### 백엔드
![springboot](https://img.shields.io/badge/springboot-6DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white) 
![springsecurity](https://img.shields.io/badge/springsecurity-6DB33F.svg?style=for-the-badge&logo=springsecurity&logoColor=white) 
![mysql](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![junit5](https://img.shields.io/badge/junit5-25A162.svg?style=for-the-badge&logo=junit5&logoColor=white) 
![gradle](https://img.shields.io/badge/gradle-02303A.svg?style=for-the-badge&logo=gradle&logoColor=white) 
![amazonec2](https://img.shields.io/badge/amazonec2-FF9900.svg?style=for-the-badge&logo=amazonec2&logoColor=white) 
![amazonrds](https://img.shields.io/badge/amazonrds-527FFF.svg?style=for-the-badge&logo=amazonrds&logoColor=white) 

### 프론트엔드
![Vercel](https://img.shields.io/badge/vercel-000000.svg?style=for-the-badge&logo=vercel&logoColor=white) 
![React](https://img.shields.io/badge/react-2320232a.svg?style=for-the-badge&logo=react&logoColor=white) 
![reactquery](https://img.shields.io/badge/reactquery-FF4154.svg?style=for-the-badge&logo=reactquery&logoColor=white) 
![recoil](https://img.shields.io/badge/recoil-3578E5.svg?style=for-the-badge&logo=recoil&logoColor=white) 
![styledcomponents](https://img.shields.io/badge/styledcomponents-DB7093.svg?style=for-the-badge&logo=styledcomponents&logoColor=white) 
![axios](https://img.shields.io/badge/axios-5A29E4.svg?style=for-the-badge&logo=axios&logoColor=white) 
![tailwindcss](https://img.shields.io/badge/tailwindcss-06B6D4.svg?style=for-the-badge&logo=tailwindcss&logoColor=white) 

### 툴
![github](https://img.shields.io/badge/github-181717.svg?style=for-the-badge&logo=github&logoColor=white) 
![intellijidea](https://img.shields.io/badge/intellijidea-000000.svg?style=for-the-badge&logo=intellijidea&logoColor=white) 
![webstorm](https://img.shields.io/badge/webstorm-000000.svg?style=for-the-badge&logo=webstorm&logoColor=white) 


## ERD
![image](https://github.com/HS-Notification-Field/.github/assets/92840513/24ea0d7a-9eec-4134-a57d-82acded9c2c5)


## API 명세서

### Response
```json
// 200
{
  "success": true,
  "message": "회원 가입에 성공했습니다.",
  "data": null
}
```

### Error
```json
// 400
{
  "success": false,
  "message": "비밀번호가 일치하지 않습니다.",
  "data": null
}
```

## 주요 기능


## 🙌🏻 협업 규칙
* 각자 저장소를 Fork하여 작업
* 작업 진행
* Pull Request 과정에서 충돌이 난 경우 충돌난 코드와 관련된 팀원들이 소통하여 충돌 해결 후 Merge
* develop에서 모든 작업이 끝난 후 main으로 Pull Request & Rebase and Merge 후 프로젝트 종료

## ✋🏻 깃허브 커밋 메시지 규칙
```text
feat: 새로운 기능 추가했을 때
fix: 버그나 오류 수정했을 때
refactor: 코드 리팩토링했을 때
chore: 약간 애매한 기타 변경사항
docs: 리드미 파일이나 md 파일 수정할 때 (문서작업)
```

