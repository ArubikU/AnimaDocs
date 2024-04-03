---
description: >-
  ​Survival RPG es la modalidad de nuestro servidor que se divide en Ciudades. Cada ciudad, es un Towny

  En caso de que seas parte de un Towny, dependiendo el rango que tengas en la misma, tendrás acceso a más o a menos comandos. Los comandos de Town funcionan para todo tipo de Town, sus variantes dependen siempre de la cantidad de residentes que tenga
---
## Survival RPG

### Variantes del Town

<table>
<!-- ! Caption no es Reconocido por GitBook -->
  <caption>Variantes del Town</caption>
  <thead>
    <tr>
      <th>Nombre</th>
      <th>Residentes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Campametento</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Asentamiento</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Tribu</td>
      <td>10</td>
    </tr>
    <tr>
      <td>Villa</td>
      <td>15</td>
    </tr>
    <tr>
      <td>Ciudad Pequeña</td>
      <td>20</td>
    </tr>
    <tr>
      <td>Ciudad</td>
      <td>35</td>
    </tr>
    <tr>
      <td>Ciudad Grande</td>
      <td>50</td>
    </tr>
    <tr>
      <td>Metrópolis</td>
      <td>80</td>
    </tr>
  </tbody>
</table>

### Comandos de Towny

Todos los comandos con prefix 'town', pueden ser reducidos a sólo 't'

<table>
<!-- ! Caption no es Reconocido por GitBook -->
  <caption>Comandos</caption>
  <thead>
    <tr>
      <th>Prefix</th>
      <th>Argumento</th>
      <th>Value</th>
      <th>Detalles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/town</td>
      <td>new</td>
      <td>string</td>
      <td>Tiene un valor de 7500 monedas</td>
    </tr>
    <tr>
      <td>/town</td>
      <td>claim</td>
      <td></td>
      <td>Reclama un chunk como parte de tu town. Es posible verlos con F3 + G</td>
      <!-- TODO Estaría bien mejorar el plugin para que muestre la zona reclamada -->
    </tr>
    <tr>
      <td>/town</td>
      <td>set homeblock</td>
      <td></td>
      <td>Crea el spawn de tu Town</td>
    </tr>
    <tr>
      <td>/town</td>
      <td>deposit</td>
      <td>number</td>
      <td>Deposita dinero en la cuenta de la ciudad, necesario para mantener la protección de la misma</td>
    </tr>
    <tr>
      <td>/town</td>
      <td>whithdraw</td>
      <td>number</td>
      <td>Retira dinero depositado en la cuenta de la ciudad<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>delete</td>
      <td></td>
      <td>Destruye la ciudad<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>toggle public</td>
      <td>on / off</td>
      <td>Permite a las personas teletransportarse a tu ciudad<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>set mapcolor</td>
      <td>on / off</td>
      <td>Establece el color de la ciudad en el mapa<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>invite nick</td>
      <td>string</td>
      <td>Invita un jugagador a la Town<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>forsale</td>
      <td>number</td>
      <td>Estable un precio de venta de un chunk a los residentes<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>notforsale</td>
      <td>number</td>
      <td>Retira la venta de un chunk<td>
    </tr>
    <tr>
      <td>/town</td>
      <td>claim outpost</td>
      <td></td>
      <td>Reclama un chunk separado de la ciudad<td>
    </tr>
  </tbody>
</table>


### Permisos Básicos y Cómo Modificarlos

En un inicio los habitantes tendrán los cuatro permisos principales activados en todos los chunks que formen parte de su Town, sin importar su rango o si algún chunk está disponible para comprar. 

1. Build: Contruir
2. Destroy: Destruir
3. Switch: Interactuar con objetivos como, cofres y shulkers
4. ItemUse: Usar items como las tijeras, perlas de ender
 
{% hint style="info" %}
**Info**: Todos los chunks se configuran individualmente.
{% endhint %}

Puedes usar el comando
<table>
  <thead>
    <tr>
      <th>Prefix</th>
      <th>Argumento</th>
      <th>Value</th>
      <th>Detalles</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>/plot</td>
      <td>set perm rol</td>
      <td>on / off perm</td>
      <td>La 'rol' es el tipo de habitante y 'perm' es el permiso que se desea conceder</td>
    </tr>
    <tr>
      <td>/plot</td>
      <td>set perm</td>
      <td>on / off perm</td>
      <td>Válido sólo para el Alcande</td>
    </tr>
  </tbody>
</table>

### Roles del Town

**Resident**: Personas que pertenecen a la ciudad.

**Outsider**: Personas que NO pertenecen a la ciudad.

**Ally**: Personas dentro de una [nación](/.gitbook/assets/category/guide/towny/details/nations.md).

**Friends**: Esta categoría se usa POR PERSONA y sirve para agregar personas a tus plots. 

{% hint style="warning" %}
**Advertencia:** concede permiso a toda la Town, no sólo a plot en la que estés parado
{% endhint %}
