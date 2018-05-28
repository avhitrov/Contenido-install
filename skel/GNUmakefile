##############################################################################
#
###############################################################################

include config.mk

LOG =	var/log/messages

.DEFAULT:
	@echo -e "\n\n##############################" >> ${LOG}	\
	&& echo "Target: $@"    >> ${LOG}			\
	&& echo "Date:   "`date` >> ${LOG}			\
	&& echo "##############################" >> ${LOG}	\
	&& cd ./src/core					\
	&& unset MAKEFLAGS					\
	&& unset MFLAGS						\
	&& unset MAKELEVEL					\
	&& ${MAKE} $@
