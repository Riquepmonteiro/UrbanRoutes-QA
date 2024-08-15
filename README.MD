# Urban Routes 🌆

## Descrição do Projeto

**Urban Routes** é um site dedicado a fornecer informações e recursos sobre rotas urbanas, facilitando o planejamento de viagens pela cidade. O site foi desenvolvido com o objetivo de proporcionar uma experiência intuitiva e eficiente para os usuários.

Este repositório contém o código-fonte do projeto e o trabalho realizado para garantir a qualidade e estabilidade do site através de testes de regressão.

## Funcionalidades

- **Mapas interativos**: Explore diferentes rotas urbanas.
- **Planejamento de viagens**: Ferramenta para planejar o trajeto ideal.
- **Informações atualizadas**: Dados em tempo real sobre condições de tráfego.

## Testes de Regressão 🧪

Testes de regressão foram realizados para garantir que novas funcionalidades ou correções não introduzam erros em partes já existentes do sistema. Abaixo está um resumo dos testes realizados:

### Casos de Teste 📋

Os casos de teste foram desenvolvidos para cobrir todas as funcionalidades principais do site, incluindo:

1. **Navegação no Mapa**: Verificar se o mapa interativo carrega corretamente e se todas as rotas são exibidas.
2. **Planejamento de Rota**: Testar a funcionalidade de planejamento de viagens para garantir que as rotas sejam calculadas corretamente.
3. **Atualização de Dados**: Testar se as informações de tráfego são atualizadas em tempo real sem afetar a performance.

### Ferramentas Utilizadas

- **Selenium**: Para automação dos testes de interface.
- **JUnit**: Para organizar e executar os casos de teste.
- **Allure**: Para a geração de relatórios de testes.

## Relatório de Bugs 🐞

Durante os testes, alguns bugs foram encontrados e documentados. Os relatórios de bugs incluem descrições detalhadas dos problemas, passos para reprodução, e a severidade de cada bug. Veja o arquivo [[BUG_REPORT](https://docs.google.com/spreadsheets/d/1RNH7MdQC6qFvd8uknVhpLbMiMHRacG0m/edit?usp=sharing&ouid=105840637536928126724&rtpof=true&sd=true)] para mais detalhes.

Exemplo de bugs encontrados:

- **URBR - 1**: Ao clicar no nome do local 'Hollywood', aparece um balão com informações.
- **URBR - 2**: Ao clicar no campo "De", o campo não fica em branco.