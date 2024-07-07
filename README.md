## Rodando a aplicação

### Criação do recurso

Para utilizar o módulo Natural Language Understanding da IBM Watson, é necessário configurar um ambiente. Este serviço não é totalmente gratuito; portanto, há um esquema de precificação. A IBM oferece um plano de testes (Lite) com uso gratuito limitado.

### Instalação do módulo de acesso às APIs

Antes de acessar a API utilizando o Python, é necessário instalar o módulo necessário. Você pode fazer isso executando o seguinte comando:

```bash
pip install --upgrade watson-developer-cloud
```

### Integração com a API

É necessário ter criado um recurso no Watson IBM  para colocar seu usuário, senha e versão na área do código

```bash
username='coloque_aqui_seu_usuario',
password='aqui_sua_senha',
version='YYYY-MM-DD'
```

### Funcionando

Para funcionar basta escrever um texto na linha 

```bash
text='Do you like cake?', #O texto precisa ser inglês
```

Em seguida, executar a próxima célula para ter as respostas

```bash
print(json.dumps(response,indent=2))
```
