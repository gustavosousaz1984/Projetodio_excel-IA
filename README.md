# Projetodio_excel-IA
# Projeto De Investimernto de simulador para investimento em Fundos Imobiliarios.
Para o êxito deste projeto, considero essencial a revisão criteriosa de todas as vídeo-aulas que fiz da DIO. Este material contém os conceitos fundamentais sobre Fundos de Investimento Imobiliário (FIIs) e as funcionalidades necessárias do Excel para a construção do simulador.
Recomendo anotar as principais fórmulas e conceitos que serão aplicados.

Os pontos-chave a serem focados durante essa revisão incluem:

A geração de renda por FIIs (proveniente de aluguéis e dividendos).
Os conceitos de rentabilidade e valorização da cota.
A identificação das perguntas típicas de investidores que a planilha deve responder, 
(ex: valor a ser investido, prazo, rendimento esperado e montante acumulado).
Estrutura da Planilha de Simulação
A concepção da planilha envolve a definição clara das entradas de dados e dos resultados a serem apresentados.

Dados de Entrada (Inserção do Usuário)
Os seguintes dados deverão ser fornecidos pelo usuário para a simulação:

*Valor do investimento mensal.
*Prazo do investimento (expresso em meses ou anos).
*Perfil do Investidor, que pode ser (conservador,Moderado e agresivo).

A planilha deverá calcular e exibir os seguintes resultados:

Patrimônio total acumulado (considerando o valor das cotas e os dividendos reinvestidos).
Dividendos mensais recebidos .

ersonalização do Perfil de Investidor
Para tornar a simulação ainda mais realista e alinhada aos objetivos do usuário, implementamos um sistema de seleção de perfis de investidor. Uma tabela de apoio com chaveamento foi desenvolvida para alimentar um PROCV, permitindo que, através de uma lista suspensa, o usuário escolha entre os seguintes perfis:

Conservador: Ideal para quem busca maior segurança e menor exposição a riscos, com uma alocação específica em tipos de FIIs de menor volatilidade.
Moderado: Para quem aceita um risco equilibrado em busca de retornos um pouco maiores, com uma diversificação entre FIIs de diferentes características.
Arrojado: Direcionado a investidores que buscam maior rentabilidade e estão dispostos a assumir mais riscos, com maior foco em FIIs com potencial de valorização.
A seleção do perfil altera dinamicamente os percentuais investidos em cada tipo de FII, simulando estratégias de alocação de carteira de acordo com o perfil escolhido.


