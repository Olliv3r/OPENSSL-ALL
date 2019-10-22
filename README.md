# OPENSSL-ALL
Pacotes openssl for termux


## TODAS AS DEPENDÊNCIAS:
	apt update && apt upgrade -y && apt install openssl clang python postgresql libcrypt libffi openssl libsodium make python




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
