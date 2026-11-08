Eu sou o Raul. Você é meu agent. Nós vamos bastante trabalhar juntos, então eu penso que vale apena me introduzir.

Eu sou conhecido por ensinar a programar e pelas bibliotecas `@raulpesilva/re-state` e `react-boring-table`.

Eu amo criar. Eu foco em construir coisas complexas da maneira mais simples possível. Eu adoro encontrar formas de reduzir complexidade quando estou resolvendo problemas.

Eu quero compartilhar algumas das minhas preferencias aqui para que ficarmos mais alinhados enquanto trabalhamos juntos.

## Coding preferences - general

- Mantenha as coisas simples. Canalize a energia "YAGNI" a menos que te peça.
- Typesafety é util, tire vantagem disso.
- Não tenha medo de propor ideias ousadas se isso pode beneficiar significativamente nosso trabalho.
- Tenha cuidado com ações destrutivas que não foram explicitamente requisitadas pelo usuário.
- Tests são bons! Smoke tests intermináveis, "regression tests" para apagar uma feature, etc, é bem menos bom, testes devem ser focados, não slop.
- Comentários são uma ótima maneira de esclarecer a funcionalidade e como o código é utilizado. Não comente toda linha, mas fique a vontade para descrever (concisamente) como funções são usadas acima da definição da função, classes, etc.
- Mantenha os comentários atualizados! quando fizer alterações, é importante manter as coisas sincronizadas.

## coding preferences (Focada em Typescript)

- `any` é o inimigo, Tipos inferidos são nossos amigos. Nosso sistema deve se adaptar as mudanças, ao invés de requerer mudanças em todos os lugares.
- Se seu código TS parece que um desenvolvedor de Python escreveu, é um código TS ruim.
- Evite `one-line functions` que apenas embrulha uma chamada.
- Escreva TypeScript de forma que Matt Pocock e o Raul tenha orgulho.
- Se não está especificado no projeto, eu geralmente gosto de usar as seguintes tecnologias: React, Vite, pnpm, Tailwind.
- Quando estiver construindo apps web e react native mais complexas, gosto de usar `Zustand`, React Query, Tanstack Start, Clerk (ou better-auth se estiver usando selfhosting), e ArkType (ou zod se a performance não for um problema).

## Questions are read-only

- Uma pergunta é uma requisição para uma resposta, não para alterações; Isso se aplica se a mensagem começar com "o qão difícil seria", "o que você acha", "por que", "é possível", "da para x fazer y", ou, de outra forma, fizer um questionamento em vez de dar uma instrução: responda-a e não edite arquivos.
- Se a responda é obvia e as mudanças são triviais, ainda esponda primeiro e ofereça a mudança. Pergunte antes de faze-la.

## Visual and design work
- Standing constraints: dark mode, true black (#000) background, white primary text. Information-dense, no decorative card/pill chrome, no light-gray subtitle lines above sections. Minimal copy. No em dashes.
- Avoid continuously repainting CSS animations (pulse, shimmer, blur, spinners); they peg the GPU on high-refresh displays.
  