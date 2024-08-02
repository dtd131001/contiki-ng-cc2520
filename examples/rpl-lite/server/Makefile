all: root-node
CONTIKI=../../..

# Include RPL BR module
include $(CONTIKI)/Makefile.dir-variables
MODULES += $(CONTIKI_NG_SERVICES_DIR)/rpl-border-router
# Include webserver module
MODULES_REL += webserver

#MODULES += os/services/shell

include $(CONTIKI)/Makefile.include
