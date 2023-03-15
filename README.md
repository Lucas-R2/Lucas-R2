## Olá! Eu sou o Lucas, homem trans, formado em Administração e estudante de programação!!! 

- 💡 Hoje eu estou em processo de migração de carreira
- 🌱 Estudando HTML, CSS, Javascript
- 📫 Contate-me no e-mail: lucasrafasreis@gmail.com
- 😄 Pronomes: Ele/Dele
- 🏳️‍⚧️🏳️‍⚧️🏳️‍⚧️🏳️‍⚧️🏳️‍⚧️🏳️‍⚧️

<div align="center">
  <a href="https://github.com/Lucas-R2">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=Lucas-R2&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
</div>
<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="Rafa-CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>

##

<div>
  <a href="https://instagram.com/rafaeu.lucas" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href = "mailto:lucasrafasreis@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/lucas-rafael-dos-reis-%F0%9F%8F%B3%EF%B8%8F%E2%80%8D%E2%9A%A7%EF%B8%8F-828214143/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
</div>

  Nome : Gerar Dados

em :
  cronograma : # executar a cada 12 horas
    - cron : " * */12 * * * "
  workflow_dispatch :

trabalhos :
  construir :
    nome : Jobs para atualizar dados
    run-on : ubuntu-latest
    passos :
      # Animação de Cobra
      - usa : Platane/snk@master
        id : cobra-gif
        com :
          github_user_name : rafaballerini
          svg_out_path : dist/github-contribution-grid-snake.svg

      - usa : crazy-max/ghaction-github-pages@v2.1.3
        com :
          target_branch : saída
          build_dir : dist
        ambiente :
          GITHUB_TOKEN : ${{ segredos.GITHUB_TOKEN }}
