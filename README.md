\# Análise de Sazonalidade do Consumo Residencial de Energia Elétrica (Tema 11)



Disciplina: Ciência de Dados

Instituição: UNESP  



\# Pergunta Central
O consumo residencial de energia elétrica apresenta um padrão sazonal claramente identificável ao longo do ano, e esse padrão varia entre as regiões brasileiras?
\# Contextualização
Visto que no cenário nacional a Empresa de Pesquisa Energética e a Operador Nacional do Sistema Elétrico são os mecanismos que estudam respectivamente o comportamento do consumidor brasileiro e os picos sazonais de temperatura na região brasileira para planejamento e operação da malha energética do país, trataremos a "instituição de planejamento energético" como sendo uma associação da EPE com a ONS.

\## Estrutura da pasta:
```text
   data/  #Planilha orginal do projeto
   notebooks/ #Jupyter com a análise exploratória
   requirements.txt  #Arquivos com as dependências
   README.md   #Documentação
```

\## Fonte dos Dados

Fonte: Empresa de Pesquisa Energética (EPE) - Consumo de Energia Elétrica

Link: https://www.epe.gov.br/

Data de Acesso:\*\* 15/09/2026

\##Tecnologias e Depenências:
Python 3.13,
Pandas & NumPy,
Matplotlib & Seaborn,
SciPy,
Jupyter Lab.

\# Como Rodar o Projeto

1\. Clone o repositório:
```bash
   git clone [https://github.com/SEU-USUARIO/tp2-energia-epe.git](https://github.com/SEU-USUARIO/tp2-energia-epe.git)
   cd tp2-energia-epe
```
2\.Crie e ative um ambiente virtual:
```bash
   python -m venv venv
   
   # No Linux/macOS:
   source venv/bin/activate
   
   # No Windows:
   venv\Scripts\activate
```
3\.Instale as dependências:
```bash
   pip install -r requirements.txt
```
4\.Inicie o Jupyter Lab:
```bash
   jupyter lab
```
