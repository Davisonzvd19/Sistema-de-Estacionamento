# Sistema de Estacionamento em JavaScript

Cadastro e listagem de veículos utilizando 
interface de armazenamento de dados, o localstorage.

## O que é o LocalStorage?

O localStorage, é uma “interface” de armazenamento
de dados, disponível nos navegadores mais atuais do mercado (FF, Chrome, Safari, 
Opera e etc.).

## Usando o localStorage
O localStorage salva dados no computador do visitante, que ficam vinculados ao 
(e apenas acessíveis pelo) seu domínio. E pra usar é bem simples:

### Use o método setItem(nome, valor) para criar/salvar novos itens e o depois o método getItem(nome) para recuperar o valor.

- Exemplo:
> //Cria um item "usuario" com valor "Davison Azevedo"
```
   window.localStorage.setItem('usuario', 'Davison Azevedo');
```

> // Depois, em outra página ou aba, recupera esse item
```
var usuario = window.localStorage.getItem('usuario');
```

> // Remove o item
```
 window.localStorage.removeItem('usuario');
```



