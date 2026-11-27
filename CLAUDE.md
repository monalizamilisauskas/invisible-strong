# Instruções para o Claude

- Converse com a dona da loja em **português**. O texto que o visitante vê no site é em **inglês**.
- Este repositório é o tema Shopify (Horizon). Blogs, posts, metacampos, menus, produtos e coleções ficam no **painel da Shopify**, não no código.
- **Sempre que alguma tarefa exigir uma ação no painel da Shopify**, entregue no fim da resposta um **prompt pronto para colar no Sidekick** (o assistente de IA da Shopify), dentro de um bloco de código. O prompt deve:
  - ser escrito em português, com os textos do site em inglês entre aspas;
  - listar cada passo com os valores exatos (nomes, handles, tipos, modelos de tema);
  - pedir que o Sidekick diga o que não conseguiu fazer e dê o caminho manual no painel.
- **Mudanças no tema:** a dona da loja autorizou o Claude a **abrir o pull request e fazer o merge na `main`** sozinho, publicando direto na loja. Ao terminar:
  1. rode o Theme Check e gere a prévia (capturas de tela);
  2. antes do merge, confira se a `main` recebeu commits do editor da Shopify nos mesmos arquivos (para não sobrescrever edições dela) — se houver conflito, pare e avise;
  3. abra o pull request, faça o merge e envie as capturas de tela, dizendo que já está no ar.
  Se ela não gostar de algo, corrija com um novo pull request e merge.

## Fluxo da série "Behind the Strength" (Diário Real)

A dona da loja envia o relato do dia **em português** (do jeito que sair, com ou sem data). O Claude faz o resto:

1. **Traduz para o inglês** com fidelidade ao tom pessoal e acolhedor, corrigindo apenas deslizes de digitação/gramática. Se houver dúvida de sentido, pergunta antes.
2. **Organiza o post** com:
   - título em inglês;
   - etiqueta do dia (tag), ex.: `Low-spoon day`, `A gentle day`, `Flare day`, `Small win`;
   - resumo (1–2 frases que dão vontade de ler);
   - meta descrição com até 160 caracteres;
   - endereço curto em inglês (handle);
   - "Diary question": mensagem final de acolhimento + pergunta ao leitor (sai do corpo do texto);
   - frase de destaque formatada como citação (`<blockquote>`);
   - conteúdo em HTML (`<p>` por parágrafo), para colar no botão `</>` do editor.
   - Data: a informada; se nenhuma, a data de hoje.
3. **Entrega um prompt completo para o Sidekick**, sem nenhum campo de exemplo, que cria o post no blog "Behind the Strength" com modelo de tema `diary`, visível. Entrega também o HTML do conteúdo à parte, como alternativa manual.
4. Lembra de conferir na barra lateral: Blog = Behind the Strength, Modelo = diary, Visível.

O Claude não tem acesso ao painel da Shopify: quem publica é o Sidekick, ou a dona da loja à mão, com o que o Claude prepara.
