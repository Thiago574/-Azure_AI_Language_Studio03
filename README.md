# Projeto: Laboratório AI-900 no Azure Machine Learning

Este README documenta o processo realizado para testar o **Azure AI Services**, incluindo a configuração de experimentos de **Reconhecimento de Fala (Speech to Text)** e **Análise de Sentimentos** utilizando o **Speech Studio** e o **Language Studio** do Azure AI.

---

## Experimento 1: Reconhecimento de Fala com Speech Studio

### Passos Realizados

1. **Acessando o Azure Speech Studio**  
   Segui a documentação no site: [Lab Speech AI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html).  
   - Acesse o portal do Speech Studio em [https://speech.microsoft.com/portal](https://speech.microsoft.com/portal).  
   - Realizei o login com minha conta da Microsoft.  

2. **Configurando um Recurso no Azure**  
   - No **Speech Studio**, selecionei "Settings" e, em seguida, "Create a resource".  
   - Configurei com os seguintes parâmetros:  
     - Nome do recurso: `TesteSpeechStudio`  
     - Assinatura: `Azure subscription 1`  
     - Região: `Leste dos EUA`  
     - Nível de preço: `Gratuito F0`  
     - Grupo de recursos: `teste`  
   - Cliquei em **Criar recurso** e aguardei a confirmação da criação. Após isso, selecionei **Usar recurso**.  

3. **Executando o Speech to Text**  
   - Na página "Get started with Speech", em **Speech to text**, selecionei "Real-time speech to text".  
   - Realizei o teste com um arquivo de áudio em inglês presente no diretório `input`.  
   - O resultado gerado foi um arquivo `.txt` contendo a transcrição do áudio, salvo no diretório `resultados`.

---

## Experimento 2: Análise de Sentimentos com Language Studio

### Passos Realizados

1. **Acessando o Azure Language Studio**  
   Segui a documentação no site: [Lab Text Analysis](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html).  
   - Acesse o portal do Language Studio em [https://language.cognitive.azure.com](https://language.cognitive.azure.com).  
   - Realizei o login com minha conta da Microsoft.  

2. **Configurando um Recurso no Azure**  
   - Configurei o recurso com as configurações indicadas na documentação:  
     - Nome do recurso: `TesteLanguageStudio`  
     - Região: `Leste dos EUA`  
     - Nível de preço: `Gratuito F0`  
     - Grupo de recursos: `teste`  
   - Após a criação do recurso, configurei no **Language Studio** para utilizá-lo.  

3. **Executando a Análise de Sentimentos**  
   - No **Language Studio**, selecionei a aba **Classificar texto** e, em seguida, o bloco **Analisar sentimento e extrair opiniões**.  
   - Configurei o idioma do texto para **Inglês** e utilizei o recurso configurado.  
   - Realizei o teste com textos de entrada e obtive os resultados de análise de sentimentos e extração de opiniões.  

4. **Resultados**  
   - Os arquivos de entrada e saída (resultados) foram armazenados nos diretórios `input` e `resultados`, respectivamente.  

---

## Diretórios do Projeto

- **input/**: Arquivos de entrada, como o áudio para o Speech Studio e textos para o Language Studio.  
- **resultados/**: Arquivos de saída contendo os resultados dos experimentos, como transcrições de áudio e análises de sentimentos.

---

## Referências

- [Documentação oficial do Speech Studio](https://speech.microsoft.com/portal)  
- [Documentação oficial do Language Studio](https://language.cognitive.azure.com)  
- [Laboratórios do Azure AI Fundamentals](https://microsoftlearning.github.io/mslearn-ai-fundamentals/)
