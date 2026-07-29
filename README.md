# Projeto Agente de IA com Tools para Atendimento Imobiliário

### 1️⃣ Descrição do Projeto
Este projeto foi desenvolvido para criar e implantar a Ana, uma agente de Inteligência Artificial focada na automação do atendimento via e-mail para a imobiliária Nova Lar Imóveis. O fluxo faz uso de tools (ferramentas) para consultar opções de imóveis em tempo real na planilha da empresa e registrar/atualizar automaticamente os dados dos leads no CRM, entregando respostas personalizadas e formatadas em HTML.

### 2️⃣ Objetivo
Automatizar o primeiro atendimento a clientes interessados em compra ou aluguel, reduzindo o tempo de resposta, padronizando a comunicação com o tom de voz da imobiliária e garantindo que nenhum lead qualificado deixe de ser registrado na base de dados.

### 3️⃣ Funcionalidades

- Atendimento automatizado e humanizado via e-mail com tom profissional e acolhedor
- Consulta inteligente de imóveis em planilha (buscar_imoveis) por bairro, tipo, preço e características
- Registro e atualização automática de potenciais clientes no CRM (registrar_lead)
- Esclarecimento de dúvidas frequentes sobre documentação, FGTS e processos de compra/aluguel
- Direcionamento estratégico de clientes qualificados para agendamento de visitas pelo WhatsApp
- Respostas dinâmicas e organizadas visualmente com formatação HTML

### 4️⃣ Informações analisadas

- Dados do cliente: Nome, e-mail, telefone, orçamento máximo e região de preferência
- Critérios da busca: Tipo de imóvel, número de quartos e aceitação de pets
- Status do atendimento: Tipo de interesse (compra/aluguel), resumo da conversa e próximo passo comercial
- Acervo de imóveis: ID do imóvel, faixas de preço (venda/locação) e regiões de atendimento (Zona Sul, Zona Oeste e Centro de SP)

### 5️⃣ Tecnologias utilizadas

- Agente de IA (Modelo de Linguagem com Function Calling / Tools)
- Tool buscar_imoveis (Integração com banco de dados/planilha de imóveis)
- Tool registrar_lead (Integração com planilha de CRM)
- Servidor de e-mail com suporte a HTML
- Microsoft Excel / Google Sheets

### 6️⃣ Benefícios da automação

- Resposta imediata e atendimento contínuo aos clientes
- Eliminação do trabalho manual de cadastro e atualização de leads
- Triagem qualificada: diferencia dúvidas genéricas de intenções reais de negócio
- Padronização no tom de voz e na apresentação visual das propostas enviadas
- Maior conversão de contatos em visitas reais para a equipe de corretagem
