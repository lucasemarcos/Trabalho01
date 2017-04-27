# TRABALHO 01
Projeto desenvolvido durante a disciplina de BD

# Sumário

### 1.COMPONENTES<br>
Lucas Cerqueira e Marcos Matos<br>

### 2.INTRODUÇÃO E MOTIVAÇAO<br>
Este documento contém a especificação do projeto do banco de dados "SegCondo". 
A motivação do Projeto foi a falta de segurança encontrada em alguns condominios, onde existe um controle ineficiente de entrada de veiculos. O projeto tem como finalidade, atraves de uma camera e escaneando a placa de um veiculo, controlar o acesso dos veiculos a um condominio de forma a agilizar o trabalho da portaria e otimizar a segurança do acesso ao condominio.  <br>

### 3.MINI-MUNDO<br>
Considerando a insegurança de muitos condominios, no que diz respeito ao acesso de veiculos, onde utiliza-se adesivos que indicam o simbolo do condominio ou até mesmo o bom-senso do porteiro para identificação dos veiculos e sendo esses metodos facilmente burlados por invasores. Criaremos um sitema para facilitar o trabalho do porteiro e otimizar a segurança do condominio. Será feito atraves de uma camera o reconhecimento da placa do veiculo que solicita entrada, as informações serão processadas e as letras e os numeros da placa serão pesquisados em um banco de dados que contera informações do carro e de seu proprietario, após a pesquisa, o porteiro sera notificado com informações referente ao veiculo e sua autorização ou não- caso não seja um veiculo cadastrado - para entrar no condominio. O sistema oferecera ao operador ainda opções para cadastra, alterar e excluir dados referentes aos veiculos e seus proprietarios. <br>

### 4.RASCUNHOS BÁSICOS DA INTERFACE (MOCKUPS)<br>
neste ponto a codificação não e necessária, somente as ideias de telas devem ser criadas, o princípio aqui é pensar na criação da interface para identificar possíveis informações a serem armazenadas ou descartadas <br>

![Alt text](https://github.com/lucasemarcos/Trabalho01/blob/master/SegCondo.pdf "SegCondo")


### 5.MODELO CONCEITUAL<br>
    a) NOTACAO ENTIDADE RELACIONAMENTO
![Alt text](https://github.com/lucasemarcos/Trabalho01/blob/master/Modelo_conceitual.PNG "Modelo Conceitual")
    
    b) NOTACAO UML (Caso esteja fazendo a disciplina de analise)

#### 5.1 Validação do Modelo Conceitual
    [Grupo01]: [Nomes dos que participaram na avaliação]
    [Grupo02]: [Nomes dos que participaram na avaliação]

#### 5.2 DECISÕES DE PROJETO
    [atributo]: [descrição da decisão]
    
    EXEMPLO:
    a) Campo endereço: em nosso projeto optamos por um campo multivalorado e composto, pois a empresa 
    pode possuir para cada departamento mais de uma localização... 
    b) justifique!

#### 5.3 DESCRIÇÃO DOS DADOS 
Morador: Tabela que armazena as informações relativas ao Morador.<br>
Nome: campo que contém o nome completo do morador.<br>
CPF: campo que armazena o número de Cadastro de Pessoa Física do morador.<br>
RG: Campo que armazena o Registro Geral do morador.<br>
Sexo: campo responsavel pelo armazenamento do genero do morador.<br>
Data de Nascimento: Data em que o morador nasceu.<br>
<br>
Veiculos: Tabela que armazena as informações relativas aos Veiculos.<br>
Placa: campo que armazena dados da placa do veiculo.<br>
Marca: Empresa fabricante do modelo.<br>
Chassi: Código único do carro.<br>
Modelo: Campo que armazena o modelo do carro.<br>
Cor: Campo que armazena a cor correspondente do veiculo.<br>
<br>
Contato: Tabela que armazena as informações relativas aos Contatos.<br>
Residencial: Campo do telefone Fixo do morador.<br>
WhatsApp: Número de contato do WhatsApp.<br>
Celular: Número de contato movel.<br>
E-mail: Endereço eletronico.<br>
<br>
Endereço: Tabela que armazena as informações relativas ao Endereço.<br>
Bloco: Campo que guarda o numero ou letra de um predio dentro do condominio.<br>
Número: Campo do número do endereço do condominio.<br>
Cidade: Campo que armazena a cidade correspondente ao endereço do condominio.<br>
Estado: Campo que armazena a estado correspondente ao endereço do condominio.<br>
País: Campo que armazena a localização nacional do condominio.<br>
Rua: Nome da rua.<br>
Bairro: Nome do Bairro.<br>
CEP: Codigo referente ao endereço do condominio.<br>
Numero do Apartamento: Campo que armazena o numero do Apartamento.<br>
Complemento: Informações adicionais.<br>


### 6	MODELO LÓGICO<br>
![Alt text](https://github.com/lucasemarcos/Trabalho01/blob/master/Modelo_Fisico.PNG "Modelo Logico.")
### 7	MODELO FÍSICO<br>

        Entrega até este ponto em (data a ser definida)
        
 
### 8	INSERT APLICADO NAS TABELAS DO BANCO DE DADOS<br>
#### 8.1 DETALHAMENTO DAS INFORMAÇÕES
        Detalhamento sobre as informações e processo de obtenção ou geração dos dados.
        Referenciar todas as fontes referentes a :
        a) obtenção dos dados
        b) obtenção de códigos reutilizados
        c) fontes de estudo para desenvolvimento do projeto
        
#### 8.2 INCLUSÃO DO SCRIPT PARA CRIAÇÃO DE TABELA E INSERÇÃO DOS DADOS
        a) inclusão das instruções para criação das tabelas e estruturas de amazenamento do BD
        b) inclusão das instruções de inserção dos dados nas referidas tabelas
        c) inclusão das instruções para execução de outros procedimentos necessários


        Entrega até este ponto em (data a ser definida)
        
### 9	TABELAS E PRINCIPAIS CONSULTAS<br>
OBS: Incluir para cada tópico as instruções SQL + imagens (print da tela) mostrando os resultados.<br>
#### 9.1	CONSULTAS DAS TABELAS COM TODOS OS DADOS INSERIDOS (Todas) <br>
#### 9.2	CONSULTAS DAS TABELAS COM FILTROS WHERE (Mínimo 3) <br>
#### 9.3	CONSULTAS QUE USAM OPERADORES LÓGICOS, ARITMÉTICOS E CAMPOS RENOMEADOS (Mínimo 2)<br>
#### 9.4	CONSULTAS QUE USAM OPERADORES LIKE (Mínimo 3)  <br>
#### 9.5	ATUALIZAÇÃO E EXCLUSÃO DE DADOS (Mínimo 6)<br>
#### 9.6	CONSULTAS COM JUNÇÃO (Todas Junções)<br>
#### 9.7	CONSULTAS COM GROUP BY (Mínimo 5)<br>
        Entrega até este ponto em (data a ser definida)
        
#### 9.8	CONSULTAS COM LEFT E RIGHT JOIN (Mínimo 4) <br>
#### 9.9	CONSULTAS COM SELF JOIN (todas) E VIEW (mais importantes) <br>
#### 9.10	SUBCONSULTAS (Mínimo 3) <br>
### 10	ATUALIZAÇÃO DA DOCUMENTAÇÃO DOS SLIDES<br>
### 11	DIFICULDADES ENCONTRADAS PELO GRUPO<br>

        Entrega até este ponto em (data a ser definida)
        
### 12  FORMATACAO NO GIT: https://help.github.com/articles/basic-writing-and-formatting-syntax/
