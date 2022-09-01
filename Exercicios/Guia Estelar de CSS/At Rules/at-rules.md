São regras relacionadas ao comportamento do CSS, começa com um sinal de @ seguido do identificador e do valor.

São as seguintes:

@import serve para incluir um CSS externo.
@media são regras condicionais para vários dispositivos.
@font-face é para colocar fontes externas.
@keyframes serve para as animations do CSS.

´´´css
@import url("http://fonts.googleapis.com/css");

@media (min-width: 500px) {
    /* rules here */
}

@font-face {
    /* rules here */
}

@keyframes nameofanimation {
    /* rules here */
}