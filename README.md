
# Speech-to-Search: Transformando Áudio em Informações na Web

Este projeto demonstra o uso de tecnologias de conversão de fala em texto e sua aplicação prática em pesquisas automáticas na web. A solução, que integra processamento de áudio e linguagem natural, conecta voz a informações relevantes, podendo ser aplicada em assistentes pessoais, sistemas de pesquisa acadêmica e ferramentas de acessibilidade, destacando a utilidade da inteligência artificial e do NLP em tarefas de pesquisa.

## Desenvolvimento
O projeto foi desenvolvido no Google Colab, utilizando Python e bibliotecas especializadas. A estrutura do pipeline inclui três etapas principais:
1. **Conversão de Áudio (m4a para wav):** Utiliza a biblioteca `pydub` para preparar arquivos de áudio no formato `.m4a` para serem processados em etapas posteriores.
2. **Transcrição de Fala para Texto:** Emprega a biblioteca `SpeechRecognition` para interpretar arquivos de áudio e convertê-los em texto, usando a API de reconhecimento de voz do Google.
3. **Pesquisa no Google:** Com a transcrição gerada, a biblioteca `googlesearch-python` é utilizada para buscar informações relevantes na web, retornando links que respondem à consulta transcrita.

## Tecnologias Utilizadas
- **Google Colab:** Ambiente de desenvolvimento para prototipação rápida e integração de código.
- **Python:** Linguagem principal utilizada, escolhida pela sua versatilidade e ampla disponibilidade de bibliotecas.
- **Pydub:** Manipulação de arquivos de áudio, essencial para a conversão entre formatos.
- **SpeechRecognition:** Transcrição de áudio para texto, aproveitando a robustez da API do Google Speech.
- **Googlesearch-python:** Ferramenta para realizar pesquisas automatizadas no Google e coletar resultados.
