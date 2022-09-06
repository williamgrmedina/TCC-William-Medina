.. figure:: https://github.com/williamgrmedina/TCC-William-Medina/blob/main/logo-uel.jpg
    :align: center
    :alt: UEL Logo

================================================================================================
Avaliação de Ferramentas do Estado da Arte Para Detecção de Erros em Bancos de Dados Relacionais
================================================================================================

Sobre
=====
Empresas e instituições em geral vêm coletando grandes quantidades de dados de
uma variedade de fontes complementares, com o objetivo de executar tarefas analíticas para as suas aplicações e negócios.
No entanto, é comum que conjuntos contenham erros, dificultando severamente análises baseadas em inteligência artificial.
Por isso, um caminho comum é que seja feita uma etapa de "limpeza manual", onde um expert de domínio verifica e corrige dados errôneos, certificando-se que os mesmos estejam corretos.

Ao longo dos últimos anos, diversas ferramentas surgiram com o objetivo de limpar dados de maneira automática ou semiautomatizada, aliviando o fardo de tempo e dinheiro necessário a esse tipo de processo. No entanto, ao melhor de nosso conhecimento, não existem estudos que englobem ferramentas mais recentes como o Raha e o HoloDetect (ambas de 2019) em suas capacidades de detecção de erros.

O objetivo deste estudo foi a análise experimental e atualizada do estado da
arte em detecção automática de erros, sistematizando e mensurando o potencial de cada
ferramenta para o campo de limpeza automatizada de dados, e é resultado da parceria entre os docentes Dr. Daniel dos Santos Kaster e Dr. Eduardo H. M. Pena, em conjunto com o aluno William G. R. Medina, graduando pela Universidade Estadual de Londrina.

Reprodutibilidade do estudo
===========================
Para reproduzir os resultados obtidos pelo presente estudo, instale a ferramenta BART (https://github.com/dbunibas/BART) e altere as porcentagens de erros e os dados para acesso ao SGBD no script desejado (scripts estão presentes na pasta de inserção de erros deste projeto; inserção de erros padrão - meio porcento). A execução da ferramenta BART gerará como resultado um conjunto de dados sujo¹, que pode ser utilizado como entrada a qualquer uma das ferramentas² utilizadas no projeto, observados as eventualidades abaixo.

¹O BART possui um bug de inserção onde algumas tuplas mudam de ordem ou podem ser duplicadas. É necessário que haja a adequação destes fatores para que o resultado seja condizente. 

²Algumas ferramentas exigem entrada em formato diferente.  

