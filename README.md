## Tutorial de instalação do node-js sem permissões de administrador
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Primeiro, acesse o link abaixo e instale o "Binário indepentente.zip"

```
https://nodejs.org/pt-br/download
```

Em seguida, extráia o arquivo, e deixe a pasta extraida exatamente nesse diretório 
```
"C:\Users\Public\Downloads\node-v24.15.0-win-x64"
```

Após isso, abra o cmd e rode o seguinte comando  |  
```cmd 
setx PATH "%PATH%;C:\Users\Public\Downloads\node-v24.15.0-win-x64"
```

Após rodar o comando, fechar e reabrir o cmd, e digitar node -v para conferir se a instalação foi realizada perfeitamente.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Notas importantes

Para abrir o cmd, aperte com o botão direito do mouse na área de trabalho, e crie um novo atalho com o nome "cmd", após, surgirá um prompt de comando desbloqueado em seu desktop.
