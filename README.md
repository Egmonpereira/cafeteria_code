# cafeteria_code
Projeto criado em cumprimento às exigências da Disciplina Projeto Integrador Transdisciplinar em Ciência da Computação II, na Universidade Cruzeiro do Sul, em parceria com outros alunos.

Segue em anexo a implementação da cafeteria code

Recomendo instalar o mysql workbech e o xampp para execução do projeto. 
Você terá que restaurar o banco de dados (executar o arquivo bd_cafeteria_gourmet.sql. Recomendo instalar o mysql workbench pela praticidade. Mas no phpmyadmin no wamp também funciona. Esse arquivo sql também já cria usuário e senha configurados no arquivo config/conexao.php.
Há também a parte da configuração do e-mail que irá enviar o código de confirmação para o usuário para troca de senha. Essa configuração é feita no arquivo config/verifica-email.php. Para que o e-mail envie a mensagem do código de confirmação, é necessário entrar no gmail, por exemplo, e configurar a senha para aplicativos. Só funciona com essa senha. Não funciona com a senha convencional.  Para configurar a senha de aplicativo, seguir o tutorial https://www.youtube.com/watch?v=vaZ_XV5yvf4
Após a criação da senha, inseri-la (sem espaços) no arquivo config/verifica-email.php 

https://manjarobrasil.wordpress.com/2015/08/05/servidor-web-local-com-xampp-no-manjaro/comment-page-1/
