# Boletim Plus

Global Solution 2026/2 · CitizenTech
Disciplina: Compliance, Quality Assurance and Tests.

## Integrantes

| Nome | RM |
|---|---|
| Gustavo Barrios de Araújo | 563358 |
| Phietro Solon Oliveira | 563842 |

## 1. Problema CitizenTech

Em diversas escolas, o responsável costuma saber da nota baixa ou das faltas do filho só no fim do bimestre, quando o boletim em papel chega. Nessa hora, a recuperação já ficou difícil.

O **Boletim Plus** é um boletim digital. O professor registra notas e presenças, e o sistema:

- calcula a média por aluno e disciplina e classifica a situação (aprovado, recuperação, reprovado);
- calcula a frequência e gera um alerta quando ela fica abaixo de 75%;
- indica quais responsáveis devem ser avisados de cada alerta;
- guarda o histórico das mudanças de status dos usuários, para auditoria.

O cidadão ganha acompanhamento escolar em tempo real, sem depender de reunião presencial ou de papel.

## Projeto no Azure DevOps

https://dev.azure.com/RM563358/BoletimPlus (professor convidado como administrador)

## Estrutura

| Arquivo | Conteúdo |
|---|---|
| `Boletim-Plus-Plano-de-Projeto-e-Testes.pdf` | Entrega oficial: Plano de projeto Scrum e Plano de testes |
| `infos.txt` | Identificação do grupo |
| `evidencias/backlog-epics-features.png` | Tela de Backlogs com Epics e Features |
| `evidencias/test-cases-por-feature*.png` | Tela Boards com os Test Cases por Feature |
| `evidencias/work-items/` | Um print por work item: descrição e critério de aceite (Feature e PBI), Sumário e Passos (Test Case) |

Os prints em `work-items/` seguem o padrão `NNN-<tipo>-<id>-<título>.png`. Nos Test Cases, `-1-summary` é a tela de Sumário e `-2-steps` é a tela de Passos.

## Backlog de produto

| Nível | Quantidade |
|---|---|
| Features | 12 |
| Product Backlog Items | 33 |
| Test Cases (positivos e negativos) | 29 |


## Uso de IA generativa

| Ferramenta | Para quê                                  |
| ---------- | ----------------------------------------- |
| Claude     | Apoio na geração do código e da documentação |
