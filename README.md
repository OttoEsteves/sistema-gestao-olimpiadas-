🏅 Sistema de Gestão das Olimpíadas (SGO) 


📌 Descrição do Projeto
O Sistema de Gestão das Olimpíadas (SGO) foi projetado para auxiliar na organização e gerenciamento de eventos olímpicos, permitindo o controle completo de competições, atletas, locais, resultados e medalhas.
O sistema centraliza informações essenciais, garantindo organização, integridade dos dados e cumprimento das regras do evento.

🎯 Objetivo
Desenvolver um sistema capaz de:

Gerenciar competições esportivas
Controlar inscrições de atletas
Evitar conflitos de alocação de locais
Registrar resultados oficiais
Gerar relatórios de medalhas por país


🧩 Funcionalidades Principais
✅ Cadastro de Competições

Criação de competições com:

Nome da modalidade
Data
Horário
Local


Associação de atletas inscritos


✅ Inscrição de Atletas

Cadastro de atletas vinculados a países
Inscrição em múltiplas competições
Restrição:

Atleta representa apenas um país por modalidade




✅ Alocação de Locais

Associação de competições a locais
Regra de negócio:

Um local não pode ter mais de uma competição no mesmo horário


Prevenção de conflitos de agenda


✅ Controle de Resultados

Registro dos resultados após cada competição
Definição de:

🥇 1º lugar (ouro)
🥈 2º lugar (prata)
🥉 3º lugar (bronze)




✅ Relatórios de Medalhas

Geração de ranking por país
Contabilização de:

Medalhas de ouro
Medalhas de prata
Medalhas de bronze


Classificação por desempenho


👥 Atores do Sistema

Administrador

Gerencia competições, locais e resultados


Atleta

Realiza inscrições nas competições




🏗️ Arquitetura do Sistema
O sistema é dividido em camadas:
🔹 Camada de Apresentação

Interface Web
Aplicativo Mobile

🔹 Camada de Aplicação

API REST responsável pela comunicação

🔹 Camada de Negócio
Módulos principais:

Competições
Inscrições
Alocação de Locais
Resultados
Relatórios
Validação de Regras

🔹 Camada de Persistência

Repositório de dados
Banco de dados relacional


🧱 Modelagem UML
📌 Diagramas desenvolvidos:

✅ Diagrama de Caso de Uso
✅ Diagrama de Classes e Pacotes
✅ Diagrama de Componentes
✅ Diagrama de Implantação

Esses diagramas representam:

Interação dos usuários
Estrutura do sistema
Organização dos módulos
Infraestrutura de execução


⚙️ Regras de Negócio

Um atleta pode participar de várias competições
Um atleta representa apenas um país por modalidade
Um local não pode ser utilizado por duas competições ao mesmo tempo
Toda competição deve possuir um local definido
Resultados devem registrar apenas 1º, 2º e 3º colocados
Relatórios devem refletir corretamente o total de medalhas por país
