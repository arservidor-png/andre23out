# Regras do projeto: site de portfólio pessoal

Este é o site de portfólio de uma pessoa iniciante em programação. Todo o código deve ser simples o bastante para ela ler e entender.

Leia o que já existe antes de criar qualquer coisa nova.

## Parte 1: Sobre o meu site

### Quem sou eu
- Nome e perfil: Maria, desenvolvedora Full Stack.
- Frase principal (usar no topo da página): "Transformo ideias em experiências digitais funcionais, bonitas e escaláveis."

### Objetivo e público
- O site é para recrutadores de tecnologia, potenciais clientes e profissionais da área conhecerem meu trabalho e minhas habilidades.
- Ações que quero que a pessoa faça: ver meus projetos, entrar em contato e acessar meu GitHub e meu LinkedIn.
- Tom dos textos: profissional, moderno e próximo.
- O site deve parecer: tecnológico, elegante e criativo.

### Identidade visual (design system)
- Cores principais: azul-marinho, roxo e branco. Defina como variáveis CSS no `:root` (se o projeto já tiver variáveis de cor, reaproveite os nomes que existem).
- Modo escuro: sim. Um botão alterna entre claro e escuro trocando os valores das variáveis, com bom contraste de texto nos dois modos.
- Fontes: modernas, simples e legíveis, com títulos marcantes. No máximo 2 famílias do Google Fonts.
- Muito espaço em branco e hierarquia visual clara (títulos, subtítulos e textos com tamanhos bem diferentes).
- Componentes (botão, card, menu): reaproveite os que já existem em vez de criar outros parecidos.

### O que evitar
- Excesso de texto, animações exageradas e visual confuso.
- Use apenas microinterações discretas (hover e transições suaves).

### Experiência da página
- Layout responsivo, funcionando bem no celular e no computador.
- Navegação simples: menu fixo no topo que leva a cada seção.
- Destaque para os projetos e chamadas para ação (botões) claras.
- Deve transmitir competência técnica sem ficar excessivamente corporativo.

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
