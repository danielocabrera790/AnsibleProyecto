## Configurar un playbook en Ansible.
Configuracion basica de ansible para los playbooks
1. Despues de la instalacion, deberemos de editar el fichero /etc/ansible/hosts con las ips de nuestros respectivos servidores
![image](https://user-images.githubusercontent.com/94164299/215326732-ae3fe69b-6d98-4c2e-92e8-edc0b0904eb1.png)
2. Es recomendable crear un usuario especifico para no utilizar el root
![image](https://user-images.githubusercontent.com/94164299/215326889-94d70cf0-b1eb-4ee1-9868-255721022ce3.png)
![image](https://user-images.githubusercontent.com/94164299/215326916-f0e872ac-9f1a-4e81-9500-647a2bc479bc.png)
3. Nos meteremos en ese usuario creado y a continuacion generaremos las claves ssh
![image](https://user-images.githubusercontent.com/94164299/215326999-632a7e8b-5c74-47cc-b18e-e619f1a863a5.png)
Los playbooks son archivos de texto en formato YAML en los que se definen varias tareas a ejecutar de forma secuencial. Aqui tenemos un ejemplo
![image](https://user-images.githubusercontent.com/94164299/215327159-fa885623-db89-4cd9-97cb-e68b5f667670.png)
Este en concreto se encarga de actualizar dos de nuestros servidores. Si lo ejecutamos obtendremos la siguiente salida
![image](https://user-images.githubusercontent.com/94164299/215327269-12fd052d-1565-41be-96aa-1f1f6444c8d3.png)
