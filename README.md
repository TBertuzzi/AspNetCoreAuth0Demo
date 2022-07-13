# AspNetCoreAuth0Demo

 Exemplo de implementação de autenticação Auth0 com .Net Core 6
 
 Para iniciar é necessario criar uma conta no Auth0 [clicando aqui](https://auth0.com/)
 
 Em Seguida configure seu projeto .net :
 
 <img src="https://github.com/TBertuzzi/AspNetCoreAuth0Demo/blob/main/Resources/CriarAplicacao.jpg?raw=true" width="500" height="400" alt="Blog" />
 
 Com a aplicação criada obtenha o Domain e ClientId :
 
  <img src="https://github.com/TBertuzzi/AspNetCoreAuth0Demo/blob/main/Resources/CriarAplicacao2.jpg?raw=true" width="500" height="400" alt="Blog" />
 
 Em seguida configure a url de Callback e Logout, para essa aplicação de teste utilize a porta 3000 :
 
 <img src="https://github.com/TBertuzzi/AspNetCoreAuth0Demo/blob/main/Resources/CriarAplicacao3.jpg?raw=true" width="500" height="400" alt="Blog" />
 
 Substitua o DOMAIN e o CLIENT_ID pelo configurado acima :
 
 ```csharp
   "Auth0": {
    "Domain": "{DOMAIN}",
    "ClientId": "{CLIENT_ID}"
  }
 ```

Execute a aplicação.

Esta aplicação foi feita com asp.net core 6 baseada na documentação original do auth0. A Documentação ogirinal pode ser lida [clicando aqui](https://auth0.com/docs/quickstart/webapp/aspnet-core)
