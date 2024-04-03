---
description: >-
  ​Survival RPG es la modalidad de nuestro servidor que se divide en Ciudades.
  Cada ciudad, es un Towny En caso de que seas parte de un Towny, dependiendo el
  rango que tengas en la misma, tendrás acceso
---

# Primeros Pasos

## Variantes del Town

| Nombre         | Residentes |
| -------------- | ---------- |
| Campametento   | 1          |
| Asentamiento   | 5          |
| Tribu          | 10         |
| Villa          | 15         |
| Ciudad Pequeña | 20         |
| Ciudad         | 35         |
| Ciudad Grande  | 50         |
| Metrópolis     | 80         |

## Comandos de Towny

Todos los comandos con prefix 'town', pueden ser reducidos a sólo 't'

| Prefix | Argumento     | Value    | Detalles                                                                                     |   |
| ------ | ------------- | -------- | -------------------------------------------------------------------------------------------- | - |
| /town  | new           | string   | Tiene un valor de 7500 monedas                                                               |   |
| /town  | claim         |          | Reclama un chunk como parte de tu town. Es posible verlos con F3 + G                         |   |
| /town  | set homeblock |          | Crea el spawn de tu Town                                                                     |   |
| /town  | deposit       | number   | Deposita dinero en la cuenta de la ciudad, necesario para mantener la protección de la misma |   |
| /town  | whithdraw     | number   | Retira dinero depositado en la cuenta de la ciudad                                           |   |
| /town  | delete        |          | Destruye la ciudad                                                                           |   |
| /town  | toggle public | on / off | Permite a las personas teletransportarse a tu ciudad                                         |   |
| /town  | set mapcolor  | on / off | Establece el color de la ciudad en el mapa                                                   |   |
| /town  | invite nick   | string   | Invita un jugagador a la Town                                                                |   |
| /town  | forsale       | number   | Estable un precio de venta de un chunk a los residentes                                      |   |
| /town  | notforsale    | number   | Retira la venta de un chunk                                                                  |   |
| /town  | claim outpost |          | Reclama un chunk separado de la ciudad                                                       |   |

## Permisos Básicos y Cómo Modificarlos

En un inicio los habitantes tendrán los cuatro permisos principales activados en todos los chunks que formen parte de su Town, sin importar su rango o si algún chunk está disponible para comprar.

1. Build: Contruir
2. Destroy: Destruir
3. Switch: Interactuar con objetivos como, cofres y shulkers
4. ItemUse: Usar items como las tijeras, perlas de ender

{% hint style="info" %}
**Info**: Todos los chunks se configuran individualmente.
{% endhint %}

Puedes usar el comando

| Prefix | Argumento    | Value         | Detalles                                                                      |
| ------ | ------------ | ------------- | ----------------------------------------------------------------------------- |
| /plot  | set perm rol | on / off perm | La 'rol' es el tipo de habitante y 'perm' es el permiso que se desea conceder |
| /plot  | set perm     | on / off perm | Válido sólo para el Alcande                                                   |

## Roles del Town

**Resident**: Personas que pertenecen a la ciudad.

**Outsider**: Personas que NO pertenecen a la ciudad.

**Ally**: Personas dentro de una [nación](nations.md).

**Friends**: Esta categoría se usa POR PERSONA y sirve para agregar personas a tus plots.

{% hint style="warning" %}
**Advertencia:** concede permiso a toda la Town, no sólo a plot en la que estés parado
{% endhint %}
