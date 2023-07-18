<h1>Instalação SQLServer e SSMS</h1>



1. Instalando SQLServer

2. Instalando SSMS (SQL Server Management Studio)

3. Configurando o SSMS (SQL Server Management Studio)

   

<h2>1. Instalando SQLServer</h2>

1. Acesse o <a href="https://www.microsoft.com/pt-br/sql-server/sql-server-downloads" target="_blank">Link</a> e role a tela para baixo até encontrar o conteúdo da imagem abaixo:

<div align="center"><img src="https://i.imgur.com/s1uhmLF.png" title="source: imgur.com" /></div>

2. Clique no botão **Fazer download agora >** do item **Desenvolvedor**:

<div align="center"><img src="https://i.imgur.com/juUzgJk.png" title="source: imgur.com" /></div>

3. Clique no arquivo de instalação, em seguida selecione o tipo de instalação **Básico**:

<div align="center"><img src="https://i.imgur.com/xc0DIP5.png" title="source: imgur.com" /></div>

4. Leia os termos de licença do Microsoft SQL Server, e clique em **Aceitar**:

<div align="center"><img src="https://i.imgur.com/5OyhZI6.png" title="source: imgur.com" /></div>

5. Mantenha o local padrão de instalação e clique em **Instalar**:

<div align="center"><img src="https://i.imgur.com/RT9cmJx.png" title="source: imgur.com" /></div>

7. Clique em **Fechar** e **Reinicie** o sistema para finalizar instalação.

<div align="center"><img src="https://i.imgur.com/lpPj0Mr.png" title="source: imgur.com" /></div>

8. Clique em **Fechar** e **Reinicie** o sistema para finalizar instalação.

<div align="center"><img src="https://i.imgur.com/PDrkl8P.png" title="source: imgur.com" /></div>

9. Clique em **Fechar** e **Reinicie** o sistema para finalizar instalação.

<div align="center"><img src="https://i.imgur.com/Udkb8ym.png" title="source: imgur.com" /></div>

<br />

<h2>2. Instalando o SSMS (SQL Server Management Studio)</h2>



1. Após clicar no botão Instalar o **SSMS** - SQL Server Management Studio, você será redirecionado para o site da Microsoft, para efetuar o download.

2. Caso não seja redirecionado, acesse o <a href="https://learn.microsoft.com/pt-br/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16#download-ssms" target="_blank">Link</a>, e faça download clicando em **Download gratuito do SSMS (SQL Server Management Studio) 19.1**, como mostra a imagem abaixo:

   <div align="center"><img src="https://i.imgur.com/Ef18nfj.png" title="source: imgur.com" /></div>

3. Clique no arquivo de instalação, mantenha o local de instalação definido pelo Windows e clique em **Instalar**:

   <div align="center"><img src="https://i.imgur.com/FjYspMu.png" title="source: imgur.com" /></div>

4.  Aguarde a conclusão da instalação.

<div align="center"><img src="https://i.imgur.com/fntanEP.png" title="source: imgur.com" /></div>

5. Clique em **Fechar** para finalizar a instalação.

<div align="center"><img src="https://i.imgur.com/WCnzo46.png" title="source: imgur.com" /></div>

6. Clique em **Fechar** para finalizar instalação.

<div align="center"><img src="https://i.imgur.com/HMublEO.png" title="source: imgur.com" /></div>

7. Caso a mensagem abaixo seja exibida, clique em **Sim** para finalizar instalação.

<div align="center"><img src="https://i.imgur.com/MSDzh1Q.png" title="source: imgur.com" /></div>

<br />

<h2>3. Configurando o SSMS (SQL Server Management Studio)</h2>



1. Após concluir a instalação do **SQL Server Management Studio**, podemos iniciar a ferramenta através da caixa de pesquisa da sua barra de tarefas, ou no menu iniciar do seu sistema operacional.

<div align="center">
  <img src="https://i.imgur.com/8Vi8dim.png" title="source: imgur.com" />
</div>

2. Uma vez que estamos no **SQL Server Management Studio** precisamos nos conectar com o **SQL Server**, através da tela abaixo:

<div align="center"><img src="https://i.imgur.com/27klobI.png" title="source: imgur.com" /></div>

3. Configure a sua conexão igual a imagem abaixo, alterando o item **Nome do servidor** para **localhost**:

<div align="center"><img src="https://i.imgur.com/ue0tGWa.png" title="source: imgur.com" /></div>

<br />

| <img src="https://i.imgur.com/RfjtOFi.png" title="source: imgur.com" width="100px"/> | <div align="left">**DICA:** *Caso localhost não funcione, mantenha o nome do seu computador no item Nome do servidor e clique em Conectar.* </div> |
| ------------------------------------------------------------ | ------------------------------------------------------------ |

<br />

4. Será aberta a janela principal do **SQL Server Management Studio**:

<div align="center"><img src="https://i.imgur.com/KjCzLoH.png" title="source: imgur.com" /></div>

5. Caso a janela de consultas (**SQLQuery1.sql**) não tenha sido aberta automaticamente, na Barra de Ferramentas do **SQL Server Management Studio**, clique no botão **Nova Consulta**:

<div align="center"><img src="https://i.imgur.com/gjdIRZ1.png" title="source: imgur.com" /></div>

6. Nesta janela (destacada com a cor verde), onde vamos criar as nossas instruções SQL.

<div align="center"><img src="https://i.imgur.com/IjIXRLb.png" title="source: imgur.com" /></div>

7. Digite o código abaixo:

```sql
select @@version
```

8. Clique no botão **Executar**, localizado na Barra de Ferramentas do **SQL Server Management Studio**, como mostra a imagem abaixo:

<div align="center"><img src="https://i.imgur.com/3EXuyTV.png" title="source: imgur.com" /></div>

9. O resultado você confere na imagem abaixo:

<div align="center"><img src="https://i.imgur.com/UMXrSn0.png" title="source: imgur.com" /></div>

Se o comando acima exibir a versão do SQL Server, a instalação e configuração foi concluída com êxito!

<br />
<br />

<div align="left"><a href="README.md"><img src="https://i.imgur.com/XMgF3gl.png" title="source: imgur.com" width="3%"/>Voltar</a></div>