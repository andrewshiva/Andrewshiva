### Hi there 👋 i am shiva 






 -🔭 I’m currently working on machine learning and deep learning 
- 🌱 I’m currently learning keras and pytorch
- 💬 Ask me about ml and data science
- 📫 How to reach me: 
linkedin -https://www.linkedin.com/in/shiva-singh-tomar-253190173/
Gmail- Singhtomar456@gmail.com
- ⚡ Fun fact:  i am vampire lol




[![Andrewshivagithub stats](https://github-readme-stats.vercel.app/api?username=andrewshiva)](https://github.com/andrewshiva/github-readme-stats)


[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=andrewshiva&layout=compact)](https://github.com/andrewshiva/github-readme-stats)


<!--START_SECTION:activity-->

name: Update README

on:
  schedule:
    - cron: '*/30 * * * *'
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    name: Update this repo's README with recent activity

    steps:
      - uses: actions/checkout@v2
      - uses: andrewshiva/github-andrewshiva
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


