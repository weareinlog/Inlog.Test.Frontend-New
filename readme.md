# Desafio Inlog - Vaga Frontend Developer
Implementar o redesign conceitual da página inicial do github proposto no layout, consumindo a API do Github para developers (REST API v3)
(seguir layout disponível na pasta assets do repositório).

- Sem requisitos de SEO;
- Deve funcionar apenas nos browsers mais atualizados;
- Não há necessidade de ser responsivo.

É permitido utilizar bibliotecas e frameworks javascript mas lembre-se, quanto menos código de
terceiros você utilizar, mais bem avaliado será.

## Requisitos ##
Ter perfil no github para consultar a API com autenticação.  
Exibir `dados do perfil`, `repositórios` e `organizações` de um determinado usuário na sidebar esquerda.  
Implementar filtragem na lista de repositórios do usuário da sidebar

- `Activity`: listar os eventos de um determinado usuário [endpoint](https://developer.github.com/v3/activity/events/)  
- `Repositories`: listar os repositórios do github com maior quantidade de stars ordenados por data da última atualização (pushed): [endpoint](https://developer.github.com/v3/search/#search-repositories)
- `Top users`: listar os usuários do github com maior número de repositórios e seguidores [endpoit](https://developer.github.com/v3/search/#search-users)

Para as três consultas acima, os itens devem ser paginados através do botão load more (10 itens por página)

---

#### O que vamos avaliar:
 - Capacidade de criar interfaces com alta fidelidade á partir de layouts/protótipos.
 - Semântica do seu código HTML
 - Estruturação do seu CSS de maneira reaproveitável e utilização de especificações mais recentes (`flexbox`, `grid layout`)
 - Boa lógica de programação e utilização de boas práticas no seu código javascript.

#### Restrições
 - Não utilize frameworks css. (Bootstrap e similares)

#### Bonus Points:
 -  Utilização de features da especificação ES6
 -  Automação com Npm scripts.

#### Submissão
 - Nos envie um link para download do seu código pelo email: beinlog@inlog.com.br


 **Api do Github**
 - Documentação: https://developer.github.com/v3/


# Boa Sorte!!!
