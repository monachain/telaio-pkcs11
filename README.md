# telaio-pkcs11
Hyperledger 프로젝트 용 TELAIO-PKCS11에 오신 것을 환영합니다. 
TELAIO-PKCS11를 통해 Fabric Java 응용 프로그램이 HSM의 PKCS11 Store를 관리 할 수 있습니다. 
또한 fabric의 crypto-gen을 통해 만들어진 Private Key와 Certificate파일을 PKCS11 Strore에 주입하는 기능을  제공합니다.
Fabric Java 응용 프로그램은 직접 PKCS11 API를 Call할 수 없기 때문에  Java에서 기본으로 제공하는 암호 관련 API인 JCA/JCE Library를 Call 하고, 
TELAIO-PKCS11 Wrapper를 연결하여 HSM을 사용합니다.
