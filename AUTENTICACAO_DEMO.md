# Autenticação do Itechub — versão demonstrativa

A V12 implementa autenticação front-end para a apresentação do projeto.

## Usuário
- Cadastro
- Login
- Validação
- Senha com SHA-256 via Web Crypto quando disponível
- Sessão via sessionStorage
- Logout
- Recuperação de senha demonstrativa

## Empresa
- Cadastro da assistência
- Login empresarial separado
- CNPJ e e-mail únicos
- Sessão empresarial
- Logout

## Armazenamento
As contas ficam no `localStorage` do navegador e a sessão fica no `sessionStorage`.
Isso é adequado apenas para demonstração acadêmica. Em produção, a autenticação deve ser feita no backend com banco de dados, cookies/sessões seguras e política adequada de senha.

Para testar:
1. Abra `login.html`.
2. Crie uma conta.
3. O site redirecionará para `index.html`.
4. Saia pelo botão de logout.
5. Acesse `empresa-login.html`.
6. Crie uma conta de assistência e teste o login empresarial.
