2025: 
gdzies jest plik z temperaturami kt�ry trzeba zmienic by m�c wchodzic przy standardowym termistorze na wyzsze temperatury. chyba temperatures.h i daelj chyba do konkretnego pliku tego typu termistora ... 
zauważyłem że mam taki config RX_BUFFER_SIZE 1024 - że odpala się SERiAL_XON_XOFF i to  można też  włączyć w ust usb com w windows
ale bez tego Cura itp. też obsłuży tą opcję. 

2024-04:
zmiany w  w pins_robin_nano_common.h - dodalem cala sekcje !!!   HAS_TMC_UART 
przepisalem z pins\stm32f1 ze starego - HAS_TMC220x

HAS_TMC_UART oryginalnie definjuje sie w src/core/drivers.h

wazne by wlaczyc serial poniewaz mam tak polaczone piny jak na rysunku || : - jakos tak t owyglada
czy;i pins_robin_nano_v1_v2 lub common jw.

dalem input shapeing ale mi rebootuje caly czas wiec wyl
pewnie trzeba dac slabszy interfejs by mial wiecej ram 
zmiana ust portu 11 na szybszy zgodny z config.h marlina 
 