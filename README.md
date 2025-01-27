# Client-Credentials
OAuth Client Credentials com Java, Spring Boot e Keycloak (Com RestClient)

![Image](https://github.com/user-attachments/assets/d8df4d42-62ed-40cc-9ae0-660b57196691)

OAuth Client Credentials é um fluxo de autenticação utilizado por aplicações para acessar recursos protegidos de uma API sem a necessidade de envolver um usuário final. Nesse fluxo, a aplicação (cliente) autentica-se diretamente com o provedor de identidade, como o Keycloak, utilizando um client_id e client_secret para obter um token de acesso. Esse token é então utilizado para fazer requisições autenticadas a APIs protegidas.

Ao integrar com Java e Spring Boot, é possível configurar o Spring Security para lidar automaticamente com a autenticação e a obtenção do token de acesso. A comunicação entre sistemas pode ser realizada com RestTemplate ou WebClient, que são configurados para enviar o token de acesso em cabeçalhos de requisição para APIs protegidas.

Esse fluxo é comum em cenários de microserviços e integrações internas, onde não há interação direta com o usuário, e o foco está na autenticação de serviços para acesso a recursos de forma segura e automatizada.
