# Plano de validação

## Data prevista
**Quinta-feira, 26/11/2026** (provisória). Se o encerramento da experiência for antes de 30/11, antecipar para 23 ou 24/11. Atualizar este registro se houver mudança.

## Método de teste
- **Modalidade:** presencial, em espaço parecido com o balcão. Alternativa: videochamada com a tela do celular compartilhada.
- **Dispositivo e conexão:** celular do participante (cerca de 6"), com a conexão que ele já usa. Sem logins nem dados pessoais.
- **Versão:** v1, de 16/11/2026 (Telas 1 a 3), com dados fictícios.
- **Duração:** cerca de 15 minutos.

**Roteiro**
1. **Apresentação (2 min):** objetivo acadêmico, participação voluntária, pode parar a qualquer momento. Testa-se a interface, não o participante.
2. **Tarefas (8 min):** leitura em voz alta, uma por vez, com o texto impresso à vista.
3. **Encerramento (5 min):** perguntas abertas sobre o que foi fácil, confuso ou faltou. Os problemas encontrados são oportunidades de melhoria da interface.

**Ajuda:** nenhuma durante a tarefa. Após 1 minuto parado, dica genérica ("o que você faria agora?"), registrada como "com ajuda". A resposta direta só vem ao final da tarefa.

**Dados registrados:** sucesso por tarefa, tempo (cronômetro), erros e hesitações, nota de 1 a 5 por tarefa e geral, comentários literais, identificação como "Participante 1".

**Observação x opinião:** o comportamento (ações, tempo, erros) é anotado na hora. A opinião (notas e comentários) é coletada só no encerramento, em coluna separada. Se divergirem, vale o comportamento observado e a divergência é registrada.

## Tarefas operacionais

### Tarefa 1: Localizar uma família
- **Objetivo:** a partir do menu, encontrar a família que vai receber a cesta.
- **Estado inicial:** protótipo aberto no menu inicial.
- **Dados fictícios:** responsável "Maria Pereira Lima" (existe também "Maria Aparecida Souza").
- **Resultado observável:** o cartão aparece e o participante diz se ela pode retirar a cesta, sem confundir as duas Marias.
- **Ajuda e erro:** dica após 1 minuto parado = "com ajuda". Cada toque fora do caminho = 1 erro.

### Tarefa 2: Registrar a entrega (função central)
- **Objetivo:** registrar a entrega da cesta para a família localizada.
- **Estado inicial:** cartão de "Maria Pereira Lima" com status "Pode retirar".
- **Resultado observável:** aparece a confirmação com nome, data e hora e o participante afirma que a entrega foi gravada.
- **Ajuda e erro:** pedir ajuda ou tocar em "Desfazer" sem querer conta como erro. Registrar o tempo até a confirmação.

### Tarefa 3: Interpretar resultado e alerta (acessibilidade)
- **Objetivo:** explicar o que ocorreu com a família bloqueada e qual ação o alerta pede.
- **Estado inicial:** tela "Entrega registrada", com alerta, contadores e lista.
- **Dados fictícios:** "Maria Aparecida Souza" (bloqueada, retirou em 05/11/2026) e estoque de 12 cestas.
- **Resultado observável:** explica o bloqueio e a ação do alerta e cita ao menos um sinal além da cor (símbolo ✗, texto "Bloqueada" ou data).
- **Ajuda e erro:** interpretação errada = 1 erro. Se só percebeu pela cor, registrar falha de acessibilidade.
