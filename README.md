# DIO_Dashboard_Porsche
Projeto de dashboard para análise comercial de Porsche vendidos nos EUA

PERGUNTAS DE NEGÓCIO:
1. Quais modelos Porsche apresentam maior volume de vendas e maior valor comercial?
2. Em quais estados americanos estão concentradas as vendas e quais apresentam maior ticket médio?
3. Quais formas de pagamento concentram maior volume e valor de vendas?

COMPONENTES, FILTROS E INTERAÇÕES
1. Filtros globais: Modelo, Ano do modelo, Estado, Cidade e Forma de pagamento.
  Os filtros deverão ser alimentados dinamicamente pelas categorias existentes na base, considerando os registros não cancelados.
2. Utilizar operadores OU dentro de cada filtro e operadores E entre filtros diferentes.
  Todos os filtros deverão iniciar na opção "Todos".
  Implementar botão "Limpar filtros".
3. Dependência entre estado e cidade
  Quando um ou mais estados forem selecionados, disponibilizar somente as cidades correspondentes.
  Quando a seleção de estado for modificada, remover automaticamente as cidades selecionadas que não pertençam aos estados escolhidos.
4.Atualização dos indicadores, criando três cartões principais:
  Quantidade de registros
  Valor total associado
  Preço médio
  OBS: Os indicadores deverão ser recalculados sempre que houver alteração nos filtros.

Tratamento utilizado:
- Padronização e saneamento da base em colunas como data, valores e meios de pagamento antes de realizar a análise;
- Oportunidade de atuar juntamente ao ChatGPT com Canvas, para geração de valor do dashboard
- Considerar exclusivamente os registros cujo campo DeliveryStatusSanitized seja diferente de Cancelled.

<img width="948" height="479" alt="image" src="https://github.com/user-attachments/assets/5948a6cb-80e6-466d-a654-6636e084e876" />
