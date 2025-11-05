# 🔐 Cibersegurança - Sistema Integrado de Segurança da Informação

[![ISO 27002:2022](https://img.shields.io/badge/ISO-27002:2022-blue)](https://www.iso.org/standard/75652.html)
[![LGPD](https://img.shields.io/badge/LGPD-Compliant-green)](http://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)
[![NIST SP 800-63B](https://img.shields.io/badge/NIST-SP%20800--63B-orange)](https://pages.nist.gov/800-63-3/sp800-63b.html)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)

Um sistema completo e integrado de ferramentas de segurança da informação desenvolvido para auxiliar organizações públicas e privadas no gerenciamento da segurança de dados, conformidade com normas internacionais (ISO 27002, ISO 27701) e adequação à LGPD.

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Características](#características)
- [Módulos do Sistema](#módulos-do-sistema)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Como Usar](#como-usar)
- [Documentação Detalhada](#documentação-detalhada)
- [Conformidade e Normas](#conformidade-e-normas)
- [Casos de Uso](#casos-de-uso)
- [Segurança](#segurança)
- [Contribuindo](#contribuindo)
- [Roadmap](#roadmap)
- [Licença](#licença)

## 🎯 Sobre o Projeto

O **Sistema Integrado de Cibersegurança** é uma solução completa que combina múltiplas ferramentas essenciais para a gestão de segurança da informação em ambientes corporativos. Desenvolvido com foco em conformidade regulatória e usabilidade, o sistema oferece:

### Pilares de Segurança

O projeto foi construído sobre os três pilares fundamentais da segurança da informação:

1. **🔒 Confidencialidade**: Garantia de que apenas pessoas autorizadas acessem informações sensíveis
2. **✅ Integridade**: Preservação da precisão e completude dos dados
3. **🌐 Disponibilidade**: Garantia de acesso aos sistemas quando necessário

### Objetivos

- **Simplificar** o gerenciamento de segurança da informação
- **Automatizar** processos de verificação e auditoria
- **Garantir** conformidade com normas nacionais e internacionais
- **Educar** usuários sobre boas práticas de segurança
- **Documentar** procedimentos e incidentes para rastreabilidade

## ✨ Características

### 🚀 Principais Funcionalidades

- **Interface Web Moderna**: Design responsivo e intuitivo
- **Múltiplos Módulos Integrados**: Ferramentas complementares em um único sistema
- **Conformidade Total**: Alinhado com ISO 27002, ISO 27701, LGPD e NIST
- **Offline-First**: Funciona localmente sem necessidade de internet
- **Multiplataforma**: Windows, macOS e Linux
- **Zero Dependências Externas** (módulo web): Código puro HTML/CSS/JavaScript
- **Geração de Relatórios**: PDFs e documentos para auditoria
- **Sistema de Notificações**: Feedback visual para todas as ações
- **Acessibilidade**: Suporte a leitores de tela (WCAG 2.1)

## 🛠 Módulos do Sistema

### 1. 🔑 Gerador de Senhas Seguras

**Arquivo**: `index.html`

Um gerador de senhas robusto que segue as melhores práticas de segurança.

#### Funcionalidades:
- ✅ Senhas aleatórias com comprimento configurável (8 a 64 caracteres)
- ✅ Seleção de tipos de caracteres (maiúsculas, minúsculas, números, especiais)
- ✅ Alta entropia com embaralhamento avançado
- ✅ Cópia segura para área de transferência
- ✅ Validação de entradas para prevenir configurações inválidas
- ✅ Interface acessível com suporte ARIA
- ✅ Feedback visual instantâneo

#### Conformidade:
- **NIST SP 800-63B**: Senhas fortes com alta entropia
- **ISO/IEC 27002:2022**: Codificação segura e validação de entradas
- **OWASP**: Boas práticas de segurança web
- **WCAG 2.1**: Acessibilidade completa

### 2. ✅ Checklist Mensal de Segurança da Informação

**Diretório**: `iso/`

Sistema completo para verificação periódica de conformidade em segurança da informação.

#### Funcionalidades:
- ✅ 130 itens de verificação organizados em 8 categorias
- ✅ Interface web com Flask
- ✅ Barra de progresso em tempo real
- ✅ Persistência de dados em JSON
- ✅ Geração de relatórios detalhados
- ✅ Estatísticas por seção e global
- ✅ Executável standalone (PyInstaller)
- ✅ Sistema de recomendações automáticas

#### Categorias do Checklist:
1. **Documentos e Dados Sensíveis** (20 itens)
2. **Segurança no Computador e Navegador** (20 itens)
3. **E-mails e Comunicação Segura** (20 itens)
4. **Senhas e Autenticação** (20 itens)
5. **Redes e Conectividade** (20 itens)
6. **Backup e Recuperação** (20 itens)
7. **Conformidade com LGPD** (15 itens)
8. **Educação e Conscientização** (10 itens)

#### Conformidade:
- **ISO 27002:2022**: Controles de segurança da informação
- **ISO 27701:2019**: Gestão de privacidade
- **LGPD**: Lei Geral de Proteção de Dados
- **NIST Cybersecurity Framework**: Práticas de segurança

### 3. 📚 Cartilhas de Segurança

**Diretório**: `cartilhas/`

Conjunto de 9 cartilhas educativas em formato PNG sobre segurança da informação.

#### Conteúdo:
- Cartilha 1: Fundamentos de Segurança da Informação
- Cartilha 2: Proteção de Dados Pessoais (LGPD)
- Cartilha 3: Senhas Seguras
- Cartilha 4: Phishing e Engenharia Social
- Cartilha 5: Segurança em Redes Wi-Fi
- Cartilha 6: Backup e Recuperação de Dados
- Cartilha 7: Dispositivos Móveis
- Cartilha 8: Trabalho Remoto Seguro
- Cartilha 9: Resposta a Incidentes

### 4. 📄 Documentação PDF

**Diretório**: `doc/`

Documentação oficial em PDF para impressão e distribuição.

- **Checklist Mensal de Segurança da Informação.pdf**: Versão impressa do checklist completo

## 🔧 Tecnologias Utilizadas

### Frontend (Gerador de Senhas)
- **HTML5**: Estrutura semântica
- **CSS3**: Estilização moderna com variáveis CSS
- **JavaScript (ES6+)**: Lógica de negócio
- **Web APIs**: 
  - Clipboard API (cópia segura)
  - ARIA (acessibilidade)
  - Crypto API (geração aleatória)

### Backend (Checklist)
- **Python 3.8+**: Linguagem principal
- **Flask 3.1.0**: Framework web
- **PyInstaller**: Criação de executáveis
- **JSON**: Armazenamento de dados

### Conformidade
- **ISO 27002:2022**: Controles de segurança
- **ISO 27701:2019**: Privacidade
- **LGPD**: Lei brasileira de proteção de dados
- **NIST SP 800-63B**: Diretrizes de identidade digital
- **OWASP Top 10**: Segurança em aplicações web
- **WCAG 2.1**: Acessibilidade web

## 📁 Estrutura do Projeto

```
ciberseguranca/
│
├── index.html                  # Gerador de Senhas Seguras (standalone)
├── README.md                   # Documentação principal (este arquivo)
├── checklist_data.json         # Dados persistentes do checklist
├── .gitignore                  # Arquivos ignorados pelo Git
│
├── cartilhas/                  # Material educativo
│   ├── cartilha1.png          # Fundamentos de Segurança
│   ├── cartilha2.png          # Proteção de Dados (LGPD)
│   ├── cartilha3.png          # Senhas Seguras
│   ├── cartilha4.png          # Phishing e Engenharia Social
│   ├── cartilha5.png          # Segurança em Wi-Fi
│   ├── cartilha6.png          # Backup e Recuperação
│   ├── cartilha7.png          # Dispositivos Móveis
│   ├── cartilha8.png          # Trabalho Remoto
│   └── cartilha9.png          # Resposta a Incidentes
│
├── doc/                        # Documentação em PDF
│   └── Checklist Mensal de Segurança da Informação.pdf
│
└── iso/                        # Sistema de Checklist
    ├── README.md               # Documentação do checklist
    ├── app.py                  # Aplicação Flask principal (909 linhas)
    ├── run.py                  # Script de inicialização
    ├── requirements.txt        # Dependências Python
    ├── run.spec                # Configuração PyInstaller
    ├── checklist_data.json     # Dados do checklist
    │
    ├── build/                  # Arquivos temporários de build
    └── dist/                   # Executáveis compilados
```

## 🚀 Como Usar

### 📦 Instalação Rápida

#### Opção 1: Gerador de Senhas (Sem instalação)

1. Abra o arquivo `index.html` diretamente no navegador
2. Pronto! A ferramenta está funcionando

#### Opção 2: Checklist Completo (Executável)

1. Navegue até `iso/dist/`
2. Execute o arquivo apropriado:
   - **Windows**: `run.exe`
   - **macOS**: `run.app`
   - **Linux**: `./run`
3. O navegador abrirá automaticamente em `http://127.0.0.1:5000/`

### 🛠 Instalação para Desenvolvimento

#### Pré-requisitos
- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Git (opcional)

#### Passos

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/estevam5s/ciberseguranca.git
   cd ciberseguranca
   ```

2. **Instale as dependências do Checklist**:
   ```bash
   cd iso
   pip install -r requirements.txt
   ```

3. **Execute o aplicativo**:
   ```bash
   python run.py
   ```

4. **Acesse no navegador**:
   ```
   http://127.0.0.1:5000/
   ```

### 🔨 Gerar Executável

Para criar uma versão standalone do checklist:

```bash
cd iso
pyinstaller --onefile --add-data "checklist_data.json:." run.py
```

O executável estará em `iso/dist/run` (ou `run.exe` no Windows).

## 📖 Documentação Detalhada

### Gerador de Senhas

#### Uso Básico

1. **Configurar Comprimento**: 
   - Use o campo numérico (mínimo 8, máximo 64)
   - Padrão: 16 caracteres

2. **Selecionar Tipos de Caracteres**:
   - ✅ Letras maiúsculas (A-Z)
   - ✅ Letras minúsculas (a-z)
   - ✅ Números (0-9)
   - ✅ Caracteres especiais (!@#$%^&*)

3. **Gerar Senha**:
   - Clique em "Gerar Senha"
   - A senha aparece imediatamente

4. **Copiar Senha**:
   - Clique no ícone 📋
   - Feedback visual (✅) confirma a cópia

#### Características de Segurança

- **Entropia Alta**: Mínimo de 40 bits (8 caracteres com todos os tipos)
- **Aleatoriedade**: Uso de `Math.random()` com embaralhamento Fisher-Yates
- **Validação**: Pelo menos um caractere de cada tipo selecionado
- **Sanitização**: Prevenção de XSS em entradas
- **Cópia Segura**: 
  - Preferência por `navigator.clipboard`
  - Fallback para `execCommand` em navegadores antigos

#### Exemplos de Senhas Geradas

```
16 caracteres (todos os tipos): K8#mL2@pQ9$vR5!a
32 caracteres (alta segurança): a3F$k9L#m2P@r8T!v5X&b7D%g1H^j4N*
64 caracteres (máxima segurança): [senha muito longa para exibir aqui]
```

### Checklist de Segurança

#### Uso Passo a Passo

1. **Iniciar Aplicativo**:
   - Execute o programa
   - Leia a introdução na página inicial
   - Clique em "Iniciar Checklist"

2. **Realizar Verificações**:
   - Navegue pelas 8 seções
   - Marque itens conformes com ✅
   - Observe o progresso na barra superior

3. **Gerar Relatório**:
   - Clique em "Gerar Relatório" no rodapé
   - Revise estatísticas e recomendações
   - Imprima ou salve como PDF

4. **Próximo Mês**:
   - Use "Resetar Checklist" no início do novo período
   - Os dados anteriores são preservados até resetar

#### Interpretação de Resultados

| Conformidade | Ação Recomendada |
|--------------|------------------|
| 90-100% | ✅ Excelente! Mantenha as práticas |
| 70-89% | ⚠️ Bom, mas há espaço para melhorias |
| 50-69% | 🔶 Atenção! Revisão urgente necessária |
| < 50% | 🚨 Crítico! Ação imediata obrigatória |

#### Estrutura de Dados

```json
{
  "1.1": true,   // Item verificado
  "1.2": false,  // Item pendente
  "1.3": true,
  // ... outros itens
}
```

## 📜 Conformidade e Normas

### ISO 27002:2022

**Controles de Segurança da Informação**

O sistema implementa os seguintes controles:

- **5.10**: Uso aceitável de ativos
- **5.12**: Classificação da informação
- **5.13**: Rotulagem de informação
- **5.14**: Transferência de informação
- **5.17**: Informação de autenticação
- **5.23**: Segurança da informação na nuvem
- **5.34**: Privacidade e proteção de dados pessoais
- **6.7**: Trabalho remoto
- **6.8**: Relatório de eventos de segurança
- **7.3**: Segurança física de escritórios
- **7.7**: Mesa limpa e tela limpa
- **7.9**: Segurança de ativos fora das instalações
- **7.10**: Mídia de armazenamento
- **8.1**: Dispositivos de ponto final do usuário
- **8.3**: Restrição de acesso à informação
- **8.7**: Proteção contra malware
- **8.8**: Gestão de vulnerabilidades técnicas
- **8.10**: Exclusão de informação
- **8.13**: Backup de informação
- **8.20**: Segurança de redes
- **8.24**: Criptografia

### ISO 27701:2019

**Sistema de Gestão de Privacidade**

Implementação de controles de privacidade:

- **6.3.2.2**: Identificação de base legal
- **6.10.2.1**: Processamento limitado de dados
- **6.10.2.2**: Minimização de dados

### LGPD (Lei 13.709/2018)

**Lei Geral de Proteção de Dados Pessoais**

Conformidade com artigos essenciais:

- **Art. 6**: Princípios de tratamento de dados
- **Art. 46**: Segurança e boas práticas
- **Art. 48**: Comunicação de incidentes
- **Art. 49**: Sistemas e aplicações dedicadas

### NIST SP 800-63B

**Diretrizes de Identidade Digital**

Implementação de:

- Requisitos de entropia de senha
- Comprimento mínimo e máximo
- Composição de caracteres
- Proibição de senhas comuns

### OWASP Top 10

Proteção contra:

- **A01:2021**: Broken Access Control
- **A02:2021**: Cryptographic Failures
- **A03:2021**: Injection
- **A04:2021**: Insecure Design
- **A05:2021**: Security Misconfiguration
- **A07:2021**: Identification and Authentication Failures

## 💼 Casos de Uso

### 1. Setor Público

**Cenário**: Prefeitura Municipal precisa adequar-se à LGPD

**Solução**:
- Use o checklist mensal para verificar conformidade
- Distribua cartilhas educativas aos servidores
- Implemente senhas seguras com o gerador
- Gere relatórios mensais para o DPO

### 2. Empresas Privadas

**Cenário**: Startup de tecnologia precisa passar em auditoria ISO 27002

**Solução**:
- Execute verificações semanais com o checklist
- Treine equipe com as cartilhas
- Estabeleça política de senhas fortes
- Mantenha documentação de conformidade

### 3. Profissionais Autônomos

**Cenário**: Consultor precisa proteger dados de clientes

**Solução**:
- Use o gerador para criar senhas únicas por cliente
- Siga o checklist mensalmente
- Consulte cartilhas para boas práticas
- Mantenha registro de conformidade

### 4. Instituições de Ensino

**Cenário**: Universidade precisa educar alunos sobre segurança

**Solução**:
- Distribua cartilhas em materiais didáticos
- Use o gerador em laboratórios de informática
- Implemente checklist em departamentos administrativos
- Crie workshops baseados nos materiais

## 🔐 Segurança

### Boas Práticas Implementadas

#### Gerador de Senhas

✅ **Aleatoriedade Criptográfica**: 
- Uso de fontes de entropia adequadas
- Embaralhamento Fisher-Yates para distribuição uniforme

✅ **Validação de Entradas**:
- Sanitização para prevenir XSS
- Limitação de comprimento (8-64 caracteres)
- Verificação de tipos de caracteres

✅ **Cópia Segura**:
- Preferência por API moderna (Clipboard)
- Fallback seguro para navegadores legados
- Limpeza de memória após uso

✅ **Sem Armazenamento**:
- Senhas nunca são salvas
- Não há histórico ou log
- Execução 100% client-side

#### Checklist

✅ **Isolamento de Dados**:
- Armazenamento local em JSON
- Sem transmissão de dados para internet
- Permissões de arquivo restritas

✅ **Validação Flask**:
- Proteção contra CSRF
- Sanitização de entradas
- Tratamento de erros robusto

✅ **Execução Segura**:
- Binding apenas em localhost
- Sem exposição externa
- Logs mínimos

### Recomendações de Uso

⚠️ **Importante**:

1. **Gerador de Senhas**:
   - Use apenas em computadores confiáveis
   - Não gere senhas em computadores públicos
   - Copie a senha imediatamente e feche a aba
   - Nunca compartilhe senhas geradas

2. **Checklist**:
   - Execute apenas em ambiente seguro
   - Proteja o arquivo JSON com permissões adequadas
   - Mantenha backups dos relatórios
   - Revise regularmente (mensal ou quinzenal)

3. **Cartilhas**:
   - Distribua apenas versões oficiais
   - Mantenha material atualizado
   - Complemente com treinamentos presenciais

## 🤝 Contribuindo

Contribuições são muito bem-vindas! Este é um projeto de código aberto focado em segurança da informação.

### Como Contribuir

1. **Fork o repositório**
2. **Crie uma branch** para sua feature:
   ```bash
   git checkout -b feature/MinhaNovaFuncionalidade
   ```
3. **Commit suas mudanças**:
   ```bash
   git commit -m 'Adiciona nova funcionalidade X'
   ```
4. **Push para a branch**:
   ```bash
   git push origin feature/MinhaNovaFuncionalidade
   ```
5. **Abra um Pull Request**

### Diretrizes

- ✅ Siga as normas de segurança (ISO 27002, OWASP)
- ✅ Documente todo o código
- ✅ Inclua testes quando aplicável
- ✅ Mantenha compatibilidade com navegadores modernos
- ✅ Respeite a privacidade dos usuários
- ✅ Não introduza dependências desnecessárias

### Áreas para Contribuição

- 📱 **Interface Mobile**: Aplicativo nativo iOS/Android
- 🌐 **Internacionalização**: Traduções para outros idiomas
- 📊 **Visualizações**: Gráficos e dashboards
- 🔔 **Notificações**: Sistema de alertas e lembretes
- 🤖 **Automação**: Scripts de verificação automática
- 📚 **Documentação**: Mais tutoriais e guias
- 🎨 **Design**: Melhorias visuais e UX
- 🔧 **Integrações**: APIs de terceiros (SIEM, ticketing)

## 🗺 Roadmap

### Versão 2.0 (Q3 2025)

- [ ] PWA (Progressive Web App) para instalação
- [ ] Modo escuro (Dark Mode)
- [ ] Exportação de relatórios em múltiplos formatos (PDF, XLSX, CSV)
- [ ] Sistema de usuários com autenticação
- [ ] Dashboard analítico com gráficos
- [ ] Histórico de verificações anteriores
- [ ] Comparação entre períodos

### Versão 2.5 (Q4 2025)

- [ ] Aplicativo mobile nativo (iOS e Android)
- [ ] Sincronização em nuvem (opcional e criptografada)
- [ ] Sistema de notificações e lembretes
- [ ] Integração com APIs de segurança (Have I Been Pwned)
- [ ] Módulo de gestão de incidentes
- [ ] Sistema de tickets para não conformidades
- [ ] Auditoria com assinatura digital

### Versão 3.0 (2026)

- [ ] IA para análise de riscos
- [ ] Recomendações personalizadas baseadas em histórico
- [ ] Integração com SIEM (Security Information and Event Management)
- [ ] Módulo de treinamento interativo
- [ ] Gamificação para engajamento
- [ ] API REST para integrações
- [ ] Suporte a múltiplas organizações

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

```
MIT License

Copyright (c) 2025 LTD-2025-1-Cyber-Security-Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[Texto completo da licença MIT...]
```

## 👥 Autores e Créditos

### Equipe de Desenvolvimento

**LTD-2025-1-Cyber-Security-Project**
- GitHub: [@estevam5s](https://github.com/estevam5s)
- Repository: [ciberseguranca](https://github.com/estevam5s/ciberseguranca)

### Agradecimentos

- **ISO/IEC**: Pelos padrões de segurança da informação
- **NIST**: Pelas diretrizes de cibersegurança
- **OWASP**: Pelo conhecimento compartilhado sobre segurança web
- **Comunidade Python/Flask**: Pelo framework robusto
- **Comunidade de Segurança**: Por revisões e feedback

## 📞 Contato e Suporte

### Suporte Técnico

- **E-mail**: contato@LTD-2025-1-Cyber-Security-Project.com.br
- **GitHub Issues**: [Reportar problema](https://github.com/estevam5s/ciberseguranca/issues)
- **Telefone**: (48) 9 9999-9999

### Redes Sociais

- **LinkedIn**: [LTD Cyber Security](https://linkedin.com/company/ltd-cyber-security)
- **Twitter**: [@LTDCyberSec](https://twitter.com/LTDCyberSec)

### Para Empresas

Entre em contato para:
- Consultoria em segurança da informação
- Treinamentos corporativos
- Customização da solução
- Suporte dedicado
- Auditorias de conformidade

---

## 📊 Estatísticas do Projeto

- **Linhas de Código**: ~2.500+
- **Módulos**: 4 principais
- **Cartilhas**: 9 educativas
- **Itens de Verificação**: 130
- **Normas Implementadas**: 5 (ISO 27002, ISO 27701, LGPD, NIST, OWASP)
- **Idiomas**: Português (BR)
- **Plataformas Suportadas**: Windows, macOS, Linux, Web

---

**🔐 Desenvolvido com dedicação para tornar a cibersegurança acessível a todos**

*"A segurança começa com conscientização e termina com ação."*

**Última atualização**: Novembro 2025  
**Versão**: 1.0.0  
**Status**: Ativo e em desenvolvimento
