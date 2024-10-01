# aulaCEEPPLG

# Conceitos Básicos de Git e GitHub

## O que é Git?

O **Git** é um sistema de controle de versão distribuído, amplamente utilizado por desenvolvedores para gerenciar o histórico de mudanças de projetos. Ele permite rastrear as modificações no código, colaborar com outros desenvolvedores, e restaurar versões anteriores do projeto.

### Principais Conceitos do Git

- **Repositório (Repo)**: Um repositório é onde o Git armazena o histórico de um projeto. Pode ser local (no seu computador) ou remoto (hospedado em uma plataforma como o GitHub).
- **Commit**: Um commit é uma "foto" do seu projeto em um determinado momento. Ele inclui uma mensagem que descreve as mudanças feitas.
- **Branch**: Um branch é uma ramificação do código, permitindo que você trabalhe em diferentes funcionalidades ou correções de bugs sem alterar o código principal.
- **Merge**: O merge é o processo de unir mudanças de um branch para outro, geralmente da branch de funcionalidade para a branch principal.
- **Pull**: O pull é a ação de baixar as últimas atualizações de um repositório remoto para o seu repositório local.
- **Push**: O push envia as suas alterações do repositório local para o repositório remoto.

### Principais Comandos do Git

- `git init`: Inicia um novo repositório Git em um diretório.
- `git clone <url>`: Clona um repositório remoto para a máquina local.
- `git add <arquivo>`: Adiciona as mudanças do arquivo à área de stage (preparação para commit).
- `git commit -m "mensagem"`: Cria um commit com as mudanças preparadas e adiciona uma mensagem descritiva.
- `git status`: Mostra o status dos arquivos e mudanças.
- `git push`: Envia as alterações para o repositório remoto.
- `git pull`: Atualiza o repositório local com as mudanças do repositório remoto.
- `git branch`: Lista os branches ou cria um novo branch.
- `git checkout <branch>`: Troca para um branch específico.

## O que é GitHub?

O **GitHub** é uma plataforma de hospedagem de código baseada em Git que facilita a colaboração entre desenvolvedores. Ele permite que você armazene, compartilhe e colabore em projetos de forma remota.

### Funcionalidades do GitHub

- **Repositórios Remotos**: O GitHub armazena repositórios remotos que podem ser acessados por diferentes colaboradores.
- **Fork**: Permite copiar um repositório existente para sua conta GitHub e fazer modificações sem afetar o projeto original.
- **Pull Request (PR)**: Uma pull request é uma proposta de mudanças no código, feita a partir de um branch. Ela permite discutir e revisar o código antes de incorporar ao branch principal.
- **Issues**: Ferramenta para rastrear bugs, melhorias e outras tarefas relacionadas ao projeto.
- **Actions**: Permitem automatizar tarefas como testes e deploys através de pipelines de CI/CD (Integração Contínua e Entrega Contínua).

### Como Contribuir em um Projeto no GitHub

1. **Fork**: Faça o fork do repositório que deseja contribuir.
2. **Clone**: Clone o repositório forkado para a sua máquina local:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```
3. **Criar uma Branch**: Crie um branch para trabalhar nas alterações:
    ```bash
    git checkout -b minha-feature
    ```
4. **Fazer Commits**: Faça as alterações no código e crie commits:
    ```bash
    git add .
    git commit -m "Adiciona nova funcionalidade"
    ```
5. **Push para o GitHub**: Envie as alterações para o seu repositório remoto:
    ```bash
    git push origin minha-feature
    ```
6. **Abrir um Pull Request**: No GitHub, abra um Pull Request para que suas mudanças possam ser revisadas e, possivelmente, incorporadas ao projeto principal.

## Recursos Adicionais

- [Documentação Oficial do Git](https://git-scm.com/doc)
- [Documentação do GitHub](https://docs.github.com/)
- [GitHub Learning Lab](https://lab.github.com/): Cursos interativos para aprender Git e GitHub.

