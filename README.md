## 

<p>
  
  
</p>


## 📝 Notes

-  Objetivo: Gerar um cenário de teste e um plano de teste. Utilizei o postman para validar a massa existente.

Descritivos	"**Account**
    - Deve ser possível obter os dados da conta a partir do ***id da conta***
 **PIX**
     **Codes**
         O ***QR Code*** deve ser enviado convertido em base64
         A Aplicação deve validar se é um ***QR Code*** válido
         A aplicação deve validar se o ***QR Code*** existe
         Em caso de erro, a aplicação deve devolver o motivo no response
         A aplicação deve devolver os dados para realizar um pagamento via PIX
     **Payment**
         Receber os dados de pagamento de acordo com os dados obtidos em ***Account*** e ***Pix/Codes***"	
Entregas	"Crie todos os cenários de testes.
* Faça um relatório de todos os problemas que forem encontrados.
* Defina um plano de testes para entrega da API
* Utilize todas as massas de testes
* Pode utilizar o postman ou a própria documentação para realizar os testes
* Suba os arquivos para um drive, copie e cole o link no campo de resposta do e-mail enviado. (Obs. deixe o link publico)"	
![image](https://user-images.githubusercontent.com/91573895/195938978-7a248360-d407-4f3d-96bd-7dedc35adc66.png)

 Modelo de teste Pix	Teste : 01/1022	Data : 13/10/2022	
		hora :	
Avaliador	Maristela Borges		
Objetivo	O objetivo da aplicação é possibilitar a realização o pagamento via PIX a partir dos dados coletados do QR Code.		
Equipe de Desenvolvimento 	 Builders		
Documentação API	 https://vagas-builders.readme.io/reference/paymentpix		
Versão			
			
Descritivos			
			
			
Cenário	Validação da Conta para recebimento - pix estático		
Ação esperada			realizado
pix com chave valida	conta encontrada.		n
pix com chave inválida	chave pix inválida		n
pix com chave inexistente			n
pix com duas contas cadastradas	Mensagem de validação de chave		n
			
			
Cenário	Validação da Conta para recebimento - pix dinamico		
			realizado
pix com chave valida	conta encontrada.		n
pix com chave inválida	chave pix inválida		n
pix com chave inexistente			n
![image](https://user-images.githubusercontent.com/91573895/195939126-cc75040e-6df3-4a1d-a8bb-91f30bc9764a.png)
