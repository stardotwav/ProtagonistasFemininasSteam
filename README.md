## 🎮 Análise de Jogos Digitais com Protagonistas Femininas na Pltaforma Steam

Esse projeto foi desenvolvido em duas etapas: (a) extração de dados de jogos mais populares, e personagens femininas na plataforma Steam; e (b) análise de dados. Ambas as etapas são descritas abaixo.

### ✨ Extração de Dados

Os dados utilizados nesta pesquisa foram obtidos em fevereiro de 2024 por meio de uma aplicação desenvolvida na linguagem Python. A aplicação foi construída utilizando as funcionalidades da biblioteca [Requests](https://requests.readthedocs.io/en/latest/), permitindo a realização de chamadas à API com informações sobre os jogos disponíveis na plataforma Steam.

A API escolhida para este propósito foi a Steam Spy, um serviço de estatísticas fundamentado na API da Valve, desenvolvedora da plataforma Steam. A [Steam Spy](https://steamspy.com/) foi selecionada devido à sua facilidade de filtragem de etiquetas específicas, necessárias para os objetivos desta pesquisa, e por apresentar restrições mais flexíveis na extração de dados.

### ✨ Análise de Dados

Para a análise dos dados usou-se da ferramenta Jupyter Notebook, de forma a gerar gráficos e cruzamento de informações relevantes para a pesquisa. O arquivo contendo as análises feitas se chama: "analisejogos.ipnyb". Já os arquivos utilizados nas análises são "jogosprotagonistafeminina.csv" e "todosjogos.csv". Além disso, a descrição das informações das colunas se encontra na página de informações da [API](https://steamspy.com/api.php).