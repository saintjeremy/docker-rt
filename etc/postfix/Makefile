all: aliases sasl_passwd
aliases: aliases.db
sasl_passwd: sasl_passwd.db

aliases.db:
	newaliases

sasl_passwd.db:
	postmap hash:sasl_passwd
