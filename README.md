Gerenciamento Inteligente de Energia com Streamlit e API

Este repositório contém um aplicativo interativo desenvolvido em Python e Streamlit, que permite o gerenciamento e a otimização do consumo energético. O sistema inclui funcionalidades como gráficos de consumo, sugestões de economia geradas por IA, alternância de fontes de energia e consulta ao preço do kWh para diferentes cidades usando uma API.

📋 Funcionalidades

	•	Gráficos Interativos:
	•	Exibição do consumo total de energia.
	•	Previsão de consumo energético com base em dados históricos.
	•	Comparação de consumo entre fontes de energia (rede elétrica e solar).
	•	Sugestões de Economia:
	•	Integração com IA para fornecer estratégias personalizadas de economia de energia.
	•	Análise baseada no consumo, período e preço atual do kWh.
	•	Consulta de Preço do kWh:
	•	Consulta ao preço do kWh para cidades específicas usando uma API de tarifação energética.
	•	Configuração simples para visualizar o custo de energia na localidade selecionada.
	•	Alternância de Fontes de Energia:
	•	Alternância dinâmica entre rede elétrica e energia solar com base na disponibilidade da energia solar.

📂 Estrutura do Projeto

├── app.py                 # Código principal do aplicativo
├── requirements.txt       # Dependências necessárias para o projeto
├── README.md              # Documentação do repositório

🛠️ Tecnologias Utilizadas

	•	Python: Linguagem principal para o desenvolvimento.
	•	Streamlit: Framework para criação de interfaces web interativas.
	•	Plotly: Visualização de dados interativos.
	•	Requests: Integração com APIs externas.
	•	Ollama: Integração com IA para geração de respostas.

🚀 Como Executar

	1.	Clone o repositório:

 git clone https://github.com/seu-usuario/gerenciamento-energia.git
 cd gerenciamento-energia

	2.	Instale as dependências:
 pip install -r requirements.txt
 
 	3.	Execute o aplicativo:
  streamlit run app.py

  	4.	Acesse o aplicativo no navegador: http://localhost:8501

🔧 Configuração da API

API para Consulta de Preço do kWh

Certifique-se de adicionar a chave de API no código antes de executar:

api_key = "SUA_CHAVE_API"  # Substitua pela chave da API Infosimples

Se não tiver uma chave de API válida, você pode utilizar o simulador de dados implementado.

📊 Funcionalidades em Detalhe

Painel de Gráficos

	•	Apresenta o consumo total e diário de energia.
	•	Permite prever o consumo dos próximos dias com base em médias históricas.

Sugestões de Economia de Energia

	•	Sugestões personalizadas geradas com IA, considerando:
	•	Consumo total de energia.
	•	Período selecionado.
	•	Fonte de energia utilizada.
	•	Preço atual do kWh.

Configuração de Tarifas

	•	Permite a consulta do preço do kWh para uma cidade específica.
	•	Exibe os resultados diretamente na interface.

📝 Exemplo de Uso

Consultar o preço do kWh

	1.	Vá até a aba Configurações.
	2.	Digite o nome da cidade.
	3.	Clique em Consultar Preço do kWh para visualizar o custo atualizado.

Gerar sugestões de economia

	1.	Navegue até a aba Sugestões de Economia.
	2.	Insira o consumo total e o período de tempo.
	3.	Clique em Gerar Sugestão para obter estratégias personalizadas de economia.

📋 Requisitos

	•	Python 3.8+
	•	Conexão com a Internet para integração com APIs e IA.

🛡️ Licença

Este projeto está licenciado sob a MIT License.

🤝 Contribuições

Contribuições são bem-vindas! Siga os passos:
	1.	Faça um fork do projeto.
	2.	Crie sua branch para as alterações:

 git checkout -b minha-feature

 	3.	Envie um pull request.

📜 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

👨‍💻 Autores

Desenvolvido por: Alan de Souza Maximiano – 557088.
Danilo Ramalho Silva – 555183
João Vitor Pires da Silva – 556213
