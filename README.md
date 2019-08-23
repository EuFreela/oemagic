<img src="code.png" width="50"> @patterns
<hr>

### OE MAGIC

É uma extensão para VSCODE com o objetivo de facilitar o uso de politicas de padronização de código. Estou em um projeto onde precisei documentar o código e padronizar a forma de desenvolvimento. Para que os desenvolvedores não precisem ler muito para ser mais produtivo, criei esta extensão para uso interno do projeto.

#### Instalação

Para fins pessoais e de projeto, esta extensão não esta (ainda), disponibilizada publicamente no repositório de extensões do VSCODE. Para utilizar, caso queira, basta importar o diretório **oemagic** para dentro da sua instalaçao do vscode.

- windows: C:\Users\seu_usuário\.vscode\extensions

Reinicie o vscode. Ele ja estará instalado. Para averiguar, clique em extensões e busque por **oemagic**.


<hr>

##### NOMENCLATURAS


> É um conjunto de nomes e designações usados no âmbito de uma área específica do conhecimento. Este arquivo tem o objetivo de padronizar nomes para diversos fins no ambiente de programação facilitando o entendimento para melhor manutenabilidade e escabilidade do código desenvolvido.

<p>A padronização também é importante para que partes do projeto possam se comunicar sem problemas, como o desenvolvimento de uma plataforma que deverá ser segmentada em diversas partes designadas à funcionalidade de cada programador da equipe. Para que as partes se comuniquem ao integrar o projeto é necessário que estejam padronizadas para se evitar problemas de incompatibilidade.</p>

<p>Tipos de Nomencaturas:</p>

- [ ] Pascal Case: Primeira letra do identificador e primeira letra de cada palavra concatenada em maiúsculo. Exemplo: <b>BackColor</b>;
- [x] Camel Case: Primeira letra em minúsculo e cada palavra concatenada em maiúsculo. Exemplo: <b>backColor</b>

##### Regras Gerais:

- Não utilizar acentos;
- Não utilizar espaços;
- Não usar abreviações; e
- Os nomes a serem definidos seu comprimento poderá ser extenso desde que seja definido de acordo com a finalidade do que o defini. Exemplo: para o nome de uma função ou método que retorne uma view que lista clientes cadastrados, poderá ser usado <b>getListClients</b>. O nome no plural é para referir-se a uma lista de clientes.

<hr>
###### Referencias:

[Clean Code](https://www.amazon.com.br/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882) <br>
[Markedown](https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)

<hr>
///////////////////////////////////////////////////////////////////////////////

#### Índice:
- Padrões para aquivos;
- Padrões para variáveis;
- Controles;
- Comentários;
- Banco de dados;
- Projetos em Laravel;

///////////////////////////////////////////////////////////////////////////////

<hr>
### Padrões para arquivos:

|           Tipo            | Nomenclatura |    Exemplo     | Sintaxe       |
|---------------------------|--------------|----------------|---------------|
|Formulário                 |frm           |frmMenu         |<b>@a.form</b>         |
|Formulário (Janela Pop up) |frmPop        |frmPopJanela    |<b>@a.form-popup</b>   |
|Classe                     |cls           |clsFuncionario  |<b>@a.class</b>        |
|Módulo                     |mdl           |mdlModulo       |<b>@a.module</b>       |
|User Control               |wuc           |wucControle     |<b>@a.usercontrol</b>  |
|Folha de Estilo            |css           |cssFormulario   |<b>@a.css</b>          |
|Java Script                |jsc           |jscFuncao       |<b>@a.jsc</b>          |
|Relatório                  |rel           |relRelatorio    |<b>@a.report</b>       |
|DataSet                    |dst           |dstFatura       |<b>@a.dataset</b>      |
|XML                        |xml           |xmlArquivo      |<b>@a.xml</b>          |
|Custom Control             |cco           |ccoControle     |<b>@a.customcontrol</b>|
|Página html                |html          |htmPagina       |<b>@a.html</b>         |

<hr>

### Padrões para variáveis:

| Tipo                                          | Nomenclatura  |Exemplo            | Sintaxe               |
|-----------------------------------------------|---------------|-------------------|-----------------------|
|Char, nChar, Varchar, nVarchar, Text, nText    |str            |strEmail           |@vp.strings            |
|Datetime, SmallDatetime                        |dte            |dteDateCreated     |@vp.datetime           |
|Tinyint, Smallint, Integer, Bigint             |int            |intContactID       |@vp.integer            |
|Bit                                            |bit            |bitPrimaryContact  |@vp.bit                |
|Real                                           |sng            |sngTotal           |@vp.real               |
|Float, Double                                  |dbl            |dblLength          |@vp.float              |
|Decimal                                        |dec            |decLength          |@vp.decimal            |
|SmallMoney, Money                              |cur            |curTotal           |@vp.money              |
|Binary, varBinary                              |bin            |binContract        |@vp.binary             |
|Image                                          |img            |imgLogo            |@vp.image              |
|Timestamp                                      |tsp            |tspCurrent         |@vp.timestamp          |
|UniqueIdentifier                               |guid           |guidOrderID        |@vp.uniqueidentifier   |
|Sql_Variant                                    |var            |varPrice           |@vp.sqlvariant         |
|Cursor                                         |crs            |crsInventory       |@vp.cursor             |
|Boolean                                        |bln            |blnRetorno         |@vp.boolean            |

<hr>

### Controles:

|Objeto                     |Nomenclatura   |Sintaxe                        |
|---------------------------|---------------|-------------------------------|
|AdRotator                  |artCustomer    |@v.adrotator                   |
|ArrayList                  |aylCustomer    |@v.arraylist                   |
|Button                     |btnCustomer    |@v.button                      |
|Calendar                   |cldCustomer    |@v.calendar                    |
|CheckBox                   |chkCustomer    |@v.checkbox                    |
|CheckBoxList               |chkLCustomer   |@v.checkboxlist                |
|ComboBox                   |cboCustomer    |@v.combobox                    |
|CompareValidator           |cmvCustomer    |@v.comparevalidator            |
|CrystalReportViewer        |crvCustomer    |@v.crystalreportviewer         |   
|CustomValidator            |ctvCustomer    |@v.customvalidator             |
|DataColumn                 |dclCustomer    |@v.datacolumn                  |
|DataGrid                   |dgdCustomer    |@v.datagrid                    |
|DataList                   |dlsCustomer    |@v.datalist                    |
|DataRow                    |drwCustomer    |@v.datarow                     |
|DataRowView                |drvCustomer    |@v.datarowview                 |
|DataSet                    |dstCustomer    |@v.dataset                     |
|DataTable                  |dtbCustomer    |@v.datatable                   |
|DataView                   |dvwCustomer    |@v.dataview                    |
|DropDownList               |ddlCustomer    |@v.dropdownlist                |
|GroupBox	                |grpCustomer    |@v.groupbox                    |
|Hashtable	                |htbCustomer    |@v.hashtable                   |
|HyperLink	                |hypCustomer    |@v.hyperlink                   |
|Image	                    |imgCustomer    |@v.image                       |   
|ImageButton	            |IbtnCustomer   |@v.imagebutton                 |
|Label	                    |lblCustomer    |@v.label                       |
|LinkButton	                |lbtnCustomer   |@v.linkbutton                  |
|LinkLabel	                |llblCustomer   |@v.linklabel                   |
|ListBox	                |lstCustomer    |@v.listbox                     |
|Literal	                |litCustomer    |@v.literal                     |
|Menu (WinForms)	        |mnuItemMenu    |@v.menu-winforms               |
|Panel	                    |pnlCustomer    |@v.panel                       | 
|Picture	                |picCustomer    |@v.picture                     |
|PlaceHolder	            |plhCustomer    |@v.placeholder                 |
|ProgressBar	            |prgCustomer    |@v.progressbar                 |
|RadioButton/OptionButton	|optCustomer    |@v.radiooptionbutton           |
|RadioButtonList	        |rbtnlCustomer  |@v.radiobuttonlist             |
|RangeValidator	            |rgvCustomer    |@v.ragevalidator               |
|RegularExpressionValidator	|revCustomer    |@v.regularexpressionvalidator  |
|Repeater	                |repCustomer    |@v.regularexpressionvalidator  |
|RequiredFieldValidator	    |rfvCustomer    |@v.requiredfieldvalidator      |
|TabControl	                |tabCustomer    |@v.tablecontrol                |
|Table	                    |tblCustomer    |@v.table                       |
|TextBox	                |txtCustomer    |@v.textbox                     |
|ValidationSummary	        |vsmCustomer    |@v.validationsummery           |
|WebService	                |wseCustomer    |@v.webservice                  |
|Xml	                    |xmlCustomer    |@v.xml                         |

<hr>

### Comentários:

#### 1. Para banco de dados:

##### 1.1. Cabeçalho: 

> <b>@cctdb</b>

<pre>
/*
||-----------------------------------------
||EMPRESA       :   OMNI
||SISTEMA       :   SISTEMA DE FATURAMENTO
||OBJETIVO      :   ALTERAÇÃO DE AVISOS
||AUTOR         :   LAMECK S.F
||CRIAÇÃO       :   14/08/2019
||MANUTENÇÃO    :   --
||OBSERVAÇÃO    :   --
||------------------------------------------
*/
</pre>
##### 1.2. Em demais áreas do código:

> <b>@ccl</b>

<pre>
/*
// -- Esta linha define qual será o faturamento de cada mês  -- //
*/
</pre>

#### 2. Para sistemas: 

> <b>@ccts</b>

<pre>
/*
|********************************************************
| EMPRESA           : OMNI
| OBJETIVO          : SISTEMA DE FATURAMENTO
|
|--------------------------------------------------------
| AUTOR             : LAMECK S.F
| DATA CRIAÇÃO      : 14/08/2019
| MANUTENÇÃO        : --
| OBSERVAÇÃO        : --
|
|*********************************************************
*/
</pre>

<hr>
### Banco de dados:
|Tipo       |Nomenclatura   |Exemplo    |
|-----------|---------------|-----------|
|Tabela     |tbl            |tblCliente |

<hr>

### PROJETOS EM LARAVEL:

#### 1. Controller
Nomes para controllers respeitam o nome da operação terminado com controller em Pascal Case.
<p>Exemplo</p>
- HomeController;
- AccountController;
- TokenController;
- DashboardController;

> php artisan make:controller HomeController

<p>A criação da controller não segue os métodos default como 'store', 'update', etc. Na criação em branco deverá haver os comentários que separam os métodos do que cada grupo 
deve apresentar. Insira na controller:</p>

> <b>@ccc.php</b>
ou
> <b>@ccc.php.f</b>

<pre>
/***************************************************************************
* GETTERS
*/

// Insira os códigos para http Get aqui..

/***************************************************************************
* POSTTERS
*/

// Insira os códigos para http Post aqui..

/***************************************************************************
* PUTTERS
*/

// Insira os códigos para http Put aqui..

/***************************************************************************
* DELETERS
*/

// Insira os códigos para http Delete aqui..

/***************************************************************************
* PRIVATE METHODS
*/

// Insira os códigos as funções privadas aqui..
</pre>


Como exemplo, considere a controller ClientController.php:
<pre>
/***************************************************************************
* GETTERS
*/

public function getListClient() 
{
    return view('backend.client.list-client');
}

public function getClientId( $client_id )
{
    return view('backend.client.client',[
        'client' => Client::find( $client_id )
    ]);
}

/***************************************************************************
* POSTTERS
*/

public function postClient( Request $request )
{
    $request->validate([
        'name' => 'required|alpha_dash',
        'email' => 'required|email|unique:client',
        'cpf' => 'required|unique:cpf',
        'street' => 'required|alpha_dash',
        'number' => 'required|numeric',
        'neighborhood' => 'required|alpha_dash',
        'complement' => 'alpha_dash',
        'zipcode' => 'required|numeric'
    ]);
    
    $client = Client::create([
        'name' => $request->name,
        'email' => $request->email,
        'cpf' => $request->cpf
    ]);
    
    $address = Address::create([
        'client_id' => $client->id,
        'street' => $request->street,
        'number' => $request->number,
        'neighborhood' => $request->neighborhood,
        'complement' => $required->complement ? $required->complement : 'null',
        'zipcode' => $required->zipcode
    ]);
    
    if( $client and $address )
        return redirect()->route('backend.client.list-client')->with('Cadastro efetuado com sucesso!');
    else
        return back()->with('Não foi possível cadastrar o cliente');
    
}

/***************************************************************************
* PUTTERS
*/

public function putClient( Request $request, $client_id ) {

    $request->validate([
        'name' => 'required|alpha_dash',
        'email' => 'required|email|unique:client',
        'cpf' => 'required|unique:cpf',
        'street' => 'required|alpha_dash',
        'number' => 'required|numeric',
        'neighborhood' => 'required|alpha_dash',
        'complement' => 'alpha_dash',
        'zipcode' => 'required|numeric'
    ]);
    
    $client = Client::find( $client_id );
    $client->name = $request->name;
    $client->email = $request->email;
    $client-cpf = $request->cpf;
    
    $address = Address::where('client_id','=',$client_id)->update([
        'street' => $request->street,
        'number' => $request->number,
        'neighborhood' => $request->neighborhood,
        'complement' => $required->complement ? $required->complement : 'null',
        'zipcode' => $required->zipcode
    ]);
    
    if( $client->save() and $address )
        return redirect()->route('backend.client.list-client')->with('Edição efetuada com sucesso!');
    else
        return back()->with('Não foi possível editar o cadastro');
}

/***************************************************************************
* DELETERS
*/

public function deleteClient( $client_id )
{
    
    $client = Client::where('id','=',$client_id)->delete();
    
    if( $client )
        return redirect()->route('backend.client.list-client')->with('Cadastro excluído com sucesso!');
    else
        return back()->with('Não foi possível excluir o cadastro');
    
}

/***************************************************************************
* PRIVATE METHODS
*/

private function calcOldPeople( birth )
{
    $old = strtotime('now') - birth;
    return $old;
}
</pre>

<hr>

#### Create Validate Request Laravel

> <b>@c.vrl</b>

<hr>


#### 2. Routes:
Camel Case.
<p>Exemplo</p>
Considere que a controller home já tenha sido criada: <b>homeController</b>. Dentro dela os métodos:
- gethome: chamada da view home;

Teremos a rota:

|Tipo       | URL    |Nome          | Exemplo                                                               |
|-----------|--------|--------------|-----------------------------------------------------------------------|
|Get        | home   |home.gethome  | Route::get('/home','homeController@gethome')->name('home.gethome');   |

<p>O nome que for parametrizado deverá respeitar o <b>"."(ponto)</b> que separa o nome da url com o método referente.</p>
<p>As rotas deverão estar dentro de um grupo com o <b>middleware</b> referente. Neste caso, para acesso público e privado:</p>

##### Create Laravel Route Crud

> <b>@cr.lc</b>
ou
> <b>@cr.lara</b>
ou
> <b>@cr.lgc</b>

```
/**
* FRONTEND
*/
Route::group(['middleware' => 'web'], function() {

    // insira aqui as rotas públicas (que não seja necessário o log no sistema)
    
});
/**
* BACKEND
*/
Route::group(['middleware' => 'auth'], function() {

    // insira aqui as rotas pós login (acesso privado)
    
});
```
<br>

#### Create Laravel Model Page

> <b>@cr.lmp</b>
ou
> <b>@cr.lm</b>

<hr>

#### Create Form Element

> <b>@cv.n.form</b>
ou
> <b>@cv.n.form.lara</b>

<hr>



#### 3. Vews
Nomes para views deverão ser minusculos incluindo o nome de diretórios. Dentro da view teremos diretórios referentes a cada funcionalidade, sendo:
- layout: diretório que define os modelos para os layouts a serem utilizados no projeto;
- frontend: diretório que conterá todas as páginas que serão acessadas sem o uso do login;
- backend: diretório que conterá todas as páginas que serão acessadas pós login;

<p>Dentro de cada diretório terá subdiretórios nomeados de acordo com sua função. Como exemplo, considere que precisamos criar as views para cliente sabendo que
trata-se de um CRUD (create, read, update, delete):</p>

<pre>
- <b>layout</b>
-------- <i>app.blade.php</i>
- <b>frontend</b>
- <b>backend</b>
-------- <b>client</b>
--------------- <i>create-client.blade.php</i>
--------------- <i>edit-client.blade.php</i>
--------------- <i>list-client.blade.php</i>
</pre>

No exemplo acima temos a descrição:
- app.blade.php, trata-se de nosso modelo utilizado como layout para as páginas do projeto. Este arquivo fica dentro do diretório, em negrito, layout;
- frontend, trata-se de nosso diretório usado para páginas acessadas sem a necessidade de login em modelo server-side;
- backend, trata-se de nosso diretório que conterá página que serão acessadas após logon.
- client, trata-se do subdiretório de backend contendo o CRUD para métodos de controle de operação com gerenciamento de clientes que são: create; edit (update); list (read);

Para nomes compostos de views utilizamos o <b>"-"(hífen)</b> para separar o radical do prefixo. Todos os nomes são definidos em minusculo dentro de um subdiretório de operação
que defini o CRUD.


#### 4. Models
Nomes para models respeitam a nomenclatura Camel Case. Como ultimo nome deve prevalecer "Model".
<p>Exemplo</p>
Considere que seja necessário criarmos uma model para clientes: <b>ClientModel</b>
<p>Além disso, todas as models deverão estar em um diretório chamado <b>Models</b>. Para isso é necessário uma configuração 
<a target="_blank" href="https://pt.stackoverflow.com/questions/107177/pasta-para-models-laravel-5-1">Clique aqui</a>.</p>

#### 5. Packagers
O uso de packagers varia conforme a necessidade da aplicação. Além de baixá-los para uso free, o desenvolvimento de packagers segue alguns padrões:
- Nome do packager: omnieletronica/nome_da_solucao;
- Para nomes de modelos, controllers, views e export, segue demais configurações utilizadas acima


#### 6. Classes
Para criarmos classes para funcionalidades específicas, será criado um diretório chamado <b>Class</b> em <b>app/Class</b>.
Dentro deste diretório conterão as classes que serão utilizadas no sistema:
<p>Considere o arquivo <b>clsHello.php</b> - class Hello</p>

```
<?php
class Hello { 
    
    // attributes
    private $hello;
    
    // constructor
    public function __construct( $hello ) 
    {
        $this->hello = $hello ? $hello : 'Olá mundo cruel!';
    }
    
    // SETTERS ------------------------------------------
    public function setHello( $hello )
    {
        $this->hello = $hello;
    }
    
    // GETTERS ------------------------------------------
    public function getHello()
    {
        return $this->hello;
    }
    
    // PRIVATE METHODS
    private function toDay()
    {
        return strtotime('now');
    }

}   
```
Chamada da classe nas controllers: <b>use app/Class/Hello</b>
Uso em documento:

```
$hello = new Hello('Olá Mundo');
ou
$hello = new Hello();

$hello.sethello('Olá, Alice no país das maravilhas.');
$hello.getHello();

```




