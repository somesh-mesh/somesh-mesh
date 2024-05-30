/**
 * Hi there, I'm Somesh Meshram 👋
 * 
 * ![GitHub followers](https://img.shields.io/github/followers/somesh-mesh?label=Follow&style=social)
 * ![GitHub commits](https://img.shields.io/github/commit-activity/y/somesh-mesh/somesh-mesh?style=social)
 * 
 * Welcome to my GitHub profile! I'm an Android and Flutter developer who dives into new technologies like a kid in a candy store—because who doesn't love spending weekends debugging? 
 * I’m always eager to learn, currently exploring the MERN stack, because why not add more to the plate? 
 * I love contributing to open-source projects; it's like unpaid overtime with the bonus of internet strangers critiquing your code.
 */

fun main() {
    // About Me
    val name = "Somesh Meshram"
    val about = """
        I'm an Android and Flutter developer who dives into new technologies like a kid in a candy store—because who doesn't love spending weekends debugging? 
        I’m always eager to learn, currently exploring the MERN stack, because why not add more to the plate? 
        I love contributing to open-source projects; it's like unpaid overtime with the bonus of internet strangers critiquing your code.
    """.trimIndent()

    // Social Media
    val instagramUsername = "looser_sometimes_"
    val linkedinUsername = "someshmeshram007"
    val twitterUsername = "looser_sometime"

    // GitHub Stats
    val githubUsername = "somesh-mesh"
    val githubFollowersBadge = "![GitHub followers](https://img.shields.io/github/followers/$githubUsername?label=Follow&style=social)"
    val githubCommitsBadge = "![GitHub commits](https://img.shields.io/github/commit-activity/y/$githubUsername/$githubUsername?style=social)"
    val githubStatsUrl = "https://github-readme-stats.vercel.app/api?username=$githubUsername&show_icons=true&theme=radical"
    val githubTopLangsUrl = "https://github-readme-stats.vercel.app/api/top-langs/?username=$githubUsername&layout=compact&theme=radical"

    // Print README
    println("# Hi there, I'm $name 👋\n")
    println("$githubFollowersBadge")
    println("$githubCommitsBadge\n")
    println("Welcome to my GitHub profile! I'm passionate about development and always eager to learn.\n")
    println("## 🚀 About Me\n")
    println(about)
    println("\n- 🔭 I’m currently working on mastering Android and Flutter development.")
    println("- 🌱 I’m currently learning the MERN stack.")
    println("- 👯 I’m looking to collaborate on open-source projects.")
    println("- 💬 Ask me about Android, Flutter, or anything related to development.")
    println("- 📫 How to reach me:")
    println("  - Instagram: [@$instagramUsername](https://www.instagram.com/$instagramUsername/)")
    println("  - LinkedIn: [@$linkedinUsername](https://www.linkedin.com/in/$linkedinUsername/)")
    println("  - Twitter: [@$twitterUsername](https://twitter.com/$twitterUsername)\n")
    println("## 🛠️ My Skills\n")
    println("### Languages\n")
    println("- Java ![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=java&logoColor=white)")
    println("- Kotlin ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=flat&logo=kotlin&logoColor=white)")
    println("- Dart ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)")
    println("- TypeScript ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)")
    println("- JavaScript ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)\n")
    println("### Frameworks and Libraries\n")
    println("- React ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)")
    println("- Node.js ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)\n")
    println("### Platforms and Tools\n")
    println("- Android ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white)")
    println("- Flutter ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white)")
    println("- MERN ![MERN](https://img.shields.io/badge/MERN-000000?style=flat&logo=mongodb&logoColor=white)")
    println("- MongoDB ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white)")
    println("- Firebase ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black)")
    println("- Adobe XD ![Adobe XD](https://img.shields.io/badge/Adobe_XD-FF26BE?style=flat&logo=adobe-xd&logoColor=white)\n")
    println("## 📈 GitHub Stats\n")
    println("![Somesh's GitHub stats]($githubStatsUrl)\n")
    println("![Top Langs]($githubTopLangsUrl)")
}
