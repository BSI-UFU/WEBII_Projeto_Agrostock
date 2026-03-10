
# Proposta de Projeto: AgroStock – Sistema de Gestão de Insumos Agrícolas

**Descrição Geral:**
O **AgroStock** é uma aplicação web completa voltada para o gerenciamento digital de insumos em propriedades agrícolas. O sistema permite o controle rigoroso de estoque de produtos como fertilizantes, defensivos e corretivos minerais (como agalmatolito e calcário), garantindo que o produtor tenha visibilidade sobre o que está disponível e o que foi aplicado no campo.

**Problema que resolve:**
Muitos produtores gerenciam seus insumos de forma manual ou por planilhas desconexas, o que leva a perdas por vencimento de produtos, falta de insumos em momentos críticos da safra e dificuldade em rastrear o custo aplicado em cada talhão da fazenda. O AgroStock centraliza essas informações, oferecendo uma interface amigável para persistência e consulta desses dados em tempo real.

**Funcionalidades Principais (CRUD e Perfis):**

* **Perfil Administrador (Gestor):**
* **Gerenciamento de Usuários:** Cadastro, edição e exclusão de funcionários ou operadores do sistema.
* **Catálogo de Insumos (Create/Read/Update/Delete):** Cadastro global de produtos, especificando composição química, fabricante e alertas de segurança.
* **Relatórios Gerenciais:** Visualização de logs de aplicação de todos os usuários para controle de custos e auditoria.

* **Perfil Usuário Comum (Operador de Campo):**
* **Lançamento de Aplicações:** Registro de quando e quanto de um insumo foi utilizado em determinado talhão.
* **Gestão de Estoque Próprio:** O usuário pode atualizar a quantidade de produtos retirados do armazém para uso imediato.
* **Consulta de Disponibilidade:** Leitura de dados para verificar se há insumo suficiente para a próxima tarefa agendada.

**Tecnologias Previstas:**
A aplicação contará com um **Frontend** responsivo para uso em campo (HTML/CSS/JavaScript), um **Backend** para processamento da lógica de negócios e uma camada de **Persistência de Dados** via banco de dados relacional para armazenamento seguro das informações.

---

