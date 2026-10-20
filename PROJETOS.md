# Como publicar seus projetos

A seção `#projetos` em `index.html` contém três espaços reservados. Procure os comentários `PROJETO 01`, `PROJETO 02` e `PROJETO 03` para editar cada apresentação.

1. Troque o título, a categoria e o resumo pelos dados do projeto.
2. Substitua o bloco `.project-cover` por uma imagem: `<img class="project-cover project-image" src="assets/nome-do-projeto.webp" alt="Descrição da interface apresentada">`. Adicione ao CSS `.project-image { width: 100%; object-fit: cover; }` e salve a imagem em `assets/`.
3. Preencha os campos dentro de `.case-content`: contexto, participação, processo, solução, resultados e aprendizados. Você pode incluir imagens e links para protótipos junto ao texto.
4. Nos resultados, use dados comprovados. Informe a fonte, o período e a comparação quando houver métricas; quando não houver, descreva evidências qualitativas e limitações.
5. Troque “Em preparação” por uma indicação adequada, como “Case publicado”, e o texto do resumo por “Ver estudo de caso”. Remova o aviso de modelo e substitua o bloco de impacto pelos resultados reais.
6. Atualize o texto introdutório e a nota final da seção conforme os cases forem publicados. Mantenha os avisos dos espaços ainda não preenchidos.

Para adicionar outro projeto, duplique um bloco `<article class="project-card">...</article>` inteiro dentro de `.projects-grid`. Não há JavaScript a configurar: os detalhes abrem com o elemento HTML nativo `details`, inclusive por teclado.
