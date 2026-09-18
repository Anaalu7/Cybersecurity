#Exploração de Técnicas de Engenharia Social

## Descrição
Análise prática e estudo detalhado sobre as principais técnicas de **Engenharia Social** (*hacking humano*), explorando como os invasores utilizam manipulação psicológica, engano e exploração de comportamentos para comprometer sistemas e obter dados confidenciais.

## Objetivo
Identificar, categorizar e compreender a mecânica de operação de ataques baseados no fator humano (virtuais e físicos) para propor medidas eficazes de prevenção, mitigação e conscientização em cibersegurança.

## Contexto
Atividade prática realizada no curso **Segurança de Endpoint da Cisco (Networking Academy)**, integrada à preparação para a certificação **Cisco Certified Support Technician (CCST) Cybersecurity**.

## Passos Realizados
1. **Análise de Técnicas Baseadas em Engenharia Social:**
   * **Isca (Baiting):** Investigação de ofertas irrecusáveis (downloads gratuitos) ou mídias físicas (pendrives USB infectados) deixadas em locais públicos para atrair a curiosidade da vítima.
   * **Navegação Bisbilhoteira (Shoulder Surfing):** Observação visual direta ou remota (via câmeras/celulares) para obtenção de PINs, senhas e dados confidenciais inseridos pelas vítimas.
   * **Pré-texto (Pretexting):** Criação de cenários e identidades falsas (ex: suporte técnico, autoridade) para induzir a vítima a fornecer informações privilegiadas.

2. **Estudo de Golpes e Disfarces Digitais e Físicos:**
   * **Phishing, Spear Phishing e Caça à Baleia (Whaling):** Diferenciação entre campanhas massivas por e-mail/telefone (Phishing), ataques direcionados a indivíduos/empresas específicas (Spear Phishing) e focado em executivos de alto nível (Whaling).
   * **Ransomware e Scareware:** Avaliação do uso de telas/mensagens alarmantes falsas (Scareware) e sequestro/criptografia de dados vitais exigindo resgate (Ransomware).
   * **Mergulho no Lixo (Dumpster Diving):** Análise do risco da recuperação de papéis contendo credenciais ou dispositivos de armazenamento descartados incorretamente no lixo.
   * **Falsificação de Identidade (Impersonation) e Farsas (Hoaxes):** Engano através do personificação de entidades oficiais ou disseminação de falsos alertas de vírus para causar pânico.
   * **Caroninha / Traslado (Tailgating / Piggybacking):** Métodos de acesso físico não autorizado a instalações restritas seguindo funcionários autorizados.

3. **Análise de Táticas de Manipulação Psicológica e Métodos Avançados:**
   * **Ataques de Autoridade, Intimidação, Urgência e Escassez:** Exploração da tendência humana de obedecer ordens superiores, medo de sanções ou apressar decisões por limitação de tempo/estoque.
   * **Consenso (Prova Social), Familiaridade e Confiança:** Uso do comportamento da maioria, clonagem de perfis conhecidos e construção de relacionamentos falsos para diminuir a guarda do alvo.
   * **Ataque do Regador (Watering Hole) e Typosquatting:** Infecção de sites frequentemente visitados pela empresa e exploração de erros de digitação em URLs para redirecionamento malicioso.
   * **Fraude da Fatura e Remoção de Adendo:** Envio de faturas e telas de login falsas e a remoção de tags de e-mails externos para simular comunicações internas legítimas.

## Resultado
* **Vulnerabilidade Comportamental:** Confirmado que a curiosidade (Isca) e a ingenuidade em validar identidades (Pretexting/Impersonation) levam à infecção direta por malware e vazamento de credenciais.
* **Ameaças Físicas e Visuais:** Verificada a facilidade com que credenciais são capturadas através de celulares (Shoulder Surfing) e o acesso indevido por portas mantidas abertas (Tailgating).
* **Engano Técnico de Domínios:** Mapeado como a digitação incorreta de URLs (Typosquatting) e infecção de sites de rotina (Watering Hole) interceptam dados de usuários sem necessidade de invadir diretamente a rede da empresa.

## Aprendizados
* **Fator Humano como Elo Frágil:** A infraestrutura técnica de segurança (firewalls, antivírus) perde eficácia se o usuário for induzido a entregar acessos ou executar arquivos maliciosos.
* **Medidas de Proteção Organizacional:**
  * **Conscientização:** Treinamentos contínuos contra Phishing, Engenharia Social e procedimentos de mesa limpa.
  * **Controles Físicos:** Uso de bloqueadores de tela (películas de privacidade), fragmentadoras de papel para descarte e eclusas/Mantraps para evitar *Tailgating*.
  * **Controles Técnicos:** Implementação de Autenticação Multifator (MFA), filtros de e-mail e correções regulares de software.
