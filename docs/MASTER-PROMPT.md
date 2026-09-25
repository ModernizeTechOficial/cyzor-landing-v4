# CYZOR V4 — MASTER PROMPT
## LANDING PAGE / LOW-FIDELITY → DESIGN SYSTEM → FINAL COMPOSITION → PRODUCTION ASSETS

---

# 0. OBJETIVO

Criar a nova landing page oficial da CYZOR com qualidade visual premium e identidade própria.

A página deve comunicar:

CYZOR = Neural Operating System for Business

Mas o resultado final precisa parecer uma experiência digital de produto real, e não:
- um banner;
- um poster;
- uma imagem conceitual;
- uma apresentação;
- um template SaaS;
- um conjunto de cards;
- uma arte de IA colocada dentro de uma página.

O processo deve separar rigorosamente:

ESTRUTURA → ESTILO → HTML → COMPOSIÇÃO VISUAL → ASSETS → CSS → POLIMENTO

A estrutura definida no wireframe é a fonte de verdade da composição.

# 1. REGRA ABSOLUTA DO PROCESSO

NÃO tente resolver tudo de uma vez.
NÃO gere a landing inteira como uma única imagem.
NÃO transforme o wireframe em uma arte bonita.
NÃO comece pelo HTML final.
NÃO gere assets antes de suas posições e dimensões estarem definidas.
NÃO altere a estrutura aprovada durante a implementação sem motivo técnico documentado.

O projeto deve passar por fases controladas.

## Ordem obrigatória

01 DISCOVERY
02 LOW-FIDELITY WIREFRAME
03 CARD VISUAL SYSTEM
04 HTML STRUCTURE
05 FINAL VISUAL COMPOSITION
06 USER APPROVAL — FINAL COMPOSITION
07 INDIVIDUAL ASSET GENERATION
08 BACKGROUND + CSS + DESIGN SYSTEM IMPLEMENTATION
09 ASSET INTEGRATION
10 MOTION + RESPONSIVE
11 ACCESSIBILITY + PERFORMANCE
12 VISUAL QA + POLISH
13 FINAL VALIDATION

# 2. REGRA DE PARADA

Existe apenas um checkpoint obrigatório com o usuário: APROVAÇÃO DA COMPOSIÇÃO VISUAL FINAL.

Até chegar nessa etapa, execute automaticamente:
Discovery → Wireframe → Card Style → HTML → Final Visual Composition.

Quando a composição visual final estiver pronta:
1. apresente a composição;
2. descreva brevemente o que foi definido;
3. peça ao usuário para confirmar o layout final;
4. PARE.

Não gere os assets finais antes da confirmação.
Não escreva o CSS final antes da confirmação.
Não integre os assets finais antes da confirmação.
Não avance automaticamente dessa etapa.

Após o usuário confirmar:
Continue automaticamente: Asset Generation → CSS → Integration → Motion → Responsive → Accessibility → Performance → Visual QA → Final Polish → Final Validation.
Depois da confirmação do layout final, não peça novas aprovações intermediárias.
Se algo falhar, corrija e continue.

# 3. RESET VISUAL

O projeto deve ser tratado como uma nova criação.
Não reutilizar landing anterior, wireframe anterior, composição anterior, HTML anterior, CSS anterior, assets anteriores, imagens anteriores ou interpretações anteriores.
As skills de UI/UX presentes em .agents/skills podem ser usadas como referência de construção, mas o layout desta execução deve nascer novamente deste processo.

# 4. DIREÇÃO DE PRODUTO

A CYZOR é uma plataforma modular de operação empresarial com CRM, ERP, Projects, People, Docs, BI, Automations, Finance, Products, Stock, POS, Agenda, AI Workforce e CYZOR AI Manager.

Conceito central:
empresa → módulos → dados → contexto → agentes → inteligência → decisão → ação

# 5. DIREÇÃO VISUAL

A direção final deve ser tecnológica, sofisticada, contemporânea, premium, neural, cinematográfica com controle, extremamente bem composta, orientada a produto e visualmente memorável.

Paleta base: #C8FF00, #030504, #080B0A, #111513, #F5F7F3, #8B938D.

O lime representa ativação, inteligência, sinal, estado, foco e ação. Não usar lime como preenchimento indiscriminado.

Evitar: cyberpunk, estética gamer, Web3, crypto, roxo/azul como linguagem principal de IA, excesso de neon, excesso de glow, glassmorphism genérico, gradientes aleatórios, grids decorativos sem função, excesso de cards, dashboards falsos, cérebro/robô/circuitos clichês, posterização, composição de banner, estética de thumbnail e arte de IA substituindo design de interface.

# 6. FASE 01 — DISCOVERY

Antes de qualquer criação visual, analisar proposta da CYZOR, arquitetura, módulos, AI Workforce, AI Manager, fluxo de dados, contexto, decisão, automações, produto, público, diferenciais reais, limitações e conteúdo que pode ser afirmado com segurança.

Criar docs/landing-v4-discovery.md.

A Discovery deve responder: O que a CYZOR é? Qual problema resolve? Como explicar isso rapidamente? Qual narrativa a landing deve seguir? Quais são as provas visuais necessárias? Quais informações devem ser HTML? Quais informações devem virar assets? Quais elementos precisam de interação? Quais são apenas atmosféricos? O que não deve aparecer?

Depois de concluir, seguir automaticamente para a Fase 02.

# 7. FASE 02 — LOW-FIDELITY WIREFRAME

ESTA É A FASE MAIS IMPORTANTE PARA A ESTRUTURA.

O wireframe NÃO é uma arte. O wireframe NÃO deve parecer um banner. O wireframe NÃO deve ser bonito. O wireframe deve parecer um projeto técnico de layout.

Usar somente fundo neutro, blocos, retângulos, linhas, círculos simples, grids, placeholders, texto de identificação, medidas, proporções e setas.
Pode usar apenas cinza, preto, branco e um tom discreto para marcação.

Não usar imagens finais, renders, efeitos 3D, glow, neon, texturas, partículas, ilustrações, fotografias ou composição cinematográfica.

O wireframe deve definir para cada seção: ordem, posição, largura, altura, grid, alinhamento, margens, espaçamento, hierarquia, headline, texto, CTA, cards, áreas de imagem, áreas de ilustração, áreas de gráfico, áreas de assets, navegação, footer e comportamento mobile.

MUITO IMPORTANTE: cada futura área visual deve ser explicitamente marcada.
Exemplos de rótulos: [ASSET: HERO-NEURAL-CORE], [ASSET: AI-WORKFORCE], [ASSET: PRODUCT-SCREEN], [ASSET: DATA-FLOW].

Cada placeholder deve conter nome, função, posição, largura aproximada, altura aproximada, proporção, comportamento desktop, comportamento mobile, tipo de arquivo esperado e fundo transparente ou não.

O wireframe deve deixar absolutamente claro: aqui ainda entrará um asset visual premium posteriormente.

# 8. ESTRUTURA DA LANDING

A estrutura deve ser definida pelo wireframe. Uma narrativa inicial possível é: Navigation, Hero, Product/System Introduction, System Architecture, AI Workforce, Module Ecosystem, Data → Context → Intelligence → Decision, Product Evidence, Security/Infrastructure, Decision/Business Impact, Final CTA, Footer.

A quantidade final de seções deve ser determinada pela Discovery e pelo wireframe. Não criar seções apenas para preencher espaço.

# 9. WIREFRAME NÃO É MOCKUP FINAL

O wireframe deve responder: Onde cada coisa ficará?
Não deve responder: Como a arte final ficará?
A arte final será criada posteriormente.

# 10. FASE 03 — CARD VISUAL SYSTEM

Depois que o wireframe estrutural estiver definido, criar uma imagem de referência exclusiva para o sistema visual dos cards.

Esta imagem NÃO é a landing. É um STYLE BOARD DE COMPONENTES.

Deve mostrar somente exemplos de card padrão, card destacado, card de métrica, card de módulo, card de informação, card de estado, card com imagem e card com ação.

O objetivo é definir cor, borda, espessura, raio, superfície, contraste, iluminação, glow, textura, profundidade, iconografia, tipografia, estados, hover, active, selected e disabled.

A imagem deve mostrar claramente: este é o padrão visual que será reutilizado em toda a landing.
Não criar uma página inteira nessa fase. Não criar banner. Não criar hero. Não criar composição de landing.

Documentar em docs/landing-v4-card-system.md.

# 11. FASE 04 — HTML STRUCTURE

Agora criar o HTML. Mas ainda NÃO é a landing final.

O HTML deve conter estrutura das seções, textos, títulos, CTAs, cards, grids, containers, navegação, footer e placeholders dos assets.

O HTML NÃO deve conter ainda imagens finais, renders finais, efeitos gráficos complexos, background artístico final, composição visual definitiva ou assets premium finais.

O HTML deve parecer um esqueleto funcional e navegável da landing.

Os placeholders devem respeitar exatamente as áreas definidas no wireframe.
Exemplo: <div class="visual-placeholder" data-asset="hero-neural-core"></div>

O HTML deve validar a estrutura antes da etapa visual.

# 12. FASE 05 — FINAL VISUAL COMPOSITION

Somente agora criar uma imagem de referência da landing final.

Esta imagem deve representar o HTML criado, a estrutura do wireframe, o sistema de cards, a direção de arte, a hierarquia, os espaços, a narrativa, a atmosfera final e os futuros assets premium.

IMPORTANTE: a imagem final deve parecer uma landing page completa apresentada em uma tela, e não um poster, banner, arte conceitual, moodboard ou coleção de imagens.

Deve mostrar a página como uma composição de interface real: navegação real, hero, conteúdo, cards, áreas de produto, imagens, espaçamento, ritmo vertical e continuidade entre seções.

Os elementos visuais premium podem aparecer nesta composição como representação final, mas continuam sendo apenas referência visual nesta fase. Ainda não são assets de produção.

# 13. CHECKPOINT ÚNICO — APROVAÇÃO DO LAYOUT FINAL

Depois de gerar a composição visual final: PARAR.

Apresentar a imagem da composição, um breve resumo, as principais decisões visuais e a lista dos assets que serão produzidos.

Perguntar exatamente em essência: Este é o layout final que devo transformar em produção?

Não avançar até o usuário confirmar. Não gerar assets de produção antes da confirmação. Não escrever o CSS final antes da confirmação. Não integrar os assets finais antes da confirmação.

# 14. FASE 07 — INDIVIDUAL ASSET GENERATION

Depois da aprovação, gerar os assets individualmente.

REGRA ABSOLUTA: UM ASSET = UMA GERAÇÃO.

Nunca gerar a landing inteira e recortar artificialmente depois. Nunca gerar uma única imagem contendo vários assets. Cada asset deve nascer separado.

Cada asset deve seguir exatamente o wireframe.

Antes de gerar cada um, verificar nome, função, largura, altura, aspect ratio, desktop size, mobile behavior, transparência, área segura, posição, contraste e relação com o card system.

Exemplos: hero-neural-core.webp, ai-workforce.png, system-network.png, data-flow.png, product-interface.webp, security-infrastructure.png, module-ecosystem.png.

Elementos isolados: PNG transparente ou SVG quando adequado. Cenas/áreas: WebP/AVIF.
Never place important copy inside an asset when HTML typography is more appropriate.


# 14.1 — REGRA ABSOLUTA DE TRANSPARÊNCIA DOS ASSETS

Todos os assets visuais individuais destinados a serem posicionados sobre o background da landing devem ser gerados com FUNDO TRANSPARENTE.

A transparência não é opcional.

## Regra

Quando o asset representar um elemento isolado, objeto, interface, núcleo, agente, módulo, ilustração, elemento neural ou componente visual:

- gerar com canal alpha;
- fundo 100% transparente;
- sem retângulo de fundo;
- sem cor sólida atrás do objeto;
- sem cenário incorporado;
- sem moldura artificial;
- sem background falso;
- sem gradient background que faça parte do arquivo;
- sem textura de fundo desnecessária.

O asset deve existir visualmente como um elemento independente, pronto para ser colocado sobre o background produzido pelo site.

## Exemplo correto

hero-neural-core.png

Deve conter somente o Neural Core e seus elementos visuais necessários, com o restante da imagem transparente.

## Exemplo incorreto

Uma imagem 1440×800 contendo Neural Core, fundo preto, grid, partículas, iluminação de toda a seção, texto e outros elementos da landing.

Isso é uma composição de seção, não um asset individual.

## Separação obrigatória

A arquitetura visual deve ser:

BACKGROUND DO SITE
+
ASSET TRANSPARENTE
+
HTML
+
CARDS
+
TIPOGRAFIA
+
MOTION

Nunca:

BACKGROUND EMBUTIDO NO ASSET
+
ASSET
+
BACKGROUND DO SITE

Isso evita caixas visuais, recortes perceptíveis, diferenças de preto, halos e perda de integração.

## Transparência e dimensões

Cada asset deve:

1. respeitar exatamente as dimensões definidas no wireframe;
2. respeitar o aspect ratio definido;
3. possuir canal alpha quando for um elemento isolado;
4. manter uma área segura adequada ao recorte;
5. não tocar desnecessariamente nas bordas do canvas;
6. não conter texto que deveria ser HTML;
7. não conter elementos pertencentes a outras seções.

## Formato preferencial

Para assets isolados:
- PNG RGBA quando transparência raster for necessária;
- SVG quando o elemento puder ser vetorial;
- WebP com alpha quando tecnicamente adequado.

Para backgrounds completos da página:
- não aplicar esta regra;
- backgrounds podem ser opacos e devem ser tratados separadamente do sistema de assets.

## VALIDAÇÃO OBRIGATÓRIA

Antes de integrar qualquer asset, verificar:

- possui alpha/transparência real;
- não possui background embutido;
- não possui halo ou borda artificial;
- não possui cor residual ao redor do objeto;
- não possui elementos pertencentes ao cenário;
- mantém qualidade na dimensão definida;
- funciona sobre o background oficial da landing.

Se qualquer item falhar:

REGENERAR O ASSET.

Não tentar esconder um fundo incorreto usando CSS.

## REGRA DE COMPOSIÇÃO

A composição visual final deve simular corretamente essa separação.

Na imagem de referência da landing, os assets devem parecer elementos posicionados sobre uma interface real, e não imagens retangulares coladas em uma página.

O objetivo é que, na implementação final, seja possível alterar o background da seção sem precisar recriar os assets.

# 15. ASSET DIMENSIONS

O wireframe define a dimensão de cada asset. Portanto: não gerar primeiro e decidir o tamanho depois.

Fluxo correto: WIREFRAME → DIMENSÃO → ASPECT RATIO → PROMPT DO ASSET → GERAÇÃO → VALIDAÇÃO → INTEGRAÇÃO.

Se o asset não respeitar a área definida: regenerar. Não corrigir deformando via CSS.

# 16. ASSET MANIFEST

Criar docs/landing-v4-assets.md.

Para cada asset registrar: Asset, Seção, Função, Desktop, Mobile, Ratio, Tipo, Transparente.

O manifest é obrigatório. Nenhum asset entra na produção sem estar no manifest.

# 17. FASE 08 — BACKGROUND + CSS + DESIGN SYSTEM

Somente após os assets existirem implementar background, surfaces, cards, borders, typography, grid, spacing, glow, shadows, gradients controlados, states, responsive tokens e animation tokens.

O CSS deve reproduzir o sistema visual definido na composição final. Não redesenhar a landing durante essa etapa.

# 18. FASE 09 — ASSET INTEGRATION

Substituir cada placeholder HTML pelo asset correspondente.
A posição deve seguir o wireframe. A dimensão deve seguir o manifest. A composição deve seguir a imagem final aprovada.

Se o resultado divergir visualmente: corrigir CSS/layout, não alterar silenciosamente a estrutura.

# 19. FASE 10 — MOTION

Motion deve existir apenas quando tiver função. Usar signal travel, glow response, node activation, reveal, hover, scroll progression, state transitions e subtle parallax quando necessário.

Evitar bounce, excesso de floating, efeitos contínuos sem função e animação em tudo.
Implementar prefers-reduced-motion.

# 20. FASE 11 — RESPONSIVE

Não reduzir simplesmente o desktop. Recompor.

Desktop: experiência espacial completa. Tablet: reduzir densidade preservando hierarquia. Mobile: priorizar mensagem, produto, prova visual, inteligência e CTA.

Cada asset deve possuir comportamento mobile definido no wireframe. Se necessário, alterar crop, mudar posição, empilhar, ocultar elementos secundários, trocar composição ou reduzir densidade. Nunca deformar assets.

# 21. FASE 12 — ACCESSIBILITY

Validar HTML semântico, keyboard navigation, focus visible, contraste, labels, alt text, touch targets, reduced motion, leitura por screen reader e headings hierárquicos.

# 22. FASE 13 — PERFORMANCE

Validar peso das imagens, dimensões, formatos, lazy loading, fontes, DOM, animações, CLS e carregamento inicial.

# 23. FASE 14 — VISUAL QA

Comparar diretamente WIREFRAME vs HTML vs FINAL COMPOSITION vs IMPLEMENTATION.

Verificar posição, proporção, hierarquia, espaçamento, typography, wrapping, cards, borders, assets, iluminação, contraste, responsive e motion.

A pergunta principal é: O site implementado realmente parece a composição aprovada?
Se não: corrigir.

# 24. FASE 15 — FINAL POLISH

Corrigir pequenos desalinhamentos, espaçamentos, escala, tipografia, crop, bordas, glow, contraste, motion, mobile e estados.
Não adicionar elementos apenas para deixar mais bonito. Cada elemento precisa ter função.

# 25. ANTI-BANNER GATE

Em todas as fases visuais perguntar: Estou criando uma interface ou uma imagem promocional?

Se parecer banner, poster, capa, thumbnail ou infographic, parar e corrigir.
A landing deve parecer uma página navegável de produto.

# 26. ANTI-GENERIC GATE

Remover o logo mentalmente. Se a página puder ser confundida com SaaS genérico, startup de IA, template, Web3 ou dashboard template, refazer a composição.
Não resolver genericidade adicionando neon. Resolver com composição, hierarquia, tipografia, proporção, produto e direção de arte.

# 27. ANTI-DRIFT GATE

Depois da aprovação da composição final, não alterar silenciosamente estrutura, número de seções, posição dos assets, sistema de cards, proporções, hierarquia ou art direction.

Se existir um bloqueio técnico real: documentar, escolher solução tecnicamente equivalente e preservar a aparência aprovada.

# 28. REGRA SOBRE TEXTO

Texto importante deve permanecer em HTML.
Assets visuais devem cuidar de atmosfera, objetos, interfaces, iluminação, elementos gráficos e composição visual.
Não usar imagem para substituir headline, parágrafo, CTA, navegação, títulos de seção ou informações críticas.

# 29. REGRA SOBRE CARDS

Cards devem seguir o Card Visual System definido na Fase 03.
Não criar uma nova linguagem visual para cada seção.
O sistema deve ser consistente, mas não repetitivo.

# 30. REGRA SOBRE IMAGENS GERADAS

As imagens geradas devem servir ao layout. Nunca o contrário.
Errado: imagem bonita → tentar encaixar na página.
Correto: wireframe → posição/dimensão → necessidade visual → prompt → asset → integração.

# 31. REGRA DE CONTINUIDADE

Antes da aprovação final: não parar entre fases. Executar automaticamente Discovery → Wireframe → Card System → HTML → Final Composition → PARAR PARA APROVAÇÃO.

Depois da aprovação: Assets → CSS → Integration → Motion → Responsive → Accessibility → Performance → QA → Polish → Final Validation.

# 32. PRIMEIRA AÇÃO

Começar somente pela FASE 01 — DISCOVERY.

Criar docs/landing-v4-discovery.md.

Não gerar imagem final. Não gerar asset. Não criar CSS final. Não criar landing final.

Após concluir Discovery, continuar automaticamente até a Fase 05.

A única parada intermediária será a aprovação da composição visual final.