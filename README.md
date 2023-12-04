# Sistema de Venda Java Swing

Este projeto é um sistema de venda simples desenvolvido em Java 18, que inclui funcionalidades básicas como login, cadastro de produto, cadastro de vendas e filtragem por data.

## Configuração do Repositório

Ao utilizar este repositório, siga as instruções abaixo:

1. Navegue até a pasta `src`.
2. Em seguida, acesse a pasta `META-INF`.
3. Abra o arquivo `persistence.xml`.
4. Modifique as seguintes linhas conforme suas credenciais de banco de dados:
   - `<property name="javax.persistence.jdbc.user" value="seu_usuario"/>`
   - `<property name="javax.persistence.jdbc.password" value="sua_senha"/>`

## Dependências

Para que o sistema funcione corretamente, é necessário fazer o download das seguintes bibliotecas:

- [jCalendar 1.4](Incluido na pasta "Drivers para o funcionamento do projeto")
- [MySQL Connector/J 8.0.20](Incluido na pasta "Drivers para o funcionamento do projeto")

Adicione essas bibliotecas ao seu projeto antes de compilar.

## Configuração Adicional para Windows

Se estiver utilizando o sistema no Windows, adicione a seguinte linha ao arquivo `persistence.xml` para ajustar o fuso horário:

<property name="hibernate.jdbc.time_zone" value="UTC"/>

## Funcionalidades

- **Login:** Permite que usuários façam login no sistema.
- **Cadastro de Produto:** Adiciona novos produtos ao sistema.
- **Cadastro de Vendas:** Registra vendas associadas a produtos.
- **Filtragem por Data:** Permite filtrar vendas por data.

## Utilização

1. Compile e execute o projeto.
2. Faça login no sistema.
3. Utilize as opções do menu para cadastrar produtos, registrar vendas e filtrar por data.

## Imagens do sistema

![Captura de tela 2023-12-04 131429](https://github.com/pedrobaschoni/Java-Swing-Vendas/assets/124200114/4b322017-8527-4a54-a204-be40e1dc307a)

![Captura de tela 2023-12-04 131439](https://github.com/pedrobaschoni/Java-Swing-Vendas/assets/124200114/d258e41f-70fe-4b3a-97a2-4b0a5a7a2e73)

![Captura de tela 2023-12-04 131449](https://github.com/pedrobaschoni/Java-Swing-Vendas/assets/124200114/686d727b-8484-4bd8-b590-c344d1af61fb)

![Captura de tela 2023-12-04 133653](https://github.com/pedrobaschoni/Java-Swing-Vendas/assets/124200114/540642d4-a06f-4e5d-8156-4dd105237b3d)

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com melhorias, correções de bugs ou novos recursos.

---

Espero que este projeto seja útil para o seu aprendizado. Se tiver alguma dúvida ou sugestão, fique à vontade para entrar em contato.

Divirta-se codificando! 🚀
