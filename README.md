<p>
<a href="https://github.com/anuraghazra/github-readme-stats#github-stats-cards">
<img align="left" src="https://github-readme-stats.vercel.app/api?username=torish14&count_private=true&include_all_commits=true&show_icons=true&theme=dracula" />
</a>

<!-- <a href="https://github.com/anuraghazra/github-readme-stats#wakatime-week-stats"> -->
<!-- <img src="https://github-readme-stats.vercel.app/api/wakatime?username=torish14&theme=dracula&layout=compact" /> -->
<!-- </a> -->

<a href="https://github.com/anuraghazra/github-readme-stats#top-languages-card">
<img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=torish14&hide=html,css,ejs,scss&theme=dracula" />
</a>

<a href="https://github.com/ryo-ma/github-profile-trophy">
<img src="https://github-profile-trophy.vercel.app/?username=torish14&theme=dracula" />
</a>

</p>

<!--START_SECTION:waka-->
name: Wakatime Stats

on:
  schedule:
  workflow_dispatch:
  jobs:
  update-readme:
    name: Update Readme with Metrics
    runs-on: macos-latest
    steps:
      - uses: anmol098/waka-readme-stats@master
        with:
          WAKATIME_API_KEY: ${{ secrets.ec7616be-3e1d-41af-af91-b8d86a33209b }}
          GH_TOKEN: ${{ secrets.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 }}

<!--END_SECTION:waka-->

