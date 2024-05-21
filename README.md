# Simulador de CDI vs Poupança

Este repositório contém um simulador em Python para comparar o rendimento de um investimento em CDI com o rendimento da Poupança ao longo do tempo. O simulador permite que você insira o capital inicial, aportes mensais e a taxa anual de CDI oferecida pelos bancos. O objetivo é fornecer uma análise visual e quantitativa das duas opções de investimento.

## Funcionalidades

- **Cálculo do rendimento de CDI**: O simulador calcula o rendimento acumulado de um investimento em CDI ao longo de um período especificado, considerando a taxa anual de CDI.
- **Cálculo do rendimento da Poupança**: O simulador calcula o rendimento acumulado de um investimento na Poupança ao longo do mesmo período.
- **Comparação visual**: Gera um gráfico de barras comparando os saldos acumulados do CDI e da Poupança, com labels indicando os valores em R$ no topo de cada barra.

## Como usar

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/seu_usuario/simulador-cdi-vs-poupanca.git
   ```
2. **Instale as dependências**:
   Certifique-se de ter o Python e as bibliotecas necessárias instaladas. As principais bibliotecas usadas são:
   - pandas
   - matplotlib
   - numpy

   Você pode instalar as dependências com o seguinte comando:
   ```bash
   pip install pandas matplotlib numpy
   ```

3. **Execute o simulador**:
   Altere os parâmetros de exemplo no script conforme necessário:
   - `capital_inicial`: O capital inicial do investimento.
   - `aporte_mensal`: O valor dos aportes mensais.
   - `taxa_cdi_anual`: A taxa anual do CDI (em decimal, por exemplo, 0.12 para 12%).
   - `meses`: O período do investimento em meses.

   Execute o script Python:
   ```bash
   python simulador_cdi_vs_poupanca.py
   ```

## Exemplo de Uso

O script vem com um exemplo de parâmetros pré-configurados:
```python
# Parâmetros de exemplo
capital_inicial = 1000  # Capital inicial
aporte_mensal = 200     # Aporte mensal
taxa_cdi_anual = 0.12   # Taxa CDI anual de 12%
meses = 24              # Período de 2 anos
```

## Resultado

O resultado é um gráfico de barras comparando os saldos acumulados no CDI e na Poupança ao longo do período especificado. Os valores acumulados são exibidos no topo de cada barra para facilitar a visualização.

![image](https://github.com/eltonsarmanho/CalculoCDI/assets/28907902/633b90de-b81c-44a1-bf28-49d36ca7f4a2)


## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e enviar pull requests para melhorias e correções.


