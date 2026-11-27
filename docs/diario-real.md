# Behind the Strength — série "Diário Real"

Relatos curtos e reais sobre a rotina com fibromialgia. O site é em inglês, então tudo o que o visitante vê fica em inglês.

## Como funciona

| O quê | Onde fica |
|---|---|
| Visual da listagem (`/blogs/behind-the-strength`) | `sections/diary-list.liquid` + `templates/blog.diary.json` |
| Visual de cada relato | `sections/diary-article.liquid` + `templates/article.diary.json` |
| **Os textos** | Painel da Shopify › Conteúdo › Posts do blog (não ficam no código) |

O tempo de leitura e o trecho do card são calculados automaticamente.

## Configuração única no painel da Shopify

> Antes: estes arquivos precisam chegar ao tema publicado. Faça o merge da branch na `main` (que está ligada à loja), ou conecte a branch como tema de pré-visualização em Loja virtual › Temas › Adicionar tema › Conectar do GitHub.

1. **Campo da pergunta final** — Configurações › Dados personalizados › **Posts do blog** › Adicionar definição
   - Nome: `Diary question`
   - Namespace e chave: `custom.diary_question`
   - Tipo: **Texto de várias linhas** › Salvar
2. **Criar o blog** — Conteúdo › Posts do blog › **Gerenciar blogs** › Adicionar blog
   - Título: `Behind the Strength` (o endereço fica `/blogs/behind-the-strength`)
   - Comentários: **Permitidos, aguardando moderação** (os leitores respondem à pergunta do relato)
   - Modelo de tema: **`diary`** › Salvar
3. **Menu** — Conteúdo › Menus › **Main menu** › Adicionar item de menu
   - Nome: `Blog` (claro para qualquer visitante; o título da página continua "Behind the Strength") · Link: Blogs › Behind the Strength › Salvar
4. **Primeiro relato** — siga "Como publicar um novo dia" abaixo, usando o texto pronto no fim deste arquivo.

## Como publicar um novo dia

Conteúdo › Posts do blog › **Adicionar post do blog**:

1. **Título** — o título do dia.
2. **Conteúdo** — o relato, um parágrafo por bloco. Para uma frase de destaque (ex.: "Come on, you can do this. Just one more day."), selecione-a e use o botão de **citação**: fica em roxo, com a barra dourada. A primeira letra do relato ganha destaque automático.
3. **Pergunta final** — no fim da página, em *Metacampos* › **Diary question**: a mensagem de acolhimento + a pergunta. Se ficar vazio, aparece "How did your day begin today?".
4. **Etiqueta do dia** — em *Tags*, escreva o humor do dia (ex.: `Low-spoon day`, `A gentle day`, `Flare day`, `Small win`). A primeira tag aparece como etiqueta dourada no card e no relato.
5. **Imagem em destaque** — opcional. Sem foto, o card mostra a ilustração das colheres.
6. Na lateral: **Blog** = `Behind the Strength`, **Modelo de tema** = `diary`, **Visibilidade** = Visível (ou agende uma data).
7. Salvar.

Dica: escreva em português, traduza para o inglês e cole a versão em inglês.

## Foto, CTA e produto em destaque (editor de temas)

A foto da autora já vem configurada com a sua foto da página inicial. Para trocar: Personalizar › modelo de blog **diary** (topo da listagem) e modelo de post de blog **diary** (quadro "With love, Monaliza").

Loja virtual › Temas › Personalizar › escolha o modelo de post de blog **diary**. Na seção *Diary entry*:

- **Soft call to action** (já vem ativo): "Carry a reminder of your strength → Find Your Piece", que leva à coleção *Gifts that say I believe you*. Dá para editar os textos, trocar o link ou esconder o bloco.
- **Featured product** (opcional): clique em *Adicionar bloco* › Featured product e escolha uma joia.

Os dois blocos valem para todos os relatos.

---

## Primeiro relato — pronto para colar

**Título**

Just one more day: what no one sees before I get out of bed

**Data de publicação:** 27/11/2026  
**Tag:** Low-spoon day

**Conteúdo**

Today was one of those hard days. Hard even to get out of bed, because my body, after a night of poor sleep, was still on high alert.

My husband, who was already awake, just kept asking: "Aren't you getting up?"

Completely drained, I couldn't say a single word. I just wanted to stay there, lying curled up, waiting for the pain to ease a little.

And I did. Not for one hour, but for two — gathering the energy to do something that seems simple to everyone else: get up and have a cup of coffee.

In my head, it was a silent battle. On one side, a voice said: "Go back to bed." On the other, another one insisted: "No. You need to find the strength to go work out."

Some time later, there I was. Walking under a cloudy sky, repeating the same words to myself, step after step:

"Come on, you can do this. Just one more day."  ← use o botão de citação nesta linha

**Diary question (metacampo)**

If today your only progress was getting out of bed and having a cup of coffee, know that it already takes a kind of strength few people understand. How did your day begin today?
