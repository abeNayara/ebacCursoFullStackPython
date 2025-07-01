# Curso de Desenvolvimento Full Stack Python

Este repositório acompanha o **meu progresso e aprendizado** no curso de Desenvolvimento Full Stack Python, oferecido pela EBAC — uma instituição voltada à formação profissional no setor tecnológico.

O objetivo aqui não é reproduzir o conteúdo do curso, mas compartilhar minha jornada e evolução com os conhecimentos adquiridos.
Ao longo do tempo, adicionarei projetos, anotações e insights que reflitam o que venho estudando.
🔗 Quer conhecer os cursos da EBAC?
Acesse através deste link: [Clique aqui!](https://ebaconline.com.br/sale/referral?grsf=sm9mok)

***

### Olá, tudo bem?
Aqui vamos ver como um documento HTML é formado.
<br>
**Algumas coisas que você deve saber:**
* HTML é uma linguagem de marcação.
* Seu principal objetivo é a estruturação de páginas web, sendo essencial para dizer ao navegador o que cada parte do conteúdo representa: título, listas, parágrafos, links, imagens, entre outras funcionalidades.
* A estrutura do HTML é formada por tags que normalmente possuem abertura "<" e fechamento "/>".

   _Obs: algumas tags, *como "img" e "br", são auto-fecháveis e não são obrigadas a serem fechadas._

## É assim que o HTML será apersentado:

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

`<!DOCTYPE html>` 

Aqui se começa toda a estrutura do HTML, indicando que começaremos um documento no formato de HTML. E que ele conversará com o navegador de forma sincrona.

`<html lang="pt-br">`  

Setamos a abertura da tag do HTML e também a linguagem com o atributo *(todo elemento que receberá algum valor)* "lang", futuramente servindo assim para mecanismos de buscas(ex: google) e também para regir o texto aplicado na página.

`<head>`

Se abre esta tag para ser um "cabeçalho" do HTML contendo alguns elementos

`<meta charset="UTF-8">` 

tag "meta" é usada para definir metadados em um documento HTML, ou seja, informações sobre os dados da página. E seu atributo "charset" é utilizado para especificar a codificação de caracteres usada no documento, assim suportando diferentes caracteres de diferentes idiomas.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">` 

Nesta tag "meta" se possui dois atributos, "name" que realiza o controle da página para diferentes dispositivos, definindo  no atributo posterior "content" a escala da janela para o tamanho de visualização.

`<title>Document</title>`

Na tag "title" definimos o nome da página. O que ficar entre as tags de abertura e fechamento é o que será exibido no seu navegador na hora de abrir um documento web.

`</head>`

Aqui temos o fechamento da tag "head"

**Brevemente, está é a estrutura de documentação, onde inserimos estas tags e atributos para podermos iniciar o conteudo que será exibido na página**

`<body>`

Na tag "body", ou seja, o corpo da página, é na onde todo o conteudo ficará. Aqui tudo o que é fundamental para o "esqueleto" do documentos estará
    
`</body>`

Fechamento da tag "body"

`</html>`

E Fechamento do documento HTML
