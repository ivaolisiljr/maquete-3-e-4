# Maquetes 3 e 4 - AutoLISP

Repositório preparado para armazenamento privado no GitHub.

## Situação

- **Maquete 3:** desenhos individuais e montagens em estágio P0; processos de fabricação sendo refeitos do zero, uma folha por arquivo.
- **Maquete 4:** ainda não iniciada. As pastas foram criadas para receber os próximos arquivos.

## Regra de arquivos

- Um arquivo `.lsp` gera uma única folha.
- Cada arquivo possui um comando `*_GERAR` e um comando `*_AUDITAR`.
- Arquivos em `Obsoletos` não devem ser usados para fabricação.
- Os processos correntes da placa-base são F01 a F04, reconstruídos do zero.

## Estrutura

- `M3/01_Desenhos_Pecas/Atuais`
- `M3/02_Desenhos_Montagem/Atuais`
- `M3/03_Processos_Fabricacao/Atuais`
- `M3/04_Auditorias`
- `M3/05_Dados_Controle`
- `M3/99_Decisoes_Projeto`
- `M4/...`

## Validação

Os arquivos foram submetidos a auditoria estática. A validação visual e dinâmica ainda deve ser feita no AutoCAD Mechanical 2025 PT-BR antes da fabricação final.
