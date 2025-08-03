# Comando Administrativo

## Nome do comando
> excluircargo

## Descrição
> Este comando exclui cargos, ele tem suporte para deletar um ou vários cargos

## Argumentos
- nome - `Obrigatório` - Nome do cargo.

## Permissões necessárias
> [!NOTE]
> Para usar este comando, você deve ter permissão de `Manage Roles | Gerenciar Cargos`

## Exemplo
> Básico:
`$excluircargo nome="Moderador"`

> Múltiplos cargos:
`$excluircargo nome="Moderador" | nome="Admin" | nome="Owner"`