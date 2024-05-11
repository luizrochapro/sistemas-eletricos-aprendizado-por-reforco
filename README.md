# Projeto de Otimização do Desligamento de Linhas de Transmissão de Energia Elétrica

Este projeto utiliza algoritmos de aprendizado por reforço para otimizar o desligamento de linhas de transmissão de energia elétrica, visando minimizar impactos negativos para os clientes. O objetivo é reduzir prejuízos financeiros por interrupções no fornecimento de energia, evitar sobrecarga nas linhas e aumentar a confiabilidade do sistema.

## Metodologia

O estudo utiliza o framework Grid2Op com o algoritmo Q-learning para simular cenários de desligamento. Foram utilizados 3 agentes: "DoNothingAgent", "PowerLineSwitch" e "MyAgent", cada um com diferentes estratégias de controle. Os testes foram realizados em dois ambientes: "rte_case5_example", com 5 subestações, e "l2rpn_neurips_2020_track2_small", com 118 subestações.

## Resultados

Os resultados indicam que o agente "PowerLineSwitch" teve melhor desempenho no ambiente menor, enquanto o "MyAgent" se destacou no ambiente maior.

## Conclusão

O estudo conclui que o Grid2Op é uma ferramenta promissora para otimizar o controle de redes elétricas e que o aprendizado por reforço tem grande potencial para tornar os sistemas de energia mais eficientes e sustentáveis.

Se houver mais detalhes sobre o estudo ou se quiser discutir alguma outra questão relacionada, sinta-se à vontade para entrar em contato.

