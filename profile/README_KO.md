# MoWA
**Mo**notoring the elder with **W**i-Fi sensing and **A**I

<!-- Skill -->
<div>
    <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
    <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
    <img src="https://img.shields.io/badge/android-3DDC84?style=for-the-badge&logo=android&logoColor=white">
    <img src="https://img.shields.io/badge/androidstudio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white">
    <img src="https://img.shields.io/badge/kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white">
    <img src="https://img.shields.io/badge/gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white">
    <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">
    <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
    <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
</div>

<br/>

<table>
    <tr>
        <td align="center"><b>장정익</b></td>
        <td align="center"><b>남선우</b></td>
        <td align="center"><b>문정곤</b></td>
        <td align="center"><b>우태경</b></td>
        <td align="center"><b>표지성</b></td>
    </tr>
    <tr>
        <td align="center"><a href="https://github.com/cheeseBG">GitHub 프로필</a></td>
        <td align="center"><a href="https://github.com/namseonu">GitHub 프로필</a></td>
        <td align="center"><a href="https://github.com/MoonJungGon">GitHub 프로필</a></td>
        <td align="center"><a href="https://github.com/wootaegyeoung">GitHub 프로필</a></td>
        <td align="center"><a href="https://github.com/pjs990301">GitHub 프로필</a></td>
    </tr>
    <tr>
        <td align="center">
            Wi-Fi sensing
        </td>
        <td align="center">
            Android, Flask
        </td>
        <td align="center">
            Wi-Fi sensing
        </td>
        <td align="center">
            Wi-Fi sensing
        </td>
        <td align="center">
            Wi-Fi sensing, Flask
        </td>
    </tr>
</table>

<br/>
<br/>

## <b>목차</b>
1. [서비스 소개](#1-서비스-소개)
2. [서비스 동기](#2-서비스-동기)
3. [시스템 아키텍처](#3-시스템-아키텍처)

<br/>
<br/>

## <b>1. 서비스 소개</b>

<br/>

![ic_mowa_not_title](https://github.com/GachonMoWA/mowa-app-android/assets/77925666/126ee4c4-8150-47e7-b65a-c0af31b7805b)

MoWA(이하 모와) 프로젝트는 'Monitoring the elder with Wi-Fi sensing and AI(Artificial Intelligence, 인공지능)'의 약자로, 와이파이 센싱 기술과 인공지능 기술을 활용하여 독거 노인을 모니터링하는 시스템입니다.
이때 와이파이 센싱 기술은 사용자의 활동을 모니터링하여 CSI(Channel State Information, 통신 채널에 대한 상태 정보) 데이터를 서버로 전송합니다.
사용자는 안드로이드 휴대 전화에 MoWA 애플리케이션을 설치하여 MoWA 서비스를 이용할 수 있으며, 해당 애플리케이션을 통해 자신의 활동량과 위험도를 확인할 수 있습니다.

✅ 와이파이 센싱 기술과 인공지능 기술을 통한 독거 노인 모니터링
✅ 독거 노인 활동 모니터링
✅ 독거 노인의 위험 상태 파악 및 대처

<br/>
<br/>

## <b>2. 서비스 동기</b>

MoWA 프로젝트는 독거 노인을 모니터링하여 발생할 수 있는 사고에 대처하고 독거 노인의 활동성을 보장하는 것을 목표로 합니다. 독거 노인을 타겟층으로 선정한 이유는 국내 고령화 및 독거 노인 문제가 증가하고 있기 때문입니다.

<img width="400" src="https://github.com/oss-inc/.github/assets/77925666/c27982bc-0326-405c-8feb-91da30fb24b3" />

<br/>

<img width="400" src="https://github.com/oss-inc/.github/assets/77925666/0ea365ec-4d2d-4e31-92fb-bb81e57f25d3" />

<br/>

와이파이 센싱 기술을 통해 독거 노인의 행동을 모니터링하고 확인합니다. 또한 안드로이드 애플리케이션을 통해 사용자는 자신의 활동 통계 수치를 확인할 수 있으며, 기타 다양한 기능을 활용할 수 있습니다.

<br/>
<br/>

## <b>3. 시스템 아키텍처</b>

![System Architecture](https://github.com/oss-inc/.github/assets/77925666/9e244278-2f3d-4997-8857-7c49c6677eef)

<br/>

<i>각 시스템의 구성 요소에 대한 소스 코드와 더 자세한 설명을 보려면 아래의 각 링크를 클릭해 주세요.</i>

- 🔗 <a href="https://github.com/oss-inc/mowa-wifi-sensing">nexmon csi를 이용한 와이파이 센싱 모니터링</a>
- 🔗 <a href="https://github.com/oss-inc/mowa-wifi-sensing-labelling">와이파이 센싱을 위한 레이블링</a>
- 🔗 <a href="https://github.com/oss-inc/mowa-backend-flask">REST API 서버 역할의 flask 서버 (백엔드)</a>
- 🔗 <a href="https://github.com/oss-inc/mowa-frontend-android">사용자가 사용할 수 있는 안드로이드 애플리케이션 (프론트엔드)</a>

<br/>
<br/>
