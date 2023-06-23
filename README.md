# trabviel
Willian Campo, Sebastian Motta
Professor: Felipe Viel
Matéria: Introdução a ciências da computação

                                                                                      
Texto sobre o código sobre exemplo_Morfologia :

O código fornecido mostra um exemplo de como usar a morfologia matemática em imagens usando a biblioteca OpenCV em Python. A morfologia matemática é uma técnica de processamento de imagens que utiliza operações como rastreamento, dilatação, abertura, fechamento e gradiente para modificar a forma e a estrutura dos objetos que estão presentes na imagem.
No início do código, são utilizados códigos para importar as bibliotecas necessárias, incluindo o OpenCV, que é uma biblioteca muito utilizada para processamento de imagens. Em seguida, são carregadas três imagens em escala de cinza, chamadas 'j.png', 'j_ruido.png' e 'j_furos.png'. Essas imagens serão usadas para mostrar diferentes mudanças que podem ser feitas com a morfologia matemática.
O código também define uma matriz chamada kernel, que é uma matriz usada nas operações de morfologia. Essa matriz tem um tamanho de 5x5. O kernel determina o tamanho e a forma da proximidade de pixels que serão considerados durante as operações de morfologia.
Em seguida, são aplicadas algumas operações de morfologia nas imagens carregadas. A injeção é usada para diminuir o tamanho dos objetos na imagem, removendo pixels das bordas. A dilatação, por outro lado, é usada para aumentar o tamanho dos objetos, preenchendo áreas vazias próximas às bordas. Essas operações são realizadas na imagem original usando o kernel definido.
Além disso, são aplicados o gradiente, a abertura e o fechamento em outras duas imagens carregadas. O gradiente se destaca como bordas dos objetos na imagem, enquanto a abertura é uma combinação de sequência de dilatação e é útil para remover pequenos objetos e ruídos. Já o fechamento é o oposto da abertura, seguindo primeiro uma dilatação seguida de entrada, e é usado para preencher pequenos buracos nos objetos.
No final do código, existem trechos comentados que mostram como exibir as imagens resultantes. Dependendo de onde o código está sendo executado, como no próprio computador ou no Google Colab, diferentes funções são usadas para exibição como imagens.
