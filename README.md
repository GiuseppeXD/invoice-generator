# 🚀 Gerador Automático de Fatura

Um aplicativo web moderno e intuitivo para converter timesheets em CSV para faturas profissionais automaticamente.

## 📋 Objetivo

Este aplicativo foi criado para simplificar o processo de geração de faturas a partir de dados de timesheet. Ele permite que freelancers e consultores convertam rapidamente seus registros de tempo de trabalho em faturas profissionais e bem formatadas.

## ✨ Funcionalidades

### 📁 **Import de Dados**
- **Upload de CSV**: Importe seu timesheet em formato CSV
- **Configuração JSON**: Importe configurações da empresa via arquivo JSON
- **Suporte a drag & drop**: Interface intuitiva para upload de arquivos

### ⚙️ **Configurações Flexíveis**
- **Meus Dados**: Configure informações da sua empresa (nome, CNPJ, endereço, taxa por hora)
- **Dados do Cliente**: Configure informações do cliente para cobrança
- **Dados da Fatura**: Defina período, datas de desenvolvimento e banco de horas

### 🧮 **Cálculos Inteligentes**
- **Agrupamento automático** de tarefas similares
- **Cálculo preciso** de horas e valores
- **Sistema de banco de horas** (atual e histórico)
- **Suporte a números brasileiros** (vírgula e ponto como separador decimal)

### 📊 **Visualização Profissional**
- **Preview da fatura** com design moderno
- **Cores e formatação** profissional
- **Resumo visual** com cards informativos
- **Tabela detalhada** de tarefas e valores

### 💾 **Export e Impressão**
- **Impressão otimizada** para PDF
- **Download em Excel/CSV**
- **Layout responsivo** para diferentes dispositivos

## 🚀 Como Usar

1. **Faça upload do seu timesheet CSV**
2. **Configure suas informações** (ou importe um arquivo JSON)
3. **Ajuste os dados da fatura** (período, banco de horas, etc.)
4. **Clique em "Gerar Fatura Automaticamente"**
5. **Visualize, imprima ou exporte** sua fatura profissional

## 📝 Formato do CSV

O aplicativo processa arquivos CSV com as seguintes colunas (opcionais):
- `duration` - Duração da tarefa em horas
- `task_value` - Descrição da tarefa
- `ticket_number` - Número do ticket/chamado
- `description` - Descrição adicional
- `tag` - Tag ou categoria da tarefa

## ⚙️ Configuração JSON

Crie um arquivo `config.json` baseado no `default-config.json` com suas informações:

```json
{
  "companyName": "Sua Empresa LTDA",
  "companyCNPJ": "00.000.000/0001-00",
  "companyAddress": "Seu endereço completo",
  "hourlyRate": 50,
  "billingCompanyName": "Nome da Empresa Cliente",
  "billingCompanyCNPJ": "00.000.000/0001-00",
  "billingCompanyAddress": "Endereço da empresa cliente"
}
```

## 🌟 Características Técnicas

- **100% Frontend**: Funciona completamente no navegador
- **Sem servidor**: Não envia dados para nenhum servidor externo
- **Privacidade total**: Todos os dados ficam no seu computador
- **Responsivo**: Funciona em desktop, tablet e mobile
- **Moderno**: Interface clean e profissional

## 📱 Compatibilidade

- ✅ Chrome/Edge/Safari (recomendado)
- ✅ Firefox
- ✅ Mobile/Tablet
- ✅ Impressão/PDF em alta qualidade

## 🎯 Ideal Para

- 👨‍💻 **Desenvolvedores freelancers**
- 📊 **Consultores**
- 🏢 **Pequenas empresas**
- ⏰ **Profissionais que trabalham por hora**
- 📋 **Qualquer pessoa que precise converter timesheet em fatura**

## 🔒 Segurança e Privacidade

- Todos os dados são processados localmente no seu navegador
- Nenhuma informação é enviada para servidores externos
- Seus dados permanecem 100% privados e seguros

---

**Transforme seu timesheet CSV em uma fatura profissional em segundos!** 🚀