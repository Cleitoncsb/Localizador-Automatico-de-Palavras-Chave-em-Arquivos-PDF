<h1>Localizador de palavras em arquivos PDF</h1>


![Localizador de palavras](https://github.com/Cleitoncsb/Analise-de-Dados-de-uma-Cafeteria-com-Python/assets/142935223/18dfc511-c4bb-455b-8332-c12018c442c3)



 <h2> 📌 Overview   </h2>
 
Esse código automatiza a busca de palavras-chave específicas em arquivos PDF dentro de um diretório, fornecendo um resumo de cada palavra-chave encontrada, 
facilitando a busca e o gerenciamento de informações em grandes conjuntos de documentos PDF.

<h2> ⚙️ Como o código pode ser usado </h2>


Certamente, o código pode ser utilizado em diversas situações, como:

<h3>Recrutamento e Seleção:</h3>Para encontrar rapidamente currículos que contenham habilidades ou qualificações específicas, como "Python", "Gestão de Projetos" ou "Design Gráfico".
<h3>Pesquisa Acadêmica:</h3> Para pesquisar rapidamente em uma coleção de artigos científicos ou documentos de pesquisa por termos técnicos específicos ou nomes de autores.
<h3>Análise Legal:</h3> Para localizar referências a casos específicos, leis ou terminologias jurídicas em grandes volumes de documentos legais ou contratos.
<h3>Auditoria de Documentos:</h3> Em empresas ou organizações, para verificar a presença de termos de conformidade, como "segurança de dados" ou "regulamentação financeira", em relatórios internos e documentos de políticas.
<h3>Gestão de Conhecimento:</h3> Para catalogar arquivos PDF em um repositório de documentos com base em palavras-chave relevantes para diferentes departamentos ou projetos.
<h3>Monitoramento de Marca:</h3> Para empresas que desejam monitorar a menção de suas marcas ou produtos em relatórios da indústria ou publicações de pesquisa.

<h2> 📊 Resultados e Insigths</h2>
O resultado do código acima retorna algumas informações sobre o arquivo, incluindo o diretório escolhido, as palavras encontradas no arquivo, a aderência à busca, a quantidade de palavras-chave buscadas e a quantidade de palavras-chave encontradas.
<br>

![Captura de Tela 2023-12-13 às 12 26 54](https://github.com/Cleitoncsb/Analise-de-Dados-de-uma-Cafeteria-com-Python/assets/142935223/cde06aef-3d74-45c0-9cf3-57c1be1c22ee)


<h2>Sobre a Metodologia</h2>
A aplicaçāo utilizada no código, segue os seguintes passos:</>

<h3> 1. Definindo o Diretório e Palavras-Chave:</h3> Primeiramente, o código estabelece o local (diretório) onde os arquivos PDF estão armazenados e as palavras-chave que você deseja buscar nesses arquivos.<br>
<h3> 2. Varredura dos Arquivos PDF:</h3> Em seguida, ele percorre todos os arquivos no diretório especificado, identificando aqueles que têm a extensão ".pdf".<br>
<h3> 3. Leitura e Análise dos PDFs:</h3> Para cada arquivo PDF encontrado, o script usa a biblioteca PyPDF2 para abrir e ler o conteúdo de cada página do documento.<br>
<h3> 4. Busca de Palavras-Chave:</h3> Enquanto lê cada página, o código verifica a presença das palavras-chave definidas. Cada vez que uma palavra-chave é encontrada, ela é registrada.<br>
<h3> 5. Compilação dos Resultados:</h3> O script compila os resultados, mostrando em quais arquivos e com que frequência as palavras-chave foram encontradas. Isso é útil para entender a relevância e a distribuição das palavras-chave nos documentos.<br>
<h3> 6. Resumo da Busca:</h3> Finalmente, ele fornece um resumo que inclui o número total de palavras-chave buscadas, quantas foram encontradas e uma medida de "aderência" - basicamente, quão bem os documentos correspondem às palavras-chave buscadas.<br>
