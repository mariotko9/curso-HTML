# 1 - INTRODUÇÃO

## Blocos (Tags)

Exemplo

<div><p>Paragrafo</p></div></br>
Ocupa toda a tela\linha</br>
DISPLAY = Block

<div><span>Linha de texto</span></div></br>
Ocupa o tamanho do seu conteúdo</br>
DISPLAY = Line

## Estrutura Básica

Sepre manter a indentação (espaços) correta na formatação
<div>
'<!DOCTYPE html>'
'<html>'
       '<head>'
       
       '</head>'
       '<body>'
    
       '</body>'
'</html>'
</div>

# Charset

Criação de caracteres para exibição na página (que o navegador entende)
A a Z, 1 a 9, Á Ê Í Ó Ú

'<meta charset=""/>'
Tag fecha de forma diferente das demais usando o /.

Ao definir o tipo ASCII a paragrafo (Á Ê Í Ó Ú) ficou assim: Ã ÃŠ Ã Ã“ Ãš

Para resolver utilizamos o tipo UTF-8 para enchergar todos os tipos de caracteres '<meta charset="UTF-8"/>'.

# Comentário

'<!-- Isso é um comentário-->'</br>
Fica visível somente no código

# 2 - TEXTO

## Headlings e Parágrafos

Podemos utilizar **!** para iniciar a criação de uma estrutura básica do html.

'<!DOCTYPE html>'
'<html lang="en">'
'<head>'
    '<meta charset="UTF-8">'
    '<meta name="viewport" content="width=device-width, initial-scale=1.0">'
    '<title>Document</title>'
'</head>'
'<body>'
    
'</body>'
'</html>'

As tags do tipo títulos '<h>' também ocupam toda a linha.</br>

Utilizar a tag '<br/>' para quebra de linha.

## Formatação de Texto

'<b></b> Para negrito ou <strong></strong>'
'<i></i> Para italico ou <em></em>'
'<ins></ins> Para sublinhar o texto'
'<del></del> Este para texto cortado'
'<mark></mark> Para marcar o texto'
'<small></small> Para diminuir o texto'
'Para Subscrito usar H<sub>2</sub>0'
'Para Sobrescrito usar X<sup>2</sup>'

## Citação e Endereço

'<blockquote cite:"url"></blockquote>' 
Para fazer a citação de um site
'<address></address>' 
Para criar um endereço
