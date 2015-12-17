% Formatafacil: produza artigos com as normas da ABNT
% Autor
% 201X

# Introdução

Historicamente os estudantes costumam ter dificuldades para elaborar
e formatar artigos utilizando as normas da ABNT (ou dos eventos que
desejam submeter seus artigos).


A ferramenta [formatafacil](https://github.com/edusantana/formatafacil) propõe-se
auxiliar os estudantes nesta tarefa de produção e formatação de trabalhos.

Este documento é um exemplo de utilização desta ferramenta para produção
de um artigo. A seguir apresentamos como é o seu funcionamento.

# Desenvolvimento

Os principais recursos utilizados na elaboração de artigos serão apresentados nesta seção.

## Criando seções

A criação de seções ou subseções não requer esforço para manter a formatação consistente. Para criar uma seção
basta adicionar um `#` no início da linha, dar um espaço e colocar o título da seção. Por exemplo, para criar um artigo com três seções com os títulos *Introdução, Desenvolvimento e Conclusão* basta digitar:

    # Introdução
    # Desenvolvimento
    # Conclusão

A numeração das seções são automáticas, a primeira seção será apresentada como **1 Introdução**, a segunda como **2 Desenvolvimento** e assim por diante.

### Criando subseções

Para criar uma subseção basta adicionar `##` (ou `###` para uma sub-sub-seção):

    ## Frutas
    ### Banana
    ### Maçã

A numeração das subseções também são automáticas, se acordo com a numeração da seção em que se encontra, de tal forma que a numeração das subseções poderiam ser: *2.1 Frutas* (subseção), *2.1.1 Banana* e *2.1.2 Maçã* (subsubseções).

## Texto dos parágrafos

Escrever um parágrafo é muito simples, basta digitar o texto (o espaço inicial do parágrafo é formatado automaticamente, sem necessitar de inserir espaços em branco ou *tab*).

Diferente do Word, um parágrafo só termina quando você
insere uma linha em branco. Até lá, todo o texto é
considerado um único parágrafo.

    Diferente do Word, um parágrafo só termina quando você
    insere uma linha em branco. Até lá, todo o texto é
    considerado um único parágrafo.

    Esta frase iniciaria um novo parágrafo.

## Itálico e negrito

Nos textos elaborados utilizando as normas da ABNT as palavras estrangeiras como *software* e *et al* devem ser grifadas em itálico.

Segundo a norma da ABNT, na seção de referências os títulos dos trabalhos podem ser grifados em *itálico* ou **negrito**.

Para realizar estas formatações basta adicionar asteriscos entre as palavras que você deseja formatar. Um asterisco faz itálico: `*`*itálico*`*`, dois fazem negrito: `**`**negrito**`**`.


## Citação

> A arrogância do “sabe com quem está falando?”, a empáfia do *sabichão* incontido
no gosto de fazer conhecido e reconhecido o seu saber, nada disso tem que ver com a
*mansidão*, não com a apatia, do humilde. É que a humildade não floresce na
insegurança das pessoas, mas na segurança insegura dos cautos. (...)
A postura do autoritário, pelo contrário, é sectária. A sua
é a única verdade que necessariamente deve ser imposta aos demais. É na sua *verdade*
que reside a *salvação* dos demais. O seu saber é “iluminador” da “obscuridade” ou da
ignorância dos outros, que por isso mesmo devem estar submetidos ao saber e à
arrogância do autoritário ou da autoritária. (FREIRE, 1997)

Para formatar um parágrafo como citação basta adicionar `>` no início da linha:

    > A arrogância do “sabe com quem está falando?”, a empáfia
    do *sabichão* incontido no gosto de fazer conhecido e
    reconhecido o seu saber, nada disso tem que ver com a
    *mansidão*, não com a apatia, do humilde. É que a
    humildade não floresce na insegurança das pessoas, mas na
    segurança insegura dos cautos. (...)

## Tabela


Fruta | Preco
-----------| -----
Algo aqui. | Algo alí.

Será que ele vai? | Não entendi.

Foi! | kkkkk.

\legend{Fonte: Fulana de tal}

## Configurando a seção de Referências bibliografia

A bibliografia é configuração em um arquivo separado.

# Conclusão

A conclusão do artigo vem aqui.
