- Escribir el comando: gpg --full-generate-key
- Presionar Enter para elegir el tipo por defecto.
- Especificar al meno "4096"
- Presionar Enter para verificar la opciones elegidas.
- Colocar nombre, correo vinculado con GitHub y un comentario.
- Crear una contraseña.
- Escribir el comando: gpg --list-secret-keys --keyid-format=long
- Se mostrará un mensaje similar a este:
  ```
  $ gpg --list-secret-keys --keyid-format=long
  /Users/hubot/.gnupg/secring.gpg
  ------------------------------------
  sec   4096R/Copiar-este-código 2016-03-10 [expires: 2017-03-10]
  uid                          Hubot 
  ssb   4096R/42B317FD4BA89E7A 2016-03-10
  ```
- Copiar el código.
- Reemplazar el código en este comando:
- ```
  $ gpg --armor --export Reemplazar-el-código 
  # Prints the GPG key ID, in ASCII armor format
  ```
- Copiar todo el código, desde...
  ```
  -----BEGIN PGP PUBLIC KEY BLOCK----- 
  ```
  hasta...
  ```  
  -----END PGP PUBLIC KEY BLOCK-----
  ```
- Pegar en GitHub.