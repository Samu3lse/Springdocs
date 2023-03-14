# Springdocs

###  @Autowired 

````
    Utilizado para iserir dependências automaticamente. A estrutura Spring é construída sobre injeção de dependência, inserimos as 
    Dependências de Classe por meio do arquivo de configuração do Bean Spring.
````

###   @Component 

````
    Uma anotação que permite ao Spring detectar automaticamente nossos beans customizados. Sem necessidade de varias linhas de código , o Spring vai escanear nosso aplicativo em busca de Classes anotadas com @Component. Instancie-os e injete quaisquer dependências especificadas neles.
````

### @EnableAutoConfiguration

````
    Permite que a classe carregue as dependecias necessarias para a executar a aplicação.
````

### @RestController

````
    Anotação que é usada para criar o controle rest ,faz automaticamente tudo o que o @Controller faz é retornar tudo em JSON e não é necessário utilizar a anotação        @ResponseBody.
````

### @RequiredArgsConstructor

````
     Injeta todas as dependências finais apenas no construtor.
````

### @RequestMapping

````
    Especificar os mapeamentos entre as solicitações e os métodos do manipulador. Para configurar o mapeamento de solicitações da web, você usa a anotação                 @RequestMapping . A anotação @RequestMapping pode ser aplicada ao nível de classe e/ou nível de método em um controlador.
````

### @GetMapping

````
    Usado para mapeiar as solicitações HTTP GET no método do manipulador específico e cria um ponto de extremidade de serviço da Web para buscas.
````

### ComponentScan

````
    Usamos a anotação @ComponentScan junto com a anotação @Configuration para especificar os pacotes que queremos que sejam verificados.
````
### SpringBootApplication

````
    Utilizado para marcar uma Classe de configuração que declara um ou mais métodos ,@Bean e também aciona a configuração automática e a varredura de componentes.
````

### 
