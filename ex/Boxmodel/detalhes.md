A propriedade box-shadow anexa uma ou mais sombras a um elemento.

Sintaxe básica:
box-shadow: h-offset v-offset blur spread color;

h-offset: Necessário. O deslocamento horizontal da sombra. Um valor positivo coloca a sombra no lado direito da caixa, um valor negativo coloca a sombra no lado esquerdo da caixa.

v-offset: Necessário. O deslocamento vertical da sombra. Um valor positivo coloca a sombra abaixo da caixa, um valor negativo coloca a sombra acima da caixa.

blur: Opcional. O raio de desfoque. Quanto maior o número, mais borrada será a sombra.

spread: Opcional. O raio de propagação. Um valor positivo aumenta o tamanho da sombra, um valor negativo diminui o tamanho da sombra.

color: Opcional. A cor da sombra. O valor padrão é a cor do texto. 
Nota: No navegador Safari (no PC) o parâmetro de cor é obrigatório. Se você não especificar a cor, a sombra não será exibida.

-----------------------------------------------------------------------------------------------------------------------

A propriedade border-radius define o raio dos cantos do elemento. Esta propriedade permite que você adicione cantos arredondados aos elementos.

Esta propriedade pode ter de um a quatro valores. Aqui estão as regras:

Quatro valores - border-radius: 15px 50px 30px 5px; 
O primeiro valor se aplica ao canto superior esquerdo, o segundo valor se aplica ao canto superior direito, o terceiro valor se aplica ao canto inferior direito e o quarto valor se aplica ao canto inferior esquerdo.

Três valores - border-radius: 15px 50px 30px; 
O primeiro valor se aplica ao canto superior esquerdo, o segundo valor se aplica aos cantos superior direito e inferior esquerdo, e o terceiro valor se aplica ao canto inferior direito.

Dois valores - border-radius: 15px 50px; 
O primeiro valor se aplica aos cantos superior esquerdo e inferior direito, e o segundo valor se aplica aos cantos superior direito e inferior esquerdo.

Um valor - border-radius: 15px; 
O valor se aplica a todos os quatro cantos, que são arredondados igualmente.
