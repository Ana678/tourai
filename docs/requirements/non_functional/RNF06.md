## RNF06 - Segurança

Os dados dos usuários devem ser protegidos por autenticação forte e comunicação criptografada (HTTPS, tokens, etc.).

---

## 📄 Metadados do Requisito

- **Autor do Requisito:** Ana Carolina
- **Justificativa:** Proteger as informações pessoais e de viagem dos usuários contra acessos não autorizados, garantindo a privacidade e a confiança na plataforma.
- **Prioridade:** Alta

---

## ✅ Critérios de Aceitação

1. Todas as comunicações entre o cliente e o servidor devem ser criptografadas usando HTTPS.
2. O sistema deve implementar autenticação de dois fatores (2FA) como uma opção para os usuários.
3. As senhas dos usuários devem ser armazenadas de forma segura, utilizando hashing e salting.
4. O sistema deve proteger contra ataques comuns de segurança web, como injeção SQL e XSS.
5. O acesso a dados sensíveis deve ser restrito apenas a usuários autorizados e com base em privilégios mínimos.
