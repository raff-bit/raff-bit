# Publicar o teu perfil README no GitHub

Este guia usa o perfil `raff-bit` e os ficheiros que acompanham este tutorial. O GitHub mostra um README no perfil quando existe um repositório público com o mesmo nome do utilizador e um `README.md` na raiz. [Documentação oficial](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/managing-your-profile-readme)

## Ficheiros preparados

- `README-profile-draft.md` — conteúdo do teu perfil.
- `assets/profile-banner.svg` — banner escuro, centrado, com Rafael Monteiro e C#.

Mantém o banner dentro da pasta `assets`, porque o README procura a imagem neste caminho: `./assets/profile-banner.svg`.

## 1. Confirma se já tens o repositório de perfil

1. Inicia sessão no [GitHub](https://github.com).
2. Abre o teu perfil em `https://github.com/raff-bit` e entra em **Repositories**.
3. Se já existir um repositório chamado `raff-bit`, abre-o e salta para o passo 3.
4. Se não existir, seleciona **New repository**.
5. Em **Repository name**, escreve exatamente `raff-bit`.
6. Escolhe **Public** e ativa **Add a README file**.
7. Seleciona **Create repository**.

Este repositório será público. Não coloques nele passwords, chaves de API, ficheiros `.env` ou dados privados.

## 2. Coloca o banner na pasta certa

1. Abre o repositório `raff-bit`.
2. Seleciona **Add file** → **Upload files**.
3. Arrasta a pasta `assets` que acompanha este tutorial para a página. Confirma que o caminho apresentado é `assets/profile-banner.svg`.
4. Escreve uma mensagem de commit, por exemplo `Add profile banner`.
5. Seleciona **Commit changes**.

Se o GitHub não aceitar a pasta, cria o ficheiro pela interface: seleciona **Add file** → **Create new file**, escreve `assets/profile-banner.svg` no campo do nome, copia o conteúdo do SVG local para o editor e confirma o commit. O GitHub também documenta a criação de ficheiros e subpastas pela interface web [aqui](https://docs.github.com/en/repositories/working-with-files/managing-files/creating-new-files).

## 3. Coloca o README no repositório

1. No teu computador, abre `README-profile-draft.md` num editor de texto.
2. Seleciona e copia todo o conteúdo.
3. No GitHub, abre o `README.md` do repositório `raff-bit` e seleciona o ícone de lápis (**Edit this file**). Se ainda não existir, usa **Add file** → **Create new file** e chama-lhe `README.md`.
4. Substitui o texto existente pelo conteúdo copiado.
5. Seleciona **Preview** e confirma se o banner aparece.
6. Escreve a mensagem `Update profile README` e seleciona **Commit changes**.

## 4. Confirma o resultado

1. Abre `https://github.com/raff-bit` numa nova página.
2. Confirma se o banner está centrado, o nome aparece como **Rafael Monteiro** e C# surge na linha de tecnologias.
3. Se o banner não aparecer, confirma no repositório que o caminho é exatamente `assets/profile-banner.svg` e que o README contém `./assets/profile-banner.svg`.
4. Podes ajustar a bio através do botão **Edit profile** no teu perfil. Sugestão: `Systems Engineering student @ ISEP | Software Engineering & Applied AI | Java, Python, C#, C/C++, PHP, SQL | Optimization & IoT`.

## 5. Adiciona e fixa os projetos

1. Publica os repositórios dos projetos que queres mostrar, depois de confirmar que não contêm segredos ou dados privados.
2. Atualiza no README os comentários HTML que dizem `Add the repository link here when available`, substituindo-os por links para os repositórios.
3. No teu perfil, escolhe **Customize your pins**, seleciona até seis repositórios públicos e guarda. [Passos oficiais para fixar repositórios](https://docs.github.com/en/account-and-profile/how-tos/profile-customization/pinning-items-to-your-profile)
4. Para o teu conjunto atual, a ordem sugerida é: Passadiços do Paiva, sistema de eventos Java, Meireles Connect.

A página de perfil e os repositórios públicos ficam acessíveis a qualquer pessoa. Não precisas de adicionar estatísticas ou um gráfico de contribuições externo: deixa o calendário nativo do GitHub mostrar a atividade real.
