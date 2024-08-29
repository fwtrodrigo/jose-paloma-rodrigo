#### Fluxo de trabalho

- Feito merge da branch "dev" para a branch "qa"
- Feito merge da branch "qa" para branch "main"(produção)
- O merge foi escolhido, pois o uso de rebase poderia gerar conflitos em cenários de pipeline, devido ao rebase trocar o HASH do commit.
- O merge é uma opção segura que preserva o histórico inteiro do repositório, enquanto o rebase cria um histórico linear movendo a ramificação de funções para a ponta da ramificação main.