<p align="center">
<a href="https://github.com/devxb/gitanimals">
  <img src="https://render.gitanimals.org/lines/audgns10?pet-id=1" width="1000" height="360"/>
</a>

<!--
  <p align="center">
 <a href="https://github.com/chlgkdms/github-readme-stats">
    <img src="https://github-readme-stats.vercel.app/api?username=chlgkdms&bg_color=30,e96443,904e95&title_color=fff&text_color=fff"/></a></p>
 -->

```kotlin
data class Profile(
    val name: String = "이명훈",
    val nickName: String = "o0뀨0o",
    val birthday: Int = 20071011,
    val major: String = "Android Developer",
    val techStack: TechStack,
    val introduce: String = "개발자가 보기 쉬운 코드를 짜자려 노력합니다",
    val school: String = "광주소프트웨어마이스터고등학교",
    val email: String = "s23065@gsm.hs.kr",
    val github: String = "https://github.com/audgns10",
    val team: String = "MSG - Team"
) {
    data class TechStack(
        val one: String = "Kotlin",
        val two: String = "Jetpack-Compose"
    )
}
```


<div align="center">
