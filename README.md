Military OSINT Course
Laboratório prático de OSINT militar e tático.

Este projeto reúne exercícios, datasets, ferramentas e documentação para estudo e prática de inteligência de fontes abertas (OSINT) aplicada ao contexto militar e de segurança.

📁 Estrutura
docs/ → Documentação e tutoriais

tools/ → Scripts e guias de ferramentas

datasets/ → Conjuntos de dados para análise

exercises/ → Exercícios práticos

legal-ethics/ → Ética e aspectos legais

🎯 Objetivo
Fornecer um ambiente de aprendizado prático e seguro para profissionais e estudantes interessados em OSINT.

📅 Roadmap de Aprendizado
Semana 1 — Fundamentos de OSINT
Introdução ao conceito de OSINT

Fontes abertas: redes sociais, registros públicos, imagens

Ética e legalidade

Semana 2 — Ferramentas Essenciais
ExifTool para metadados

Google Earth para imagens de satélite

Maltego e SpiderFoot para análise de redes

Semana 3 — Geolocalização e Imagens
Análise de metadados EXIF

Identificação de locais por imagens

Exercício prático: desafio de geolocalização

Semana 4 — Inteligência em Redes Sociais
Coleta de dados em Twitter, Facebook, Telegram

Identificação de padrões de comportamento

Exercício prático: análise de perfis

Semana 5 — Dados Públicos e Registros
Bancos de dados governamentais

Documentos oficiais

Exercício prático: cruzamento de informações

Semana 6 — Automação e Scripts
Introdução a Python para OSINT

Automação de coleta

Exercício prático: script de coleta de dados

Semana 7 — Estudos de Caso
Aplicações militares e táticas

Análise de operações reais (open source)

Discussão ética

🧩 Exercício Resolvido: Identificação de Localização
Imagem: soldado.jpg

Objetivo: descobrir onde a foto foi tirada.

Passos usados:

Identificação de placa de rua

Busca por padrão arquitetônico

Comparação com imagens públicas

Confirmação: Recife, PE

Ferramentas:

Google Lens

Street View

TinEye

🔍 Exemplo de Análise EXIF
Arquivo: exemplo.jpg

Modelo da câmera: Nikon D3200

Data da captura: 2024-05-12

Coordenadas: -23.55052, -46.63331

Software utilizado: exiftool

Comando usado:

bash
exiftool exemplo.jpg
Resultado:

Localização indica região central de São Paulo

Metadados não removidos → risco de exposição de informações sensíveis

📍 Exemplo de Geolocalização
Imagem: torre.jpg

Passos usados:

Identificação de elementos visuais

Busca reversa no Google Lens

Comparação com Street View

Confirmação: Guarulhos, SP

Ferramentas:

Google Lens

Mapillary

Street View

🤖 Exemplo de Coleta Automatizada
Script: coleta_twitter.py

Função:

Coleta tweets contendo palavras-chave militares

Armazena em CSV

Filtra por geolocalização

Bibliotecas usadas:

Tweepy

Pandas

🤝 Como Contribuir
Faça um fork do repositório

Crie uma branch com sua melhoria

Envie um pull request

Aguarde revisão

Sugestões de contribuição:

novos exercícios

novas ferramentas

novos datasets

correções de documentação

🛡️ LGPD e ISO 27001 aplicadas ao OSINT
📘 LGPD — Lei Geral de Proteção de Dados
Mesmo quando usamos informações públicas, a LGPD ainda se aplica.
Ela protege dados pessoais e define como eles podem ser coletados e usados.

Princípios importantes da LGPD para OSINT
Finalidade: ter um objetivo claro para a coleta.

Necessidade: coletar só o mínimo necessário.

Transparência: nunca enganar pessoas.

Segurança: proteger os dados coletados.

Prevenção: evitar riscos ao titular.

Não discriminação: nunca usar dados para prejudicar alguém.

O que NÃO pode ser feito
Coletar dados pessoais sensíveis sem base legal.

Expor informações privadas.

Criar perfis invasivos.

Reidentificar pessoas anonimizadas.

Compartilhar dados pessoais sem autorização.

O que PODE ser feito
Usar dados públicos.

Analisar perfis abertos.

Investigar documentos oficiais.

Coletar dados para segurança, defesa ou prevenção de fraudes.

🏛️ ISO 27001 — Segurança da Informação
A ISO 27001 define boas práticas para proteger informações.
Aplicar esses princípios no OSINT deixa o projeto mais seguro e profissional.

Controles importantes da ISO 27001 para OSINT
🔐 A.5 — Políticas de Segurança
Definir regras claras sobre coleta e uso de dados.

🧑‍💻 A.6 — Organização da Segurança
Controlar quem acessa datasets e ferramentas.

🔒 A.8 — Gestão de Ativos
Classificar dados coletados (públicos, sensíveis, críticos).

🛂 A.9 — Controle de Acesso
Restringir acesso a dados pessoais.

Usar autenticação forte.

📊 A.12 — Segurança Operacional
Registrar logs de scripts e coletas.

Monitorar uso das ferramentas.

🛠️ A.14 — Desenvolvimento Seguro
Criar scripts sem expor credenciais.

Evitar armazenar dados sensíveis em código.

⚠️ A.18 — Conformidade
Garantir respeito à LGPD e leis locais.

Documentar riscos e mitigação.

⚖️ Ética e Legalidade no OSINT
Nunca invadir sistemas (isso não é OSINT).

Nunca coletar dados privados.

Nunca expor pessoas sem necessidade.

Sempre respeitar leis e normas.

Usar OSINT apenas para fins legítimos: segurança, defesa, investigação autorizada.

🏷️ Tags (SEO)
OSINT, Cybersecurity, Military Intelligence, SOC, Blue Team, Threat Intelligence, Segurança da Informação, Defesa Digital

