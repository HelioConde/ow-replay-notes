<div align="center">
  <h1>🧪 OW Replay Notes</h1>
  <p><strong>Sistema leve de notas por replay, voltado a decisões, contexto e ações corretivas.</strong></p>
  <p><img alt="Status" src="https://img.shields.io/badge/status-concep%C3%A7%C3%A3o-64748b"></p>
</div>

> **Projeto em concepção — documentação apenas.** O repositório ainda não contém frontend, backend ou aplicativo executável. O fluxo abaixo é um plano de produto, não uma funcionalidade disponível.

## Problema

Rever uma partida sem estrutura pode gerar muitas observações, mas poucas ações úteis no treino seguinte.

## Experiência proposta

Identificar replay/vídeo → registrar momento ou timestamp → classificar a decisão → descrever aprendizado → revisar por categoria.

## Dados mínimos do primeiro protótipo

Identificador do replay, herói, mapa, timestamp, categoria, observação e próxima ação.

## MVP planejado

Formulário de notas e busca por partida/categoria, com exportação de JSON.

**Critério para considerar o MVP útil:** Uma revisão completa pode ser salva, reencontrada e exportada sem upload de vídeo.

## Limites e dependências

Não há integração implementada com replays locais ou API Overwatch; arquivos reais e automação serão avaliados separadamente.

A implementação deve começar com **dados demonstrativos identificados e armazenamento local**, se adequado. Integrações externas, autenticação e anúncios exigem revisão própria; não serão anunciados como funcionais antes de existirem.

## Próximo passo

1. Desenhar uma tela com o fluxo principal.
2. Implementar um protótipo pequeno que funcione no celular.
3. Testar navegação, salvar/recuperar dados e tratamento de casos vazios.
4. Pedir feedback de usuários antes de ampliar o escopo.

## Projetos relacionados

Este conceito faz parte do [Ideias IA Lab](https://github.com/HelioConde/ideias-ia-lab). Explore [outros repositórios de Hélio Conde](https://github.com/HelioConde?tab=repositories).

*Overwatch pertence aos seus respectivos titulares. Projeto independente, sem afiliação oficial.*

Autor: [Hélio Conde](https://github.com/HelioConde).
