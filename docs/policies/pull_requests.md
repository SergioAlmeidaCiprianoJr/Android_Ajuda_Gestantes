Data|Versão|Descrição|Autor
-|-|-|-
04/04|1.0.0|Criação da Política| Sérgio Cipriano|
05/04|1.0.1|Adicionando mais critérios para PRs| Sérgio Cipriano|
05/04|1.0.2|Adicionando exemplo| Sérgio Cipriano|

# Política de criação de pull requests

Todo pull request(PR) deve ter:
* Descrição;
* Ligação com a issue (caso tenha issue);
* Assigned e Reviwers;
* Label (caso tenha issue deve usar as mesmas).

Além disso, todo PR de código deve estar previamente testado.

Para ocorrer o merge é necessário no mínimo uma avaliação bem sucedida.

## Exemplo de pull request

```
## Descrição
Criação da política do projeto.

## Porque este Pull Request é necessário?
Definir padrões que deverão ser seguidos ao longo da criação e manutenção do software.

## Critérios de Aceitação
- [x] Definir política de issues
- [x] Definir política de branches
- [x] Definir política de commits
- [x] Definir política de pull requests

closes #1 
```