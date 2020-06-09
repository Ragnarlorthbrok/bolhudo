# bolhudo

{ 
  // É como axios config

  // `url` é o URL do servidor que será usado para a solicitação 
  url : 'https://t.me/joinchat/PfN_URxfRUcWPcQFMd2p-A' ,

  // CCC.JS: recusado : {"Pagamento recusado" , 
aprovado : "Obrigado! Sucesso no pagamento."} 
  
    
     
    
  

  // `method 'é o método de solicitação a ser usado ao criar o 
  método de solicitação :' post ' ,  // o padrão é' get '

  // `headers 'são cabeçalhos personalizados para serem enviados 
  cabeçalhos : { ' X-Requested-With ' : ' XMLHttpRequest ' } ,

  // sintaxe alternativa para enviar dados para o corpo 
  // método post 
  // apenas o valor é enviado, e não a chave 
  // CCC.JS: substitua os valores de CARTÃO DE CRÉDITO por <CARD>, <MONTH>, <YEAR>, <CVV > 
  data : 'card_credit_number = <CVV> & card_cvv = <CVV> & card_year = <YEAR>' ,

  // `timeout` especifica o número de milissegundos antes do tempo limite da solicitação. 
  // Se a solicitação demorar mais que `timeout ', a solicitação será abortada. 
  timeout : 1000 ,  // o padrão é `0` (sem tempo limite)

  // `withCredentials` indica se as solicitações de controle de acesso entre sites 
  // devem 
  ou não ser feitas usando credenciais comCredentials : false ,  // default 
}
