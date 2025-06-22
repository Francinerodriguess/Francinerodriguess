# 👩🏽‍💻 Fran Rodrigues

**'Desenvolvedora de Software'**

 Me chamo Francine Rodrigues, tenho 29 anos e sou natural de Salvador. Moro atualmente em Jundiaí-SP, estou cursando Engenharia de Software. Sou apaixonada por tecnologia e me mantenho atualizada através dos cursos da plataforma Alura.  

 <p align="left">
      <a href="https://www.youtube.com/@dev_fran">
            <img 
                alt="Inscritos"
                title="Inscreva-se" 
                src="https://custom-icon-badges.demolab.com/youtube/channel/subscribers/UCz9D4wHaXfimINCIcZkvDWw?color=%23E05D44&label=Inscreva-se&logo=video&logoColor=white&style=for-the-badge&labelColor=CE4630"
                />
    </a> 
      <a href="https://www.youtube.com/@dev_fran">
         <img 
            alt="youtube views" 
            title="YouTube views" 
            src="https://custom-icon-badges.demolab.com/youtube/channel/views/UCz9D4wHaXfimINCIcZkvDWw?color=%23E1AD0E&logo=eye&logoColor=white&style=for-the-badge&labelColor=C79600"/>
    </a> 
             <a href="https://github.com/Francinerodriguess?tab=repositories&sort=stargazers">
         <img 
         alt="Total de estrelas" 
         title="Total de estrelas GitHub" 
         src="https://custom-icon-badges.demolab.com/github/stars/Francinerodriguess?color=55960c&style=for-the-badge&labelColor=488207&logo=star&label=estrelas"/>
    </a>
      <a href="https://github.com/Francinerodriguess">
         <img 
         alt="Seguidores" 
         title="Me siga no Github" 
         src="https://custom-icon-badges.demolab.com/github/followers/Francinerodriguess?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=Github&label=seguidoreS&logoColor=white"
         />
    </a>  
</p>

---

### 🤖 Linguagens e Tecnologias que estou aprendendo


<img 
    align="left" 
    alt="HTML"
    title="HTML" 
    width="30px" 
    style="padding-right: 10px;"    
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
/>


<img 
    align="left" 
    alt="CSS" 
    title="CSS"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
/>
<img 
    align="left" 
    alt="JavaScript" 
    title="JavaScript"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" 
/>
<img 
    align="left" 
    alt="TypeScript"
    title="TypeScript" 
    width="30px" 
    style="padding-right: 10px;" 


 name: Generate snake animation

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"

  workflow_dispatch:

  push:
    branches:
    - main

jobs:
  generate:
    permissions:
      contents: write
    runs-on: ubuntu-latest
    timeout-minutes: 5

    steps:
      - name: generate snake.svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: dist/snake.svg?palette=github-dark


      - name: push snake.svg to the output branch
        uses: crazy-max/ghaction-github-pages@v3.1.0
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" 
/>
<img 
    align="left" 
    alt="React"
    title="React" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/react/react-original.svg" 
/>
