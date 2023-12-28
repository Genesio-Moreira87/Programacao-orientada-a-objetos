# Programacao Orientada a Objetos

Antes de começar

Faça login na sua conta da Google. Acesse o **Google Colab** e faça o download do arquivo notebook “Profissão Analista de dados M6 Material de apoio”. 

# Nesta tarefa, iremos praticar 2 exercícios. 

Prepare o ambiente

Vamos trabalhar com os arquivos de csv e txt definidos no material de apoio. Execute cada uma das células de código para escrever os arquivos na sua máquina virtual.

# 1º Exercício: Classe para ler arquivos de texto

**Parte 1**: 

Crie a classe ArquivoTexto. Ela deve conter os seguintes atributos:
self.arquivo: atributo do tipo str com o nome do arquivo;
self.conteudo: atributo do tipo list onde cada elemento é uma linha do arquivo;
A classe também deve conter o seguinte método:
self.extrair_linha: Método que recebe como parâmetro o número da linha e retorna o seu conteúdo.

**Parte 2**: 

Utilize o código indicado para testar sua classe. 

# 2º Exercício: Classe para ler arquivos de csv

**Parte 1**:

Crie a classe ArquivoCSV. Ela deve extender (herdar) a classe ArquivoTexto para reaproveitar os seus atributos (self.arquivo e self.conteudo ) e método ( self.extrair_linha ). Além disso, adicione o seguinte atributo:

self.colunas : Atributo do tipo list onde os elementos são os nome das colunas;
A classe também deve conter o seguinte método:

self.extrair_coluna_da_linha : Método que recebe como parâmetro o número da linha e o índice da coluna e retorna o valor em questão.

**Parte 2**: 

Utilize o código indicado no material de apoio para testar sua classe. 

## Autor: Genésio Moreira Coutinho 
- Graduado: Bacharelado em Sistemas de Informação | Pós Graduando:  MBA em Gestão da Qualidade em Tecnologia da Informação |Analista de Dados| 1x Azure - AZ900
- Date Analyst | Cloud Infrastructure | Azure | Analista Cloud | Analista Dados | Infraestrutura Cloud | Python
- Linkedin: https://www.linkedin.com/in/genesio-coutinho-554733124/
- Kaggle:https://www.kaggle.com/genesiomoreira

- Notebook para execução dos códigos Google Collab: https://colab.research.google.com/drive/1PoE8QI5EUr7p-Sm2UuMpoUqp6r7kT0a5?usp=sharing
