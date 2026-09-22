# Git e GitHub

## Comandos

### 🏫 Curso: configuração local

```sh
# Configuração (apenas uma vez)
git config --local user.name "adrianoGomes2010"
git config --local user.email "adrianogsthiago16@gmail.com"

# Fluxo do README
git pull
git status
git add .
git commit -m "Melhora o README do projeto"
git push
```

### 🏠 Casa: configuração global ou local

Use `--global` quando somente você utiliza Git no computador. Se outra pessoa usa Git/GitHub no mesmo PC, troque apenas `--global` por `--local` dentro da pasta do projeto.

```sh
# Configuração (apenas uma vez)
git config --global user.name "nomedeusuariodoaluno"
git config --global user.email "nomedeusuariodoaluno@email.com"

# Fluxo do README
git pull
git status
git add .
git commit -m "Melhora o README do projeto"
git push
```

Para um repositório novo ainda sem conexão com o GitHub:

```sh
git branch -M main
git remote add origin https://github.com/nomedeusuariodoaluno/nomedorepositorio.git
git push -u origin main
```

O `git status` confere o que foi alterado, preparado ou ainda está pendente antes do `push`.