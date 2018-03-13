Configurações básicas:
----------------------


	Alinhamento da tabela: **align="center"**

	Boas práticas em e-mail marketing:

	* adicionarmos uma mensagem em cima do e-mail marketing que terá um link para abrir o documento em outra aba do navegador. Fazemos isso pois o usuário, por algum motivo, pode não visualizar as imagens.
	* uma mensagem dando a opção para o usuáro não receber mais e-mails como esse. Também estará na parte de cima, pois assim não será necessário rolar até embaixo para clicar no link (isso previne que os usuários denunciem o e-mail como spam).
	  

			<td colspan="5" align="center"><font size="1" face="Arial, sans-serif" color="######">Exibir esta mensagem no navegador</font></td>

	  		<td colspan="7" align="center"><font size="1" face="Arial, sans-serif" color="######">Não quero receber estes e-mails</font></td>



	* definirmos as imagens com a propriedade **display block**, sem bordas, o que as previne de colapsarem	  

	* adicionar nas **imagens** display block: **<img style="display: block;"**. 

	* bordas das imagens com valor zero, **border="0"**

		
			<img border="0" style="display: block;" ...>