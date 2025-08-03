# Comando de Gerenciamento

## Nome do comando
> criarcargo

## Descrição
> Este comando é uma boa opção para criar cargos, ele tem suporte para criar um ou vários cargos.

## Argumentos
- nome - `Obrigatório` - Nome do cargo.
- hex - `Opcional` - Cor do cargo ('#')
- vis - `Opcional` - Visibilidade ao cargo, ou, separar um cargo de outros membros, use "true/false".

## Permissões necessárias
> [!NOTE]
> Para usar este comando, você deve ter permissão de `Manage Roles | Gerenciar Cargos`.

## Exemplo
> `$criarcargo nome="Moderador"`

> `$criarcargo nome="Moderador" hex=#ffd700 vis=true`

> `$criarcargo nome="Moderador" hex=#ffd700 vis=true | nome="Admin" vis=true | nome="Owner"`