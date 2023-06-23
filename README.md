# Imersão IA - Alura

## Aula 01
### Desafios

Jogo de adivinhação de palavras

A ideia é você escolher uma palavra aleatória e pedir ao ChatGPT para tentar adivinhar, dando uma dica por vez. Por exemplo, o ChatGPT pode começar dando a primeira letra da palavra e, em seguida, pedir a você para confirmar se essa letra faz parte da palavra escolhida. Se sim, ele pode dar a segunda letra e assim por diante. O objetivo do jogo é adivinhar a palavra com o menor número possível de dicas.

Jogo de adivinhação de filmes

Escolha um dos seus filmes favoritos e sugira ao ChatGPT que faça perguntas sobre a trama, os personagens, o gênero do filme ou a sua data de lançamento para tentar adivinhar qual é o nome do filme que você escolheu. O objetivo do jogo é que o ChatGPT adivinhe o nome do filme com o menor número possível de perguntas.


### Links
- [Poe - centralizador de chats GPT](https://poe.com/)
- [Framer - IA para gerar sites](https://www.framer.com/)
- [Link do navegador Bing AI](https://www.bing.com/?/ai)
- [IA do Google - utilizar com navegador Opera devido a necessidade de uma VPN](https://bard.google.com/?hl=en)

## Aula 02
### Desafios
1. Crie 10 críticas variadas para filmes

Peça ao ChatGPT para gerar 10 críticas variadas para outro filme. Em seguida, solicite que ele converta essas respostas para o formato CSV, copie esses valores e salve-os em um arquivo de texto (.txt). Depois disso, abra o Google Sheets, crie uma nova planilha e importe o arquivo .txt (em "Arquivo -> Importar -> Fazer upload"). Ao fazer essa importação, pode ocorrer um erro se o Google Sheets confundir as vírgulas de separação com vírgulas presentes no texto. Caso ocorra algum erro, peça ao ChatGPT para corrigi-lo.

2. Sugira descrições de imagens para serem inseridas em outras IA's

Utilize o ChatGPT para sugerir descrições de imagens que possam ser inseridas em outras inteligências artificiais, como o Stable Diffusion. Peça ao ChatGPT para criar 5 descrições de imagens com estilos diferentes, a fim de explorar essa combinação entre o ChatGPT e o Stable Diffusion.

3. Calcule a média salarial de pessoas com o Google Sheets e o ChatGPT

Usando a função GPT_LIST() do SheetGPT, gere 20 nomes de pessoas brasileiras na coluna A, a área de atuação dessas pessoas (como "Marketing", "TI", "Direito" ou "Saúde") na coluna B e 20 valores aleatórios de salário entre 1.000 e 20.000 na coluna C. Agora, peça ao ChatGPT para criar uma macro para o Google Sheets que calcule a média desses salários e mostre a resposta na célula D2.


### Links
- [Planilha com as críticas ao filme Avatar](https://docs.google.com/spreadsheets/d/1qnOo2Gm-AeOjyZMQygmtvKIxxIUFCN9R_sWwZYy4QHc/edit?usp=sharing)
- [ArquivoJSON com 20 filmes e sem as notas](https://gist.github.com/fabriciocarraro/796e9e2f8fafac3712b33fc09c93c43e)
- [Arquivo JSON com 20 filmes e com as notas](https://gist.github.com/fabriciocarraro/a1760940faf23eb5a264c79732dc27ac)
- [SheetGPT - Extensão para Google Spreadsheets](https://sheetgpt.ai/)
- [Link da ferramenta ChatGPT.openai](https://chat.openai.com/)
- [Link para a ferramenta Stable Diffusion - IA Geradora de imagens](https://stablediffusionweb.com/)


=GPTLIST("Gere uma lista com 20 nomes de pessoas brasileiras na coluna A. Na coluna B adicione uma profissão com umas seguintes profissoões: Marketing, TI, Direito ou Saúde. Na coluna C adicione um salário com um valor entre 1300 a 20000")
