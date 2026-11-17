# MVP Entrega de Cestas

Protótipo de um sistema para registrar a retirada de cestas básicas em uma organização parceira, com bloqueio automático de segunda retirada no mesmo mês.

> **Todos os dados são fictícios.** Este repositório não contém dados pessoais reais.

## Problema
- Uma mesma família pode retirar mais de uma cesta no mês, e outra deixa de ser atendida.
- A conferência em listas de papel é lenta e gera erros no balcão, com fila esperando.

## O que o MVP faz
1. **Buscar família** por nome ou documento.
2. **Mostrar o status do mês** no próprio resultado (pode retirar / já retirou em [data]).
3. **Registrar a entrega** e bloquear a segunda retirada no mês.
4. **Confirmar o registro** com alertas de estoque e lista dos últimos registros.

## Telas
| Tela | Função |
|---|---|
| 1 | Menu inicial |
| 2 | Buscar família e registrar entrega |
| 3 | Entrega registrada, alertas e últimos registros |

Capturas em `assets/`.

## Documentação (`docs/`)
- [Descrição funcional das telas](docs/descricao-telas.md)
- [Representante do público externo](docs/representante-externo.md)
- [Plano de validação](docs/plano-de-validacao.md) (data, método e tarefas)
- [Critérios de aceitação e regra de decisão](docs/criterios-e-decisao.md)

## Estrutura
```
mvp-entrega-cestas/
├── README.md
├── src/       código do MVP
├── docs/      documentação do projeto
└── assets/    capturas das telas
```

## Como rodar
[Preencher quando o código estiver em `src/`: pré-requisitos e comando de execução.]

## Resultado da validação
[Preencher após o teste com o representante externo: resultados por tarefa, tempos, notas e decisão.]

## Privacidade
Não suba documentos, endereços, telefones ou dados reais de famílias. Este repositório é público...
