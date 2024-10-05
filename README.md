# Sistema de Gestão para Clínica Odontológica

![Logo](https://via.placeholder.com/150)

## Sumário

- [Descrição](#descrição)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Funcionalidades](#funcionalidades)
  - [Recepção](#recepção)
  - [Dentista](#dentista)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
  - [Exemplo de Uso](#exemplo-de-uso)
    - [Recepção](#recepção-1)
    - [Dentista](#dentista-1)
- [Autor](#autor)
- [Declaração de Autoria](#declaração-de-autoria)

## Descrição

Este projeto consiste em um sistema de gestão para uma clínica odontológica, desenvolvido em Python. Ele permite o gerenciamento de sessões, pacientes, consultas e a interação entre a recepção e os dentistas. O sistema facilita a organização das atividades diárias, garantindo eficiência no atendimento aos pacientes.

## Tecnologias Utilizadas

- **Sistema Operacional:** Windows 10
- **Linguagem de Programação:** Python 3.11.5 (64-bit)

## Funcionalidades

### Recepção

- **Criar Nova Sessão:** Permite a criação de novas sessões com data e horários específicos.
- **Listar Sessões:** Exibe todas as sessões criadas.
- **Buscar Sessão:** Localiza uma sessão específica pela data.
- **Adicionar Novo Paciente:** Cadastra novos pacientes no sistema.
- **Marcar Consulta:** Agenda consultas para pacientes em sessões específicas.
- **Listar Consultas Marcadas:** Mostra todas as consultas agendadas para um paciente.
- **Iniciar Sessão:** Inicia uma sessão específica para atendimento.
- **Confirmar Consulta:** Verifica se um paciente possui consulta marcada para a sessão atual.
- **Adicionar Paciente à Fila:** Insere um paciente na fila de atendimento por ordem de chegada.
- **Listar Próximo da Fila:** Mostra o próximo paciente na fila de atendimento.
- **Listar Consultas Realizadas:** Exibe todas as consultas realizadas em uma sessão.
- **Encerrar Sessão:** Finaliza a sessão atual.

### Dentista

- **Buscar Sessão:** Localiza uma sessão específica pela data.
- **Iniciar Sessão do Dentista:** Inicia a sessão para o dentista.
- **Atender Próximo Paciente:** Chama o próximo paciente da fila para atendimento.
- **Ler Prontuário Completo:** Exibe o prontuário completo do paciente atual.
- **Ler Primeira Anotação:** Mostra a primeira anotação feita para o paciente atual.
- **Ler Última Anotação:** Exibe a última anotação feita para o paciente atual.
- **Anotar Prontuário:** Permite ao dentista adicionar anotações ao prontuário do paciente atual.

## Instalação

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/sistema-clinica-odontologica.git
   ```
2. Navegue até o diretório do projeto:

```bash
cd sistema-clinica-odontologica
```
3. **Certifique-se de ter o Python 3.11.5 (64-bit) instalado.** Você pode verificar a versão instalada com:

```bash
python --version
```
4. Execute o programa:

```bash
python main.py
```
## Como Usar

Ao executar o programa, você será apresentado a um menu principal com as opções de **Recepção** e **Dentista**. Navegue pelas opções inserindo o número correspondente e siga as instruções na tela para gerenciar sessões, pacientes e consultas.

### Exemplo de Uso

#### Recepção

1. **Criar Nova Sessão:**
   - Insira a data, horário de início e horário de término da sessão.
   
2. **Adicionar Novo Paciente:**
   - Forneça o nome e a idade do paciente para cadastrá-lo no sistema.
   
3. **Marcar Consulta:**
   - Agende uma consulta para um paciente específico em uma sessão existente.
   
4. **Iniciar Sessão:**
   - Inicie uma sessão para começar o atendimento aos pacientes.
   
5. **Confirmar Consulta:**
   - Verifique se um paciente possui consulta marcada para a sessão atual.
   
6. **Adicionar Paciente à Fila:**
   - Insira um paciente na fila de atendimento por ordem de chegada.
   
7. **Listar Próximo da Fila:**
   - Veja qual paciente será atendido em seguida.
   
8. **Listar Consultas Realizadas:**
   - Exiba todas as consultas que já foram realizadas em uma sessão.
   
9. **Encerrar Sessão:**
   - Finalize a sessão atual quando não houver mais atendimentos.

#### Dentista

1. **Iniciar Sessão do Dentista:**
   - Inicie a sessão do dentista para começar a atender os pacientes.
   
2. **Atender Próximo Paciente:**
   - Chame o próximo paciente da fila para atendimento.
   
3. **Ler Prontuário Completo:**
   - Consulte o prontuário completo do paciente atualmente sendo atendido.
   
4. **Ler Primeira Anotação:**
   - Veja a primeira anotação feita no prontuário do paciente.
   
5. **Ler Última Anotação:**
   - Veja a última anotação feita no prontuário do paciente.
   
6. **Anotar Prontuário:**
   - Adicione novas anotações ao prontuário do paciente após o atendimento.

## Autor

- **Nome:** João Marcelo Nascimento Fernandes
- **Componente Curricular:** Algoritmos I
- **Data de Conclusão:** 19/02/2024
- **Sistema Operacional:** Windows 10
- **Versão Python:** 3.11.5 (64-bit)

## Declaração de Autoria

Declaro que este código foi elaborado por mim de forma individual e não contém nenhum trecho de código de outro colega ou de outro autor, tais como provindos de livros e apostilas, e páginas ou documentos eletrônicos da Internet. Qualquer trecho de código de outra autoria que não a minha está destacado com uma citação para o autor e a fonte do código, e estou ciente que estes trechos não serão considerados para fins de avaliação.
