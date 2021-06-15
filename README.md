### RealBluxy:

**Hi, My Name's RealBluxy, I'm A PHP Dev

## My Latest Projects !

query {
  viewer {
    repositories(first: 100, privacy: PUBLIC) {
      pageInfo {
        hasNextPage
        endCursor
      }
      nodes {
        name
        releases(last:1) {
          totalCount
          nodes {
            name
            publishedAt
            url
          }
        }
      }
    }
  }
}

![Bluxy's github stats](https://github-readme-stats.vercel.app/api?username=RealBluxy&show_icons=true&hide_border=true)

<!--
**RealBluxy/RealBluxy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
