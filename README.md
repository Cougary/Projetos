# Projetos
Projetos em Bash e Python

#!/bin/bash

# Executa o comando date mas filtra para imprimir somente o horário na tela
date | cut -d " " -f 5

#!/bin/bash 

# Elimina processos apenas passando o PID
read -p "Digite o número de identificação processo ou PID: "
echo "O processo com o PID $REPLY será eliminado"
kill -9 $REPLY


















