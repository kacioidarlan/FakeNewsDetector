# FakeNewsDetector
Projeto desenvolvido para Imersão Inteligência Artificial 2ª Edição da Alura com o Google

Fake News Detector
------------------

### Combater desinformação com o poder do Gemini

Este projeto utiliza o poder do Google Gemini para identificar notícias falsas, analisando-as através de um sistema de agentes especializados.

### Arquitetura do Sistema:

O sistema é composto por quatro agentes principais:

1.  **Agente de Verificação de Fatos:**
    
    *   Recebe o texto da notícia.
        
    *   Consulta fontes confiáveis para verificar a veracidade das informações.
        
    *   Classifica a notícia como VERDADEIRA, FALSA ou INCONCLUSIVA.
        
    *   Fornece evidências e links para as fontes que sustentam sua conclusão.
        
2.  **Agente de Detecção de Tendências:**
    
    *   Analisa a notícia para identificar características comuns de fake news:
        
        *   Clickbait
            
        *   Sensacionalismo
            
        *   Teorias da conspiração
            
        *   Propaganda política
            
        *   Outras tendências
            
    *   Apresenta exemplos específicos da notícia que justifiquem sua análise.
        
3.  **Agente de Análise de Sentimento:**
    
    *   Avalia o tom emocional da notícia:
        
        *   Neutro e objetivo
            
        *   Positivo e otimista
            
        *   Negativo e pessimista
            
        *   Alarmista e sensacionalista
            
        *   Outro (especifique)
            
    *   Justifica sua resposta com exemplos da notícia.
        
4.  **Agente de Análise Final:**
    
    *   Recebe as respostas dos três agentes anteriores.
        
    *   Analisa as informações, ponderando a importância de cada agente.
        
    *   Classifica a notícia como CONFIÁVEL, SUSPEITA, INCONCLUSIVO ou FALSA.
        
    *   Gera um relatório final com a classificação e as evidências.
        

### Fluxo do Projeto:

1.  O usuário fornece o texto da notícia.
    
2.  O **Agente de Entrada** recebe o texto e o distribui para os agentes especializados.
    
3.  Cada agente especializado processa a notícia usando prompts específicos para o Gemini.
    
4.  O **Agente de Análise Final** recebe as respostas dos agentes especializados.
    
5.  O **Agente de Análise Final** gera um relatório final com a classificação da notícia e as evidências.
    

### Observações:

*   Este projeto está em desenvolvimento e a precisão da detecção de fake news depende da qualidade dos prompts e da capacidade do Gemini em interpretar as informações.
    
*   É fundamental analisar criticamente as respostas do Gemini e não considerá-las como verdade absoluta.
    

### Próximos Passos:

*   Aperfeiçoar os prompts para cada agente.
*   Avaliação de implementação de novos agentes como: consulta a banco de dados de fake news, análise de deepfakes, análise de checagem de fontes confiáveis, etc
*   Implementar pesquisa na internet para o agente de análise de fatos
*   Implementar a análise através de links fornecidos pelo usuário
*   Implementar a funcionalidade de analisar imagens e vídeos
*   Criar uma interface gráfica para o usuário.
