# Phishing para captura de senhas do Facebook

### Ferramentas

- Kali Linux
- setoolkit

### Configurando o Phishing no Kali Linux

##### Por conta de problemas com o clone do facebook, utilizei métodos apresentados no: https://github.com/Weslley22Marques/cibersecurity-desafio-phishing

- Acesso root: ``` sudo su ```
- Iniciando o setoolkit: ``` setoolkit ```
- Tipo de ataque: ``` Social-Engineering Attacks ```
- Vetor de ataque: ``` Web Site Attack Vectors ```
- Método de ataque: ```Credential Harvester Attack Method ```
- Método de ataque: ``` Custom Import ```
- Abra o editor de arquivos e insira nele o conteúdo de: ``` view-source:www.facebook.com ```
- Delete no código: ``` <script src="https://static.xx.fbcdn.net/.......></script> ``` (Resolve o funcionamento do botão de Log In)
- URL do site importado: http://www.facebook.com

### Resutados
![image](https://github.com/user-attachments/assets/88593041-a409-45c8-9159-705a5654a668)
![image](https://github.com/user-attachments/assets/8b89c48b-d565-4356-8448-1addadce259c)
