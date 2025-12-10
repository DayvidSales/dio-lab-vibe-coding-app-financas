# 💸 App de Organização de Finanças Pessoais com Vibe Coding

# PRD
~~~markdown
1. Contexto
Aplicativo de finanças pessoais baseado em conversas em linguagem natural, eliminando formulários e planilhas. A proposta é tornar o controle financeiro simples, acessível e intuitivo.

2. Problema
Usuários abandonam apps financeiros por exigirem muita entrada manual, categorização trabalhosa e pouca personalização. A solução busca reduzir atrito com interação conversacional e automação.

3. Público-Alvo
Iniciantes no controle financeiro, pessoas que buscam simplicidade e usuários que não gostam de interfaces complexas.

4. Proposta de Valor
Assistente financeiro conversacional que registra gastos, organiza automaticamente e oferece recomendações personalizadas.

5. Funcionalidades-Chave
5.1 Registro de gastos por conversa.
5.2 Classificação automática de transações.
5.3 Definição e acompanhamento de metas.
5.4 Agente Financeiro com dicas personalizadas.
5.5 Relatórios simples e explicados em linguagem natural.

6. Entregável da IA (para o MVP)
- Plano de MVP com telas essenciais.
- Recursos mínimos necessários.
- Fluxo básico de interação.
- Esboço de validação inicial.

Telas essenciais:
1. Tela de Conversa
2. Resumo Financeiro
3. Metas
4. Relatórios Simples
5. Configurações

Recursos necessários:
- Interpretação de linguagem natural
- Banco de dados simples
- Motor de categorização automática
- Sistema de metas e alertas
- Módulo de recomendações

Validação inicial:
- Testar registro de gastos via conversa
- Avaliar clareza da categorização
- Verificar uso das metas
- Medir utilidade percebida das dicas
- Medir retenção em 7 dias

7. Princípios de Design Universal
A solução deve ser utilizável pelo maior número possível de pessoas. Requisitos:
- Interface simples e clara
- Linguagem natural acessível
- Contraste adequado e tipografia legível
- Suporte a diferentes formas de interação
- Tolerância a erros e correções simples
- Fluxos intuitivos e de baixo esforço cognitivo

8. Light e Dark Mode
O app deve oferecer modo claro e escuro, com:
- Alternância manual
- Opção de seguir o tema do sistema
- Contraste adequado em ambos os modos
- Consistência visual e legibilidade preservadas

Conceitos Didáticos

PRD (Product Requirements Document):
Documento que define o que será construído, para quem, por quê e quais funcionalidades são essenciais. Serve como mapa para orientar o desenvolvimento e evitar retrabalho.

Design Universal:
Abordagem de design que cria produtos utilizáveis pelo maior número possível de pessoas, independentemente de habilidades, idade ou limitações. Baseia-se em princípios como simplicidade, flexibilidade, clareza, tolerância ao erro e acessibilidade.

Vibe Coding:
Forma de construir produtos guiando a IA por linguagem natural, focando na intenção e na experiência desejada, não no código. Permite criar interfaces e comportamentos rapidamente por meio de iterações conversacionais.
~~~
# Interações com Lovable:
> Ao questionar o assistente sobre dúvidas financeiras (O que é Buy and Hold, explique este conceito) o mesmo me retornou o seguinte: Me fala quanto você gastou ou recebeu! Por exemplo: "Gastei R$25 no almoço". Preciso que ele seja capaz de tirar minhas dúvidas também e que os campos : Chat, Resumo, Metas e Relatórios, sejam interconectados/interligados para que as informações de um sejam usadas ou consultadas em outra opção sem muito trabalho. Adicione/Altere essas funcionalidades.

> Vou melhorar o assistente para responder dúvidas financeiras e interconectar os módulos. Deixe-me ver os arquivos atuais primeiro.

Resultado Final Lovable:
https://bate-papo-dinheiro.lovable.app/
<img width="1919" height="869" alt="image" src="https://github.com/user-attachments/assets/9914c760-03d0-4fd8-af24-9b8f7c35a4e1" />


# Resumo do App: 

## Visão Geral
Aplicativo de organização de finanças pessoais que funciona por meio de conversas em linguagem natural.  
O objetivo é tornar o controle financeiro acessível, intuitivo e personalizado, especialmente para iniciantes.

## Problema Resolvido
Usuários desistem de apps financeiros por exigirem entrada manual excessiva, categorização complexa e pouca personalização.  
Este app resolve isso com uma interface conversacional, categorização automática e recomendações inteligentes.

## Público-Alvo
- Pessoas iniciantes no controle financeiro
- Usuários que buscam praticidade e simplicidade
- Pessoas que não gostam de planilhas ou interfaces tradicionais

## Funcionalidades Principais
- Registro de gastos e ganhos via chat em linguagem natural
- Classificação automática de transações
- Definição e acompanhamento de metas financeiras
- Dicas personalizadas do “Agente Financeiro”
- Relatórios simples e explicativos
- Suporte a Light Mode e Dark Mode

## Design Universal
O app foi projetado para ser acessível ao maior número possível de pessoas, com:
- Interface clara e intuitiva
- Tipografia legível e bom contraste
- Fluxos tolerantes a erros e fáceis de corrigir
- Suporte a diferentes formas de interação (texto e voz)
- Experiência inclusiva para diferentes perfis de usuários

## MVP Entregue
### Telas Implementadas
- Chat com assistente financeiro
- Resumo financeiro
- Metas
- Relatórios
- Configurações

### Elementos Visuais
- Interface em modo escuro (Dark Mode)
- Sugestões rápidas de entrada ("Gastei R$", "Recebi R$", etc.)
- Navegação inferior com ícones intuitivos
- Placeholder educativo no campo de texto

### Fluxo de Interação
1. Usuário inicia conversa com o assistente
2. Registra gastos ou ganhos com frases naturais
3. Recebe confirmação e categorização automática
4. Acompanha metas e recebe dicas personalizadas
5. Visualiza relatórios simples e acessíveis

## Tecnologias e Requisitos
- Processamento de linguagem natural
- Banco de dados para transações
- Motor de categorização inteligente
- Sistema de metas e alertas
- Módulo de recomendações financeiras
- Suporte a temas visuais (light/dark)

## Validação Inicial
- Teste de usabilidade da conversa
- Clareza na categorização automática
- Utilização das metas financeiras
- Percepção de utilidade das dicas
- Retenção de usuários após 7 dias

## Conceitos Utilizados
### PRD (Product Requirements Document)
Documento que define escopo, público, funcionalidades e critérios de sucesso do produto.

### Design Universal
Princípios que garantem acessibilidade e usabilidade para o maior número de pessoas possível.

### Vibe Coding
Abordagem de criação guiada por intenção e linguagem natural, usando IA para transformar ideias em interfaces e comportamentos.

# Reflexão
# O que funcionou bem?
O processo de automatização e design do App.

# O que não funcionou como esperado?
Interação entre as funcionalidades, o que precisou de mais refinamento mas foi limitado pelo esgotamento dos créditos do Lovable.

# O que aprendeu sobre conversar com IAs?
É como conversar com um adulto superinteligente que faz quase tudo mas com a nescessidade de diálogos com enormes contextos.







