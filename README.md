Neste projeto, o utilizei o conhecido dataset da competição do Titanic, obtido do Kaggle.  
Na etapa de Análise Exploratória de Dados, procurei responder às seguintes perguntas:  

Q1 - Qual a proporção de sobreviventes para não-sobreviventes, no desastre?  
Q2 - Proporcionalmente, morreram mais homens ou mulheres?  
Q3 - Como o nível social (ou classe a bordo) influenciou na proporção de mulheres que seriam salvas?  
Q4 - De onde partiram a maioria das pessoas que embarcaram no navio?  
Q5 - Como a idade influenciou na proporção de pessoas salvas?  
Q6 - Em qual classe estava a maioria das pessoas que morreu no desastre?  
Q7 - Em qual classe estava a maioria das pessoas que se salvou no desastre?  
Q8. O fato de estar viajando com cônjuges e/ou irmãos influenciou na chance de ser salvo?  
Q9. O fato de estar viajando com pais e/ou filhos influenciou na chance de ser salvo?  
Q10. As pessoas que pagaram taxas maiores tem mais chance de ser salvas?  
Para a construção dos gráficos, empreguei a biblioteca Altair.  
Para a modelagem empreguei o Random Forest Classifier, e otimizei os parâmetros com o GridSearchCV.  
Ao final, apresentei um gráfico construído utilizando a interatividade do Altair, onde é possível visualizar todos os dados simultaneamente, aplicando filtros, para entender melhor o problema.  
