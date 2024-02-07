# TreasureHunt

### Indicações Git
- Quando pegra a ISSUE, mudar assinar com seu nome, criar a branch e subir na mesma branch.
- Ao iniciar a tarefa, comente na issue.
- Ao finalizar tarefa, comente na issue a finalização.
- Quem desenvolve nunca aprova o próprio PR.


### Padrões
ISSUE Título
```
[USxxx] - Titulo da issue aqui
[BUG] - Titulo da issue aqui
```

ISSUE Descrição
```
### Objetivo:
Criação do projeto

### Descrição:
Criar projeto com estrutura base (a mesma que vem quando você cria o projeto) e subir 

### Observações:
N/A

### Definição de pronto (ok/nok):
[--] Descrição da demanda possui detalhamento suficiente para a compreensão do desenvolvimento evitando interrupções durante o desenvolvimento devido a falta de informações.  
[--] Fluxo da aplicação está claro e as quebras que deve ser tratadas dentro do escopo.  
[--] Está claro em qual ambiente a demanda deve ser entregue. 

### Anexo(s):
N/A
```

Commit
```
feat(header): criacao de funcionalidade de novo usario.
no botão 'user', ao clicar chamar o modal 'userModal'
[US0003]
```
- Padrão de nomeclatura:
  - docs: apenas mudanças de documentação;
  - feat: uma nova funcionalidade;
  - fix: a correção de um bug;
  - perf: mudança de código focada em melhorar performance;
  - refactor: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;
  - style: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);
  - test: adicionar ou corrigir testes.

Exemplo commit
```
feat(header): criacao de funcionalidade de novo usario.
no botão 'user', ao clicar chamar o modal 'userModal'
US0003
```
