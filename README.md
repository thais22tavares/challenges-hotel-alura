# challenges-hotel-alura
challenges do hotel Alura feito com liguagem Java
Primeiros Passos:
🔹 Marque esse projeto com uma ⭐
🔹 Siga as orientações do que temos neste repositório 📚
🔹 Visite a página do desafio clicando aqui! Link do Desafio 📃

🖥️ Tecnologias Utilizadas:
Java
Eclipse
MySql
Biblioteca JCalendar
Plugin WindowBuilder
⚠️ Importante! ⚠️
☕ Use o Java na versão 8 ou superior para ter compatibilidade.

📝 Recomendamos utilizar o editor Eclipse para compatibilidade da interface gráfica.

🎨 A interface contém dois importantes métodos:

setResizable(false): determina o tamanho da janela, e através do parâmetro false, a tela não poderá ser maximizada;
setLocationRelativeTo(null): determina a localização da janela, e através do parâmetro null ele a mantém centralizada na tela.
Para este desafio, concentre-se na parte lógica e de conexão com o Banco de Dados, após concluir o desafio, sinta-se a vontade para incluir novas funcionalidades e modificar a interface gráfica.
🔍 Analisando nosso repositório!
Este é o repositório base do nosso projeto, nele você encontrará:
🔹 src/views: pasta com toda a interface gráfica das telas necessárias para desenvolver o programa;
🔹 src/imagens: pasta com imagens que você pode utilizar em seu projeto. Sinta-se a vontade para utilizar outras, caso deseje.

⬇️ Baixar
Como fazer o download:
🔹 Garfo
1 - Faça o fork do projeto. No lado superior direito, ao clicar no ícone ele criará um repositório do projeto em sua conta pessoal do GitHub.




2 - Após ter o repositório "forkado" para sua conta, verifica se a url da página é a do repositório da sua conta.




3 - Clique na opção Code. Ele apresentará três formas para instalar o repositório em sua máquina, e destacamos duas:




🔹 Clonar ou baixar o ZIP
1 - Para clonar, basta copiar a url destacada na imagem e localizada logo abaixo do HTTPS, criar uma pasta em seu computador, abrir o cmd ou o git bash dentro dessa pasta e em seguida insira o comando git clone e com o botão direito do mouse dentro do terminal clicar na opção Paste para colar a url e dar Enter.




2 - A segunda opção é baixar o código em um pacote "zipado" e extrair a pasta para o seu computador.


📝 Eclipse
Como importar o meu projeto no Eclipse?
1 - Uma vez dentro do Editor do lado esquerdo, clique em File que está no menu na parte superior, escolha a opção Open Projects from File System.



Em seguida, clique em Directory e localize o diretório do projeto "clonado" ou "extraído" em seu computador. Clique em Finish para concluir a importação.



2 - A segunda forma de importar está em File na opção Import. Ou através do Project Explorer, clique no campo vazio com o botão direito do mouse e escolha a opção Import.





Se optar pelo Import, abrirá a janela correspondente, clique na opção Existing Projects Into Workspace e no botão Next.



Em seguida, clique no botão Browse e busque o projeto no diretório local.



📅 JCalendar
Após importar para o seu editor, é necessário instalar a biblioteca JCalendar, caso contrário o projeto apresentará um erro e não será possível abrir a janela de Reservas.

Para instalar, você precisa baixar o pacote através desse link: 🔹 Link para o JCalendar



A próxima etapa será extrair os arquivos da pasta lib para uma pasta local e importar os arquivos para o Eclipse.



Arquivos da pasta lib:



Clique com o botão direito do mouse sobre o projeto localizado no Package Explorer e escolha a opção Build Path e Configure Build Path.



O projeto estará com um aviso de erro, indicando que não existe a rota da biblioteca em seu computador. Clique em Libraries, em seguida em Classpath selecione o arquivo do JCalendar, escolha a opção Remove e Apply and Close.



Para importar o Jcalendar do seu computador, após ter "extraído" os arquivos do download, clique em Classpath e depois em Add External JARS adicione um a um e clique em Apply and Close.



Assim, o projeto deve conter os seguintes arquivos após as importações:



🚧 Projeto
Ao clonar ou baixar o projeto base e ter o JCalendar instalado, você terá esta apresentação ao executar o projeto no Eclipse:


⚠️ Baixei o projeto, mas os caracteres especiais não funcionam:
Caso o seu projeto apresente erros como os da imagem, siga os passos abaixo:



Vá até Window e clique em Preferences.



Em seguida, clique em General e Workspace. Se o seu Text File Enconding não estiver com o Default (UTF-8), clique em Other, e escolha a opção UTF-8 e finalize clicando em Apply and Close.



📊 Banco de Dados
Como importar o MySqlConnector no projeto?
É o mesmo caminho descrito para a importação do JCalendar, clicar com o botão direito do mouse em cima do projeto, Build Path, Configure Build Path, Libraries, Add External JARs. Para encontar o caminho desse aquivo .jar, vá até o disco rígido do seu computador e entre na pasta Arquivos de Programas (x86).

Arquivos de Programas (x86):


MySQL


Conector J 8.0:


Meu SQL Connector Java:


Modelagem das tabelas:
Para este desafio propomos duas tabelas: Reservas e Hóspedes. A tabela de hóspedes deve conter a chave estrangeiro (foreign key) idReserva.

 

🗔 Plugin WindowBuilder
No menu do Eclipse, vá até a aba Help e selecione a opção Eclipse Marketplace.



Na barra de pesquisa, insira window builder e clique em Go. Após a busca, selecione a primeira opção e clique em Install.



Na próxima janela, selecione o botão Confirm.



Clique na opção para aceitar os Termos de Uso, e para concluir clique em Finish.



📬 Entrega
Como incluir meu projeto com a "#" do desafio?
Tenha o Fork do projeto em seu repositório no Github.
Utilize o tópico #challengeonealurahotelbr2. Vá na aba esquerda do seu projeto na seção About e clique na engrenagem de configuração selecione o campo topics e insira a etiqueta challengeonealurahotelbr3.
gif-vitrine

Como faço a entrega final do meu Projeto?
Preencha o formulário a seguir com seus dados pessoais, juntamente com o link do seu repositório.🔹 Link para o formulário


Vá para seu e-mail e resgate sua badge conquistada por encerrar mais um desafio no Projeto ONE! 🏆

Não se esqueça de colocar um link ou vídeo de seu projeto no Linkedin! Marque com a #Oracle #AluraLatam 🏁
