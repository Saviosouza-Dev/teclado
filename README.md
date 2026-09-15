# Primeiros Acordes no Teclado — Cartilha do Aluno

Material de apoio para aulas de teclado iniciante.
Feito para o aluno abrir no celular ou no computador, sem instalar nada.

**Cartilha (igual para todos):** https://saviosouza-dev.github.io/teclado/

---

## Material de cada aluno

Cada aluno tem uma pasta dentro de `alunos/`, com o link dele:

```
https://saviosouza-dev.github.io/teclado/alunos/NOME-DO-ALUNO/
```

Essa página monta a lista de materiais **sozinha**, a partir dos arquivos que
existem na pasta. Você sobe um arquivo novo e ele aparece lá em cerca de um
minuto — sem editar a página, sem mexer em índice nenhum.

Exemplo no ar: https://saviosouza-dev.github.io/teclado/alunos/exemplo/

### Rotina de toda semana (pelo site do GitHub, sem comandos)

1. Abra a pasta do aluno aqui no GitHub: `alunos/NOME-DO-ALUNO`
2. Clique em **Add file → Upload files** e arraste o arquivo da aula
3. Clique em **Commit changes** (botão verde)

Pronto. Em cerca de um minuto o material aparece na página do aluno.

### Como nomear o arquivo da aula

```
2026-09-22-troca-de-acordes.html
```

- **A data na frente**, no formato ano-mês-dia. É ela que coloca o material na
  ordem certa e que vira o rótulo lateral ("22 set").
- **Depois o título**, com hífen no lugar do espaço. Vira o título que o aluno vê.
- Acentos funcionam: `2026-09-22-mão-esquerda.html` aparece como "Mão esquerda".

### Como criar um aluno novo

1. **Add file → Create new file**
2. No nome do arquivo, digite: `alunos/maria/index.html`
   (a barra cria a pasta sozinha)
3. Abra `alunos/exemplo/index.html`, clique em **Copy raw file** e cole aqui
4. Troque **só** a linha `const ALUNO = 'Exemplo';` pelo nome do aluno
5. **Commit changes**

O link da Maria passa a ser `.../alunos/maria/`.

### Para escrever a aula

Use `alunos/modelo-de-aula.html` como ponto de partida — ele já tem o visual
pronto e blocos comentados (texto, dica, atenção, lista de exercícios, vídeo).
Copie, preencha, salve com o nome no padrão acima.

> **Atenção:** o repositório é público. Qualquer pessoa com o link vê o
> material. Para aula de música isso costuma ser o desejado, mas não escreva
> nada pessoal sobre o aluno nas páginas.

---

## O que tem na cartilha

- As partes do teclado
- Postura e altura certa
- Suas mãos e os números dos dedos
- Teclas brancas e pretas: o padrão que se repete
- Achar o Dó e o nome das notas
- Como ler uma cifra e um diagrama
- Seus primeiros 4 acordes (C, G, Am, F)
- Exercícios de troca de acordes
- Seu primeiro acompanhamento
- Dúvidas frequentes

## Como funciona

A cartilha inteira está em `index.html` — um arquivo só, sem dependências além
das fontes do Google Fonts. Layout responsivo e folha de estilo para impressão.

---

Sávio Souza — material didático para aulas de teclado.
Cartilha irmã: [violão](https://saviosouza-dev.github.io/violao/)
