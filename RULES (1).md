# Regras do projeto: site sobre a raça Schnauzer

Este é o site de uma pessoa iniciante em programação. Todo o código deve ser simples o bastante para ela ler e entender.

Leia o que já existe antes de criar qualquer coisa nova.

## Parte 1: Sobre o meu site

### Quem sou eu
- Nome: André.
- Assunto do site: a raça schnauzer (fotos, descrição da raça e filhotes).
- Frase principal (usar no topo da página): [frase principal a definir pelo André]. Não invente a frase.
- 3 palavras que descrevem o site: schnauzer, cão, amigo. Também faz parte do clima do site a ideia de "quero um".

### Objetivo e público
- O site é para entusiastas da raça schnauzer conhecerem a raça (fotos e descrição) e adquirirem filhotes.
- Ações que quero que a pessoa faça: ver as fotos e a descrição da raça e entrar em contato para adquirir filhotes.
- Tom dos textos: descontraído, simpático e próximo, com jeito de blog.
- O site deve parecer: acolhedor, amigável e organizado, com um toque sóbrio e elegante.

### Inspirações (usar só o que está listado, não copiar o site inteiro)
- Canil Amor ao Quadrado (https://canilamoraoquadrado.com.br/): aproveitar a arte de fundo da home. Não quero muita informação no rodapé nem no menu do topo.
- SchnauzerMini (https://schnauzermini.com.br/): aproveitar a logo centralizada na home. Não quero muita informação no rodapé.
- Canil Kelsen (https://canilkelsen.com.br/): aproveitar a disposição do menu e o rodapé. Não quero muitos botões de "fale com o criador".

### Identidade visual (design system)
- Cores principais: cinza grafite e cinza prateado. Defina como variáveis CSS no `:root` (se o projeto já tiver variáveis de cor, reaproveite os nomes que existem). Para texto e fundo, use apenas tons neutros que combinem com os dois cinzas.
- Modo escuro: sim. Um botão alterna entre claro e escuro trocando os valores das variáveis, com bom contraste de texto nos dois modos.
- Fontes: estilo alemão (formas firmes, geométricas e sóbrias, que lembrem design industrial alemão), sempre legíveis. No máximo 2 famílias do Google Fonts. Evite fontes góticas decorativas que atrapalhem a leitura.
- Página inicial: arte de fundo na home e logo centralizada. A logo e a arte de fundo ficam na pasta `img/`; enquanto eu não enviar os arquivos, use marcadores como [logo] e [arte-de-fundo].
- Muito espaço em branco e hierarquia visual clara (títulos, subtítulos e textos com tamanhos bem diferentes).
- Componentes (botão, card, menu): reaproveite os que já existem em vez de criar outros parecidos.

### O que evitar
- Muita informação no menu do topo e no rodapé.
- Muitos botões de contato espalhados pela página.
- Excesso de texto, animações exageradas e visual confuso.
- Use apenas microinterações discretas (hover e transições suaves).

### Mapa do site (na ordem, do topo ao rodapé)
1. **Início** (essencial): menu com Home, Quem somos nós e Galeria; logo centralizada e arte de fundo.
2. **Sobre a raça** (essencial): texto com fotos.
3. **Projetos** (desejável): texto e fotos.
4. **Contato** (essencial): e-mail, redes sociais e endereço. Use [e-mail], [endereço] e [link da rede social] até eu enviar os dados reais.

Rodapé: simples e enxuto, com poucas informações.

### Experiência da página
- Layout responsivo, funcionando bem no celular e no computador.
- Navegação simples: menu no topo, com poucos itens, que leva a cada seção.
- Destaque para as fotos e chamadas para ação (botões) claras, poucas e bem escolhidas.
- Deve transmitir carinho pela raça e confiança para quem quer adquirir um filhote.

### Pendências da ficha (perguntar antes de decidir)
- A ficha não diz se o site terá uma página só ou várias. Não crie arquivos novos antes de eu responder.
- O menu cita "Quem somos nós" e "Galeria", que não aparecem como seções no mapa. Pergunte se viram seções ou páginas.
- A seção "Projetos" não ficou clara para um site sobre schnauzer. Pergunte o que ela deve mostrar (por exemplo, ninhadas ou filhotes disponíveis).
- Não há frase principal definida. Use o marcador até eu informar.

## Parte 2: Como trabalhar (igual para todos, não editar)

### Tecnologias e arquivos
- Use somente HTML, CSS e JavaScript puros. Não use frameworks nem bibliotecas.
- Exceções permitidas: Font Awesome (ícones) e Google Fonts (fontes), ambos por link no HTML. Nunca use emojis como ícones.
- Mantenha a estrutura de arquivos que já existe. Só crie arquivos novos se eu pedir.
- Imagens ficam na pasta `img/`.

### HTML
- Use tags semânticas: `header`, `nav`, `main`, `section`, `article` e `footer`.
- Escreva nomes de classes e comentários em português, em minúsculas e com hífen (exemplo: `cartao-projeto`).
- Todo `img` deve ter um `alt` descritivo.
- Use apenas um `h1` por página.
- Não use as tags `table` e `blockquote`.

### CSS
- Escreva CSS simples, sem truques avançados.
- Use medidas somente em `rem`, `px` e `%`.
- Use variáveis CSS para as cores. O modo escuro troca essas variáveis.
- Organize o `style.css` em blocos com comentário, um por seção da página.
- Agrupe todos os efeitos de `hover` e `transition` em um único bloco, no final do arquivo, com um comentário que o identifique.
- Faça o layout funcionar no celular, com no máximo uma `media query` simples por seção.

### JavaScript
- Escreva JS simples e comentado em português, usando `querySelector`, `addEventListener` e `classList`.
- Cada função deve fazer uma coisa só.

### Forma de trabalhar
- Faça somente o que foi pedido, uma seção ou uma mudança por vez. Não crie nem altere arquivos que eu não pedi.
- Antes de uma mudança grande (várias seções ou refazer algo inteiro), explique o plano em poucas linhas e espere a minha confirmação.
- Ao terminar, explique em 3 a 5 linhas, em linguagem simples, o que foi criado ou alterado.
- Nunca invente textos pessoais, links ou dados. Use marcadores entre colchetes.
- Se um pedido meu entrar em conflito com estas regras, avise e pergunte como prefiro seguir.

### Interação
- Só pergunte quando faltar uma informação essencial, e faça uma pergunta por vez. Se o pedido estiver claro, execute.
- Se eu disser "vai direto", registre a suposição que você fez e siga.
- Ao trocar de modo, diga qual modo está sugerindo e por quê, em uma frase, e pergunte se pode seguir.

## Modos de trabalho

Cada modo tem um arquivo em `.agents/rules/`. Use o modo que combina com o pedido, ou o que eu chamar pelo nome (`modo planejador`, `modo depurador`, `modo revisor`, `modo explicador`).

| Sinais no pedido | Modo |
| --- | --- |
| planejar, dividir em fases, ordem das seções, o que fazer primeiro | Planejador |
| bug, quebrou, não aparece, erro no console, não funciona no celular | Depurador |
| revisar, conferir, checklist, está bom?, antes de entregar | Revisor |
| explica, o que esse código faz, não entendi | Explicador |

### Transições
- Planejador: executa uma fase por vez e, ao fim de cada uma, pode ir para Revisor.
- Depurador: se o problema mostrar falha de estrutura, volta para Planejador.
- Revisor: se achar um bug, passa para Depurador. Só corrige o que eu pedir.
- Explicador: depois de explicar, volta ao que estava sendo feito.

### Gates (checagens antes de agir)
- **A. Interação:** vale a seção "Interação" acima.
- **B. Mudança em algo que já existe** (várias seções, estilos globais, variáveis, estrutura do HTML): siga `analise-de-mudanca.md`.
- **C. Decisão que afeta mais de uma área** (visual, conteúdo e código ao mesmo tempo): siga `multi-persona.md`.
- **D. A ficha manda:** objetivo, público e identidade visual desta Parte 1 não mudam sozinhos. Se um pedido contrariar a ficha, avise e pergunte.
