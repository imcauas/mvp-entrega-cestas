# Critérios de aceitação e regra de decisão

## Critério 1: Taxa mínima de sucesso = 67%
- **Sucesso:** atinge o resultado sozinho, na primeira tentativa.
- **Sucesso com ajuda:** concluiu após dica. Não entra na taxa, mas é registrado.
- **Falha:** não conclui, interpreta errado ou desiste. Na Tarefa 3, citar só a cor também é falha.
- **Conversão:** 67% de 3 tarefas = 2 sucessos sem ajuda (2/3 = 66,7%). Uma tentativa por tarefa.
- **Regra:** a Tarefa 2 precisa ser sucesso obrigatoriamente.
- **Se não atingido:** revisar as telas com falha ou ajuda e repetir o teste com a nova versão.

## Critério 2: Tempo máximo do fluxo central = 60 segundos
- **Tarefa medida:** Tarefa 2 (registrar a entrega).
- **Cronômetro:** inicia após a leitura da tarefa e para quando a confirmação aparece.
- **Esclarecimentos:** não interrompem a contagem e são registrados como ajuda.
- **Fluxo concluído com erro:** vale o tempo total, com os erros anotados.
- **Fluxo não concluído:** falha, tempo desconsiderado.
- **Se não atingido:** achar o trecho mais lento, simplificar e medir de novo.

## Critério 3: Nota mínima de satisfação = 4
- **Pergunta:** "Pensando no que você fez agora, como foi usar essa tela para registrar a entrega?"
- **Escala:** de 1 (muito difícil) a 5 (muito fácil). A nota 4 equivale a "fácil".
- **Aplicação:** uma nota por tarefa e uma geral. Aprovado se a média for igual ou maior que 4. Nota 2 ou menor em qualquer tarefa vira ponto de melhoria.
- **Se não atingido:** cruzar as notas com a observação e os comentários, priorizar a pior tela e reaplicar.

## Regra integrada de decisão

**Falhas críticas:** não concluir a função central, perda ou gravação errada de informação, alerta ou status acessível só pela cor.

| Decisão | Condição |
|---|---|
| Aceito | Os 3 critérios atendidos e nenhuma falha crítica |
| Aceito com ajustes | Sem falha crítica e 2 dos 3 critérios atendidos, ou todos atendidos com nota 2 ou menor, ajuda recorrente ou erro |
| Não aceito | Qualquer falha crítica, ou só 1 critério (ou nenhum) atendido |

**Resultados divergentes**
- Tempo bom, mas falha de compreensão ou acessibilidade: não aceito.
- Tempo ruim, mas sucesso e nota altos: aceito com ajustes, simplificando o trecho lento.
- Nota alta, mas comportamento ruim: vale o comportamento observado.
- Nota baixa, mas desempenho bom: investigar o comentário e priorizar pelo impacto.

**Correção obrigatória antes de implementar:** falhas críticas, falhas na Tarefa 2 e na acessibilidade da Tarefa 3, mensagens que levam a interpretação errada.

**Pode ficar para depois:** ajustes visuais sem impacto, sugestões só de opinião, funções extras (filtros, relatórios).

## Evidências preservadas
Tempos, resultado por tarefa, notas por tarefa e geral, comentários literais do participante (separados da observação) e decisões de revisão (o que mudou, por quê e em qual versão). Identificação apenas como "Participante 1".
