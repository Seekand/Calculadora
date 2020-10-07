# Cifra_de_cesar
 A Cifra de César, também conhecida como cifra de troca, código de César ou troca de César, é uma das mais simples e conhecidas técnicas de criptografia. 
 É um tipo de cifra de substituição na qual cada letra do texto é substituída por outra, que se apresenta no alfabeto abaixo dela um número fixo de vezes.
 
 1° linha do algoritmo é uma lista, com todas as letras do alfabeto
 2° laço de repetição
 3° Variavel "dc" que armazenar o número 1 ou 2, criptografar ou descriptografar, respectivamente
 
 5° e 8° são os condicionais que vão basicamente mudar o nome baseada na escolha do "dc"
 6° e 9° variavel, que receberá a palavra pelo qual será feito o processo escolhido
 
 11° variavel que recebera a chave, que corresponde a posição da letra da palavra no alfabeto + chave
 12° 13° Retira os espaços, inicia a string que recebera a palavra com a aplicação da chave, respectivamente
 14° loop de repetição, iterando cada letra da palavra após a remoção dos espaços.
 15° 18° baseado na escolha da variavel "dc", a variavel "pala_cript" ira receber letra a letra alterada baseada em seu índice + chave 
 Chave essa que podera ser subtraindo, caso for descriptografar, ou Somando caso for criptografar

20° Exibe a palavra após a criptografia ou descriptografia.
