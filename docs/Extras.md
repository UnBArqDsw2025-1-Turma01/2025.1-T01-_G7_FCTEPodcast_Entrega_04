# Extras

Aqui apresentamos iniciativas que, embora não estejam diretamente relacionadas ao escopo de reutilização de software, consideramos relevantes destacar. São ações que contribuem significativamente para o aumento da confiabilidade, segurança e maturidade do projeto, refletindo o compromisso da equipe com boas práticas de desenvolvimento e entrega de software de qualidade.


---

## **Deploy da Aplicação em Ambiente de Produção**

A aplicação está configurada para o ambiente de produção com foco em:

- Estabilidade
- Segurança
- Automação

O processo de deploy segue uma estrutura padronizada, permitindo atualizações controladas e confiáveis.

---

## **Medidas de Segurança**

> A segurança é tratada como prioridade em todas as etapas do desenvolvimento.

As seguintes camadas de proteção foram implementadas:

- **Autenticação Segura**
  - Utilização de **JWT (JSON Web Token)** para sessões autenticadas.
- **Cookies HTTPOnly**
  - Impede o acesso via JavaScript, protegendo contra ataques de Cross-Site Scripting (XSS).
- **HelmetJS**
  - Configuração de cabeçalhos HTTP de segurança para reduzir vulnerabilidades conhecidas.
- **Resposta a Incidentes**
  - Durante o desenvolvimento, a aplicação sofreu um **ataque hacker**. A partir dessa ocorrência, medidas de monitoramento e reforço da segurança foram implementadas.

---

## **Automação com Github Actions**

A aplicação conta com um fluxo de integração contínua automatizado por meio do **Github Actions**, incluindo:

- **Lint**
  - Validação automática de estilo e boas práticas do código.
- **Build**
  - Processo automatizado de construção da aplicação.
- **Deploy**
  - Pipeline de deploy contínuo para o ambiente de produção. Atualmente, em fase de ajustes.
- **Dependabot**
  - Monitoramento automático das dependências do projeto e sugestões de atualizações.

---

## **Testes Unitários**

Os testes unitários garantem a confiabilidade do código e possibilitam:

- Detecção rápida de falhas
- Confiança na manutenção e evolução do sistema
- Redução de erros em produção

A implementação de testes é parte essencial do ciclo de desenvolvimento da aplicação.

---

## **Transformação em Software Livre**

O projeto está em processo de transição para **Software Livre**, seguindo as melhores práticas da comunidade open-source:

- **Guia de Contribuição**
  - Instruções claras para facilitar a participação de novos colaboradores.
- **Licença de Software Livre**
  - Documento que define os direitos e responsabilidades no uso, modificação e distribuição do código.
- **Integração com Github Actions**
  - Todas as contribuições passam por validações automatizadas, garantindo que o código siga os padrões de qualidade e segurança estabelecidos.

---

