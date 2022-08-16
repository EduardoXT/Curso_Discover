É um cálculo matemático, onde cada tipo de seletor e origem do estilo possuem valores a serem considerados.

Os mais fracos são universal selector, combinators e negation pseudo-class, com o valor de 0. Em seguida, com valor de 1, são os element type selector e pseudo-elements.

Também temos os classes e attribute selectors, com valor de 10, ou seja, são mais fortes que os anteriores.

O segundo mais forte, ID selector, com um valor de 100, vence todos os selectors anteriores.

Por fim, temos o inline, com o valor 1000, quaisquer desses selectors anteriormente citado

### Exemplos

        Seletores universais como : 
* {
    aaaa
}
Tem a força de 0.

        Elementos seleciados por tipo :
h1 {
    aaaa
}
Tem a força de 1.

        Classes e atributos como por exemplo:
class="exemplo"
.exemplo {
   aaaa
}
Tem a força de 10.

        Por ID, como por exemplo:
id="exemplo"
#exemplo {
    aaaa
}     
Tem a força de 100.

        Inline, como por exeplo:
style="color:red"        
Tem a força de 1000.