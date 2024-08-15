@@ -6,8 +6,102 @@
    < meta  charset =" UTF-8 " >
    < meta  name =" viewport " content =" width=largura-do-dispositivo, escala-inicial=1 " >
    < link  rel =" folha de estilo " href =" styles.css " >
    < link  rel =" pré-conexão " href =" https://fonts.googleapis.com " >
    < link  rel =" preconnect " href =" https://fonts.gstatic.com " crossorigin >
    < link  href =" https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap " rel =" folha de estilo " >
</ cabeça >

< corpo > </ corpo >
< corpo >
    < section  class =" contêiner principal " >
        < div  class =" container__caixa " >
            < h1  class =" container__titulo " > Com o Combo+, você pode aproveitar o Alura+ e o Alura Língua por um preço
                único. </ h1 >
            < img  src =" img/Combo.png " alt =" O combo+ é a especificamente do alura+ e o alura língua " class =" container__imagem " >
            < a  href =" www.alura.com.br " class =" container__botao " > Assinatura por 12x de R$ 120,00* </ a >
            < a  href =" www.alura.com.br " class =" container__botao botao_secundario " > Assinar somente o Alura+ </ a >
            < p  class =" container__aviso " > *O preço pode variar caso a assinatura seja feita em outros planos. </ p >
        </div>​​
    </ seção >

    < section  class =" container secundário " >
        < img  src =" img/Plataformas.png " alt =" Um monitor e um celular com aura mais aberta " class =" secundario__imagem " >
        < div  class =" container__descricao " >
            < h2  class =" descricao__titulo " > Assista do seu jeito </ h2 >
            < p  class =" descricao__texto " > Aproveite a tela grande da TV ou assista no tablet, laptop, celular e outros
                aparelhos. Nossa seleção de cursos não para crescer. </ p >
        </div>​​
    </ seção >

    < section  class =" container secundário " >
        < div  class =" container__descricao " >
            < p  class =" descrição__texto " >
                Só o Combo+ oferece Alura+ e Alura Língua juntos para você ter acesso a cursos de diversas áreas da
                tecnologia e aprender inglês ou espanhol, onde e como quiser.
            </ p >
            < a  href =" www.alura.com.br " class =" container__botao secundario__botao " container > Assine o Combo+ </ a >
        </div>​​
        < img  src =" img/Telas.png " alt =" Tela do alura+ e alura língua " class =" secundario__imagem " >
    </ seção >

    < section  class =" container secundário " >
        < img  src =" img/Notebook.png " alt =" Notebook com a página do curso HTML5 e CSS3 da Alura aberta "
            class =" secundario__imagem " >
        < div  class =" container__descricao " >
            < h2  class =" descricao__titulo " > Baixe seus cursos </ h2 >
            < p  class =" descricao__texto " > Baixe e assista quando e onde quiser. Assim, seus favoritos estão sempre com
                você, até mesmo sem internet. </ p >
        </div>​​
    </ seção >

    < seção  class =" dispositivos " >
        < h2  class =" dispositivos__titulo " > Disponível nos seus dispositivos favoritos </ h2 >
        < ul  class =" dispositivos__lista " >
            < li >
                < img  src =" img/tv.png " alt =" Ícone de televisão " >
                < h3  class =" lista__item " > TV </ h3 >
            </ li >
            < li >
                < img  src =" img/computador.png " alt =" Ícone de computador " >
                < h3  class =" lista__item " > Computador </ h3 >
            </ li >
            < li >
                < img  src =" img/celular.png " alt =" Ícone de celular " >
                < h3  class =" lista__item " > Celular </ h3 >
            </ li >
        </ul>​​
    </ seção >

    < rodapé  classe =" rodape " >
        < img  src =" img/Logo.png " alt =" Alura+ " class =" rodape__logo " >
        < ul  class =" rodape__lista " >
            < li  class =" lista__link " >
                < a  href =" # " > Idioma </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Dispositivos compatíveis </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Contrato de assinatura </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Política de privacidade </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Proteção de dados no Brasil </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Anúncios personalizados </ a >
            </ li >
            < li  class =" lista__link " >
                < a  href =" # " > Ajuda </ a >
            </ li >
        </ul>​​
        < p  class =" rodape__texto " > ® 2021 Alura, Alura+ e Alura Língua. Todos os direitos reservados. Serviço de
            assinatura paga. Conteúdo sujeito a disponibilidade. </ p >
        < p  class =" rodape__texto " > Alura+ é um serviço pago, baseado em assinatura e sujeito a termos e condições. Ó
            serviço Alura+ é comercializado pela Aovs Sistemas de Informática SA, Rua Vergueiro, 3185 - Liberdade, São
            Paulo - SP, 04101-300, Brasil e CNPJ 05.555.382/0001-33 </ p >
    </ rodapé >
</ corpo >

</ html >
  155 alterações: 155 adições e 0 exclusões155 
estilos.css
Número da linha do arquivo original	Número da linha de diferença	Mudança de linha diferencial
@@ -0,0 +1,155 @@
: raiz {
    --branco- principal :  #FFFFFF ;
    --cinza-secundario :  # C0C0C0 ;
    --botao-azul :  # 167BF7 ;
    --cor-de-fundo :  # 00030C ;
    --fonte-principal :  'Inter' ;
    --botao-azul-efeito :  # 3c92fa ;
}

corpo {
    cor de fundo :  var ( -cor-de-fundo );
    cor :  var ( --branco-principal );
    família de fontes :  var ( -fonte-principal );
    tamanho da fonte :  16 px ;
    espessura da fonte :  400 ;
}

* {
    margem :  0 ;
    preenchimento :  0 ;
}

. diretor {
    imagem de fundo :  url ( "img/Background.png" );
    background-repeat : sem repetição;
    tamanho-de-fundo : conter;
    alinhar-itens : centro;
    alinhamento de texto : centralizar;
}

. recipiente {
    altura :  100 vh ;
    exibição : grade;
    colunas-de-modelo-de-grade :  50 %  50 % ;
}

. container__botao {
    cor de fundo :  var ( -botao-azul );
    raio da borda :  5 px ;
    preenchimento :  1 em ;
    cor :  var ( --branco-principal );
    exibir : bloco;
    decoração de texto : nenhuma;
    margem-inferior :  1 em ;
}

. botao_secundario {
    cor de fundo : transparente;
    borda :  var sólida de 2 px ( --branco-principal )
}

. container__aviso {
    tamanho da fonte :  12 px ;
    cor :  var ( -cinza-secundario );
}

. container__titulo {
    tamanho da fonte :  28 px ;
    espessura da fonte :  700 ;
}

. container__imagem {
    margem :  1 em  0  2 em  0 ;
}

. container__caixa {
    margem :  0  6 em ;
}

. secundario__imagem {
    largura :  80 % ;
}

. secundário {
    alinhar-itens : centro;
    margem :  0  10 em ;
}

. descrição__titulo {
    espessura da fonte :  700 ;
    tamanho da fonte :  48 px ;
    cor :  var ( --branco-principal );
    margem inferior :  0,1 em ;
}

. descrição__texto {
    cor :  var ( -cinza-secundario );
}

. secundario__botao {
    exibição : bloco embutido;
    margem-superior :  1 em ;
}

. container__descricao {
    preenchimento :  2 em ;
}

. dispositivo__lista {
    exibição : flex;
    justificar-conteúdo : centro;
    tipo-de-estilo-de-lista : nenhum;
    margem :  5 em  0 ;
}

. dispositivo {
    alinhamento de texto : centralizar;
}

. dispositivo__titulo {
    tamanho da fonte :  48 px ;
    cor :  var ( --branco-principal );
}

. lista__item {
    tamanho da fonte :  32 px ;
    cor :  var ( --branco-principal );
}

. rodape {
    alinhamento de texto : centralizar;
    margem :  5 em  3 em ;
}

. rodape__lista {
    exibição : flex;
    justificar-conteúdo : centro;
    tipo-de-estilo-de-lista : nenhum;
    margem-superior :  1 em ;
}

. lista__link  para {
    decoração de texto : nenhuma;
    cor :  var ( --branco-principal );
    margem-esquerda :  1 em ;
}

. rodape__texto {
    margem :  1 em  0 ;
    cor :  var ( -cinza-secundario );
    tamanho da fonte :  14 px ;
}

. lista__link  a : hover {
    cor :  var ( --botao-azul );
}

. lista__link  a : ativo {
    cor : roxo;
}

. container__botao : pairar {
    cor de fundo :  var ( --botao-azul-efeito );
    cor :  var ( --cor-de-fundo );
}
