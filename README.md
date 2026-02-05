# 🏛️ Sistema de Emissão de Certificados - Monte Sinai

Sistema profissional e completo para emissão de certificados de presença da Loja Maçônica Monte Sinai, com autenticação de usuários, gerenciamento de dados e funcionalidades avançadas.

## ✨ Funcionalidades

### 📜 Emissão de Certificados
- ✅ Preenchimento de dados: Sessão, Grau, Nome do Irmão, Obreiro, Potência e Data
- ✅ Preview em tempo real do certificado
- ✅ Busca de irmãos por inicial (A-Z)
- ✅ Impressão de certificados
- ✅ Download em PDF
- ✅ Design profissional e elegante

### 🔐 Autenticação e Segurança
- ✅ Sistema de login com usuário e senha
- ✅ Dois níveis de acesso: Administrador e Usuário Regular
- ✅ Autenticação persistente com LocalStorage
- ✅ Logout seguro

### 👥 Gerenciamento de Usuários (Admin)
- ✅ Criar novos usuários
- ✅ Definir tipo de acesso (Admin/Usuário)
- ✅ Deletar usuários (com proteção para último admin)
- ✅ Histórico de criação de usuários

### ⚙️ Gerenciar Dados (Admin)
- ✅ Adicionar/Deletar Sessões
- ✅ Adicionar/Deletar Graus
- ✅ Adicionar/Deletar Nomes de Irmãos (com ordenação automática)
- ✅ Adicionar/Deletar Obreiros
- ✅ Adicionar/Deletar Potências
- ✅ Tudo salvo automaticamente

### 💾 Armazenamento de Dados
- ✅ Dados salvos em LocalStorage (não precisa banco de dados)
- ✅ Persistência entre sessões
- ✅ Preparado para migração futura para banco de dados
- ✅ Backup e restore facilmente

### 📱 Interface
- ✅ Responsivo (Desktop, Tablet, Mobile)
- ✅ Design moderno com cores da Maçonaria
- ✅ Menu de navegação intuitivo
- ✅ Alertas visuais (sucesso, erro, info, aviso)
- ✅ Modal para adicionar usuários
- ✅ Otimizado para impressão

## 🚀 Como Usar

### 1️⃣ Acessar o Sistema

Abra o arquivo `index.html` em um navegador web.

**Credenciais de Demonstração:**
- **Administrador:** `admin` / `admin`
- **Usuário Regular:** `user` / `user`

### 2️⃣ Como Usuário Regular

1. Faça login com suas credenciais
2. Vá para "📜 Certificados"
3. Preencha os campos:
   - Sessão
   - Grau
   - Nome do Irmão (use A-Z para buscar por inicial)
   - Obreiro
   - Potência
   - Data
4. Clique em "📥 Baixar PDF" ou "🖨️ Imprimir"

### 3️⃣ Como Administrador

Além de emitir certificados, você pode:

**Gerenciar Dados (⚙️ Gerenciar Dados):**
- Adicionar/Deletar Sessões
- Adicionar/Deletar Graus
- Adicionar/Deletar Irmãos
- Adicionar/Deletar Obreiros
- Adicionar/Deletar Potências

**Gerenciar Usuários (👥 Usuários):**
- Criar novos usuários
- Definir se são Admin ou Usuário Regular
- Deletar usuários (exceto o último admin)
- Ver histórico de criação

## 📋 Dados Padrão

O sistema vem com dados pré-configurados:

### Sessões
- Sessão Ordinária
- Sessão Extraordinária
- Sessão Especial

### Graus
- 1º Grau - Aprendiz
- 2º Grau - Companheiro
- 3º Grau - Mestre

### Obreiros
- Venerável Mestre
- Primeiro Vigilante
- Segundo Vigilante
- Orador
- Secretário

### Potências
- Porto Alegre
- Rio Grande do Sul
- Brasil

## 💾 Armazenamento de Dados

Todos os dados são armazenados localmente no navegador usando **LocalStorage**. Isso significa:

✅ Nenhum servidor necessário
✅ Dados persistem entre acessos
✅ Funciona offline
✅ Privacidade total

**Para fazer backup dos dados:**
1. Abra o Console do navegador (F12)
2. Execute: `localStorage.getItem('montesinai_certificados_db')`
3. Copie o resultado
4. Guarde em um arquivo seguro

**Para restaurar dados:**
1. Abra o Console (F12)
2. Execute: `localStorage.setItem('montesinai_certificados_db', '[cole os dados aqui]')`

## 🎨 Design e Cores

- **Cor Primária:** #1a472a (Verde Maçônico)
- **Cor Secundária:** #d4a574 (Dourado)
- **Cor de Perigo:** #c41e3a (Vermelho)
- **Cor de Sucesso:** #27ae60 (Verde)

## 📱 Compatibilidade

- ✅ Chrome/Chromium
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Navegadores mobile (iOS Safari, Chrome Mobile)

## 🔒 Segurança

- ✅ Validação de formulários
- ✅ Proteção contra duplicatas
- ✅ Autenticação de usuários
- ✅ Separação de permissões
- ✅ Proteção do último administrador

## 📧 Contato

Para dúvidas ou sugestões sobre o sistema, entre em contato com a administração da Loja Monte Sinai.

---

**Versão:** 1.0.0  
**Última Atualização:** 5 de Fevereiro de 2026  
**© 2026 Loja Maçônica Monte Sinai - Todos os direitos reservados**