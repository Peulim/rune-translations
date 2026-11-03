# Rune – pacotes de tradução (pt-BR)

Pacotes de tradução para o app Rune. O app lê `manifest.json` e baixa o pacote indicado, conferindo o SHA-256.

- `manifest.json`: catálogo dos pacotes disponíveis.
- `pt-BR.<versão>.json`: o pacote completo, com todos os livros (usado por versões antigas do app).
- `pt-BR.<versão>.<livro>.json`: o pacote de um único livro (por exemplo `pt-BR.2026.11.03.1.xphb.json`). O app baixa o pacote do livro junto com o livro, no idioma selecionado. Cada entrada de pacote por livro traz o campo `source` com o código do livro.

Os textos traduzidos vêm de livros oficiais de D&D 5e (incluindo textos da Wizards of the Coast). Uso pessoal e de teste; a publicação depende da decisão de licença de quem mantém o repositório.
