# Guia de Contribuição
## Como Contribuir Com o Repositório 

**Para contribuir com o repositório, seja adicionando conteúdo, corrigindo erros teóricos e em códigos, abra uma pull request assim como ensinado abaixo. Obrigado!**

### 1. Fork o Repositório
Primeiro, faça um fork do repositório. Isso cria uma cópia do projeto em sua conta do GitHub.

1. Acesse a página principal do repositório.
2. Clique no botão "Fork" no canto superior direito.
3. Isso criará uma cópia deste repositório no seu GitHub pessoal.

### 2. Clone o Repositório Forkado
Clone o repositório que você acabou de forkear para seu ambiente local.

```bash
git clone https://github.com/seu-usuario/nome-do-repo.git
```

Navegue até a pasta do repositório clonado:
```bash
cd nome-do-repo
```

### 3. Criar uma Nova Branch
Antes de fazer alterações, crie uma nova branch para isolar seu trabalho.

```bash
git checkout -b minha-nova-branch
```

Nomeie a branch de maneira descritiva para indicar o que você está desenvolvendo ou corrigindo. Por exemplo: ajuste-na-rotina-x ou nova-funcionalidade-y.

### 4. Faça Suas Alterações
Faça as alterações necessárias em seu ambiente local. Certifique-se de seguir as melhores práticas de código, e mantenha os commits organizados e claros.

### 5. Commit e Push
Após finalizar suas alterações, faça o commit das mudanças:

```bash
git add .
git commit -m "Descrição clara das alterações"
```

Envie as alterações para o seu repositório forkado no GitHub:

```bash
git push origin minha-nova-branch
```

### 6. Abra um Pull Request (PR)
Após fazer o push da sua branch, você está pronto para criar um Pull Request.

- Acesse o repositório original no GitHub.
- Clique no botão "Compare & pull request" que aparecerá logo após seu push.
- Preencha o formulário com um título descritivo e um comentário detalhando as mudanças feitas.
- Envie o Pull Request para revisão.

### 7. Revisão e Feedback
Os mantenedores do projeto revisarão seu Pull Request. Eles podem sugerir mudanças ou pedir explicações adicionais. Fique atento a possíveis comentários e faça os ajustes necessários.

### 8. Dicas para Contribuições
Commits pequenos e descritivos: Faça commits frequentes e com mensagens claras sobre as mudanças.
Código limpo e bem documentado: Certifique-se de que seu código seja legível e, sempre que possível, com comentários explicativos.
Atualize sua branch com a main: Antes de abrir um Pull Request, sempre sincronize sua branch com as alterações mais recentes da branch main do projeto.

```bash
git checkout main
git pull origin main
git checkout minha-nova-branch
git merge main
```
