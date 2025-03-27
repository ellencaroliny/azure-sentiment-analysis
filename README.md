## Análise de Sentimentos com Azure
# Descrição do projeto
Este projeto é uma análise exploratória do serviço de Análise de Sentimentos do Azure. 
O objetivo é testar a precisão e a eficácia da ferramenta ao processar frases com diferentes 
emoções e nuances, utilizando exemplos práticos.
# Metodologia
Frases diversas foram inseridas na ferramenta, e os resultados foram analisados para verificar se
o sentimento identificado era condizente com a intenção e o tom da frase original. Prints das 
análises e observações foram registrados para documentar os resultados.

# Testes
Abaixo estão alguns exemplos das frases testadas e os resultados obtidos:

![image](https://github.com/user-attachments/assets/a5d61abe-331a-4a82-8618-bb63b2807c6c)
Apesar de a frase indicar um entusiasmo inicial, ela também contém um tom de desânimo no final.
A ferramenta classificou como positivo, o que pode sugerir que não captou completamente a nuance emocional.

![image](https://github.com/user-attachments/assets/7d20976b-7bd2-4a91-9ebe-a39852cb4973)
Mas ao adicionar um advérbio "negativo" ele define a frase como negativa com mais precisão.

![image](https://github.com/user-attachments/assets/f780db7f-fc36-4fae-a22d-5ca9ee104703)
Nota-se que o serviço tem dificuldade de identificar o sentimento predominante em frases não tão diretas.

![image](https://github.com/user-attachments/assets/56470455-2390-4062-9e49-787bcf006b88)
Parece que a ferramenta focou mais nas palavras "seria fácil", que têm conotações positivas, 
sem levar em conta o contexto completo da frase. 

# Conclusão
A análise de sentimento do Azure mostrou resultados consistentes para frases mais diretas, mas apresentou dificuldades para interpretar nuances e sentimentos mistos. Esta exploração serve como um primeiro passo para entender as capacidades e limitações da ferramenta.
