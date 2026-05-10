# Raciocínio Lógico

Excelente escolha! Vamos mergulhar na **Lógica Proposicional**. 🔗
Nessa área, não analisamos o conteúdo das frases, mas sim a sua estrutura. Uma **proposição** é qualquer sentença declarativa que pode ser classificada como **Veradeira (V)** ou **Falsa (F)**.
Para construir raciocínios mais complexos, usamos os **conectivos lógicos**. Eles funcionam como "colas" que unem frases simples.
Aqui estão os principais conectivos que governam essa estrutura:

| Conectivo | Símbolo | Nome | Exemplo |
|---|---|---|---|
| **E** | \land | Conjunção | "Está chovendo **e** faz frio." |
| **OU** | \lor | Disjunção | "Vou ao cinema **ou** fico em casa." |
| **SE... ENTÃO** | \to | Condicional | "**Se** estudar, **então** passarei." |
| **NÃO** | \neg | Negação | "**Não** é verdade que..." |

### O Desafio da Tabela Verdade 🧩
O valor lógico de uma frase composta depende dos seus conectivos. Por exemplo, na **Conjunção (E)**, a frase inteira só é verdadeira se **ambas** as partes forem verdadeiras.
Vamos testar sua intuição com um exemplo prático:

Imagine que eu te diga a seguinte frase: *"Eu te darei um livro **E** te darei uma caneta"*.
**Se eu te der o livro, mas esquecer de te entregar a caneta, eu falei a verdade ou eu menti para você?**

Entender a negação é fundamental porque ela "inverte" o valor lógico de uma proposição. Se algo é **Verdadeiro**, sua negação é **Falsa**, e vice-versa. 🔄
Para negar as operações que vimos, usamos regras específicas. No caso do **E** e do **OU**, usamos as famosas **Leis de De Morgan**:
| Operação Original | Como Negar 🚫 | Regra Prática |
|---|---|---|
| **P \land Q** (E) | \neg P \lor \neg Q | Nega a primeira, nega a segunda e troca **E** por **OU**. |
| **P \lor Q** (OU) | \neg P \land \neg Q | Nega a primeira, nega a segunda e troca **OU** por **E**. |
### A Negação do "Se... Então" (Condicional) ⚡
Esta é a que mais confunde as pessoas! Para negar uma promessa ou condição (P \to Q), você mantém a primeira parte e nega a segunda.
 * **Regra:** P \land \neg Q (conhecida como regra do "marido": **Ma**ntém a primeira **E** **Ne**ga a segunda).
**Exemplo:**
 * Frase: "Se chover, eu levo o guarda-chuva."
 * Negação: "Choveu **E** eu **não** levei o guarda-chuva." (É a única situação onde a promessa original seria considerada mentira).
Vamos aplicar isso? Imagine a seguinte frase:
> **"Eu estudo E não fico cansado."**
> 
**Como ficaria a negação lógica dessa frase inteira usando as regras que acabamos de ver?**



