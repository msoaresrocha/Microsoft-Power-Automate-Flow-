## Microsoft Power Automate (Flow)
### Como usar Microsoft Power Automate (Flow)
Este exemplo foi criado de forma a atender Abonos e aprovações de horas extras de integrantes de uma determinada empresa a qual trabalho.
A primeira coisa a ser criada é um formulário, contendo as informações que sejam úteis para seu RH. no caso da empresa a qual trabalho foi a da imagem abaixo:
####  
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2013_57_44-Microsoft%20Forms.png)
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2013_58_02-Microsoft%20Forms.png)

![]()
Feito isso, podemos ir para o Power Automate.
Você deve criar um fluxo em branco e ir construindo os triggers e ações.
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2014_24_37-Gerenciar%20seus%20fluxos%20_%20Microsoft%20Power%20Automate.png)


Feito isso você irá começar a adicionar o Trigger inicial, que para a nossa finalidade é "Aguardando a cada recebimento de formulário" e depois marcar a ação para cada "Recebimento", conforme imagme abaixo.
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2014_28_52-Editar%20o%20fluxo%20_%20Power%20Automate.png)

Dentro da aplicação cada "Recebimento", você vai pegar as informações do Formulário e colocá-las na aprovação que vai para o gestor que a pessoa escolheu.
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2014_31_59-Editar%20o%20fluxo%20_%20Power%20Automate.png)

Caso ele seja aprovado ou reprovado, um email formatado em HTML é enviado ao prórpio integrante, ao responsável do RH e ao gestor. Também há a opção de enviar ao Sharepoint (estarei colocando abaixo)
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2014_35_15-Editar%20o%20fluxo%20_%20Power%20Automate.png)

Formato do email
![](https://github.com/msoaresrocha/Microsoft-Power-Automate-Flow-/blob/main/MD/2020-12-04%2014_48_18-Window.png)
![]()
![]()
