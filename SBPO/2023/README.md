# SBPO 2023 - Determinação do tamanho ótimo de janela do filtro Spatial XOR

SEP = ;

---
# Aquivos

## XOR_JANELA_JANELAS_V_T.exp
> Arquivo com os experimentos iniciais para determinar qual o melhor número de hashes e o tamanho idel para a janela

Dados => **{k};{alpha};{z};{p}**

- k = número de funções hash
- alpha = fator de carga
- z = tamanho janela
- p = probabilidade de sucesso

## exp_004_3_val_{n}.exp
> Arquivo com os experimentos para encontrar as janelas, para cada n selecionado

Dados => **{k};{alpha};{z};{p};{t}**

- k = número de funções hash
- alpha = fator de carga
- z = tamanho janela
- p = probabilidade de sucesso
- t = variável interna