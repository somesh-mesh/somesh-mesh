/**
 * Hi there, I'm Somesh Meshram 👋
 * 
 * GitHub followers: ![GitHub followers](https://img.shields.io/github/followers/somesh-mesh?label=Follow&style=social)
 * GitHub commits: ![GitHub commits](https://img.shields.io/github/commit-activity/y/somesh-mesh/somesh-mesh?style=social)
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
    println("- 🔭 I’m currently working on mastering Android and Flutter development.")
    println("- 🌱 I’m currently learning the MERN stack.")
    println("- 👯 I’m looking to collaborate on open-source projects.")
    println("- 💬 Ask me about Android, Flutter, or anything related to development.")
    println("- 📫 How to reach me:")
    println("  - Instagram: [@$instagramUsername](https://www.instagram.com/$instagramUsername/)")
    println("  - LinkedIn: [@$linkedinUsername](https://www.linkedin.com/in/$linkedinUsername/)")
    println("  - Twitter: [@$twitterUsername](https://twitter.com/$twitterUsername)\n")
    println("## 📈 GitHub Stats\n")
    println("![Somesh's GitHub stats]($githubStatsUrl)\n")
    println("![Top Langs]($githubTopLangsUrl)")
}
