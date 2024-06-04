# Projeto de Teste API Pet Store 🚀

Este projeto tem como objetivo simular uma aplicação de uma Pet Store, onde são realizadas operações de cadastro, alteração e exclusão de informações por meio de chamadas a APIs públicas. Utilizando Python 3.10 ou a versão mais recente, juntamente com o Robot Framework, é possível automatizar essas interações e garantir a integridade e a qualidade do sistema.

***Configurações***

Antes de utilizar o projeto, certifique-se de instalar o Python 3.10 ou a última versão disponível, assim como o Robot Framework, utilizando os seguintes comandos:
```
pip install -r requirements.txt
pip install robotframework
```
## Pipeline de Testes Automatizados com Notificação no Telegram

Este repositório inclui uma pipeline automatizada que executa os testes definidos no projeto e envia uma mensagem de notificação no Telegram com os resultados.

### Recursos da Pipeline:

- **Testes Automatizados:** A pipeline executa os testes automatizados definidos no projeto para garantir sua integridade e qualidade.

- **Integração Contínua:** A pipeline é acionada automaticamente sempre que há uma nova alteração no repositório, garantindo que os testes sejam executados regularmente.

- **Notificação no Telegram:** Após a conclusão dos testes, a pipeline envia uma mensagem no Telegram para notificar os desenvolvedores sobre o status dos testes.

### Como Funciona:

1. **Configuração da Pipeline:** A pipeline está configurada usando uma ferramenta de integração contínua, como GitHub Actions ou GitLab CI/CD. Os detalhes específicos da configuração podem ser encontrados nos arquivos de configuração da pipeline no repositório.

2. **Execução dos Testes:** Durante a execução da pipeline, os testes automatizados são executados para verificar se o projeto está funcionando conforme esperado.

3. **Notificação no Telegram:** Após a conclusão dos testes, a pipeline envia uma mensagem no Telegram para um grupo ou canal especificado, informando sobre o resultado dos testes.

### Contribuições:

Contribuições para a melhoria da pipeline ou para adicionar novos recursos são bem-vindas! Se você tem sugestões ou ideias para melhorar a pipeline de testes automatizados, sinta-se à vontade para enviar um pull request.

***Estrutura de Pastas***

O projeto segue uma estrutura organizada em pastas:

- **Data**: Contém os corpos das chamadas das APIs e massas de dados.
  
- **Services**: Responsável por realizar as requisições às APIs.

- **Tests**: Aqui são definidas as suítes de testes.

***Pipeline***

Uma robusta pipeline de testes foi estabelecida utilizando o Jenkins para automatizar o processo de integração contínua. Esta pipeline executa os testes definidos no projeto após cada alteração no repositório. Ao término dos testes, o Jenkins envia notificações para um canal específico no Slack, mantendo toda a equipe informada sobre o status da execução dos testes. Essa integração contínua garante a qualidade do código e facilita a colaboração da equipe.

Para interagir com a API mock, você pode acessar o link: [MockAPI](https://mockapi.io/projects)
