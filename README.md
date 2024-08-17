# balta.iocourse

- C# é uma linguagem de programação
- .NET é um framework de desenvolvimento

**Do que você precisa:**

- Ter habilidades em algoritmos e estruturas de dados;
- Conhecimento em engenharia de software, como princípios, boas práticas e padrões de arquitetura; Experiência com desenvolvimento de Aplicações Escaláveis;
- Vivência com algumas linguagens de programação como: Python, Golang, Java, Ruby, Elixir, Scala, Clojure, C/C++, C#, JavaScript, etc.;
- Prática com as ferramentas de versionamento (como GIT, SVN, etc.);
- Experiência em escrever testes;
- Conhecimento em bancos de dados MySQL, SQL, MongoDB, Oracle, etc.);
- Vivência com metodologias ágeis.

**Conhecimentos que te destacam:**

- Experiência com Cloud, como AWS e Google Cloud Platform.

## **Compilação x interpretação**

- Código fonte = código escrito pelo programador
    - O código precisa ser transformado em código executavel e para isso existem dois processos
    
    - **Compilação:**
        - Processo de transformação do código para que seja possível executa-lo na plataforma específica ( Windows, mac, linux)
        
        ![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/b64dbfaa-aacd-43e6-8e3c-cf6d911268e9/image.png)
        

- **Interpretação**:
    - Para cada plataforma existe um interpretador específico. Não é feito a geração de um arquivo executável nem passa pelo processo de compilação.
    
    **Abordagem híbrida:** 
    

[C](https://www.notion.so/C-5a5cf2ba899949eb9f46953b8c38a37b?pvs=21)

## Linguagem de programação

- É a forma como dizemos para o computador executar algo
- Fazem intermédio
- O que escrevemos é traduzido para binário
- O processo de tradução é conhecido como compilação
    - Compilador: Agente que executa a compilação, que é a transformação do texto que escrevemos para binário

## Baixo e alto nível

- Ao enviar uma instrução ao computador, estamos falando em nível de máquina
- Essas instruções sempre serão no formato binário
- Quanto mais detalhada a necessidade, mais baixo o nível
- As linguagens mais modernas como C# e Java são consideradas alto nível.

Exemplo: 

- Codigo assembly é considerado uma linguagem de baixo nível

## Linguagens compiladas

- Existe o processo de compilação da mesma
- Consiste em receber um arquivo de texto e convertê-lo para binário.
- Normalmente otimizado para leitura de humanos

**prós**: 

- Tempo de compilação
- Detecção mais rápida de erros
- tamanho menor das aplicações
- Maior otimização da execução
- apenas um arquivo final

## Linguagens interpretadas

- Arquivos de texto que não são convertidos para binários, são somente lidos
- Feito em tempo de execução
- Javascript é interpretado

> Tempo de execução é o que acontece durante a execução do código pelo computador ou interpretador
> 

**prós:** 

- não precisa ser compilada
- correções mais fáceis de serem executadas
- Mais simples de serem distribuídas

**contras**: 

- Detecção de erros
- Somente em tempo de execução
- Tamanho final da aplicação maior
- menor otimização da execução
- Múltiplos arquivos

## Tipagem de dados

- Também chamadas de fortemente tipadas
- Obrigam a especificar o tipo de dado da informação
- menor liberdade
- maior otimização
- Definir tipos é padronizar os dados para nós e para o processador/memória
- o let utiliza sempre o mesmo tamanho de alocação
- Tipando temos uma otimização

## Por que escolher o C#?

- Tipada, compilada e gerenciada
- Principal linguagem da microsoft

## C# como primeira linguagem

- Não é a mais fácil
- Focada em OOP
    - Programação funcional
- OOP te dá a base para aprender coisas novas
- A conta uma hora vem
- Quanto mais tempo na base, mais fácil aprender coisas novas
- a quantidade de horas é a mesma
    - Você escolhe o tempo que vai investir no básico

## Compilação e gerenciamento

# IL

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/c8e52aa3-22ae-4aad-9fc9-5735d90b3c77/image.png)

## JIT

- O processo de conversão do IL para binário é conhecido como JIT

## **CLR**

- O que é uma linguagem gerenciada?
    - Definimos uma linguagem como gerenciada quando a sua execução depende de um gerenciador, também conhecido como Runtime
    - No caso do C# este runtime se chama CLR ou CLR Runtime
    - Gerencia memória, segurança, entre outros recursos.

# Frameworks

O que são frameworks? 

- É uma estrutura para construir nossas aplicações
- um conjunto de bibliotecas
- Usamos como base para construir nossas aplicações para que não seja necessário construir todo o nosso código do zero
- Neste curso, veremos o .NET, um framework da microsoft

## .NET Framework

- C# é a linguagem
- O framework se chama .NET
- Teve primeira versão em meados de 2001
    - Chamado de .Net Framework
- Recebeu as versões 1.0, 1.1, 2.0, 3.0, 3.5, 4.x(atualmente)
- Compatível somente com windows
- Considerado **legado**
- Pode ser instalado side-by-side

## .Net Core

- Versão moderna do .NET Framework
- Lançado em meados de 2015
- Veio para suportar outros SOs como Linux e Mac
- Suas primeiras versões continham apenas o básico
    - Core significa Nucleo, ou seja, essencial
    - Mudar um framework usado por milhões não é fácil
    - Foi totalmente reescrito
    - Ainda assim com ótima retro compatibilidade

## .NET Standard

- .NET framework e .NET Core coexistem
- podem ser instalados juntos
- Podem ser utilizados no mesmo projeto

Como garantir que algo que escrevemos roda em ambos? 

- O .NET Standard é a intersecção do .NET Core e .NET framework
    
    

**Definições**

- Não é um framework, apenas um contrato/definição
    - Chamamos de Surface API
- Garante que tudo que escrevemos será compatível com ambos frameworks

## .NET 5

- Unificação dos frameworks
- .NET Core chegou ao .NET framework em nível de conteúdo
- Não faz mais sentido ter dois frameworks
- Atualmente em preview ( 2020)
- Lançamento em 11/20

## Releases

Definições

- .NET Framework
    - Não possuía uma data de lançamento programada
- .NET Core
    - Lançamentos semestrais
- .NET 5
    - Lançamentos anuais

## LTS

- Sigla para long term support
    - Suporte de longa data
- .NET Framework
    - Todos eram
- .NET CORE
    - Versões com final 1
    - 1.1, 2.1, 3.1
- .NET 5 e futuros
    - Versões maiores (major version)
- Optar sempre por LTS para projetos em produção

## Versionamento

- Versão semântica
- Dividida em fases
    - Alpha, beta, release candidate, final
- Divida em três partes
    - Major, minor, Patch

major.minor.patch

2.1.4

- Major
    - Pode contar incompatibilidade com versões anteriores
    - Chamadas de Breaking changes
- Minor
    - Possui mudanças mas é totalmente compatível com versões anteriores
    - Backward compatibility
- Patch
    - Correções de bugs e outros itens simples
- Alpha
    - Ainda não se sabe como serão as coisas
- Beta
    - Já tem ideia da estrutura
    - as coisas ainda podem mudar
- Release candidate
    - Candidata a versão final
- Final
    - Versão final

## Runtime e SDK

- Runtime
    - Necessário para executar as aplicações
    - São dividios em 3
        - [ASP.NET](http://ASP.NET) para aplicações web
        - Desktop para aplicações desktop
        - .NET Core para qualquer outra aplicação
            - Console, batch, serviço
            - Não possui uma interface por exemplo
    - Também possui versões
        - A versão tem que ser compatível com a versão utilizada durante a codificação
            - apenas executa
                - Tamanho menor, otimizado para execução

SDK

- Sigla para software development kit
    - Kit para desenvolvimento de software
- Possui tudo que precisamos para criar aplicações
- Já vem com o runtime integrado
- Não devemos utilizar em produção
    - Para execurar precisamos apenas do runtime
- É Maior que o runtime
    - Já vem com tudo que precisamos

CLI

- Sigla para command Line Interface
    - Interface de linha de comando
    - Comandos adicionados ao nosso terminal
    

## Tipos de projeto

- Class library
    - O resultado final é uma DLL
    - Não possui interface
- Console Application
    - O resultado final é uma aplicação que roda no terminal
    - Pode receber dados, esperar input do usuário
- Projeto web
- Projeto testes

- Projeto web
    - [ASP.NET](http://ASP.NET) WEB
    - [ASPE.NET](http://ASPE.NET) MV
    - [ASP.NET](http://ASP.NET) WEBAPI
- Projeto testes
    - Microsoft Tests

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/120b96d7-d87d-417d-ac4d-507d33e0f0ea/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/9200e1e2-1078-40be-bf3e-f6c93a1c6c47/image.png)

## Comandos principais

- ***dotnet restore*** é o primeiro comando a ser utilizado ao abrir um projeto .net
- **Comando de compilação:**
    
    *dotnet build* 
    
- **Limpar cache do projeto**
    
    *dotnet clean*
    
- **Executar aplicação**
    
    dotnet run
    

## Variáveis de ambiente

É comum termos vários ambientes para nossas aplicações 

- Desenvolvimento
- Homologação
- Produção

Cada ambiente possui suas configurações 

- Chaves de acesso externo
- Conexões com bancos de dados

# DEBUG

Claro! Vamos detalhar o funcionamento de cada ícone da barra de depuração do Visual Studio Code, conforme a imagem fornecida.

### Barra de Depuração do Visual Studio Code

1. **Continue / Play (F5)**
    - **Função:** Continua a execução do programa até encontrar o próximo breakpoint ou até o fim do programa.
2. **Step Over (F10)**
    - **Função:** Executa a próxima linha de código, pulando sobre as chamadas de função. Se a próxima linha contém uma função, a função é executada, mas não entra nela.
3. **Step Into (F11)**
    - **Função:** Entra na próxima linha de código. Se a próxima linha contém uma função, entra dentro dessa função e permite depurar linha por linha dentro da função.
4. **Step Out (Shift+F11)**
    - **Função:** Continua a execução do código até sair da função atual e retorna para a função chamadora, permitindo continuar a depuração do ponto onde a função foi chamada.
5. **Restart (Ctrl+Shift+F5)**
    - **Função:** Reinicia a sessão de depuração, parando o programa em execução e começando novamente do início, com os breakpoints ainda ativos.
6. **Stop (Shift+F5)**
    - **Função:** Para a sessão de depuração e termina a execução do programa.

### Uso Típico na Depuração

- **Continue (F5)** é utilizado para continuar a execução do programa após parar em um breakpoint.
- **Step Over (F10)** é usado para avançar linha a linha, sem entrar nas funções chamadas.
- **Step Into (F11)** permite entrar dentro das funções chamadas para depurar linha a linha.
- **Step Out (Shift+F11)** é útil para sair de uma função e voltar ao contexto onde a função foi chamada.
- **Restart (Ctrl+Shift+F5)** reinicia a depuração desde o início do programa.
- **Stop (Shift+F5)** termina a depuração e para a execução do programa.

Essas funcionalidades são essenciais para uma depuração eficiente e ajudam a identificar e corrigir problemas no código de forma detalhada.

## Linguagem de programação C#

- Não utilize espaços nem caracteres especiais na criação do programa
    - Bons: MeuApp, Pedidos, MinhaApp
    - Ruins: “Meu app”, $app, app $teste
- Tente utilizar caminhos curtos e sem caracteres especiais
    - Bons: C:\dev, C:\apps
    - Ruins: C:\Caminho com espaços e caracteres especiais
- Evite caminhos de rede
    - se possível, utilize C:\
    
- O C# é Case Sensitive
    - Significa que ele diferencia maiúsculas de minúsculas
    - Teste é diferente de teste

## Escopo de um programa

- Importações
- Namespace
- Classe
- Método principal

### Namespaces

- Divisões lógicas
- Assim como não podemos ter dois arquivos com o mesmo nome nas pastas, não podemos ter duas classes com o mesmo nome em um namespace
- O escopo de um namespace é definido entre CHAVES
    - Classes e métodos também
- Um namespace pode ser reutilizado

## USING

- importação de namespaces são feitas com o **using**
- Importações definem as bibliotecas que nosso programa irá utilizar
- por padrão so básico vem incluso
- Precisamos importar o que desejamos para poder trabalhar
- isto é feito no início do problema
- utilizamos a palavra reservada using para isto

## Variáveis

- Uma variável é algo que utilizamos para armazenar uma informação
- Ser variável significa que seu valor pode ser alterado a qualquer momento
- Sempre que criamos uma variável dizemos que estamos inicializando ela

**Definições**

- Podemos usar um TIPO ou palavra reservada **var** para criar uma variável
- no c# o tipo vem sempre antes do nome da variavel
- podemos informar um valor já na criação
- se não informado o valor padrão será aplicado

```csharp
int idade; //correto inicia com zero 
int idade = 25 // correto inicia com 25 
var idade = 25 // correto inicia com 25
var idade; // errado 
```

- Utilize nomes coesos
- não utilize caracteres especiais ou espaços
- não comece com números
- A primeira letra de cada palavra é SEMPRE minúscula

## Constantes

- Também utilizamos uma constante para armazenar uma informação
- As constantes não podem ser alteradas
- Uma vez criadas somos obrigados a atribuir um valor
- Feito isto elas não poderão ser modificadas novamente
- não funcionam com utilização de var
- são mais otimizados que as variáveis
- recomendadas para usos frequentes

```csharp
const int IDADE_MINIMA // correto inicia com zero 
const int IDADE_MINIMA = 25; //CORRETO INICIA COM 25
const var IDADE_MINIMA = 25 // ERRADO 
const var IDADE_MINIMA; // errado
```

## **Nomes reservados**

- Também chamados de keywords
- São palavras de uso exclusivo do C#

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/2bec0dc0-788b-4a8d-8f44-79916a49c86e/image.png)

## Tipos primitivos

- Também conhecidos como built-its types
- são tipos base cujo outros tipos (complexos) irão derivar
- Definir o tipo correto otimiza a execução do programa
- são chamados de tipos de valor
- Armazenam o valor e não a referência para um item na memória
- São classificados em
    - Tipos simples (simple types)
    - Enumeradores (enums)
    - Estruturas (structs)
    - Tipos nulos (nulllable types)
- Cada tipo possui uma capacidade
- Caso esta capacidade exceda, o programa gera um erro
- esta capacidade pré-definida ajuda na otimização do seu programa

## Byte

- O tipo byte é utilizado para representar um byte de fato
- Em diversos casos precisamos de cadeira de bytes de um arquivo por exemplo
    - Também de byte array
- Temos também o sbyte, que permite
- Byte (8-bit)
    - 0 a 255
- sbyte(8bit)
    - -128 até 127
- note que o sbyte permite valores negativos, por isto o nome sbyte, que significa signed byte

## System

- No .NET tudo começa de um tipo base chamado system
- Todo e qualquer tipo, seja built-in ou complexo, deriva dele
- Ele é a base de todos os objetos no .NET
- Não precisamos nos preocupar em usa-lo ou qualquer coisa similar.
- Seu uso já é implícito

## Inteiros

- Números inteiros, ou seja, sem pontuação, podem ser definido pelo tipos
    - Short/ushort
    - int/uint
    - long/ulong
- Assim como temos o signed nos bytes, nos números por padrão são permitidos valores negativos
- Então usamos o unsigned para definir que o mesmo não pode receber valores negativos
- o tipo int é o mais comum a ser encontrado

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/eca62f1e-957b-41e8-935c-5d54e6813d16/image.png)

## Números reais

- Números que exigem uma maior precisão, ou seja, utilizam pontuação
    - Float (notação F)
    - Double
    - Decimal (notação M)
- Possuem assimilação negativa e positiva por padrão, dispensando uso de signed/unsigned em seus tipos

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/416ef042-3927-4ffa-a199-8c0da432d2c2/ba35a045-9668-44b2-8f31-7a0be1570c29/image.png)

teste