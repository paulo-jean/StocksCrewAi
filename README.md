### **Analista de Ações - Um Aplicativo Streamlit com CrewAi** 🎫🧐🤖

Este projeto utiliza Crew.ai e Streamlit para criar um aplicativo web que funciona como um analista de mercado de ações. Ele permite que você insira o código de uma ação e receba insights sobre o desempenho da ação e notícias relacionadas.

🚨 *ATENÇÃO*: Os resultados das análises feitas pelos agentes de IA não são recomendações de investimentos. Foi feita para fins de aprendizado das tecnologias aqui usadas durante um curso.

**Funcionalidades:** ⚙️

* **Análise de Preço de Ações:** Analisa dados históricos (último ano) para determinar a tendência do preço da ação (alta, baixa ou lateral).
* **Análise de Notícias de Ações:** Resume as últimas notícias relacionadas à ação e sua empresa.
* **Pontuação Medo/Avareza:** Fornece uma pontuação de análise de sentimento com base nos artigos de notícias, indicando o sentimento do mercado (medo ou avareza).
* **Boletim Informativo de Ações:** Gera um boletim informativo de 3 parágrafos abrangente, resumindo a análise, incluindo a tendência de preços, destaques das notícias e considerações futuras.

**Tecnologias Utilizadas:** ⚡

* **Python:** A linguagem de programação principal para o aplicativo.
* **Crew.ai:** Uma estrutura para construir agentes de IA conversacionais.
* **Streamlit:** Uma biblioteca Python para criar aplicativos web.
* **Langchain Tools:** Ferramentas para integrar Crew.ai com várias APIs e serviços.
* **Langchain Groq:** Permite a interação com o modelo de linguagem OpenAI GPT-3.
* **yfinance:** Obtém dados históricos de ações do Yahoo Finance.
* **DuckDuckGoSearchResults:** Pesquisa artigos de notícias usando o DuckDuckGo.

**Como Usar:** ⚙️

1. **Clone o repositório:** Use o Git para clonar este repositório para sua máquina local.
2. **Instale as dependências:** Execute `pip install -r requirements.txt` para instalar as bibliotecas necessárias.
3. **Configure as variáveis de ambiente:** Crie um segredo Streamlit chamado `GRO_API_KEY` e armazene sua chave de API OpenAI lá.
4. **Execute o aplicativo:** Execute `streamlit run app.py`.
5. **Insira um código de ação:** Na barra lateral do Streamlit, insira o código da ação que você deseja analisar.
6. **Clique em "Executar Pesquisa":** Clique no botão para iniciar a análise.
7. **Visualize os resultados:** O aplicativo exibirá o relatório de análise, incluindo a tendência de preços, resumo das notícias, pontuação de medo/avareza e o boletim informativo.

**Desenvolvimento Futuro:**

* Implementar recursos de análise adicionais, como indicadores técnicos.
* Integrar com outras fontes de dados financeiros.
* Melhorar a interface do usuário para uma experiência mais interativa.

**Sinta-se à vontade para contribuir!**

Este projeto é open-source e aceita contribuições. Se você tiver alguma ideia ou melhoria, fique à vontade para criar um pull request.
