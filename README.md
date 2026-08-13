### Escopo da Função
### Dentro de uma função, todas as variáveis declaradas com var, let, const, tem ou possuem Escopo de Função nesse exemplo: 
### function myfunction() {
###   var x = 1;
###   let y = 2;
###   const z = 3;
### }
### //x não pode ser usado aqui
### //y não pode ser usado aqui
### //z não pode ser usado aqui

&nbsp;

| Declaração | Escopo real | No exemplo |
|------------|-------------|----------------|
| `var x`    | Função      | Fica na função |
| `let y`    | Bloco       | Fica na função (pois a função é o bloco mais externo) |
| `const z`  | Bloco       | Fica na função (pois a função é o bloco mais externo) |

&nbsp;

<a href="https://github.com/user-attachments/assets/c3c5de1b-11cf-4a78-a5ef-cc1f30c9e620" >
  <img width="100%" alt="html-javascript" src="https://github.com/user-attachments/assets/c3c5de1b-11cf-4a78-a5ef-cc1f30c9e620"/>
</a>

&nbsp;

