### Hi there 👋 

<!-- dynamic typing effect 动态打字效果 -->
<h1 align="center">
  <a href="https://blog.sunguoqi.com/">
    <img src="https://readme-typing-svg.herokuapp.com/?lines=Hello%2C%20World!;咸鱼祝您今天愉快!&center=true&size=27" />
  </a>
</h1>
<br/><br/>

- 📙 博客 site [blog.xianyuya.ltd](https://blog.xianyuya.ltd/)
- 🍄 胆小认生，不易相处，
- 🌱 年轻无为，卖码为生。

<!-- profile logo 个人资料徽标 -->
<div align="center">
  <a href="https://xy.kuvinet.cn/"><img src="https://img.shields.io/badge/Website-咸鱼日记-fad434" /></a>&emsp;
  <a href="https://blog.xianyuya.ltd/"><img src="https://img.shields.io/badge/Website-博客-blue" /></a>&emsp;
  <a href="https://note.xianyuya.ltd/"><img src="https://img.shields.io/badge/Website-知识库-c32136" /></a>&emsp;
  <!-- visitor statistics logo 访客数统计徽标 -->
  <img src="https://visitor-badge.glitch.me/badge?page_id=sun0225SUN" alt="访客统计" />
</div>

✨ 统计 ✨

<div align="center">
    <img  src="https://github-readme-streak-stats.herokuapp.com/?user=s-xianyu&theme=dark&hide_border=true" />
</div>

<!-- GitHub 数据统计 -->
<div align="center">
  <img height="137px" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api?username=s-xianyu&hide_title=true&hide_border=true&show_icons=trueline_height=21&text_color=000&icon_color=000&bg_color=0,ea6161,ffc64d,fffc4d,52fa5a&theme=graywhite" />
  <img height="137px" src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=s-xianyu&hide_title=true&hide_border=true&layout=compact&langs_count=6&text_color=000&icon_color=fff&bg_color=0,52fa5a,4dfcff,c64dff&theme=graywhite" />
</div> 
  
<!-- GitHub 奖杯🏆 -->
<div align="center"><img  src="https://github-profile-trophy.vercel.app/?username=sun0225SUN&theme=gruvbox&row=1&column=6&no-frame=true&no-bg=true" /></div><br>

<!-- Awesome repo 比较好的仓库-->
<div align="center">
  <a href="https://github.com/s-xianyu/xy-diary">
    <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/pin/?username=s-xianyu&repo=xy-diary&theme=dark&bg_color=121212&hide_border=true" /></a>
  <a href="https://github.com/s-xianyu/xianyu-cli">
    <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/pin/?username=s-xianyu&repo=xianyu-cli&theme=dark&bg_color=121212&hide_border=true" /></a>
</div><br>

✨ 活动图 ✨
<!-- GitHub Activity Graph GitHub 活动图 -->
<table align="center">
  <tr>
    <td>
      <img src="https://github-readme-activity-graph.cyclic.app/graph?username=s-xianyu&theme=xcode&bg_color=FF000000&hide_border=true" alt="Activity"/>       </td>
  </tr>
</table>

# Visit https://github.com/lowlighter/metrics#-documentation for full reference
name: Metrics
on:
  # Schedule updates (each hour)
  schedule: [{cron: "0 * * * *"}]
  # Lines below let you run workflow manually and on each commit
  workflow_dispatch:
  push: {branches: ["master", "main"]}
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    permissions:
      contents: write
    steps:
      - uses: lowlighter/metrics@latest
        with:
          # Your GitHub token
          # The following scopes are required:
          #  - public_access (default scope)
          # The following additional scopes may be required:
          #  - read:org      (for organization related metrics)
          #  - read:user     (for user related data)
          #  - read:packages (for some packages related data)
          #  - repo          (optional, if you want to include private repositories)
          token: ${{ secrets.METRICS_TOKEN }}

          # Options
          template: classic
          base: header, activity, community, repositories, metadata
          config_timezone: Asia/Shanghai
          plugin_isocalendar: yes
          plugin_isocalendar_duration: half-year
          plugin_languages: yes
          plugin_languages_analysis_timeout: 15
          plugin_languages_analysis_timeout_repositories: 7.5
          plugin_languages_categories: markup, programming
          plugin_languages_colors: github
          plugin_languages_limit: 8
          plugin_languages_recent_categories: markup, programming
          plugin_languages_recent_days: 14
          plugin_languages_recent_load: 300
          plugin_languages_sections: most-used
          plugin_languages_threshold: 0%
          plugin_notable: yes
          plugin_notable_from: organization
          plugin_notable_types: commit
          plugin_posts: yes
          plugin_posts_limit: 4
          plugin_posts_user: .user.login
          plugin_tweets: yes
          plugin_tweets_limit: 2
          plugin_tweets_user: .user.twitter
<!--
**s-xianyu/s-xianyu** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
