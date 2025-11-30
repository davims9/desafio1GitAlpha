<p align="center">
  <img src="images/" alt="Imagem de topo" style="max-width:700px; width:100%; height:auto;" />
</p>

# Assuntos aprendidos nas aulas

Bem-vindo! Este índice reúne os topicos dos assuntos aprendidos em aulas.

---

## 1. Fundamentos: Internet, Web e Comunicação de Rede

- **Diferenças entre INTERNET e WEB**
  - Conceitos e distinções (camadas, serviços e protocolos)
- **Princípio da comunicação de rede**
  - Modelo cliente/servidor, pacotes, roteamento
- **Importância das diferentes topologias de rede**
  - Barramento, estrela, malha, anel — vantagens e desvantagens
- **O que é Backbone**
  - Função e exemplos

---

## 2. Protocolos, Endereçamento e NAT

- **O que são protocolos de rede**
  - Função de protocolos (regras, empacotamento, sinalização)
- **O que é o NAT (endereçamento IP público e portas)**
  - Tradução de endereços, mapeamento de portas
- **Problemas do NAT**
  - Traversal, P2P, endereçamento e rastreabilidade
- **Máscara de rede**
  - CIDR, sub-redes e cálculo básico
- **Mudanças do IPv4 para IPv6**
  - Motivação, espaço de endereçamento e impactos

---

## 3. Transporte: TCP, UDP e Confiabilidade

- **Diferença dos cabeçalhos do TCP e UDP**
  - Campos principais e objetivos
- **Como funcionam o TCP e UDP e qual é usado na web**
  - Confiabilidade, handshake, uso típico (HTTP(S), QUIC)
- **Confiabilidade da rede**
  - Erros de conexão
  - Erros de envio e confirmação (ACKs, retransmissão)
- **Funcionamento e exemplos de latência de rede**
  - Causas, medição e impacto em aplicações

---

## 4. Serviços de Rede: DNS, Balanceamento e QoS

- **Disponibilidade de servidores DNS e balanceamento de carga**
  - Técnicas, failover e replicação
- **NS Lookup**
  - Como usar e interpretar resultados
- **Registro PTR e dificuldade da configuração**
- **DNS dinâmicos**
- **Implicações da migração de domínios**
- **Como funciona o balanceamento de carga na rede**
  - Layer 4 vs Layer 7, algoritmos (round-robin, least-conns)
- **Funcionamento do QoS**
  - Prioritização de tráfego, filas e classes

---

## 5. VPNs, Tunneling e Segurança de Transmissão

- **Funcionamento da VPN**
  - Tipos (site-to-site, remote-access), encapsulamento e criptografia
- **Funcionamento de VPNs e tunneling**
- **Proteção de dados na transmissão cliente-servidor**
  - TLS/SSL, certificados e boas práticas

---

## 6. Web: História, Arquiteturas e APIs

- **História web**
  - Início da Web
  - Web 2.0
  - Web 3.0 (conceito e expectativas)
- **API RESTful**
  - O que é
  - Segurança da API
  - Exemplo: webservice simples (endpoints, verbos)
- **Arquitetura de 3 camadas**
  - Apresentação, Negócio e Dados — responsabilidades e fluxo
- **Microserviços**
  - Conceito, vantagens e desafios
- **Web 2.0 e SPA**
  - Diferenças e exemplos

---

## 7. Dados e Formatos

- **Diferença e usos do JSON e XML**
- **Protobuf**
- **O que é YAML**

---

## 8. Autenticação e Autorização

- **O que é o OAuth**
  - Fluxos principais e uso comum
- **Contratos inteligentes**
  - O que são e como funcionam (visão geral)

---

## 9. DNS, Domínios e Registro

- **Registro de domínios: regras, funcionamentos e entidade de registro**
- **Implicações da migração de domínios** (repetido para reforço)

---

## 10. Ataques e Mitigações

- **Ataques DDoS**
  - Como ocorre
  - Exemplos notórios (ex.: ataques a grandes provedores)
  - Mitigação: blackholing, rate limiting, CDN/edge
- **Envenenamento de cache e como evitar**
- **Ameaças à segurança de redes**
  - Principais ameaças e vetores
- **Insider Threat**
  - O que são, como prevenir, exemplos práticos
- **Malwares**
- **Gerenciamento de patches e atualizações contra vulnerabilidades**

---

## 11. Redes LAN/WAN/MAN/PAN e Tecnologias de Enlace

- **LANs, WANs, MANs e PANs**
  - Funcionamento e uso
  - Protocolos típicos
- **Arquiteturas Ethernet e Token Ring**
  - Como funcionam, usos e comparações
  - Conceito de lista circular (Token Ring)

---

## 12. Git e Controle de Versão

- **Locais de configurações do Git**
- **Diferença entre `git restore` e `git reset`**
- **Cuidados no uso de flags como `--hard`**
- **Passo a passo de criação/edição de arquivos no Git**
- **Boas práticas para commits**
- **Conexão entre Índice (staging) e Working Tree**
- **Uso do `.gitignore`**
- **Uso da extensão GitLens**

---

## 13. Branches, Stash e Merge

- **O que é uma branch**
- **Convenções para branch**
- **Uso seguro através das branches**
- **Como funciona o HEAD**
- **Histórico de alterações**
- **Flags importantes**
- **`git stash`**
- **Merge e como resolver conflitos**
  - Estratégias: manter ambas as seções, manual edit, ferramentas de merge
