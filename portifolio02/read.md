# Processamento de Imagens — Análise e Correção de Exposição

## Entrega

A entrega deverá ser feita no **GitHub**, contendo um notebook **`.ipynb` executado**, com todas as figuras e resultados visíveis.

## 1. Seleção das imagens

Escolha **três fotos suas**, podendo ser fotografias tiradas com celular, câmera ou até mesmo prints de tela.

As três imagens devem representar diferentes condições de exposição:

* **Imagem escura demais:** por exemplo, foto noturna, contraluz ou ambiente interno com pouca iluminação;
* **Imagem clara demais ou saturada:** por exemplo, foto com flash forte, sol direto, neblina ou print de uma tela clara;
* **Imagem bem exposta:** uma foto que você considera possuir uma exposição adequada.

---

## 2. Análise de cada imagem

Para **cada uma das três imagens**, realize as seguintes etapas.

### 2.1 Conversão para tons de cinza

Converta a imagem para **tons de cinza** e plote seu **histograma de intensidades**.

### 2.2 Diagnóstico do histograma

A partir da análise do histograma, escreva **uma ou duas frases de diagnóstico**, indicando:

* Em qual faixa de intensidades os pixels estão concentrados;
* O que essa distribuição indica sobre a exposição da imagem.

### 2.3 Correção da imagem

Escolha e aplique **uma única operação** entre:

* **Expansão de contraste**;
* **Equalização de histograma**;
* **Correção de gamma**.

Para a operação escolhida:

1. Justifique por que ela foi utilizada naquela imagem;
2. Informe o parâmetro utilizado:

   * **L e H**, no caso da expansão de contraste; ou
   * **γ (gamma)**, no caso da correção de gamma.

### 2.4 Comparação antes e depois

Monte uma figura contendo, **lado a lado**:

1. A imagem original;
2. A imagem após a operação;
3. O histograma da imagem original;
4. O histograma da imagem corrigida.

A comparação deve permitir visualizar claramente o efeito da operação realizada.

---

## 3. Análise final

Ao final do notebook, responda em **um único parágrafo**:

> **Em qual das três imagens a operação realizada fez menos diferença? Por quê?**

A resposta deve relacionar o resultado observado com as características da imagem e de seu histograma.

---

## Regras

* É permitido **reaproveitar as funções disponibilizadas no notebook da aula**, como:

  * `histograma`
  * `expandir_contraste`
  * `equalizar`
  * `corrigir_gamma`



