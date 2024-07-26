CONTIKI_PROJECT = my_sensor_app

PLATFORMS_EXCLUDE = sky nrf52dk simplelink

all: $(CONTIKI_PROJECT)

# Incluye los archivos fuente de tu proyecto
PROJECT_SOURCEFILES += sht21.c

CONTIKI = ../..

# Incluye las configuraciones de Contiki
include $(CONTIKI)/Makefile.include
