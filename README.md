<p align="center">
    <img width="150px" src="https://angular.io/assets/images/logos/angular/angular.png" align="center" alt="Angular logo" />
    <h2 align="center">
        Angular Simple Loader
    </h2>
    <p align="center">
        O presente projecto, refere-se a um componente loading feito com angular. Um componente loading é um elemento que é exibido enquanto a informação desejada não é carregada, algo no estilo placeholder
    </p>
</p>


## O que foi utilizado
- Angular +12
- Node 14+
- NPM 8+

Instalação do Angular 12

code:: node
    
    npm install -g @angular/cli@12


## Chamada do componente

code:: node

    <app-loading [text]="'Carregando'" [show]="true"></app-loading>

| Propriedade               | Tipo                                                                         | Descrição                             |
| ------------------------- | ---------------------------------------------------------------------------- | ------------------------------------- | 
| `text`                    | String                                                                       | Mensagem a apresentar no carregamento |                                                                                         
| `show`                    | Boolean                                                                      | `true` ou `false`                     |                                                                                         


<p>O componente está dentro de um módulo <b>shared.module.ts.ts</b>, que por sua vez é instanciado no <b>app.module.ts</b></p>

<p>Por fim, temos o resultado 😎</p>

<p aling="center">
    <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcXNtZmo2aDFucmFseW1pYzY4YW5pYnZoOTY1enpyZWc0NXptN3Z3ZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/IjBZbH0aUdQ2YdWWgR/giphy.gif" width="100%">
</p>
