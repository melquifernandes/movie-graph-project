<h1>Movie Graph Project</h1>

<p>
Este repositório apresenta um projeto de modelagem de dados em grafo,
utilizando o banco de dados Neo4j, com foco no universo de filmes e séries.
</p>

<h2>Sobre o repositório</h2>

<p>
A proposta deste repositório é demonstrar como entidades do mundo real
podem ser conectadas de forma natural quando o foco está nos relacionamentos.
Em vez de tabelas isoladas, o projeto explora conexões entre usuários,
filmes, séries, gêneros, atores e diretores.
</p>

<p>
O conteúdo aqui foi organizado para fins educacionais, portfólio técnico
e estudo de bancos de dados em grafo.
</p>

<h2>O que este projeto representa</h2>

<p>
O grafo modela situações comuns do dia a dia no consumo de entretenimento,
como:
</p>

<ul>
  <li>usuários assistindo filmes e séries</li>
  <li>filmes e séries classificados por gênero</li>
  <li>atores atuando em produções</li>
  <li>diretores responsáveis pelas obras</li>
</ul>

<h2>Entidades principais</h2>

<ul>
  <li>User</li>
  <li>Movie</li>
  <li>Series</li>
  <li>Genre</li>
  <li>Actor</li>
  <li>Director</li>
</ul>

<h2>Relacionamentos modelados</h2>

<ul>
  <li><strong>User</strong> WATCHED <strong>Movie</strong></li>
  <li><strong>User</strong> WATCHED <strong>Series</strong></li>
  <li><strong>Movie</strong> HAS_GENRE <strong>Genre</strong></li>
  <li><strong>Series</strong> HAS_GENRE <strong>Genre</strong></li>
  <li><strong>Actor</strong> ACTED_IN <strong>Movie</strong></li>
  <li><strong>Actor</strong> ACTED_IN <strong>Series</strong></li>
  <li><strong>Director</strong> DIRECTED <strong>Movie</strong></li>
  <li><strong>Director</strong> DIRECTED <strong>Series</strong></li>
</ul>

<h2>Objetivo</h2>

<p>
O objetivo principal é servir como base para compreender conceitos de
modelagem em grafos, boas práticas no uso do Neo4j e exploração de dados
conectados. O repositório também pode ser facilmente expandido para
cenários como sistemas de recomendação e análise de preferências.
</p>

<h2>Público-alvo</h2>

<p>
Este repositório é indicado para estudantes, profissionais de dados,
desenvolvedores e qualquer pessoa interessada em aprender ou demonstrar
conhecimento em bancos de dados em grafo.
</p>

  }
};

export default repository;
