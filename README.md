# NotePad-Clock
  Esse foi um dos exercicios que eu encontrei perdido pela internet e decide tentar fazer.
    Criei então um mostrador das horas em tempo real e data. 
      Pretendo no futuro aprimorar para utilizar na criação um web site, utilizando webe3.
        qualquer dica por favor, deixe por aqui, obrigado 
        
       
       
#codigo utilizando. 

@echo off
  Title Clock
    @mode con cols=30 Lines=7
      color 03 
        : main
          cls
            echo.
              echoTime: %time%
                echo.
                  echo Date: %date%
                    echo.
                      ping -n 2 0.0.0.0>n
                        goto main
