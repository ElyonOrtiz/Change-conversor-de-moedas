# Conversor de Moeda - Backend em Java

Este projeto é um backend simples desenvolvido em Java que permite a conversão de moedas utilizando a [ExchangeRate-API](https://www.exchangerate-api.com/). O sistema oferece um menu interativo no terminal, onde você pode selecionar opções para converter valores entre diferentes moedas, como Dólar, Real, Peso Argentino, e Peso Colombiano.

## Funcionalidades

- Menu interativo para selecionar pares de moedas.
- Conversão de valores entre diferentes moedas usando uma API de câmbio.
- Tratamento de erros em caso de falha de comunicação com a API ou seleção de opção inválida.
- Exibição da taxa de conversão e do valor convertido.

## Tecnologias Utilizadas

- **Java 21** (ou versão superior)
- **HTTP Client** para realizar requisições à API de câmbio.
- **Gson** para tratamento de JSON.
- **IntelliJ IDEA** (opcional, pode ser qualquer IDE que suporte Java)

## Como Executar

### Pré-requisitos

1. **Java 21** ou superior instalado no sistema.
2. Uma chave válida da [ExchangeRate-API](https://www.exchangerate-api.com/). Substitua a chave de API no código pelo seu próprio token.

### Dependências

Este projeto utiliza o Gson para trabalhar com JSON. Adicione a seguinte dependência ao seu projeto:

#### Maven
Adicione a seguinte dependência ao arquivo `pom.xml`:
```xml
<dependency>
    <groupId>com.google.code.gson</groupId>
    <artifactId>gson</artifactId>
    <version>2.8.8</version>
</dependency>
```
### Configuração da Chave da API

1. Localize o arquivo DadosDaAPI.java.
2. Substitua ef7277df487ebf3bae0012be pela sua própria chave de API no seguinte trecho de código:

#### Execução

1.  Clone o repositório ou copie os arquivos para o seu ambiente de desenvolvimento.
2.  Compile o projeto:
```xml
javac ConversorDeMoeda.java
```
```xml
javac ConversorDeMoeda
```

### Licença

Este projeto é de código aberto e pode ser utilizado conforme os termos da licença MIT.
