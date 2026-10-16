# FATECH-PROJETOS

Projetos feitos para a **FATECH — Feira de Administração e Tecnologia
Mercadológica**, do Colégio Estadual Mendes Gonçalves (Guaíra-PR): cada turma
construiu sua própria loja de pedidos online para o dia da feira.

## 🔗 Sites

> Para os links abaixo funcionarem, ative o GitHub Pages em **Settings → Pages
> → Branch: `main` / `(root)`**. Depois disso cada pasta fica no ar sozinha,
> sem precisar de nada além de um `git push`.

| Site | Link | O que é |
|---|---|---|
| 🏠 **Divulgação Fatech** | [`fatech-website-3`](https://elianahippler.github.io/FATECH-PROJETOS/fatech-website-3/) | Site de divulgação da edição de 9 e 10/11/2023 |
| 🛒 **Fatech** | [`fatech`](https://elianahippler.github.io/FATECH-PROJETOS/fatech/) | Loja de pedidos — versão inicial |
| 🛒 **Fatech · 2º ADM** | [`fatech2adm`](https://elianahippler.github.io/FATECH-PROJETOS/fatech2adm/feira/) | Loja de pedidos da turma 2º ADM |
| 🛒 **Fatech · 4º ADM** | [`fatech4adm`](https://elianahippler.github.io/FATECH-PROJETOS/fatech4adm/) | Loja de pedidos da turma 4º ADM |
| 🛒 **Feira** | [`feira`](https://elianahippler.github.io/FATECH-PROJETOS/feira/) | Loja de pedidos — 25ª Feira Mercadológica |
| 🛒 **Feira · 1º ADM** | [`feira1adm`](https://elianahippler.github.io/FATECH-PROJETOS/feira1adm/) | Loja de pedidos da turma 1º ADM |
| 🛒 **Feira · 2º ADM** | [`feira2adm`](https://elianahippler.github.io/FATECH-PROJETOS/feira2adm/) | Loja de pedidos da turma 2º ADM |
| 🛒 **Feira · 4º ADM** | [`feira4adm`](https://elianahippler.github.io/FATECH-PROJETOS/feira4adm/) | Loja de pedidos da turma 4º ADM |
| 🌱 **Reino Plantae** | [`site`](https://elianahippler.github.io/FATECH-PROJETOS/site/) | Trabalho de Biologia (não é da Fatech — ver nota abaixo) |

Todas as lojas de pedidos (`fatech*`, `feira*`) seguem o mesmo molde: uma
página de boas-vindas com o botão **"Pedir"**, carrinho e finalização de
pedido — o que muda de turma pra turma é o cardápio e a identidade visual.

> **Nota sobre `fatech2adm`:** essa pasta tem um nível de pasta a mais por
> dentro (`fatech2adm/feira/index.html`, em vez de `fatech2adm/index.html`
> como as outras) — por isso o link dela aponta um nível mais fundo. Se quiser
> deixar igual às demais, é só mover o conteúdo de `fatech2adm/feira/` para a
> raiz de `fatech2adm/`.

> **Nota sobre `site`:** o commit que trouxe essa pasta está registrado como
> "Primeiro Projeto FATECH 2022", mas o conteúdo dela é sobre o Reino Plantae
> (trabalho de Biologia do 2º Técnico de Informática), sem relação óbvia com a
> feira. Mantive como está — só avisando pra você conferir se é mesmo isso que
> queria aqui, ou se foi parar neste repositório por engano.

## Pastas ou branches?

Fiquei com **pastas** (como já estava), não branches — pro seu objetivo de
"aparecer o link de cada site de cara" isso é o que funciona melhor:

- O GitHub Pages de um repositório só tem **uma** fonte ativa (uma branch +
  uma pasta) por vez. Se cada edição fosse uma branch, só uma ficaria no ar a
  cada momento — as outras exigiriam trocar a configuração do Pages pra
  visitar.
- Com pastas, todas ficam no ar **ao mesmo tempo**, cada uma com seu próprio
  link fixo, a partir de uma única configuração (`main` / `root`). É exatamente
  a tabela acima.
- Branches fazem mais sentido quando você quer **uma política de edição**
  diferente por versão (ex.: só o professor pode mexer na branch antiga) ou
  **não** quer todas as versões visíveis ao mesmo tempo — não é o seu caso.

Se quiser marcar "essa foi a versão apresentada no dia da feira tal", o jeito
mais limpo é uma **tag** do git (ex. `git tag feira-2024 <commit>`) — ela
carimba aquele ponto da história sem criar uma cópia paralela nem mudar o que
está no ar.
