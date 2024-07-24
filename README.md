# Readme

### Prototipagem de 27 Telas para Serviços Específicos

Pensando em um eco simples de sistema, serão desenvolvidas 27 telas, conforme descritas abaixo:

1. **Tela de Busca de Anuidades**
2. **Tela de Alteração de Situação da Anuidade**
3. **Tela de Alteração de Valor da Anuidade**
4. **Tela de Exclusão de Anuidade**
5. **Tela de Alteração de Anuidade**
6. **Tela de Inserção de Anuidade**
7. **Tela de Listagem de Anuidades**
8. **Tela de Listagem de Carteiras**
9. **Tela de Listagem de CREAs**
10. **Tela de Listagem de Grupos de Títulos Profissionais**
11. **Tela de Listagem de Modalidades de Títulos Profissionais**
12. **Tela de Listagem de Níveis de Formação Profissional**
13. **Tela de Exclusão de Endereço**
14. **Tela de Alteração de Endereço**
15. **Tela de Inserção de Endereço**
16. **Tela de Listagem de Endereços**
17. **Tela de Inserção de Histórico de Registro**
18. **Tela de Alteração de Histórico de Registro**
19. **Tela de Listagem de Histórico de Registro**
20. **Tela de Listagem de Imagens**
21. **Tela de Alteração de Profissional**
22. **Tela de Busca de Profissional por RNP**
23. **Tela de Exclusão de Profissional**
24. **Tela de Inserção de Profissional**
25. **Tela de Listagem de Profissionais**
26. **Tela de Listagem de Títulos**
27. **Tela de Alteração de Títulos**

### Estrutura do Protótipo no Bubble.io

#### 1. Sistema de Registro Unificado:
- **Objetivo:** Criar uma interface onde os usuários podem se cadastrar e registrar suas informações utilizando tecnologias de blockchain para segurança e transparência.
- **Campos Necessários:**
  - Nome Completo
  - CPF
  - Número do CREA
  - Endereço
  - E-mail
  - Senha (com criptografia)
  - Confirmação de Senha
  - Registro no Blockchain (gerado automaticamente após o cadastro)

#### 2. Integração de Sistemas de Inteligência Artificial:
- **Objetivo:** Validar automaticamente documentos e dados dos profissionais utilizando IA.
- **Campos Necessários:**
  - Upload de Documento (PDF, Imagem)
  - Tipo de Documento (RG, CPF, Diploma, etc.)
  - Análise de IA (campo gerado automaticamente após upload)
  - Status de Validação (Aprovado, Rejeitado, Em Análise)

#### 3. Uso do NLTK para Processamento de Linguagem Natural:
- **Objetivo:** Utilizar NLTK para análise de textos em documentos submetidos e automatizar a extração de informações relevantes.
- **Campos Necessários:**
  - Texto Extraído (campo gerado automaticamente após upload do documento)
  - Entidades Reconhecidas (Nome, Número do CREA, Data de Emissão, etc.)
  - Status de Análise (Completado, Em Análise)

#### 4. Criação de APIs e Sistemas de Interoperabilidade:
- **Objetivo:** Facilitar a comunicação entre a plataforma nacional e os sistemas regionais dos CREAs e Mútua.
- **Endpoints Necessários:**
  - Enviar Dados Cadastrais
  - Receber Atualizações de Situação
  - Listar Dados Regionais
  - Sincronização de Dados

### Template Inicial no Bubble.io

#### Página Inicial (Dashboard)
- **Objetivo:** Fornecer uma visão geral e acesso rápido às principais funcionalidades.
- **Elementos:**
  - Menu de Navegação: Registro, Validação, APIs, Análise de Documentos
  - Resumo de Registro: Total de Usuários, Registros Recentes
  - Resumo de Validação: Documentos Pendentes, Documentos Validados
  - Resumo de Análise: Textos Extraídos, Entidades Reconhecidas
  - Acesso Rápido: Botões para Cadastro, Upload de Documentos, Sincronização de Dados

#### Página de Registro
- **Objetivo:** Permitir que novos usuários se cadastrem no sistema.
- **Elementos:**
  - Formulário de Registro: Nome, CPF, CREA, Endereço, E-mail, Senha, Confirmação de Senha
  - Botão de Enviar: Aciona a função de registro e criação no blockchain

#### Página de Validação de Documentos
- **Objetivo:** Permitir upload e validação de documentos utilizando IA.
- **Elementos:**
  - Formulário de Upload: Selecionar Tipo de Documento, Upload do Arquivo
  - Status de Validação: Mostra o status atual do documento enviado
  - Botão de Analisar: Aciona a função de validação por IA

#### Página de Análise de Documentos (com NLTK)
- **Objetivo:** Processar e analisar textos dos documentos submetidos, extraindo informações relevantes.
- **Elementos:**
  - Lista de Documentos Enviados: Mostra os documentos que foram submetidos para análise
  - Texto Extraído: Campo que exibe o texto extraído do documento
  - Entidades Reconhecidas: Lista das entidades (Nome, Número do CREA, etc.) extraídas do texto
  - Botão de Reanalisar: Aciona novamente a função de análise para reprocessar o documento

#### Página de APIs
- **Objetivo:** Gerenciar comunicação e sincronização de dados com sistemas regionais.
- **Elementos:**
  - Lista de Endpoints Disponíveis
  - Formulário para Enviar Dados
  - Status de Sincronização: Mostra o status das últimas sincronizações
  - Botão de Sincronizar: Aciona a função de sincronização de dados
