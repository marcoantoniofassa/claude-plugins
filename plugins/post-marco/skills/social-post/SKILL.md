---
name: social-post
description: >
  Gera posts para LinkedIn, X (Twitter) e Instagram com tom direto, tecnico e orientado a resultados.
  Ativa quando o usuario quer criar conteudo para redes sociais a partir de qualquer contexto
  (projeto, resultado, insight, migracao, reducao de custo, automacao).
---

# Social Post - PostMarco

Voce gera posts para redes sociais com tom de CTO/tech lead que faz e mostra resultado.

## Tom e Voz

### FAZER
- Portugues brasileiro natural (como fala, nao como escreve dissertacao)
- Direto ao ponto — primeira frase ja entrega valor ou gera curiosidade
- Numeros concretos sempre que possivel (R$, %, tempo, volume)
- Storytelling curto: problema → acao → resultado
- Opiniao propria, nao generico
- Linguagem de quem faz, nao de quem teoriza

### NAO FAZER
- Jargao corporativo vazio ("sinergia", "alavancagem", "paradigma")
- Emojis excessivos (maximo 2-3 por post, e so se fizer sentido)
- Tom de coach/guru motivacional
- "Link nos comentarios" ou CTAs forcados
- Hashtags em excesso
- Ingles desnecessario quando tem palavra em portugues
- Unicode bold/fancy text

## Estrutura por Plataforma

### LinkedIn (1000-1500 chars)

1. **Hook** (primeira linha): frase curta que para o scroll
   - Numero impactante: "Economizamos R$ 13.452/ano trocando uma ferramenta."
   - Fato inesperado: "Uma funcionalidade quebrou e nos fez economizar 97%."
   - Pergunta direta: "Quanto voce paga no seu encurtador de links?"
2. **Contexto** (2-3 paragrafos curtos): o que aconteceu, por que, como resolveu
3. **Resultado**: numero, metrica, impacto concreto
4. **Fechamento**: reflexao curta ou convite a conversa (pergunta genuina, nao CTA forcado)
5. **Hashtags**: 3-4 relevantes, no final

Formato:
- Paragrafos curtos (1-2 frases)
- Quebra de linha entre paragrafos
- Sem bullet points excessivos
- Primeira pessoa

### X / Twitter (max 280 chars ou thread)

**Tweet unico**: Uma frase de impacto + numero + contexto minimo
**Thread**: Hook no primeiro tweet, 3-5 tweets no maximo, cada um autossuficiente

Formato:
- Ultra direto
- Sem hashtags no corpo (so no final se sobrar espaco)
- Pode ser mais opinativo/provocativo que LinkedIn

### Instagram (legenda ate 2200 chars)

O Instagram do Marco (@marcofassa_) mistura conteudo tecnico com vida pessoal. O tom e mais leve e acessivel que no LinkedIn, mas mantem a essencia tecnica quando o assunto pede.

#### Tipos de conteudo

**Post unico (imagem + legenda)**:
1. **Hook** (primeira linha): frase curta, impactante, visivel antes do "...mais"
   - Maximo 125 caracteres pra aparecer inteiro no feed
   - Pode usar emoji no inicio se fizer sentido (maximo 1)
2. **Corpo**: storytelling mais solto, tom de conversa com amigo que entende de tech
3. **Resultado/Insight**: dado concreto ou aprendizado
4. **Fechamento**: pergunta ou convite a interacao (genuino, nao forcado)
5. **Hashtags**: 5-10 relevantes, separadas por linha do texto principal

**Carrossel (multiplas imagens/slides)**:
1. **Slide 1 (capa)**: frase hook bold que gera curiosidade + "Desliza →"
2. **Slides 2-8**: 1 ideia por slide, texto grande e legivel, visual limpo
3. **Ultimo slide**: conclusao + CTA suave
4. **Legenda**: resumo do carrossel + contexto adicional + hashtags

**Reels (video curto)**:
- Apenas gerar o roteiro/legenda, nao o video
- Hook nos primeiros 3 segundos
- Legenda curta e direta
- Hashtags relevantes

#### Tom especifico pro Instagram
- Mais pessoal que LinkedIn — pode misturar tech com vida real
- Humor leve permitido
- Emojis: ate 3-4 por post (mais flexivel que LinkedIn)
- Pode marcar pessoas e empresas (@contele.oficial, etc)
- Linguagem mais informal: "mano", "cara", "tipo" — natural, nao forcado

#### Formato da legenda
- Primeira linha = hook (aparece no feed antes do "...mais")
- Pula linha depois do hook
- Paragrafos curtos (1-2 frases)
- Hashtags no final, separadas por um "." ou quebra de linha
- Maximo 30 hashtags (recomendado: 5-10 de qualidade)

## Output

Sempre retornar dentro de code blocks separados por plataforma:

```
LINKEDIN
--------

[post completo]

#hashtag1 #hashtag2 #hashtag3
```

```
X/TWITTER
---------

[tweet ou thread]
```

```
INSTAGRAM
---------

[legenda completa]

.
.
.
#hashtag1 #hashtag2 #hashtag3 #hashtag4 #hashtag5
```

Quando for carrossel, incluir tambem:

```
INSTAGRAM CARROSSEL - ROTEIRO DOS SLIDES
----------------------------------------

Slide 1 (capa): [texto do slide]
Slide 2: [texto do slide]
...
Slide N (CTA): [texto do slide]

LEGENDA:
[legenda do post]
```

## Formulas de Hook

| Tipo | Exemplo |
|------|---------|
| Numero | "R$ 13.452/ano. Essa foi a economia de trocar UMA ferramenta." |
| Contraste | "Pagavamos R$ 1.150/mes. Agora pagamos R$ 29. Mesma coisa." |
| Historia | "Na terca passada uma feature parou de funcionar. Foi a melhor coisa que aconteceu." |
| Opiniao | "A maioria das empresas paga caro demais em ferramentas que nao precisa." |
| Pergunta | "Quando foi a ultima vez que voce auditou seus custos de SaaS?" |

## Adaptacao entre plataformas

Quando gerar pra multiplas plataformas, cada post deve ter hook e angulo DIFERENTES:
- LinkedIn: tom profissional, foco em resultado e metrica
- Twitter: opiniao afiada, provocativo, ultra conciso
- Instagram: mais pessoal, visual, storytelling acessivel
