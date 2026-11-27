# Finanças da Família

Aplicativo web (um único arquivo `index.html`) para controlar salários e gastos mensais de duas pessoas e as despesas da família.

## Como usar
Abra o arquivo `index.html` no navegador, no computador ou no celular. Não precisa instalar nada.

## Funcionalidades
- **Duas pessoas** com nomes configuráveis.
- **Salários e outras rendas** por pessoa, marcadas como mensais (repetem todo mês) ou só deste mês.
- **Despesas** com categoria, dia de vencimento e status de paga ou a pagar. Cada despesa pode ser:
  - **da família**, dividida entre as duas pessoas;
  - **pessoal**, de uma das pessoas.
- **Regra de divisão** das despesas da família: proporcional à renda, meio a meio ou percentual fixo.
- **Acerto de contas**: mostra quem deve transferir quanto para quem, com base em quem pagou cada despesa da família.
- **Resumo do mês**: renda, despesas, saldo, valor ainda a pagar, sobra de cada pessoa e gastos por categoria.
- **Visão anual** mês a mês.
- Rendas e despesas fixas são **copiadas automaticamente** quando você abre um mês novo.
- **Backup**: exportar e importar JSON, e exportar o mês em CSV (abre no Excel).

Os dados ficam salvos no navegador (`localStorage`). Para usar em outro aparelho, exporte o backup e importe lá.
