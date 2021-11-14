# Enterprise-Service-BUS
Protótipo, em Java de um ESB, que realizará integração de dados clínicos usando HL7

Operações:

	Recebe dados clínicos:
		- Recebe dados em HL7
			- Recebe um arquivo em HL7, faz a leitura do mesmo, o transforma em objeto, valida e salva na base de dados.
			
		- Recebe dados pré HL7 (web services)
			- Recebe um XML ou Json, trasnforma em objeto, valida e salva na base
	
	Emite dados clínicos:
		- Gera um arquivo HL7
			- Dados são alimentados na tela do sistema, e esses são transformados em objeto e depois jogados em um arquivo em formato HL7
