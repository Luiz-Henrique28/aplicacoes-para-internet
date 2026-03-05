# Projeto: Refatoração do Site Institucional – Banca Central

## Autor
Luiz Henrique da Silva Araujo

---

## Descrição do Projeto
Este projeto consistiu na auditoria e refatoração do site institucional da Banca Central, com foco em:

- Boas práticas de desenvolvimento front-end
- Acessibilidade
- SEO básico
- Estrutura e organização semântica
- Legibilidade e contraste de cores

O objetivo foi manter o conteúdo original da página, mas elevá-la a um padrão profissional.

---

## Alterações Realizadas

### 1. Estrutura Semântica
- Substituição de `<div id="header">` por `<header>`  
- Substituição de `<div id="content">` por `<main>`  
- Substituição de `<div id="footer">` por `<footer>`  
- Uso correto de títulos (`h1`, `h2`) para hierarquia semântica  
- Isso melhora acessibilidade, organização e SEO

### 2. Meta Tags e SEO
- Adicionado `<meta name="description" content="Banca Central - Revistas semanais e mensais disponíveis com destaque da semana e atendimento na Rua Principal, 456.">`  
- Mantido `<title>` com o nome completo do autor  
- Adicionado `lang="pt-br"` no `<html>`  
- Imagens receberam atributo `alt`  
- Essas alterações aumentam a pontuação de SEO e melhoram indexação

### 3. CSS e Separação de Responsabilidades
- Criado arquivo externo `style.css`  
- Mantido padrões de cores, fontes e espaçamentos  
- Ajustadas cores de links e subtítulos para **contraste suficiente** conforme WCAG 2.1  
- Isso melhora legibilidade e acessibilidade

### 4. Correções de Acessibilidade (Lighthouse)
- Corrigido contraste insuficiente em links e subtítulos  
- Adicionado ponto de referência principal com `<main>`  
- Essas alterações aumentam a nota de acessibilidade no Lighthouse

### 5. Organização e Padronização
- Melhorias na indentação e clareza do código  
- Padronização de classes e IDs  
- Código mais legível e fácil de manter

---

## Auditorias e Validações

### W3C Validator
- O código foi validado no [W3C Markup Validation Service](https://validator.w3.org/)  
- Garantindo conformidade com HTML5  
- Print do resultado anexado neste repositório

### Lighthouse (Chrome/Edge)
- Auditoria realizada para SEO, acessibilidade e boas práticas  
- Problemas de contraste e ponto principal corrigidos  
- Print do relatório anexado neste repositório

---

## Conclusão
O site foi refatorado mantendo seu propósito original, porém com melhorias técnicas significativas:

- Estrutura semântica correta (`header`, `main`, `footer`)  
- SEO básico implementado (`meta description`, alt, lang, títulos)  
- Contraste adequado para legibilidade  
- CSS externo separado e organizado  
- Código limpo, legível e padronizado  

Com essas alterações, o site atende melhor a padrões profissionais de desenvolvimento front-end.