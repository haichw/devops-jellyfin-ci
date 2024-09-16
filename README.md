## CI/CD Pipeline com GitHub Actions

### Introdução
Este documento descreve a configuração do pipeline CI/CD para o projeto Jellyfin usando GitHub Actions.

### Estrutura do Pipeline

1. **Checkout do Código**:
   - Clona o repositório para o ambiente de execução.

2. **Setup do .NET Core**:
   - Configura a versão do .NET Core necessária para o projeto.

3. **Build do Projeto**:
   - Constrói o projeto usando a configuração Release.

4. **Testes Automatizados**:
   - Executa os testes automatizados para garantir que o código funcione corretamente.

5. **Publicação de Artefatos**:
   - Publica os artefatos de build.

6. **Análise de Qualidade de Código**:
   - Integra CodeQL para análise de segurança e qualidade do código.

7. **Deploy**:
   - Cria uma imagem Docker.

### Ferramentas Utilizadas

- **GitHub Actions**: Plataforma para CI/CD.
- **.NET Core**: Framework para o desenvolvimento do projeto.
- **Docker**: Para criação e gerenciamento de imagens de contêineres.

### Benefícios do Pipeline

- **Automação**: Reduz o trabalho manual e acelera o processo de integração e entrega.
- **Qualidade**: Garante que o código seja testado e validado antes de ser implantado.
- **Consistência**: Mantém a qualidade e integridade do código ao longo do tempo.
- **Escalabilidade**: O sistema passa a ser escalonavel.
- **Redução de Custos**: Com a agilidade do processo há uma redução no custo do tempo necessário para realizar as tarefas.