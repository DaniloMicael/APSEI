# Possiveis perguntas

## Como classificam o vosso sistema com base no AI Act?

O sistema é classificado como **alto risco** pelo **AI Act**, pois lida com **dados biométricos, saúde e decisões automatizadas** que podem impactar diretamente os utilizadores, exigindo transparência, supervisão humana e conformidade com regulamentos.

## Como garantem a segurança dos dados dos utilizadores?
    1. Engineering
        - Encriptação de dados (AES-256 por exemplo)
        - Autenticação segura (OAuth2, JWT)
        - Proteção contra ataques adversariais em IA (differential privacy e federated learning)
    2. Legal & Compliance
        - auditorias regulares
        - garantia de transparência (explicação aos utilizadores sobre o uso dos seus dados)
    3. QA
        - Testes de segurança
        - Resolução de vulnerabilidades (OWASP)
        - Testes de penetração
    4. Docker + Kubernetes (para escalabilidade e segurança)
    5. AWS GuardDuty

## Com quem vão partilhar os dados dos utilizadores?
    1. Fornecedores de infraestrutura (AWS)
    2. Instituições de saúde (dados anonimizados)

## Então mas isso já não existe?
    - Sim, mas há pontos diferenciais
        - Third party tools como consensus
        - Correção de postura real-time