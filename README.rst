.. figure:: https://github.com/williamgrmedina/TCC-William-Medina/blob/main/logo-uel.jpg
    :align: center
    :alt: UEL Logo

================================================================================================
Avaliação de Ferramentas do Estado da Arte Para Detecção de Erros em Bancos de Dados Relacionais
================================================================================================

Sobre
=====
O objetivo deste estudo foi a análise experimental e atualizada do estado da
arte em detecção automática de erros, sistematizando e mensurando o potencial de cada
ferramenta para o campo de limpeza automatizada de dados, e é resultado da parceria entre os docentes Dr. Daniel dos Santos Kaster e Dr. Eduardo H. M. Pena, das universidades UEL e UFPR, respectivamente, em conjunto com o aluno William G. R. Medina, graduando pela Universidade Estadual de Londrina.

Empresas e instituições em geral vêm coletando grandes quantidades de dados de
uma variedade de fontes complementares, com o objetivo de executar tarefas analíticas para as suas aplicações e negócios.
Para garantir bons resultados, um processo de correção e certificação de integridade dos dados é realizado previamente a qualquer atividade de análise. Devido à natureza de erros em dados, processos de correção manual representam uma parcela considerável de custo. Por isso, ao longo dos últimos anos, várias ferramentas surgiram com o objetivo de auxiliar tarefas de análise.  

O presente estudo engloba ferramentas mais relevantes e novidades do mercado sob um único ambiente de testes, trazendo um panorama sobre o estado do ramo de detecção de erros e identificando vantagens em soluções existentes, ao passo que também identifica problemas que necessitam contorno.

Reprodutibilidade do estudo
===========================
Para reproduzir os resultados obtidos pelo presente estudo, instale a ferramenta BART (https://github.com/dbunibas/BART) e altere as porcentagens de erros e os dados para acesso ao SGBD no script desejado (scripts estão presentes na pasta de inserção de erros deste projeto; inserção de erros padrão - meio porcento). A execução da ferramenta BART gerará como resultado um conjunto de dados sujo¹, que pode ser utilizado como entrada a qualquer uma das ferramentas² utilizadas no projeto.

¹Descobrimos que o BART possui um bug de inserção onde, em algumas ocasiões, tuplas podem mudar de ordem ou ser duplicadas. É necessário que haja a adequação destes fatores para que o resultado seja condizente com os nossos estudos. 

²Algumas ferramentas exigem entrada em formato diferente. Adeque o conjunto de dados.  

