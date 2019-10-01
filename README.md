# Next.js (SSR)

- SSR é mais performático, e além disso permite que o site seja indexado pelo Google, e práticas de SEO sejam aplicadas no site.
- A aplicação ClientSide até é indexada, porém os dados que são exibidos na tela são provenientes de uma API, e fazemos uma request para ela. Esse tempo até a API responder os scrappers do Google não esperam. O Google acessa nossas páginas com o JS desabilitado, logo, o conteúdo precisa estar lá já.
- Com o SSR nós iremos renderizar o conteúdo no nosso server antes que o client seja renderizado, então a página já virá com o contéudo.
- Performance do google chrome com processamento limitado, e memória limitada, perante ao gerenciamento de memória de um backend em um servidor potente.
- Uma vez que a página já foi montada pelo server, ela não precisa mais fazer o processamento pelo server side, logo, ela aloca os recursos pelo clientside, aproveitando tudo o que já foi montado pelo serverside.
- Se o JS estiver desabilitado, ele joga pro server sempre, se não, vai pro client. Ele sabe quando e onde alocar os recursos.
