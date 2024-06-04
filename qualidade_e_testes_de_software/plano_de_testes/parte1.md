## 1 - Introdução

Este documento possui a funcionalidade de realizar os testes no site da Magazine Luiza, uma varejista nacional que está presente em nosso cotidiano desde a década de 50 e possui diversas empresas parceiras, como a Netshoes, Zattini, Época Cosméticos, Estante Virtual, Kabum!, Consórcio Magalu, entre outras. Estaremos analisando funcionalidades do site e seu contexto de forma que atenda os padrões de qualidade impostos por nossos estudos. 

Ao listar os casos de uso, temos em mente os critérios: “A aplicação está realizando seu papel?”,  “A aplicação está disponível para todas as plataformas?”,  “Possui o destaque de acordo com sua funcionalidade?”, entre outras.

## 2 - Requisitos de Teste

Esta seção contém os requisitos identificados como objetos dos testes ao longo do desenvolvimento do projeto.

Requisitos funcionais (RF)
| Requisito | Descrição                  |
| --------- | -------------------------- |
| RF001     | Cadastro/Login na plataforma        |
| RF002     | Abrir página do produto |
| RF003     | Filtrar produtos |

Requisitos não funcionais (RNF)
| Requisito  | Descrição                  |
| ---------- | -------------------------- |
| RNF001     | Coesão entre aplicativo e site        |
| RNF002     | Verificar healthcheck Liveness Probe  |
| RNF003     | Animações |

## 3 - Tipos de Testes
<ul>
    <li>
Teste de integração <br>
    O site e o aplicativo devem estar coesos um ao outro na maioria dos
    casos, portanto, caso analisemos uma funcionalidade que deveria
    estar integrada, mas isso não ocorre, consideraremos isso como
    uma falha.
    </li>
    <li>
Teste de caixa preta <br>
    Analisaremos os requisitos do sistema, ou seja, se o software
    cumpre as funções que deve executar, sem a utilização do códigofonte, pois não temos acesso
    </li>
</ul>

## 3.1 - Execução dos testes

<br/>
<table>
    <tr>
        <th>
            Objetivo:
        </th>
        <th colspan="4">
            RF01
        </th>
    </tr>
    <tr>
        <th>
            Método de Execução:
        </th>
        <th colspan="2">
            Manual (x) 
        </th>
        <th colspan="2">
            Automática ( ) 
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            Teste Estrutural ( )
        </th>
        <th colspan="2">
            Teste Funcional (x)
        </th>
    </tr>
    <tr>
        <th>
            Nível de Teste:
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável:
        </th>
        <th colspan="2">
            Fábio Cypreste
        </th>
    </tr>
    <tr>
        <th>
            Resultado do teste
        </th>
        <th colspan="2">
            Na etapa de cadastro, é crucial que não ocorram falhas, mas foram encontradas
            algumas questões que podem ser melhoradas. Aopressionar Ctrl+A e apagar tudo 
            na seleção de CPF, é apagado apenas um caractere, e não toda o campo. A senha 
            pode ser qualqueruma, desde que tenha 6 caracteres, o que abre margem para senhas
            como “123456” e “abcdef”.
        </th>
    </tr>

    <br/>
<table>
    <tr>
        <th>
            Objetivo:
        </th>
        <th colspan="4">
            RF02
        </th>
    </tr>
    <tr>
        <th>
            Método de Execução:
        </th>
        <th colspan="2">
            Manual (x) 
        </th>
        <th colspan="2">
            Automática ( ) 
        </th>
    </tr>
    <tr>
        <th>
            Técnica:
        </th>
        <th colspan="2">
            Teste Estrutural ( )
        </th>
        <th colspan="2">
            Teste Funcional (x)
        </th>
    </tr>
    <tr>
        <th>
            Nível de Teste:
        </th>
        <th>
            Integração ( )
        </th>
        <th>
            Sistema ( )
        </th>
        <th>
            Unidade (x)
        </th>
    </tr>
    <tr>
        <th>
            Responsável:
        </th>
        <th colspan="2">
            Fábio Cypreste
        </th>
    </tr>
    <tr>
        <th>
            Resultado do teste
        </th>
        <th colspan="2">
            Nessa etapa, ao usuário ir para baixo da página, um header aparece
            para manter o preço e o botão de compra na tela do mesmo. Por
            vezes, esse item continua na tela, mesmo que você já não esteja
            indo para baixo da página. Acontece tanto no aplicativo quanto no site.
        </th>
    </tr>
</table>

## 5 - Recursos

<table>
    <tr>
        <th>
        Placa de vídeo
        </th>
        <th>
        RTX 3060
        </th>
    </tr>
    <tr>
        <th>
        Processador:
        </th>
        <th>
        Ryzen 5 5500 
        </th>
    </tr>
    <tr>
        <th>
        Memória RAM:
        </th>
        <th>
        16 GB 
        </th>
    </tr>
    <tr>
        <th>
        Velocidade da internet
        </th>
        <th>
        300Mb
        </th>
    </tr>
</table>

<br>

<table>
    <tr>
        <th>
        Placa de vídeo
        </th>
        <th>
        GTX 1050ti
        </th>
    </tr>
    <tr>
        <th>
        Processador:
        </th>
        <th>
        Xeon 
        </th>
    </tr>
    <tr>
        <th>
        Memória RAM:
        </th>
        <th>
        16 GB 
        </th>
    </tr>
    <tr>
        <th>
        Velocidade da internet
        </th>
        <th>
        300Mb
        </th>
    </tr>
</table>

    <table>
    <tr>
    </tr>
    <tr>
        <th>
        Processador:
        </th>
        <th>
        Intel 3 3100
        </th>
    </tr>
    <tr>
        <th>
        Memória RAM:
        </th>
        <th>
        8 GB 
        </th>
    </tr>
    <tr>
        <th>
        Velocidade da internet
        </th>
        <th>
        100Mb
        </th>
    </tr>
</table>
### 5.2 - Software

<table>
    <tr>
        <th colspan="3">
        Sistema Operacional:
        </th>
        <th colspan=3>
        Windows 11 Pro 64-bit e Linux Ubuntu
        </th>
    </tr>
    <tr>
        <th colspan=3>
        Navegador(es):
        </th>
        <th>
        Google Chrome (x)
        </th>
        <th>
        Microsoft Edge (x)
        </th>
        <th>
        Mozilla Firefox (x)
        </th>
        <th>
        Opera GX (x)
        </th>
    </tr>
</table>