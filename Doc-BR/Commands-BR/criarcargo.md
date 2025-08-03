# Comando Administrativo

## Nome do comando
> criarcargo

## Descrição
> Este comando é uma boa opção para criar cargos, ele tem suporte para criar um ou vários cargos

## Argumentos
- nome - `Obrigatório` - Nome do cargo.
- hex - `Opcional` - Cor do cargo ('#')
- vis - `Opcional` - Visibilidade ao cargo, ou, separar um cargo de outros membros, use "true/false".
- perm - `Opcional` - Setaria permissões para tal cargo, os tipos são: 'Mod', 'Adm', 'Leitura', 'Tudo', 'Escrever'

## Permissões necessárias
> [!NOTE]
> Para usar este comando, você deve ter permissão de `Manage Roles | Gerenciar Cargos`

## Exemplo
> Básico:
`$criarcargo nome="Moderador"`

> Com outros:
`$criarcargo nome="Moderador" hex=#ffd700 vis=true`

> Múltiplos cargos:
`$criarcargo nome="Moderador" hex=#ffd700 | nome="Admin" vis=true | nome="Owner"`