<h1>Localizador de palavras em arquivos PDF</h1>


![Localizador de palavras](https://github.com/Cleitoncsb/Analise-de-Dados-de-uma-Cafeteria-com-Python/assets/142935223/18dfc511-c4bb-455b-8332-c12018c442c3)



 <h2> 📌 Overview   </h2>
 
Esse código automatiza a busca de palavras-chave específicas em arquivos PDF dentro de um diretório, fornecendo um resumo de cada palavra-chave encontrada, 
facilitando a busca e o gerenciamento de informações em grandes conjuntos de documentos PDF.

<h2> ⚙️ Como o código pode ser usado </h2>


Certamente, o código pode ser utilizado em diversas situações, como:

<h3>Recrutamento e Seleção:</h3> Para encontrar rapidamente currículos que contenham habilidades ou qualificações específicas, como "Python", "Gestão de Projetos" ou "Design Gráfico".<br>
<h3>Pesquisa Acadêmica:</h3> Para pesquisar rapidamente em uma coleção de artigos científicos ou documentos de pesquisa por termos técnicos específicos ou nomes de autores.<br>
<h3>Análise Legal:</h3> Para localizar referências a casos específicos, leis ou terminologias jurídicas em grandes volumes de documentos legais ou contratos.<br>
<h3>Auditoria de Documentos:</h3> Em empresas ou organizações, para verificar a presença de termos de conformidade, como "segurança de dados" ou "regulamentação financeira", em relatórios internos e documentos de políticas.<br>
<h3>Gestão de Conhecimento:</h3> Para catalogar arquivos PDF em um repositório de documentos com base em palavras-chave relevantes para diferentes departamentos ou projetos.<br>
<h3>Monitoramento de Marca:</h3> Para empresas que desejam monitorar a menção de suas marcas ou produtos em relatórios da indústria ou publicações de pesquisa.<br>

<h2> 📊 Resultados e Insigths</h2>
O resultado do código acima retorna algumas informações sobre o arquivo, incluindo o diretório escolhido, as palavras encontradas no arquivo, a aderência à busca, a quantidade de palavras-chave buscadas e a quantidade de palavras-chave encontradas.
<br>

![Captura de Tela 2023-12-13 às 12 26 54](https://github.com/Cleitoncsb/Analise-de-Dados-de-uma-Cafeteria-com-Python/assets/142935223/cde06aef-3d74-45c0-9cf3-57c1be1c22ee)


<h2>Sobre a Metodologia</h2>
A aplicaçāo utilizada no código, segue os seguintes passos:</>

1. Importação de Bibliotecas:<br>
Pandas: Usada para manipular e analisar dados em tabelas (chamadas de DataFrames).<br>
Plotly.express: Uma biblioteca para criar gráficos interativos.<br>
Streamlit: Uma biblioteca para criar aplicações web rapidamente.<br>

2. Configuração Inicial:<br>
st.set_page_config(layout="wide"): Define a configuração da página da aplicação web para usar todo o espaço disponível na tela.<br>

3. Carregar Dados do Excel:<br>
df = pd.read_excel('/caminho/do/arquivo'): Carrega os dados de vendas de um arquivo Excel para uma tabela (DataFrame) chamada df.<br>

4. Preparação dos Dados:<br>
Converte a coluna com datas para um formato de data padrão e cria uma nova coluna chamada "Month" que contém o ano e o mês de cada venda.<br>
Filtro de Mês:<br>
Cria uma lista de meses únicos presentes nos dados e permite que o usuário escolha um mês específico para visualizar, através de um menu na lateral da aplicação.<br>

5. Visualização dos Dados Filtrados:<br>
Mostra na aplicação web os dados filtrados pelo mês escolhido.<br>

6. Criação de Gráficos:<br>
O código divide a tela em diferentes áreas para mostrar gráficos variados.<br>
Cria e exibe gráficos como:<br>
Evolução do faturamento por mês.<br>
Faturamento por dia da semana.<br>
Faturamento por filial da cafeteria.<br>
Faturamento por tipo de produto.<br>
Quantidade de vendas por tipo de produto.<br>

7. Uso dos Gráficos:<br>
Cada gráfico é criado usando plotly.express e exibido na aplicação web com streamlit.<br>
Os gráficos são interativos, permitindo ao usuário explorar os dados de formas diferentes.<br>
