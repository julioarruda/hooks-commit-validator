# Git Hooks

Nesse repositório, você encontra dois Git Hooks, dentro do diretório [hooks](hooks).

Esses Hooks são utilizados para apoiar a padronização de Branches e também da mensagem de commits utilizados em seus projetos.

Para conseguir utilizar esses Hooks, você precisa seguir os seguintes passos:

```
git clone https://github.com/julioarruda/hooks.git

chmod +x /workspaces/hooks/hooks/pre-commit
chmod +x /workspaces/hooks/hooks/prepare-commit-msg

git config core.hooksPath /workspaces/hooks/hooks
```

# Sugestão de Uso

Você poderia criar um repositório centralizado, com todos os Hooks que sejam padrões para a empresa. Novas pessoas colaboradoras, devem baixar esse repositório centralizado, e configurar o diretório de Hooks da máquina para esse repositório central, garantindo que todas as pessoas sigam os mesmos passos.

.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.
.

baseado em: [https://dev.to/anibalardid/how-to-check-commit-message-and-branch-name-with-git-hooks-without-any-new-installation-n34](https://dev.to/anibalardid/how-to-check-commit-message-and-branch-name-with-git-hooks-without-any-new-installation-n34)
