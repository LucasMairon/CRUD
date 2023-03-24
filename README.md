# Crud 2023-03-01

## Comandos github
- `git init`
    - cria a pasta .git e inicializa o repositorio
- `git add` ou (Stage Changes)
    - Adiciona as alterações dos arquivos em uma um espaço
    - usando o `git add .` adiciona todos os arquivos nesse espaço
- `git commit "mensagem do commit"`
    - salva as alterações feitas no `git add` e da um nome para essas alterações
        - a mensagem que enviamos junto do commit é o nome que será dado as alterações
- `git status`
    - mostra o status dos codigos/arquivos que estamos guardando para enviar ao github
- `git remote add origin https://github.com/LucasMairon/CRUD.git`
    - sincroniza o projeto local com o repositorio remoto que está no github(o nome do usuario e do repositorio devem ser alteraos para o de quem está fazendo)
- `git push -u origin main`
    - origin: destino(no caso ORIGIN è o github que foi adicionado quando fizemos o remote)
    - main: a ramificação ou branch que queremos atualizar
- `git pull`
    - o git pull traz as inforações que estão no github para o projeto localmente
- `git checkout -b nome-da-branch`
    - cria uma nova branch com o nome escolhido e já coloca o usuario na branch
- `git checkout nome-da-branch`
    - muda para a branch que foi dada o nome, se ela ja existir
- `git merge nome-da-branch`
    - junta a branch atual com a que foi informado o nome

### Se o usuario começou tudo pelo github
- `git clone link-do-repositorio-que-queremos-clonar`

## Qualidade
- Linter
    - ESLINT
        - Padrão Airbnb
    
