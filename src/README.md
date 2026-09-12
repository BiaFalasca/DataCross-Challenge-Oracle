# 💻 Código-fonte

Este diretório reúne os códigos desenvolvidos para a implementação, testes e evolução do **DataCross**.

Os arquivos estão relacionados principalmente à modelagem do banco de dados, preparação dos dados, desenvolvimento do motor de scoring, criação da aplicação no Oracle APEX e experimentos relacionados à utilização de PLN e Inteligência Artificial.

---

## 📁 Organização

Os códigos deste diretório podem ser divididos em cinco principais grupos:

1. **Banco de Dados**
2. **Geração de dados fictícios**
3. **Motor de Scoring**
4. **Oracle APEX**
5. **Testes e evolução do PLN/IA**

---

# 🗄️ 1. Banco de Dados

Nesta parte estão os scripts utilizados para criar e estruturar o banco de dados necessário para o funcionamento do DataCross.

### DDL

Os scripts **DDL (Data Definition Language)** são responsáveis pela criação da estrutura do banco de dados.

Eles contemplam elementos como:

- tabelas;
- colunas;
- relacionamentos;
- chaves;
- restrições;
- demais estruturas necessárias para o armazenamento dos dados.

### DML

Os scripts **DML (Data Manipulation Language)** são utilizados para inserir e manipular os dados necessários para os testes do sistema.

Entre eles está o processo de importação do **dataset sintético completo** para utilização no banco de dados através do SQL Developer.

---

# 🤖 2. Geração de prontuários fictícios

Também está disponível um código desenvolvido em **Python** para geração automática de prontuários fictícios.

Esse código foi desenvolvido como um teste para avaliar a possibilidade de automatizar a criação dos dados utilizados durante o desenvolvimento.

A geração automática permite criar diferentes exemplos de prontuários sem utilizar informações reais de pacientes.

> Este código possui caráter experimental e foi utilizado como apoio ao desenvolvimento dos datasets e testes da solução.

---

# 🧮 3. Motor de Scoring

O motor de scoring é um dos principais componentes do DataCross.

Sua função é analisar as informações disponíveis sobre o paciente e aplicar as regras definidas para gerar uma **pontuação (score)** utilizada como apoio à triagem.

O motor foi inicialmente desenvolvido em **Python** para validação da lógica.

Posteriormente, essa lógica foi adaptada para **SQL**, permitindo sua execução dentro do ambiente **Oracle APEX** utilizado no MVP.


Pontuação final
       ↓
Resultado para apoio à triagem
