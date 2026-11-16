# Explorar Évora

**Eren Öztürk · 77222**  
Tecnologias Web · INF13207L · Universidade de Évora · 2026/2027  
Contacto: ex77222@alunos.uevora.pt

## Demonstração e entrega

- [Abrir aplicação](https://hostilian.github.io/explorar-evora-77222/)
- [Código-fonte](https://github.com/Hostilian/explorar-evora-77222)
- [Descarregar pacote](https://hostilian.github.io/explorar-evora-77222/projeto.zip)
- [Relatório técnico de duas páginas](https://hostilian.github.io/explorar-evora-77222/relatorio.pdf)

Extraia o ZIP e abra `index.html`. Não requer instalação, frameworks ou compilação.
É necessária ligação à Internet para os dados da universidade e os mapas.

## Funcionalidades

Próximos quatro eventos, catálogo paginado, pesquisa remota, filtros locais,
detalhes com morada/GPS e mapa, comentários e perfis simulados de visitante,
agente cultural e administrador. Interface responsiva com navegação móvel,
tema claro/escuro e suporte a movimento reduzido.

## Verificação

Operações reais de leitura, criação, edição, comentário e eliminação verificadas
em 16/11/2026. Os registos temporários foram removidos; os restantes não foram
alterados. A edição usa POST; a eliminação de comentários envia event_id e
comment_id. O código de registo devolvido pelo servidor é apresentado ao utilizador.

Treze verificações focadas: `node verify.cjs` (opcional). Node.js não é necessário
para utilizar a aplicação. Ver README.txt para instruções e contratos HTTP.

Os perfis são simulações client-side, conforme o enunciado; não constituem
autenticação real. A disponibilidade da API e dos mapas depende dos serviços externos.

## Créditos

Fotografia: Efe Ersoy / Pexels. Licença, fonte e adaptações em CREDITS.txt.
Mapas: OpenStreetMap. Dados: servidor de apoio da disciplina.
