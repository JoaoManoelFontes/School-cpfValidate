<h1>Java Project: Cpf Validate</h1>
<h2>Mostra se o cpf que o usuário colocou é válido ou não</h2>
<br/>
<h2> Métodos: </h2>
<ul>
    <li>
    <h3>Main:</h3>
    <p>Recebe o cpf que o usuário digitou com a biblioteca <i>Java.util.Scanner</i> e armazena em uma String para mandar o método <i>validate</i> verificá-la e retornar um boolean true(Se o cpf for válido) ou false(se o cpf for inválido).</p>
    </li>
    <hr/>
    <li>
    <h3>Validate</h3>
    <p>Recebe a String contendo o cpf faz algumas verificações.</p>
    <p>tira os caracteres do cpf deixando somente os números e chama o método <i>isNumber</i> para verificar se todos os caracteres que sobraram são números.</p>
    <p>confere o comprimento da String só com os números, para ver se não está faltando nenhum.</p>
    <p>convoca o método <i>validateChars</i> para verificar se não está faltando nenhum dos caracteres que um cpf necessita ("." ou "-")</p>
    <p>chama os métodos <i>validateDigit</i> para conferir se os digitos verificadores (ultimos 2 digitos) batem com a conta de validação de cpf e o <i>validateSameNumbers</i> para ver se os números do cpf estão todos iguais (ex:000.000.000-00), pois seria inválido</p>
    </li>
    <hr/>
    <li>
    <h3>validateChars</h3>
    <p>Verifica, usando o <i>indexOf()</i> e o <i>substring()</i> se está faltando algum caractere tirando os números ("." ou "-") ou se esses caracteres estão na posição errada.</p>
    </li>
    <hr/>
    <li>
    <h3></h3>
    </li>
</ul>
