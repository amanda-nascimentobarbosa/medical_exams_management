# Dashboard para Controle de ASO (Atestado de SAúde Ocupacional)

## Business Case

Esse projeto é similar a outro projeto que desenvolvi enquanto atuava como residente em Gestão Hospitalar em um Hospital Universitário.

O setor de saúde ocupacional carecia de uma ferramenta que pudesse fazer a gestão dos exames ocupacionais de seus colaboradores. 
Inicialmente, verifiquei que o setor contava com uma planilha de Excel onde todas as informações eram lançadas de forma manual, sem nenhum tipo de automatização e nem visualização, o que resultava em dados duplicados, dados faltantes e dificuldade de se apurar os exames que estavam vencidos de forma rápida. 
Esse projeto foi desenvolvido durante a pandemia do Covid-19, período o qual esses exames foram suspensos, temporariamente, resultando em um grande número de atrasos.

## Solução

Ferramenta:

O dashboard foi desenvolvido no Excel, pois já era utilizada pela equipe, a quantidade de registro era pequena, de fácil manutenção.

Inicialmente, os dados foram validados, as duplicatas removidas, e todos os dados atualizados.

Foram inseridas fórmulas para a geraração informações automáticas:
  - Cálculo da data de vencimento levando em consideração a data do último exame e a periodicidade (semestral ou anual);
  - Cálculo de quantos dias faltam para vencer ou já está vencido;
  - Inserção do status do exames (válido, vencido, menos de 30 dias para vencer, funcionário desligado)
  
  
  ![image](https://user-images.githubusercontent.com/100388639/225771477-dc321b68-06d7-4c84-9023-0de6353e65d3.png)




https://user-images.githubusercontent.com/100388639/225772903-6efcc39d-026b-4c7f-9830-c5d8683b4c8d.mp4

