<h1 align="center"> Projeto Laravel – Migration</h1>

<p align="center">
  Guia passo a passo .
</p>

<hr>

<h2>1 Preparando o Ambiente</h2>
<p>Ative as extensões necessárias no arquivo <code>php.ini</code> localizado em <code>xampp/php/php.ini</code>, removendo o ponto e vírgula (<code>;</code>) das linhas:</p>
<pre>
extension=ftp
extension=ffi
extension=zip
</pre>

<hr>

<h2>2 Instalando o Laravel</h2>
<p>Execute os comandos no terminal e siga as opções apresentadas.</p>

<p><strong>1°</strong></p>
<img src="https://github.com/user-attachments/assets/8f350ea0-16d6-483b-bc3c-a4715aca31b4" width="500">

<p><strong>2°</strong></p>
<img src="https://github.com/user-attachments/assets/d466e7fb-3bc6-4196-8632-1f3496498809" width="500">

<p><strong>3°</strong></p>
<img src="https://github.com/user-attachments/assets/08d7a344-1fc5-425c-b9ed-2f4adc41b109" width="500">

<p><strong>4°</strong></p>
<img src="https://github.com/user-attachments/assets/6965ac59-3653-4f62-a152-8a51fc6f6aed" width="500">

<p><strong>5°</strong></p>
<img src="https://github.com/user-attachments/assets/186326e5-9982-467f-8c54-29176e5a6a74" width="500">

<p><strong>6°</strong></p>
<img src="https://github.com/user-attachments/assets/9c7f2129-70f8-4925-a8a8-558aa198b4f7" width="500">

<hr>

<h2>3 Criando a Migration</h2>
<p>Para criar a tabela <code>user_alunos</code>:</p>
<img src="https://github.com/user-attachments/assets/cb03c110-c5ec-4e74-ae9d-d38aac133b4f" width="500">

<p>Um arquivo será criado em <code>database/migrations</code>:</p>
<img src="https://github.com/user-attachments/assets/0dcb3ccf-ba31-4407-a092-e833cf80c570" width="500">
<hr>

<h2>4 Definindo os Campos da Tabela</h2>
<p>No arquivo gerado, adicione:</p>

<img src="https://github.com/user-attachments/assets/a410ff03-89ef-467a-a6a6-364406deb356" width="500">

<hr>

<h2>5 Executando a Migration</h2>
<p>Para criar a tabela no MySQL, rode:</p>
<img src="https://github.com/user-attachments/assets/23ecd5c6-7b63-4594-b1f4-453f5531716a" width="500">

<p>A tabela será criada e poderá ser visualizada no <strong>phpMyAdmin</strong>:</p>
<img src="https://github.com/user-attachments/assets/de196a66-b25f-4a78-af10-2fe8dae7d04a" width="700">

<hr>

<p align="center">Feito com  Laravel e MySQL</p>

