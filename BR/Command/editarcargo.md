# Comando de Gerenciamento

## Nome do comando
> **editarcargo**

## Descrição
> Este comando é uma opção para editar cargos, ele tem suporte para editar um ou vários cargos.

## Argumentos
- nome - `Obrigatório` - Nome do cargo para editar.
- novo - `Opcional` - Novo nome do cargo.
- hex - `Opcional` - Cor do cargo ('#')
- vis - `Opcional` - Visibilidade ao cargo, ou, separar um cargo de outros membros, use "true/false".

> [!NOTE]
> Os opcionais se tornarão obrigatórias caso você não tenha escolhido pelo menos **UM** argumento!

## Permissões necessárias
> [!NOTE]
> Para usar este comando, você deve ter permissão de **`Manage Roles | Gerenciar Cargos`**.

## Exemplo
> `$editarcargo nome="Moderador" novo="[M] Moderador"`

> `$editarcargo nome="Moderador" novo="[M] Moderador" hex=#ffd200`

> `$editarcargo nome="Moderador" novo="[M] Moderador" hex=#ffd200 | nome= "Admin" novo="[A] Admin" vis=false`