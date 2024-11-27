# Projeto de Automação web
## Tecnologias utilizadas:
- **Selenium WebDriver, Junit, Cucumber, Maven**
- Utilizado Design Patters **Page Objects e Page Factory**

## Estrutura do Projeto

- **features/**: Cenários escritos em Gherkin.
- **pages/**: Mapeamento de elementos.
- **tasks/**: Ações das páginas.
- **steps/**: Passos dos cenários.
- **Runner.java**: Classe de execução dos testes.

## Como clonar o projeto

1. Clonar repositório:
### no terminal usar:
   ```bash
   git clone https://github.com/maiquel-dias/trilha-automacao-2024-desafio-final.git


## Passos do Cenário Principal

```gherkin
Funcionalidade: Fazer a compra de um produto

  Contexto:
    Dado que estou na pagina inicial

  Cenario: Adicionar um item no carrinho de compras
    Dado que clico na categoria monitores
    E clico no produto escolhido
    E clico em adicionar para o carrinho
    E valido a mensagem de confirmação
    E que clico no menu de carrinho
    E clico em fazer pedido
    E preencho os campos do formulário
    Quando clicar no botão comprar
    Entao deve exibir uma mensagem de sucesso
```

## Relatórios

Os relatórios são definidos no diretório `reports/` e gerados para visulização em formato de arquivos `html,xml,json` 

## Conclusão

Desafio proposto para aplicar o conhecimento adquirido com que foram orientados pela capacitação da Dbserver quanto automação web e Design patterns 