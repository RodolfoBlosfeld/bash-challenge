<html>

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=Generator content="Microsoft Word 15 (filtered)">

</head>

<body lang=PT-BR link="0563C1" vlink="#954F72">

<div class=WordSection1>
<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal>Obrigado pela oportunidade de ter participado desse desafio.</p>

<p class=MsoNormal><br>
Tive uma dificuldade muito maior do que imaginei, não consegui gerar um arquivo
nos padrões pedidos no passo 2 e acredito que, os IPs duplicados eram removidos
usando o comando</p>

<p class=MsoNormal>&nbsp;</p>

<p class=MsoNormal><b>awk '!a[$1]++' control_file.txt</b></p>

<p class=MsoNormal><b>awk '{a[$1]++;b[$1]=$0}END{for(x in a)if(a[x]==1)print
b[x]}' control_file.txt</b></p>

<p class=MsoNormal><b>&nbsp;</b></p>

<p class=MsoNormal>Acredito que, poderia contribuir muito mais, sob um ponto de
vista de Infraestrutura mais computacional e processual, no tocante a “<b><i>Infrastructure
as Code</i></b>” poderia ajudar em pontos práticos mais básicos que o teste
proposto e teoricamente.<br>
<br>
Em suma, poderia também, “copiar” o desafio do Colega <a
href="https://github.com/gvccandido/bash-challenge">Gabriel</a>, mas acho que
isso seria apenas uma questão de tempo para que, se de fato o ponto forte
pedido é o Código, eu seria descoberto.<br>
<br>
<br>
</p>

<p class=MsoNormal>Obrigado e estou a disposição,<br>
<br>
Rodolfo Blosfeld</p>

</div>

</body>

</html>
