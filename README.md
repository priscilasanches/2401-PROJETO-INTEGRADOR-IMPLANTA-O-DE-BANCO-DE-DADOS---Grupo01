### _Curso de tecnologia de banco de dados - Centro Universitário Senac_
# Projeto Integrador III: Implantação de Banco de Dados
<p>O presente projeto implementa um <b>banco de dados</b> para uso em um sistema de gerenciamento de notas e boletins escolares, cujo objetivo principal é melhorar a eficiência do processo de registro de notas, cálculo de médias, geração de boletins, comunicados e monitoramento de faltas. Propõe-se uma solução abrangente para a <b>gestão educacional</b>, visando otimizar a interação entre professores e administração.</p>
<p>Na modelagem dos dados, aplicou-se a normalização de tabelas até a Terceira Forma Normal (3FN), visando à redução de redundâncias, garantia na integridade dos dados, facilidade de manutenção, alta escabilidade e desempenho.</p>  
<br>

## Instanciando o BD
Para instanciar o banco de dados deste projeto é necessário ter instalado o MySQL 8.0 ou superior.  
Para melhor visualização e manipulação dos dados aconselha-se o uso do MySQL Workbench.  
<br>
**INSTRUÇÕES:**  
<br>
Baixe o [arquivo DDL](Grupo01_DDL.sql). Ele contém as instruções e comandos para definição da estrutura do banco de dados.   
Caso opte pela utilização do MySQL Workbench, vá na opção _File_, _Open SQL Script_, e escolha o arquivo baixado. Execute as intruções.  
Por linha de comando, siga o padrão:
<code> mysql -u root -p senha seu_banco_de_dados < C:\caminho\para\seu\Grupo01_DDL.sql </code>  
<br>
Para teste do banco de dados disponibilizamos um [arquivo DML](Grupo01_ScriptsDML.sql).  
Siga as instruções acima, lembrando de referenciar o nome do seu banco de dados em USE DATABASE nome_BD.
<br>
<br>

_**Acesse o projeto completo [aqui](Grupo01_Rev03.pdf)**_ 
<br>

_**Assista ao vídeo de demonstração [aqui](https://drive.google.com/file/d/1AFvvSHpcgDdDpOgYTPcLTkLbR0GAQoas/view?usp=sharing)**_  
<br>

## Diagrama de Entidade-Relacionamento
Para melhor visualização da estrutura do BD, segue abaixo a representação de suas entidades e seus relacionamentos.  
<br>
![image](https://github.com/priscilasanches/ReadMePI/assets/90432175/da053af0-ded1-4440-9ed5-42e28a547fe1)    

<br>


### Colaboradores (Grupo 1)
Bruno Giacomelli Chiarello  
Kelvin Santos de Souza Parreira  
Marcio Vianna Júnior  
Priscila Sanches Januário  
Stefani Dal Puppo  
Tatiana Roman  

____________________________________
*O colega Leandro Normandia Tavares, no dia 18/05 informou que não tinha concluído sua etapa e que não a iria fazer, informou ao colega Márcio que iria trancar o curso e que poderiam tirar o nome dele do trabalho.


