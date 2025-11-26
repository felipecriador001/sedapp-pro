# SedApp Pro - Plataforma de Treinamento em Seducao Consciente com IA

## Descricao

SedApp Pro eh uma plataforma SaaS completa de treinamento em seducao consciente, combinando inteligencia artificial, pratica real e ferramentas de analise social. Projetada para usuarios que desejam aprimorar suas habilidades sociais de forma estruturada e consciente.

## Recursos Principais

### 1. **Sistema de Autenticacao**
   - Login seguro com email e senha
   - Dados armazenados localmente (localStorage)
   - Credenciais de demo para teste rapido

### 2. **Dashboard Inteligente**
   - 5 modulos principais integrados
   - Interface profissional e responsiva
   - Sistema de creditos integrado

### 3. **Trilhas de Aprendizado**
   - 4 categorias de treinamento:
     * Fundamentos da Seducao Consciente
     * Comunicacao e Presenca
     * Leitura Emocional
     * Pratica e Aplicacao
   - Conteudo detalhado e estruturado
   - Progresso rastreado automaticamente

### 4. **Chat IA Avancado**
   - Simula conversas reais com uma pessoa
   - IA faz perguntas e compartilha experiencias
   - **Scoring APENAS ao final** (nao durante a conversa)
   - Usuario mantenhama controle total da conversa
   - Feedback detalhado apos conclusao

### 5. **Pratica Real com Captura**
   - Cole mensagens reais do WhatsApp
   - IA gera 3 sugestoes de resposta
   - Analisa contexto e emocoes
   - Custo: 1 credito por uso

### 6. **Social Scout - Analise de Alvo**
   - Insira nome do alvo
   - Analisa interesses e personalidade
   - Coloque URLs das redes sociais (Instagram, Facebook, LinkedIn)
   - IA fornece insights comportamentais
   - Recomendacoes de abordagem personalizada
   - Custo: 3 creditos por uso

### 7. **Relatorio de Progresso**
   - Acompanhamento de evolucao
   - Pontos acumulados
   - Nivel de proficiencia
   - Historico completo de atividades
   - Graficos e estatisticas

## Sistema de Creditos

- **Creditos Iniciais**: 5 creditos gratis
- **Pratica Real**: -1 credito por uso
- **Social Scout**: -3 creditos por uso
- **Recarrega**: Usuario pode adicionar mais creditos
- **Armazenamento**: LocalStorage (dados persistem entre sessoes)

## Credenciais de Teste

```
Email: demo@sedapp.com
Senha: Demo123!@
```

## Instalacao e Uso

### Opcao 1: Abrir no Navegador
1. Clone o repositorio: `git clone https://github.com/felipecriador001/sedapp-pro.git`
2. Abra o arquivo `index.html` diretamente no navegador
3. Efetue login com as credenciais de teste

### Opcao 2: Usar com Servidor Local
1. Clone o repositorio
2. Instale um servidor HTTP simples (ex: `python -m http.server` ou `live-server`)
3. Acesse `http://localhost:8000`

### Opcao 3: Deploy em Vercel
1. Faça fork deste repositorio
2. Conecte ao Vercel: https://vercel.com/import
3. Deploy automaticamente

## Seguranca

- **LGPD Compliant**: Sem coleta de dados pessoais nao autorizados
- **Anti-XSS**: Todos os inputs sao sanitizados
- **LocalStorage Seguro**: Dados armazenados apenas localmente
- **Sem Servidor**: Nenhuma informacao sensivel enviada para servidores

## Arquivos do Projeto

```
sedapp-pro/
├── index.html          # Aplicacao completa em um arquivo
├── README.md           # Esta documentacao
└── package.json        # Metadados do projeto
```

## Tecnologias Utilizadas

- **HTML5** - Estrutura
- **CSS3** - Estilo profissional com design responsivo
- **JavaScript ES6+** - Logica da aplicacao
- **LocalStorage API** - Persistencia de dados
- **Responsive Design** - Compativel com desktop e mobile

## Funcionalidades Principais

### Chat IA - Scoring Apenas ao Final
A funcionalidade mais importante: o chat nao mostra scoring apos cada mensagem. O usuario aprende e pratica livremente, e apenas ao final da conversa recebe um feedback detalhado com sua pontuacao.

**Fluxo**:
1. Usuario inicia conversa com IA
2. IA simula uma pessoa real
3. Usuario e IA trocam mensagens normalmente
4. Usuario clica "Finalizar Conversa"
5. IA analisa e gera scoring detalhado

### Pratica Real - 3 Sugestoes Inteligentes
O usuario copia mensagens reais do WhatsApp e a IA oferece 3 opcoes de resposta otimizadas.

### Social Scout - Analise Comportamental Completa
Insira nome e URLs sociais do alvo - a IA fornece analise comportamental, interesses e recomendacoes de abordagem.

## Desenvolvimento Futuro

- [ ] Integracao com API de IA avancada (GPT-4)
- [ ] Video tutoriais integrados
- [ ] Comunidade de usuarios
- [ ] Estatisticas avancadas
- [ ] Sistema de gamificacao
- [ ] Mobile app nativo

## Suporte

Para problemas ou sugestoes, abra uma "Issue" neste repositorio.

## Licenca

Este projeto eh de uso privado. Todos os direitos reservados.

---

**Versao**: 1.0.0  
**Ultima Atualizacao**: 2025  
**Autor**: felipecriador001
