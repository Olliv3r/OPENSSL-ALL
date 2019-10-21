# OPENSSL-ALL
Pacotes openssl for termux


# TODAS AS DEPENDÊNCIAS:
	pkg install clang python-dev postgresql-dev libcrypt-dev libffi-dev openssl-dev libsodium-dev make python




###  TENTANDO INSTALAR pynacl SE DÊ ERRO.
O pynacl depende da biblioteca libsodium-dev que
se encontra entre as dependências acima
Sodium é uma nova biblioteca de software fácil
de usar para criptografia, descriptografia, assinaturas,
hash de senha e muito mais.


### configurar
	SODIUM_INSTALL=system pip install pynacl
	pip install magic-wormhole


# OUTRO MÉTODO DE CORREÇÃO DO pynacl
	git clone https://github.com/pyca/pynacl
	cd pynacl
	python setup.py install
