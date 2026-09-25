# Relatório - Coelinhos do Brasil

> [!CAUTION]
> - Lembre-se que você <ins>**não pode utilizar ferramentas de IA para
>   escrever este relatório**</ins>

## Dados do aluno

- **Cartão UFRGS**: 00341038
- **Nome**: Nickolas Xisto Machado

## Passos que eu segui para resolver o problema especificado (em formato de *"prompt"*)

> [!IMPORTANT]
> - Coloque aqui todas as informações necessárias para que alguém
>   (pessoa ou ferramenta de IA) possa reproduzir os seus passos para
>   solucionar o problema
> - Escreva em formato imperativo, como se fosse um *prompt* com as
>   instruções a serem seguidas na solução do problema
> - Seja objetivo e conciso: quanto *menos palavras* você utilizar,
>   melhor
> - Seja técnico e use terminologia adequada: assuma que quem irá ler
>   os seus passos possui conhecimento de Ciência da Computação e
>   Computação Gráfica
> - Caso você queira incluir informações "longas" (como algum *prompt*
>   grande usado com alguma ferramenta de IA), crie arquivos à parte e
>   adicione links no texto (por exemplo, crie o arquivo `PROMPTS.md`
>   e adicione um link markdown `[os prompts detalhados estão
>   aqui](PROMPTS.md)`)
> - Novamente, lembre-se que você *não pode utilizar ferramentas
>   de IA para escrever este relatório*

- Crie uma coordenada inicial contendo os vértices do retângulo exterior da bandeira, centrado na origem;
- Inicialize delta T, considerando o tempo entre frames;
-Calcule o perímetro, a altura, a altura, o centro em x, e o centro em z do triângulo;
- Faça o mesmo para o losango, que deve ser diretamente dependente do tamanho do retângulo;
- Calcule 2pi e o raio do círculo, considerando as medidas obtidas para o losango;
- Armazene o "gap" entre cada coelho no perímetro de suas respectivas formas geométricas;
-Para cada coelho do retângulo:
- calcule o deslocamento de frame (a "distância percorrida" por um coelho durante cada frame) utilizando o gap inicial, o tempo entre frames, a velocidade e o perímetro do retângulo, mantendo o coelho dentro dos limites definidos nos vértices.
- Calcule as coordenadas do coelho, considerando o offset, e em qual reta se encontra
- Desenhe o coelho 
- Neste ponto, os coelhos do retângulo foram desenhados, agora faça o mesmo para o losango e o círculo, considerando suas respectivas fórmulas geométricas e tamanhos calculados anteriormente.

## Principais dificuldades encontradas durante o desenvolvimento (formato livre)

Dentre as funcionalidades implementadas, a movimentação foi a parte mais complexa, pois tive que alterar toda a lógica de desenho (com ajuda da IA) pensada anteriormente para o funcionamento correto da movimentação

## Você acha que conseguiu resolver o problema de forma adequada?
Parcialmente, faltou adicionar os chapéis, fazê-los olhar para a direção ao qual estavam andando e fazê-los pular, bem como possuírem uma transição suave ao transicionar de uma reta para outra. ALém disso, a ponta do losango coincide com as retas do retâgulo.

## Se você quiser compartilhar mais alguma coisa, coloque aqui:

Acabei me organizando indevidamente, me perdi nos prazos e não conseguirei avançar mais no laboratório durante o tempo hábil de entrega. Entretanto, pretendo finalizar o laboratório este fim de semana e deixá-lo atualizado no github.

## Se você possui alguma sugestão para o professor sobre esta atividade, coloque aqui:

<mark>`<preencher>`</mark>
