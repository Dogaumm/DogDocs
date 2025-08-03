# Comando de Gerenciamento

## Nome do comando
> excluircargo

## Descrição
> Este comando exclui cargos, ele tem suporte para deletar um ou vários cargos.

> [!NOTE]
> Caso tenha mais de dois cargos com o mesmo nome, eles **TAMBÉM** serão excluídos.

## Argumentos
- nome - `Obrigatório` - Nome do cargo.

## Permissões necessárias
> [!NOTE]
> Para usar este comando, você deve ter permissão de `Manage Roles | Gerenciar Cargos`.

## Exemplo
> `$excluircargo nome="Moderador"`

> `$excluircargo nome="Moderador" | nome="Admin" | nome="Owner"`