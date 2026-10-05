# Missão 05 · Biblioteca Livre

## Lore
A turma empresta livros entre si. Sem sumiço, com status.

## Itens sugeridos
| Livro | Status inicial |
|-------|----------------|
| Clean Code (resumo) | disponível |
| Dom Casmurro | disponível |
| O Guia do Mochileiro | emprestado |
| Use a Cabeça Java | disponível |
| Comic da turma | esgotado / indisponível |

## Boss (obrigatório)
Só empresta se status for **disponível**. Ao emprestar, status vira **emprestado** e grava no Firestore.
Badge vermelha em indisponível.

## Cofre (Firestore)
Coleção: `emprestimos_biblio` (aluno, livro, data).

## Rank sugerido da guilda
Cor: marrom / creme papel
