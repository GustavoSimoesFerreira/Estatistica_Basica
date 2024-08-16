# Análises Estatísticas

Este projeto visa demonstrar, em python, métodos para análise estatística, sendo exemplificada com dados criados sobre saúde.
Inclui análises estatísticas descritivas e testes de normalidade, bem como análises univariadas e multivariadas para um conjunto de dados específico.
As técnicas empregadas incluem testes Qui-Quadrado, Teste T de Student, ANOVA, correlações e regressões.
O objetivo é fornecer uma compreensão detalhada dos dados e suas relações para, por fim, exemplificar práticas comuns na área de ciência de dados e estatística.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- **`Estatistica_Basica/`**: Diretório contendo os dados brutos e arquivos relacionados.
- **`/Analise_estatística.ipynb`**: Jupyter Notebooks com as análises e visualizações.
- **`/analise_estatística.py`**: Scripts Python para análises e funções auxiliares.
- **`/bancomodelo.csv`**: Banco de dados modelo com dados inventados da área da saúde.
- **`/requisitos.txt`**: Arquivo com a lista de pacotes necessários.
- **`README.md`**: Este arquivo.

## Como Rodar o Projeto

- Clone o repositório

	```bash
	git clone https://github.com/GustavoSimoesFerreira/Estatistica_Basica.git
	cd Estatistica_Basica
	```
	
- Instale as dependências

	```bash
	pip install -r requisitos.txt
	```

- Execute o notebook

	Abra o Jupyter Notebook e execute o Analise_estatística.ipynb para replicar as análises e modelagens.

- Resultados

	O notebook Analise_estatística.ipynb apresenta as visualizações e análises detalhadas.
	As principais técnicas utilizadas incluem:
	
	- Análises descritivas (Média, Mediana, Desvio-padrão, ...).
	- Testes de normalidade (Shapiro-Wilk, Kolmogorov-Smirnov, assimetria e curtose).
	- Análises univariadas para dados qualitativos (Qui-Quadrado, Exato de Fisher, McNemar).
	- Correlações (Pearson, Spearman, Tau de Kendall).
	- Análises univariadas para dados quantitativos (Levene, T de Student, ANOVA, Mann-Whitney, Wilcoxon, Kruskal Wallis, Post Hoc de Tukey, PostHoc Conover, PostHoc Dunn).
	- Análises multivariadas (Regressão Linear Simples e Múltipla, Regressão Logística Binária e Multinomial, Curva ROC, Sobrevida de Kaplan-Meier, De Long, Regressão Quantílica).

- Contribuições
	
	Sinta-se à vontade para contribuir com o projeto! Se você encontrar problemas ou tiver sugestões, abra uma issue ou envie um pull request.

- Licença

	Este projeto está licenciado sob a Licença MIT.
