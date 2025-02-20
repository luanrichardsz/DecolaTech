# Spring Framework
Framework open source desenvolvido para a plataforma Java baseado nos padrões de projetos inversão de controle e injeção de dependência. (Atribuir responsabilidade a um container e recuperar os métodos desejados)

## Spring Módulos
- **Data Acess**  
  - JDBC, ORM, OXM, JMS, TRANSACTIONS  

- **Web**  
  - WEB, PORTIET, SERVIET, STRUTS  

- **RunTime**  
  - AOP, ASPECTS, INSTRUMENTATION  

- **Core Container**  
  - BEANS, CORE, CONTEXT, EXPRESSION LANGUAGE  

## Spring VS Java EE
Só depois da versão 5 do Java EE que a discussão dos dois ficou mais quente.  

## Inversão de Controle
Com IoC, é só deixar o container configurado para não criar repetidamente diferentes objetos.  

## Injeção de Dependências
Padrão de desenvolvimento com a finalidade de manter baixo o nível de acoplamento entre módulos de um sistema.  

## Beans
Objeto criado e gerenciado por um container através do princípio da inversão de controle.  

## Scopes (Escopos)
- **Singleton**  
  - Um único objeto sendo compartilhado por toda a aplicação quando solicitado.  

- **Prototype**  
  - Criando um novo objeto a cada requisição ao container.  

### Tipos de HTTP
- **Request**  
  - Um bean será criado para cada requisição HTTP, mas quando finalizada esse bean é destruído.  

- **Session**  
  - Um bean será criado para a sessão do usuário.  

- **Global**  
  - Um bean para o ciclo de vida do contexto da aplicação.  

## Autowired
Onde deverá ocorrer uma injeção automática de dependência.  

- **byName**: Método set onde corresponde um nome.  
- **byType**: Tipo de classe para inclusão do Bean.  
- **byConstrutor**: Usamos o construtor para incluir a dependência.  
