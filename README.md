# Desafio GitHub-Markdown
## Contribuindo para o Repositório

Este documento explica o processo de fazer um fork de um repositório, fazer alterações (commits), criar um pull request e fazer o merge no repositório principal. Este fluxo de trabalho foi executado pelo usuário do GitHub **caio-GPT** (conta secundária que criei utilizando outro endereço de e-mail)com o repositório principal de propriedade de **caio-videmelo**.

## Guia Passo a Passo

### 1. Fazendo Fork do Repositório

1. **Navegar até o Repositório**: Através da conta caio-GPT, naveguei até o repositório https://github.com/caio-videmelo/desafio-github-markdown de **caio-videmelo** para o qual desejava contribuir.

2. **Fazer Fork do Repositório**:
   - Cliquei no botão "Fork" no canto superior direito da página. Isso criou uma cópia do repositório na conta **caio-GPT** do GitHub.

### 2. Clonando o Fork

1. **Clonar o Repositório**:
   - Na conta **caio-GPT** naveguei até o repositório forkado, `https://github.com/caio-GPT/desafio-github-markdown`.
   - Cliquei no botão "Code" e copiei o URL.

   ```bash
   git clone https://github.com/caio-GPT/repository-name.git
   ```

2. **Navegar até o Diretório do Repositório**:
  ```bash 
  cd repository-name
   ```

3. ## Fazendo Alterações:
    3.1. Criar uma Nova Branch:
        É uma boa prática criar uma nova branch para as alterações.
```bash
git checkout -b nome-da-branch
```

    3.2. Editar os Arquivos:

        Abri o repositório no editor de código e fiz as alterações necessárias.

    3.3. Fazer Commit das Alterações:
```bash
git add .
git commit -m "Descrição das alterações"
```

4. ## Enviando as Alterações para o GitHub
    4.1. Enviar as Alterações:
          ```bash
          git push origin nome-da-branch
            ```
5. Criando um Pull Request
    5.1. Fui para o Repositório Forkado no GitHub:

          Naveguei até https://github.com/caio-GPT/desafio-github-markdown.

    5.2. Criar Pull Request:

          Clique no botão "Compare & pull request".

    5.3. Adicionei um título descritivo e uma descrição para o seu pull request explicando as alterações feitas.

          Enviar o Pull Request:

    5.4. Cliquei no botão "Create pull request".

6. Fazendo Merge do Pull Request
Loguei na conta principal, **caio-videmelo**, e naveguei até o Repositório Principal: https://github.com/caio-videmelo/desafio-github-markdown.

    6.1. Revisar o Pull Request:

          Cliquei na aba "Pull requests".

          Selecionei o pull request criado por caio-GPT.

    6.2. Fazer Merge do Pull Request:

          Revisei as alterações e clique no botão "Merge pull request".

          Confirmei clicando em "Confirm merge".

    6.3. Excluir a Branch (Opcional):

          Após o merge, exclui a branch para manter o repositório organizado.
            ```bash
            git push origin --delete nome-da-branch
            ```

7. Sincronizando o Fork

    7.1. Naveguei até https://github.com/caio-GPT/desafio-github-markdown.

    7.2. Buscar as Últimas Alterações:
          ```bash
          git fetch upstream
         ```

   7.3. Fazer Merge das Alterações:
          ```bash
          git checkout main
          git merge upstream/main
          git push origin main
         ```
   
## Conclusão

Consegui fazer um fork, realizar alterações (commits), criar um pull request e fazer o merge das alterações no repositório principal. Este fluxo de trabalho garantiu um processo de colaboração quee mantém o repositório organizado.

Se você tiver alguma dúvida ou precisar de mais assistência, sinta-se à vontade para entrar em contato!

PrintScreens da realização do desafio:

![PrintScreen](https://github.com/user-attachments/assets/ff39129b-c13a-4a74-a0f4-d28942bd5f80){:width="600px"}
![PrintScreen1](https://github.com/user-attachments/assets/8f9abcb9-3aa6-4de5-b8d7-6aaf7e9e92c1){:width="600px"}
![PrintScreen2](https://github.com/user-attachments/assets/913d2ecc-39d0-4c79-adde-8ca5d25a6cb9){:width="600px"}
![PrintScreen3](https://github.com/user-attachments/assets/9f1db144-ecd6-4a81-9b3d-e31cf4b51608){:width="600px"}
![PrintScreen4](https://github.com/user-attachments/assets/1dd4fd0d-f4df-47d6-b791-b109d7e535b5){:width="600px"}
![PrintScreen5](https://github.com/user-attachments/assets/5d1676ef-1869-486e-a78c-4e2c7aa10077){:width="600px"}
![PrintScreen6](https://github.com/user-attachments/assets/5c181ed1-c2a9-4de5-8153-b71b6560c226){:width="600px"}
![PrintScreen7](https://github.com/user-attachments/assets/5a9098ad-e7f9-47fd-98e0-741a536490cf){:width="600px"}
![PrintScreen8](https://github.com/user-attachments/assets/0e7ac262-75af-4674-a8dd-423a64b8e952){:width="600px"}

# Resultado Final:

# 👋 Hi, I'm Caio V. I. de Melo (aka @caio-videmelo)

## About Me

I am a psychologist with an MSc in Mental Health from Brazil, currently transitioning into the field of Data Science and Development. My journey into tech is driven by my belief in leveraging data to drive impactful solutions, particularly within the health sciences domain. I am passionate about integrating technology with healthcare to create innovative and efficient solutions.

## Skills and Interests

:trophy: Badges: ![badge-GPT](https://github.com/user-attachments/assets/bd4b4a71-6a20-48e5-9649-f715eae614f3)

**Programming Languages**: Python, R, JavaScript

**Technologies**: SQL

**Areas of Expertise**: Data Science, Statistics, Mental Health

## Current Focus

🌱 I am currently enhancing my skills in JavaScript and Python to broaden my expertise in data-driven development.

## Collaboration

💞️ I am eager to collaborate on projects related to Data Science, especially those intersecting with the health sciences. I believe in the transformative power of technology in healthcare and am enthusiastic about contributing to innovative projects in this field.

## Courses and Certifications

| Courses                                               | Certificates                                              |
|-------------------------------------------------------|-----------------------------------------------------------|
| Programming Logic Fundamentals                        | [Certificate1](https://hermes.dio.me/certificates/cover/IKZWS7UF.jpg) |
| Practical Applications of Artificial Intelligence     | [Certificate2](https://hermes.dio.me/certificates/cover/PSAOKYWW.jpg) |
| Using ChatGPT as a Programming Copilot                | [Certificate3](https://hermes.dio.me/certificates/cover/VTDQ3DSN.jpg) |
| Using ChatGPT to Refactor Code                        | [Certificate4](https://hermes.dio.me/certificates/cover/Q6UFDRJT.jpg) |
| ChatGPT Essentials                                    | [Certificate5](https://hermes.dio.me/certificates/cover/X7MNPJHM.jpg) |
| Effective Prompts for ChatGPT                         | [Certificate6](https://hermes.dio.me/certificates/cover/JR70LQWJ.jpg) |

## GitHub Stats

![caio-videmelo's GitHub stats](https://github-readme-stats.vercel.app/api?username=caio-videmelo&show_icons=true&theme=tokyonight)

## Get in Touch

📫 You can reach me via email at caio.videmelo@gmail.com.

## Personal Details

😄 Pronouns: He/His

⚡ Fun Fact: Despite my background in psychology, I am deeply passionate about becoming a developer in Data Science.

## Projects

Feel free to explore my repositories to see the projects I'm working on and have contributed to.
