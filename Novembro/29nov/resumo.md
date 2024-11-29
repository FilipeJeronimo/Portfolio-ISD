# 10ª Aula – Circuitos Combinacionais

## Conteúdos Abordados

Nesta aula, o professor apresentou a matéria sobre **Circuitos Combinacionais**, explorando os seguintes tópicos:

- **Multiplexadores CI**  
- Multiplexadores com **8 entradas**  
- **Multiplexador para Display de 7 Segmentos**  
- **Demultiplexadores**  
- **CI Demultiplexador**

Além disso, foram resolvidos exercícios relacionados aos conceitos apresentados.

---

## Objetivo da Aula

Compreender o funcionamento dos **Circuitos Combinacionais**, incluindo os **multiplexadores** e **demultiplexadores**, através da análise teórica e prática de circuitos lógicos. Familiarizar-se com dispositivos CI específicos, como os **74LS157**, **74LS151**, **74LS47**, **74LS139**, e **74HC154**.

---

## Exercícios Resolvidos

### **1º Exercício**  
**(Página 7 da apresentação)**  
**Enunciado:**  
Sabendo que:  
- D0 = 0  
- D1 = 0  
- D2 = 1  
- D3 = 0  
- S0 = 1  
- S1 = 0  

Qual é o nível lógico da saída?  

**Resolução:**  
Com base nos valores fornecidos e na configuração de seleção, a saída corresponderá ao dado presente na entrada **D2**.  
Logo, o **nível lógico de saída é 1**.

---

### **2º Exercício**  
**(Página 33 da apresentação)**

1. **Identificação de dispositivos**:  
   - **74LS157**: Multiplexador de 4 entradas com seleção de dados.  
   - **74LS151**: Multiplexador de 8 entradas com seleção binária.  

2. **Forma de onda na saída de dados do 74LS151**:  
   As entradas de dados alternam entre níveis BAIXO e ALTO começando por **D0** (0, 1, 0, 1...). Com as linhas de seleção variando em contagem binária (000, 001, 010, ...), a saída do multiplexador refletirá a sequência correspondente das entradas, resultando numa forma de onda de frequência **1 kHz** com períodos alternados conforme os dados selecionados.  

3. **Finalidade dos dispositivos (Slide 24)**:  
   - **74LS157**: Seleciona e combina sinais de várias fontes, permitindo a escolha de 1 entre 4 conjuntos de dados.  
   - **74LS47**: Decodificador BCD para 7 segmentos, utilizado para displays.  
   - **74LS139**: Decodificador/demultiplexador de 2 para 4 linhas.

---

### **3º Exercício**  
**(Página 42 da apresentação)**

4. **Decodificador como demultiplexador**:  
   Um **decodificador** pode atuar como **demultiplexador** ao direcionar um único sinal de entrada para uma das várias saídas, dependendo do código binário fornecido nas linhas de seleção.

5. **Estados das saídas do 74HC154**:  
   Com o código binário **1010** nas linhas de seleção e a entrada de dados em nível BAIXO:  
   - A saída correspondente ao código binário **1010** estará em nível BAIXO.  
   - Todas as outras saídas permanecerão em nível ALTO.

---

## Conclusão

Nesta aula, aprofundei o meu entendimento sobre **multiplexadores e demultiplexadores**, além de aprender sobre circuitos integrados importantes como o **74LS151** e o **74HC154**. Os exercícios foram úteis para consolidar os conceitos, especialmente a análise de estados e formas de onda.

O **exercício 1** foi particularmente interessante, pois destacou a aplicação prática da lógica binária nos multiplexadores. Continuo a achar desafiador compreender todos os detalhes dos dispositivos CI, mas com mais prática, acredito que a matéria ficará mais clara.

---

**Data da aula:** 29/11
