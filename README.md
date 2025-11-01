
# 📈 Análise de Desempenho e Recomendação da Alura Store

Este projeto realiza uma **análise comparativa detalhada** do desempenho de quatro unidades da Alura Store. O objetivo principal é identificar a loja com a performance mais baixa e propor uma **venda estratégica** dessa unidade, liberando capital para reinvestimento em novos empreendimentos ou fortalecimento das lojas de maior rentabilidade.

---

## 💾 Dados

A análise foi conduzida a partir de dados de vendas, avaliações e logística de cada loja.

Os dados provêm de quatro arquivos CSV separados (`loja_1.csv` a `loja_4.csv`), que foram consolidados em um único DataFrame Pandas.

### Colunas Chave Analisadas:

* **Produto:** Nome do item vendido.
* **Categoria do Produto:** Classificação do item (e.g., 'eletronicos', 'livros').
* **Preço:** Valor unitário do produto.
* **Frete:** Custo de envio.
* **Avaliação da compra:** Nota dada pelo cliente (escala de 1 a 5).
* **Local da compra (lat/lon):** Coordenadas geográficas.
* **Loja:** Identificador da unidade de venda (adicionado após unificação).
* **Outras:** `Data da Compra`, `Vendedor`, `Tipo de pagamento`, `Quantidade de parcelas`.

---

## ⚙️ Metodologia

O fluxo de trabalho da análise foi estruturado nas seguintes etapas:

1.  **Importação e Unificação dos Dados:** Leitura e combinação dos arquivos CSV em um DataFrame centralizado.
2.  **Análise do Faturamento:** Cálculo do faturamento total por loja e identificação da participação percentual de cada unidade no faturamento geral.
3.  **Análise de Vendas (Categoria e Produto):** Verificação de vendas por contagem de transação e faturamento para identificar produtos e categorias-chave.
4.  **Avaliação e Frete Médio:** Cálculo da Avaliação Média dos Clientes e do Frete Médio por loja para métricas de qualidade e logística.
5.  **Visualização de Dados:** Geração de gráficos (barras, setores, dispersão) para apresentar as descobertas de forma clara.
6.  **Recomendação:** Formulação da conclusão e recomendação de desinvestimento baseada nas métricas de desempenho.

---

## 🎯 Principais Descobertas

As conclusões apontam consistentemente para a necessidade de reestruturação do portfólio de lojas:

* A **Loja 4** demonstrou o **menor faturamento total** entre todas as unidades.
* A **Loja 4** também registrou uma das **piores avaliações médias** dos clientes, sinalizando problemas na satisfação ou qualidade de serviço.
* O cálculo do **coeficiente de correlação** entre Avaliação Média e Faturamento revelou uma relação fraca, mas a posição isolada da **Loja 4** no gráfico de dispersão a identificou claramente como a unidade de menor desempenho geral.
* O menor frete médio da **Loja 4** não foi suficiente para impulsionar seu volume de vendas.
* Categorias como **'eletronicos'** e **'eletrodomesticos'** são os principais pilares do faturamento geral da rede.

---

## 📝 Conclusão e Recomendação

Com base nas métricas de faturamento e avaliação de clientes, a **Loja 4** é identificada como a unidade de menor desempenho geral.

**Recomendação:** A venda da Loja 4 é recomendada para liberar capital, que deverá ser reinvestido nas operações e expansão das lojas mais lucrativas ou em novos projetos estratégicos para a Alura Store.

---

## ▶️ Como Usar e Reproduzir a Análise

Este projeto foi desenvolvido em um **notebook Google Colab** e pode ser reproduzido facilmente:

1.  **Download:** Faça o download do arquivo `.ipynb` deste repositório.
2.  **Upload:** Abra o [Google Colab](https://colab.research.google.com/) e faça o upload do notebook.
3.  **Execução:** Execute as células sequencialmente.

> **Observação:** Os dados são carregados diretamente de URLs dentro do notebook, eliminando a necessidade de baixar os arquivos CSV separadamente.

---

## 👤 Autor

[LEONARDO FARIAS SOUZA/[FariasLeonado](https://github.com/FariasLeonardo/challenge-analise-lojas-alura-store)]

## 📜 Licença

[MIT License]
