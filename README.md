# Custom Branding Apache Guacamole

### Customização do Apache Guacamole

#### Requisitos

- `sudo apt install zip unzip`

- Apache Guacamole

#### Diretórios

- default: padrão do apache

- imagens: customiza (favicon e logo)

- reziped: sua customização já zipada

- work: área de trabalho

#### Como customizar

- Em **/work/tranlations** se encontra as strings usadas no app (customiza palavras chaves)

- Em **/work/images** se encontra as imagens usadas no app

- Deve-se após realizar as alterações no diretório **work** zipar novamente o diretório com o nome **guacamole.war**

- Após isso substitua **/var/guacamole/guacamole.war** pelo zip alterado

- `sudo systemctl restart guacd`
