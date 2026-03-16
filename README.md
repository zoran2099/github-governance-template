# Template de Governança de Commits e Releases 

Este template inclui:

- GitHub Actions para PR e release
- SonarQube + JaCoCo
- Gitleaks
- semantic-release
- commitlint
- gitlint
- template de PR
- templates de mudança (`feature.md`, `bugfix.md`, `hotfix.md`, etc.)
- exemplo de `pom.xml` com JaCoCo e Sonar

## Segredos/variáveis esperados no GitHub

- `SONAR_TOKEN`
- `SONAR_HOST_URL`
- `GITLEAKS_LICENSE` (opcional, dependendo da sua estratégia/licença)

O `GITHUB_TOKEN` já existe por padrão nas GitHub Actions.

## Dependências locais opcionais

### Node (para commitlint + semantic-release)

```bash
npm install
```

### Python (para gitlint)

```bash
pip install gitlint
```

## Convenção recomendada de merge

- `squash merge`
- título do PR no padrão Conventional Commits

## Observação

O workflow de release abaixo foi desenhado para `main`.
Se você quiser release por `release/*` ou `master`, ajuste o gatilho no arquivo de workflow e o campo `branches` do `.releaserc.json`.
