# Calculadora_Consumo_Ve-culo

Atividade Proposta 

ORIENTAÇÕES GERAIS

      • O desafio é dividido em duas partes denominadas de DESAFIO – PARTE 1 e DESAFIO – PARTE 2
      • O desafio deve ser realizado individualmente
      • A atividade deverá ser postada somente no local específico para esta ação no Ambiente Virtual
      de Aprendizagem.
      
DESAFIO – PARTE 1

Agora, que você aprendeu as estruturas de lógica de programação utilizando a linguagem
JavaScript, desenvolva um programa para uma grande empresa, seguindo as informações a seguir:

O aumento nos preços dos combustíveis é algo que tem preocupado muitas famílias na tomada de decisões ao
buscar locais onde abastecer. Você é colaborador da FORD, e, assim como você, existem outros colegas que
precisam avaliar:

    • O consumo necessário em litros para o descolamento da casa para o trabalho
    • O local mais acessível para abastecimento de combustível
    • A média de valores de preços de combustíveis na região pesquisada
    • O gasto diário com combustível
    
Com base nesta avaliação, cada colaborador realizou uma pesquisa na região onde mora, e os dados coletados serão
inseridos no programa a ser construído por você, que deve conter a seguinte estrutura:

    1. Deve ser solicitado ao usuário a distância percorrida de sua casa até seu trabalho (em km).
    
DESAFIO | INGLÊS TÉCNICO ELÓGICA DE PROGRAMAÇÃO


Dica: é possível usar o método prompt para solicitar ao usuário a distância percorrida e como essa distância pode
ser um valor real. Deve-se usar a função parseFloat para que seja lida uma entrada em valor flutuante.
O usuário poderá digitar qualquer valor real. 
Por exemplo: 20 Km ou 20.4 Km, como segue na imagem abaixo:
    2. Deve ser solicitado ao usuário o consumo médio do veículo (em Km/L). Uma caixa de diálogo será exibida

    Dica: é possível usar o método
    prompt, para solicitar ao usuário o consumo médio do veículo e como o consumo
    médio pode ser um valor real. Deve-se usar a função
    parseFloat para que seja lida uma entrada em valor flutuante.
    
O usuário poderá digitar qualquer valor real. Por exemplo: 10 Km ou 10.2 Km

3. Deve ser calculado o consumo necessário em litros para realizar o deslocamento da casa até o trabalho
   

consumo_NecessarioLitros = distancia_Percorrida/consumo_Medio

Dica: Deve ser declarada a variável consumoNecessarioLitros e atribuída a ela a razão entre a distância percorrida da
casa até o trabalho e o consumo médio do veículo, da seguinte forma:

    var consumo_Necessario_Litros = distancia_Percorrida/consumo_Medio;

4. Deve ser apresentado na tela o consumo necessário em litros para realizar o deslocamento da casa até o trabalho.
Se usar o exemplo acima, com a distância percorrida de 20.4 Km e o consumo médio de 10.2 Km, deve ser exibida
na tela uma mensagem semelhante a essa:

    O consumo necessário é 2 litros
   
Dica: Devem ser construídas funções, para quebrar linhas, nas saídas da tela e para mostrar as saídas na tela, sem
necessidade de repetir comandos de quebra de linha e para escrever no html da página. Como, por exemplo: usar a
palavra reservada function para criar funções e dentro dessa função usar comandos para quebrar linha, como:

    document.write("<br>");
    
E para mostrar algum texto:

    document.write(texto);
    
5. Deve ser solicitada ao usuário a quantidade de postos de combustíveis pesquisados e seus respetivos valores.

Dica: é possível usar o método prompt para solicitar ao usuário a quantidade de postos de combustíveis pesquisados
e, como a quantidade pode ser um valor inteiro, deve-se usar a função parseInt para que seja lida uma entrada em
valor inteiro.
O usuário poderá digitar qualquer valor inteiro, como, por exemplo: 4

6. Deve ser solicitado ao usuário, os valores de combustíveis pesquisados nos postos, lembrando que tais valores
devem ser números reais a serem somados e colocados em uma variável de quantidade total de valores de
combustíveis digitadas pelo usuário.

    Dica 1: Tal solicitação deve ocorrer em uma estrutura de repetição, como, por exemplo, o
    for, pois ela irá controlar a quantidade de valores de combustíveis pesquisados pelo colaborador e auxiliar na soma da quantidade total de
    valores de combustíveis digitados pelo usuário.
    
    Dica 2: O comando for vai executar um conjunto de comandos, de acordo com a quantidade de postos de
    combustíveis pesquisada pelo usuário.
    
    Dica 3: é possível usar o método prompt para solicitar ao usuário os valores de combustíveis e como estes de
    combustíveis podem ser valor reais. Deve-se usar a função parseFloat para que sejam lidas entradas com valores
    flutuantes.
Observação: No exemplo acima o usuário digitou a quantidade de 4 postos de combustíveis, logo, serão exibidas 4
caixas de diálogo para o usuário digitar o valor de cada posto solicitado
