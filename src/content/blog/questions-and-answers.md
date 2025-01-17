---
title: 'Perguntas Frequentes'
description: 'Perguntas Frequentes / Q&A'
pubDate: 'Jun 05 2025'
tags: ['q&a', 'pergunta', 'resposta', 'preço', 'plano', 'msp', 'API', 'Selenium']
heroImage: '/q&a-1.webp'
keywords: 'Hostedscan funcionalidades, usar Selenium com Hostedscan, Selenium-side-runner CLI, varredura autenticada Hostedscan, OpenVAS varredura autenticada, mover Targets entre Workspaces, Hostedscan API, Hostedscan assinatura upgrade, erros técnicos Selenium, element click intercepted Selenium, varreduras falhando timeout Hostedscan, Hostedscan conformidade GDPR, Hostedscan certificações SOC ISO 27001, segurança da informação Hostedscan, Hostedscan relatórios personalizados, Hostedscan plano MSP, varredura de vulnerabilidades Hostedscan, Hostedscan suporte técnico, gestão de segurança Hostedscan, Hostedscan infraestrutura de segurança'
---

## 1. Funcionalidade do Produto
### Como posso usar o Selenium com a empresa Hostedscan?

> Certifique-se de que seus arquivos Selenium estão configurados corretamente para o ambiente da empresa. Se ocorrerem erros, verifique se os comandos estão alinhados com os requisitos da empresa, como configurações de tamanho de janela ou visibilidade de elementos. Use ferramentas como o CLI selenium-side-runner para testes locais.

### A plataforma suporta varredura autenticada?

> Sim, é possível realizar varreduras autenticadas se configuradas adequadamente. Por exemplo, o OpenVAS suporta essa funcionalidade, mas as instruções específicas podem variar de acordo com o scanner. Se precisar entre em contato com o suporte para obter ajuda.

### Posso mover Targets (alvos) entre Workspaces (áreas de trabalho)?

> Atualmente, a plataforma não permite mover alvos diretamente. Considere usar a API para exportar e reimportar os alvos na área de trabalho desejada, embora os resultados das varreduras anteriores não possam ser transferidos.

## 2. Assinatura

### Posso fazer um upgrade do meu plano durante o ciclo?

> Sim, os upgrades são permitidos. Você será cobrado de forma proporcional pelo tempo restante no plano atual, e o novo plano será aplicado imediatamente.

## 3. Erros Técnicos
### O que devo fazer se encontrar erros "element click intercepted" no Selenium?

> Esse erro geralmente indica elementos sobrepostos. Ajuste o script para garantir que o elemento alvo esteja acessível e visível. Para modais, feche ou descarte-os programaticamente antes de tentar novamente.

### Por que minhas varreduras estão falhando com erros de timeout?

> Erros de timeout podem ocorrer se a configuração da varredura exceder os limites de recursos das ferramentas da empresa baseado no seu plano. Reduza o escopo ou a complexidade da varredura.

## 4. Conformidade e Segurança
### A plataforma é compatível com o GDPR?

> Sim, a plataforma está em conformidade com o GDPR. Ela processa um volume mínimo de dados pessoais, principalmente para usuários do painel de administração. Entre em contato com a empresa para obter a documentação detalhada de conformidade.

### A plataforma possui certificações como SOC ou ISO?

> A plataforma está trabalhando para obter a certificação SOC Tipo II e segue os padrões ISO 27001 internamente para seu sistema de gestão de segurança da informação.

## 5. Perguntas Gerais
### Os relatórios podem ser personalizados ou brandados?

> Sim, no plano MSP, você pode substituir o logotipo, nome e rodapé dos relatórios. Use as configurações no painel para configurar isso.

### Vocês oferecem varredura na dark web?

> Não, a plataforma se concentra em infraestrutura e varredura de vulnerabilidades, e não em serviços relacionados à dark web.
