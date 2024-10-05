# GitHub Actions

[![Repo](https://img.shields.io/badge/GitHub-repo-blue?logo=github&logoColor=f5f5f5)](https://github.com/michelmetran/github_actions_personal)

É possível definir ações ao fazer operações nos repositórios utilizando o [Git Actions](https://github.com/marketplace?type=actions).

O presente repositório visa testar algumas ações ao fazer um _push_, além de outras operações, em repositórios!

sasasas

<br>

## Repositórios de Testes

- https://github.com/michelmetran/github_actions_personal (principal)
- https://github.com/michelmetran/github_actions_personal_output
- https://github.com/open-dsa/github_actions_org_private
- https://github.com/open-dsa/github_actions_org_public

<br>

---

## Glossário

- PAT token (Personal Access Token)

<br>

---

## Actions

### FTP

[<img alt="Deployed with FTP Deploy Action" src="https://img.shields.io/badge/Deployed With-FTP DEPLOY ACTION-%3CCOLOR%3E?style=for-the-badge&color=2b9348">](https://github.com/SamKirkland/FTP-Deploy-Action)

Ao fazer um _push_, é possível replicar o conteúdo para um **FTP**. Apenas para testar criei um _site gratuito_ usando o [br.000webhost.com](https://br.000webhost.com/), que disponibiliza um _FTP Server_ gratuito.

- [Deploy Automático com GitHub Actions em Hospedagem Compartilhada em 12 minutos](https://www.youtube.com/watch?v=3cLbh-k2qKk)
- [GitHub Action FTP Deploy](https://github.com/marketplace/actions/ftp-deploy)
- [Site](https://djangotestmiche.000webhostapp.com/)

<br>

---

### Upload Artifact

Cria um artifício

<br>

---

### First Interaction

Arquivo _greetings.yml_

Quando um usuário interagir (criando um _Issue_ ou _Pull Request_), receberá uma mensagem.

- [GitHub Action First interaction](https://github.com/marketplace/actions/first-interaction)

<br>

---

### PyPi

No projeto que fiz, sobre o [gerador_endereco](https://github.com/open-dsa/gerador_endereco) usei um Git Action que cria um pacote no PyPi!, o repositório oficial do Python.

<br>

---

### Python

Com auxílio do GitAction _python-script.yml_ é possível executar um código em python, utilizando algum código presente no repositório.

Observações:

- Roda em repositório privado!

<br>

---

### Order

Antes eu definia os workflows individualmente e criava um artifício que um só rodaria após o outro estar completo.
Descobri uma maneira mais correta com o uso do _needs_. Apliquei isso no repositório "sp_piracciaba"

- [How to set the order of your GitHub Action jobs](https://www.youtube.com/watch?v=JNqButrPjcE)

<br>

---

## Token

Descobri que se eu "sobrepor" o token eu consigo copiar entre repositórios privados!!!!!!!!!!!!!!!!

![](https://i.imgur.com/itPNspB.png)

<br>

---

## Referências

- https://github.com/peter-evans/create-pull-request (Estudar)
