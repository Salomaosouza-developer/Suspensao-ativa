# Suspensão ativa
Repositório do projeto de reposição ativa baseada no sistema (Quarter Car)


## O Problema



O conforto e a estabilidade veicular dependem fortemente da resposta dinâmica do sistema de suspensão. Este projeto objetiva modelar matematicamente um sistema de suspensão ativa (baseado no modelo quarter-car com duas massas: suspensa e não-suspensa) e otimizar seus parâmetros internos. Utilizando um conjunto de dados experimentais obtidos no laboratório do CTAI (fornecidos via arquivo dados_suspensao.csv), foi possível comparar a resposta do modelo fenomenológico, regido por Equações Diferenciais Ordinárias (EDOs), com o comportamento físico real do protótipo (dados).



## Tecnologias



Para a simulação numérica e otimização, foi utilizada a biblioteca scipy; para a manipulação dos dados, pandas e numpy; para o controle e regressão linear, scikit-learn; para visualização dos resultados, matplotlib e plotly.



# Como Executar


Tenha o Python propriamente instalado, bem como as bibliotecas citadas e o Jupyter Lab. Após isso, baixe todos os arquivos deste repositório e os mantenha na mesma pasta. Execute o primeiro script (Prova_Final_Estudos_especiais(1)(3)) e depois o segundo (EE12 Final (2)). OBS.: esses dois scripts envolvem execução de métodos numéricos e métodos de otimização com grande quantidade de dados e, portanto, exigirão grande tempo de execução. 
