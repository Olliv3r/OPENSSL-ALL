# OPENSSL-ALL
Pacotes openssl for termux


## TODAS AS DEPENDÊNCIAS:
	pkg install clang python-dev postgresql-dev libcrypt-dev libffi-dev openssl-dev libsodium-dev make python




### Tentando instalar pynacl se dê erro.
O pynacl depende da biblioteca libsodium-dev que
se encontra entre as dependências acima
Sodium é uma nova biblioteca de software fácil
de usar para criptografia, descriptografia, assinaturas,
hash de senha e muito mais.


### Configurar
	SODIUM_INSTALL=system pip install pynacl
	pip install magic-wormhole


### Outro método de correções do pynacl
	git clone https://github.com/pyca/pynacl
	cd pynacl
	python setup.py install
