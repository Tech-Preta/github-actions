- # GitHub Actions Templates Repository

Este repositório contém arquivos declarativos que podem ser reutilizados livremente para configurar pipelines no GitHub Actions. As pipelines são definidas usando arquivos YAML para automatizar fluxos de trabalho, testes, integração contínua e implantação.

## Como usar esses modelos 
1. **Clone o repositório:** 

```bash
git clone https://github.com/Tech-Preta/github-actions.git
``` 
2. **Copie o arquivo YAML desejado para o seu projeto:**  
- Navegue até o diretório raiz:

```bash
cd github-actions
``` 
- Copie o arquivo YAML para o seu repositório:

```bash
cp template.yml /caminho/do/seu/repositorio/.github/workflows/
``` 
3. **Personalize conforme necessário:**  
- Abra o arquivo copiado em `/caminho/do/seu/repositorio/.github/workflows/template.yml`.
- Personalize as configurações conforme necessário para se adequar ao seu projeto. 
4. **Commit e Push:**  
- Commit suas alterações:

```bash
git add .
git commit -m "Adiciona pipeline usando o template XYZ"
``` 
- Faça push para o seu repositório:

```bash
git push origin nome-do-seu-branch
``` 
5. **Ative as GitHub Actions:** 
- Vá para a seção "Actions" no seu repositório no GitHub. 
- GitHub Actions detectará automaticamente os novos arquivos YAML no diretório `.github/workflows/`.
- Selecione e ative o workflow desejado.
## Lista de Templates
### 1. Template de Build e Testes 
- **Nome:**  `build-test` 
- **Descrição:**  Configura uma pipeline simples para compilar o código e executar testes automatizados.
### 2. Template de Implantação 
- **Nome:**  `deploy` 
- **Descrição:**  Configura uma pipeline para implantar o aplicativo em um ambiente de produção após a conclusão bem-sucedida de testes.
### 3. Template de Publicação de Release 
- **Nome:**  `release-publish` 
- **Descrição:**  Define uma pipeline para automatizar a criação e publicação de releases sempre que uma nova tag é criada.
## Contribuindo

Sinta-se à vontade para contribuir adicionando novos templates ou melhorando os existentes. Abra uma issue para discussão ou envie uma pull request.