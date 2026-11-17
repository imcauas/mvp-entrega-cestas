# Descrição funcional das telas

## Tela 2: Buscar família

**Função central:** localizar uma família e registrar a entrega da cesta, bloqueando a duplicidade no mês.

**Dor que resolve:** controle de duplicidade e lentidão no balcão. O status de retirada aparece no próprio resultado, em cor, símbolo e texto.

**Sequência**
1. O voluntário vem do menu e digita nome ou documento em "Nome ou documento".
2. A lista mostra cartões com responsável, número de pessoas na casa e status do mês.
3. Quem pode retirar mostra "✓ Pode retirar a cesta" e botão "Registrar entrega" ativo.
4. Quem já retirou mostra "✗ Já retirou em [data]", botão desabilitado e a explicação "Indisponível: esta família já retirou a cesta neste mês."
5. Se a família não aparece, o link "Não encontrou? Cadastrar nova família" leva ao cadastro. "Voltar ao menu" sai da tela.

**Campo:** "Nome ou documento" (texto livre, obrigatório para iniciar a busca).

**Resultados**
- Confirmar: a entrega é gravada com data e responsável e o status passa a "Já retirou".
- Cancelar ou voltar: nada é alterado.

**Requisitos**
- RF1 buscar por nome ou documento. RF2 exibir situação do mês. RF3 registrar entrega. RF4 impedir segunda retirada no mês. RF5 cadastrar família não encontrada.
- Segurança: bloqueio feito pelo sistema, mínimo de dados no resultado, documento mascarado (LGPD), validação do campo de busca, registro de data e responsável, acesso só para voluntários autenticados.

## Tela 3: Entrega registrada

**Estados apresentados**
- Confirmação: "✓ Cesta entregue com sucesso", com nome, pessoas na casa, data, hora, voluntário e data da próxima retirada.
- Alerta de estoque: "! Estoque baixo: restam 12 cestas".
- Indicadores do dia: entregas realizadas e bloqueios por duplicidade.
- Últimos registros: entregas (✓) e bloqueios (✗, com a data da retirada anterior).

**Quem consulta e decisão:** o voluntário confirma a gravação e decide se atende a próxima família ou desfaz um registro errado. A coordenação usa o alerta e os contadores para repor estoque ou revisar duplicidades.

**Ações:** "Buscar outra família" (principal), "Desfazer esta entrega" (com confirmação) e "Voltar ao menu".

## Acessibilidade
- A cor nunca é a única informação: sucesso (verde, ✓, "Entregue"), bloqueio (vermelho, ✗, "Bloqueada: já retirou em…") e alerta (amarelo, "!", "Estoque baixo").
- Confirmação e alerta usam marcações de status e alerta para leitores de tela.
- Botões com 52 px de altura e largura total, rótulos em verbo de ação, contraste alto.
- **Barreira atendida:** voluntários com pouca familiaridade digital, em pé, com fila e pressa.
- **ODS:** [preencher o ODS selecionado, ex.: ODS 2]. O impacto se limita ao contexto do parceiro.
