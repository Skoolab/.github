# Skoolab | Organização

Bem-vindo ao repositório `.github` da Skoolab, uma __EdTech inovadora__ que visa transformar o processo educacional para a Geração Z e futuras, oferecendo uma experiência de aprendizado interativa, personalizada e gamificada.

<hr>

O repositório .github é um repositório especial que pode ser criado em uma organização ou conta de usuário no GitHub. Ele é utilizado para armazenar arquivos de configuração e metadados que podem ser aplicados a todos os repositórios da organização ou do usuário. Esses arquivos podem incluir templates de issues, templates de pull requests, workflows do GitHub Actions, arquivos de configuração de segurança, entre outros.

### Principais usos de um repositório .github para organizações:

1. Templates de Issues e Pull Requests:

  Você pode criar templates de issues e pull requests que serão aplicados automaticamente a todos os repositórios da organização. Isso ajuda a padronizar a forma como os colaboradores reportam problemas ou sugerem mudanças.
  Arquivos típicos:
  .github/ISSUE_TEMPLATE.md
  .github/PULL_REQUEST_TEMPLATE.md

2. GitHub Actions Workflows:

  O repositório .github pode conter workflows do GitHub Actions que podem ser reutilizados em outros repositórios da organização. Isso facilita a automação de tarefas como testes, deploys e integrações contínuas.
  Arquivo típico:
  .github/workflows/<workflow>.yml

3. CODEOWNERS:

  O arquivo CODEOWNERS pode ser usado para definir quem é responsável por revisar mudanças em partes específicas do código em todos os repositórios da organização.
  Arquivo típico:
  .github/CODEOWNERS

4. SECURITY.md:

  O arquivo SECURITY.md pode ser usado para documentar as políticas de segurança da organização, como o processo de reportar vulnerabilidades.
  Arquivo típico:
  .github/SECURITY.md

5. FUNDING.yml:

  O arquivo FUNDING.yml permite que você configure links para plataformas de financiamento, como GitHub Sponsors, para todos os repositórios da organização.
  Arquivo típico:
  .github/FUNDING.yml

6. Dependabot:

  Arquivos de configuração do Dependabot podem ser armazenados no repositório .github para gerenciar automaticamente as dependências de todos os repositórios da organização.
  Arquivo típico:
  .github/dependabot.yml

### Benefícios de usar um repositório .github para organizações:

**Centralização**: Permite centralizar configurações e templates que serão aplicados a todos os repositórios da organização, evitando a necessidade de duplicação de arquivos em cada repositório individual.
**Padronização**: Garante que todos os repositórios sigam as mesmas práticas e padrões, como templates de issues e pull requests, o que facilita a colaboração e a manutenção.
**Automação**: Facilita a automação de processos com GitHub Actions e Dependabot, aplicando as mesmas regras e workflows a todos os repositórios.

### Como criar um repositório .github para uma organização:

1. Acesse a página da sua organização no GitHub.
2. Crie um novo repositório com o nome .github (o nome deve ser exatamente esse).
3. Adicione os arquivos de configuração desejados dentro da pasta .github no repositório.

### Exemplo de estrutura de um repositório .github:

```
.github/
│
├── ISSUE_TEMPLATE/
│   ├── bug_report.md
│   └── feature_request.md
│
├── PULL_REQUEST_TEMPLATE.md
├── CODEOWNERS
├── SECURITY.md
├── FUNDING.yml
└── workflows/
    ├── ci.yml
    └── deploy.yml
```
Esse repositório é uma maneira eficiente de gerenciar e aplicar configurações em escala para todos os repositórios de uma organização no GitHub.
