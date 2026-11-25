
# Sistema de Senhas de Atendimento Clínico

## Objetivo
Sistema desenvolvido em linguagem C para cadastrar pacientes,
gerar senhas e organizar filas de atendimento por prioridade.

## Funcionalidades
- Cadastro de pacientes.
- Classificação automática.
- Geração de senhas sequenciais.
- Consulta da próxima senha.
- Chamada e finalização de atendimento.
- Painel de atendimento.

## Classificação
- U: Urgente (idade acima de 80 anos).
- P: Preferencial (condições prioritárias da atividade).
- N: Normal (demais pacientes).

Ordem de atendimento: U > P > N.

## Tecnologias
- Linguagem C.
- Struct e vetores.
- Funções.
- Condições e repetições.

## Compilação

Com GCC:

```bash
gcc main.c -o clinica
```

## Execução

Linux:
```bash
./clinica
```

Windows:
```bash
clinica.exe
```

## Exemplo

Paciente: João
Idade: 85 anos

Resultado: U001

Paciente: Maria
Idade: 30 anos
Gestante: Sim

Resultado: P001

## Autor
Projeto desenvolvido para atividade acadêmica
de programação em linguagem C.
