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

## Aula 3
### Prompts da aula
Aqui você encontra os prompts iniciais da aula:

Vamos simular o funcionamento do ChatGPT. Para cada frase que você escrever no prompt, você deve listar as 5 palavras com maior probabilidade de completá-la, juntamente com a probabilidade de cada uma delas. Apenas as palavras e probabilidades, sem mais nada, certo?
Resuma em português este texto.

Crie um texto para LinkedIn para divulgar a Imersão em IA da Alura.

Pergunta: Um diretor de cinema já dirigiu 16 filmes. Metade dos filmes que ele dirigiu são de ação, e metade dos filmes de ação conta com a participação do Nicolas Cage. Quantos filmes de ação com a participação do Nicolas Cage ele dirigiu? Resposta: A resposta em números é...

### Desafio
Explorando as respostas do ChatGPT
Teste as respostas do ChatGPT quando você faz perguntas curtas, sem dar exemplos, e quando você elabora mais a pergunta, fornecendo um ou mais exemplos.

Calculando Imposto com ChatGPT: Cadeia de Raciocínio e Valores da Planilha
Utilize a lista de valores da [planilha](https://docs.google.com/spreadsheets/d/1ur7AK_YFBmaD4A7obKFjUfw1CiCCGikmtfNqo7Wosgk/edit#gid=0) e o método Chain-of-Thought (Cadeia de raciocínio) no ChatGPT para obter o cálculo do valor do imposto a ser arrecadado. Considere que pessoas com rendimento de até R$20.000,00 pagam 10% de imposto, pessoas com rendimento entre R$20.000,00 e R$40.000,00 pagam 20% de imposto, e pessoas com rendimento acima de R$40.000,00 pagam 30% de imposto.


### Links:
- [Ferramenta IA para otimizar o seu uso do Linkedin: Engage-AI](https://engage-ai.co/)
- [Hipsters ponto tech](https://www.hipsters.tech/chatgpt-transformers-e-redes-neurais-hipsters-ponto-tech-352/)
- [Artigo: Whats is ChatGPT Doing… and why does it work?](https://writings.stephenwolfram.com/2023/02/what-is-chatgpt-doing-and-why-does-it-work/)
- [Artigo: Large Language Models are zero-shot reasoners](https://arxiv.org/abs/2205.11916)
- [Artigo: Language Models Perform Reasoning via Chain of Thought](https://ai.googleblog.com/2022/05/language-models-perform-reasoning-via.html)
- [Artigo: Melhores práticas de uso do GPT](https://platform.openai.com/docs/guides/gpt-best-practices)
- [Artigo: Maieutic prompting (Técnica maiêutica)](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md#maieutic-prompting)
- [Artigo: Chain-of-thought Prompting Elicits Reasoning in LLM](https://arxiv.org/abs/2201.11903)

## Aula 04
### Prompts da aula
Aqui você encontra os prompts iniciais da aula:

Tenho uma planilha no Google Sheets com notas de alunos. Na coluna A está o nome do aluno e na coluna B a nota. Crie uma fórmula para filtrar os alunos com nota acima de 7.

Tenho uma planilha no Google Sheets com uma lista de alunos e as notas de cada aluno em 4 diferentes provas. Quero uma função em App Script para calcular a nota final do aluno. Ela recebe as 4 notas das provas e devolve uma nota com o seguinte critério: Se o aluno tirou algum zero a nota final é 0; Senão a nota final é a média das 3 maiores notas.
Escreva um email para um aluno de física para apresentar a nota dele no semestre. Nome: Marcelo Barbosa; Nota: 8,8.

### Desafio
1. Tokenização: Explorando o GPT-Tokenizer e o ChatGPT

Peça para o ChatGPT padrão gerar um texto curto sobre um assunto de seu interesse. Em seguida, acesse a página do GPT-Tokenizer, cole esse texto e observe como o modelo do GPT separa as palavras para gerar 'x' tokens.

2. Playground OpenAI: Brincando com Modelos e Temperaturas no Modo Chat

Crie uma conta na OpenAI, acesse o Playground, selecione o modo 'Chat' e experimente com os diferentes modelos e temperaturas. Gere o mesmo texto em diferentes temperaturas e analise as diferenças entre elas.

3. Gerando Mensagens com base em Notas dos Alunos: Usando a API_KEY

Usando o código do Sérgio e a sua API_KEY, faça a alteração no campo "content:" de 'role: "system"' no código, com o objetivo de gerar uma mensagem personalizada e carinhosa para cada aluno(a), com base na nota que ele(a) recebeu.

### Links
- [Link da ferramenta: Script](https://www.google.com/script/start/)
- [Link da ferramenta: Eightify - Resumos de vídeos do Youtube com ChatGPT.](https://eightify.app/)
- [Link da ferramenta: Gamma - cria slides](https://gamma.app/)
- [Link da ferramenta: Jasper - cria conteúdo para blog](https://www.jasper.ai/free-trial?_from=ads&fp_sid=1-g-Cj0KCQjwnMWkBhDLARIsAHBOftp3-2_GQsww0SIqFbn0x56rZWHUlJDDIFeF8UskgLWHk9we0Us-dKAaAsk1EALw_wcB)
- [Link para a Planilha de notas (Lembre-se de fazer uma cópia da planilha para conseguir editar)](https://docs.google.com/spreadsheets/d/1jMZToQ1y5aThfBIG8U8H00V4CEdujRgn4hmuiXjjy5A/edit?usp=sharing)
- [Link para o GPT Tokenizer](https://gpt-tokenizer.dev/)
- [Link para o Código para gerar um email com a API do GPT](https://gist.github.com/sergiolopes/faf25d8781f4340edfc65a11b37ceb60)
- [Link para a ferramenta: ElevenLabs - gera texto para fala](https://elevenlabs.io/)
- [Link para a ferramenta: Whisper - fala para texto](https://huggingface.co/spaces/openai/whisper)
- [Link para o conteúdo apresentado na live: 7 ferramentas de IA além do chatGPT](https://docs.google.com/presentation/d/1YWqJEKJxJToQNFKL-vpQ26ojem2oV60sxnD4TtB4dq0/edit?usp=sharing)
