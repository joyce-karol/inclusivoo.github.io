# inclusivoo.github.io

## Descrição

A Inclusivoo é plataforma de avaliação diagnóstica e capacitação para diversidade, uma solução desenvolvida para ajudar empresas a avaliarem e melhorarem suas práticas de diversidade e inclusão. Através de um diagnóstico detalhado, as empresas recebem insights sobre o estado atual de suas políticas de diversidade e têm acesso a treinamentos específicos para promover um ambiente de trabalho mais inclusivo e conquistar os Selos da Diversidade. 

## Funcionalidades

- **Cadastro de Empresas e Funcionários**: Permite que empresas e seus funcionários se cadastrem na plataforma.
- **Diagnóstico de Diversidade**: Empresas recebem um diagnóstico detalhado sobre suas práticas de diversidade e inclusão.
- **Capacitação**: Acesso a treinamentos e materiais educativos baseados no diagnóstico recebido.
- **Privacidade Garantida**: O formulário preenchido pelos funcionários utiliza criptografia de Prova de Conhecimento Zero para garantir a privacidade dos funcionários frente às informações fornecidas.

## Tecnologias Utilizadas

- **Backend**: PHP
- **Frontend**: Bootstrap
- **Banco de Dados**: MySQL
- **Outras Tecnologias**: Libsnark (biblioteca C++ para zk-SNARKs)

## Instalação

Siga os passos abaixo para configurar e executar a plataforma localmente:

### Pré-requisitos

- PHP 7.4+
- MySQL 5.7+
- Composer
- Servidor Web (Apache, Nginx, etc.)

### Passos

1. **Clone o repositório**

   ```bash
   git clone https://github.com/jaquequeroz/inclusivoo.git
   cd inclusivoo
   ```

2. **Instale as dependências do Composer**

   ```bash
   composer install
   ```

3. **Configure o arquivo `.env`**

   Renomeie o arquivo `.env.example` para `.env` e atualize as configurações conforme necessário, especialmente as informações do banco de dados.

4. **Crie o banco de dados**

   Execute o comando abaixo para criar as tabelas necessárias no banco de dados:

   ```bash
   php artisan migrate
   ```

5. **Inicie o servidor**

   Utilize o servidor embutido do PHP para iniciar a aplicação:

   ```bash
   php -S localhost:8000 -t public
   ```

6. **Acesse a aplicação**

   Abra seu navegador e acesse `http://localhost:8000`.

## Estrutura do Projeto

- **public/**: Contém os arquivos públicos, como `index.php` e ativos (imagens, CSS, JS).
  - **css/**: Arquivos de estilo (CSS) utilizados na aplicação.
  - **fonts/**: Arquivos de fontes utilizados na aplicação.
  - **images/**: Imagens utilizadas na aplicação.
  - **js/**: Arquivos JavaScript utilizados na aplicação.
- **src/**: Código fonte da aplicação, incluindo controladores, modelos e visualizações.
- **database/**: Arquivos de migração e seeds do banco de dados.

## Contribuição

1. Faça um fork do projeto.
2. Crie uma nova branch com sua feature: `git checkout -b minha-feature`.
3. Commit suas mudanças: `git commit -m 'Adicionei minha feature'`.
4. Faça um push para a branch: `git push origin minha-feature`.
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Para mais informações, entre em contato pelo email: [jaquequeroz@gmail.com](mailto:jaquequeroz@gmail.com).

---

Esperamos que esta plataforma ajude sua empresa a criar um ambiente mais inclusivo e diverso. Obrigado por conhecer nossa solução!
```
