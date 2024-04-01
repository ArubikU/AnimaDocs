---
description: A continuación tendrás el temario de todos los tutoriales y explicaciones que verás en esta guía.
---

# INICIANDO EN TOWNY, Crear desde cero y permisos

1. **Cómo crear un Towny de cero**
2. **Permisos estándarPermisos estándar y su manera de cambiarlos**
3. **Categorías de personas**

### **Survival RPG**

​**Survival RPG** es la modalidad de nuestro servidor que se divide en Ciudades. Cada ciudad, es un Towny (puede variar).\&#x20

En caso de que seas parte de un Towny, dependiendo el rango que tengas en la misma tendrás acceso a más o a menos comandos.Los comandos de Town funcionan para todo tipo de TOWN, sus variantes dependen siempre de la cantidad de residentes que tenga.

<details>

<summary>Click aquí para ver las variantes</summary>

Campamento (1 residente), asentamiento (5 residentes), Tribu (10 Residentes), Villa (15 residentes), Ciudad pequeña (20 residentes), Ciudad (35 residentes), Ciudad grande (50 residentes), Metrópolis (80 residentes)

</details>

#### COMANDOS TOWN <a href="#comandos-town" id="comandos-town"></a>

**Como crear un TOWN desde cero.**

**Todos los comandos que sean “/town \[...]” pueden simplificarse con “ /t \[...] “ en su lugar.**\&#x20

**/town new “nombre de la ciudad ”**: creas una ciudad con el nombre elegido (Costo $7500)\&#x20

**/town claim:** Para reclamar un chunk como parte de tu TOWN. (Para ver un chunk pulsar F3 + G), según vayas comprando más chunks el precio irá subiendo.\&#x20

**/town set homeblock**: establece el bloque home de tu ciudad (necesario para designar un spawn de ciudad)\&#x20

**/town deposit “#####”**: Depositas la cantidad de dinero indicada a la ciudad.\&#x20

**/town whithdraw “#####”**: sacas el dinero indicado de tu ciudad.\&#x20

**/town delete**: eliminas la ciudad (rango requerido alcalde o subalcalde)\&#x20

**/town toggle public on/off**: Haces la town pública o privada. (Esto hará que la gente pueda tepearse a su SPAWN (si está pública) o enviarte una solicitud para unirse a ella. (si está pública))\&#x20

**/town set mapcolor**: establece el color de tu ciudad en el mapa\&#x20

**/town invite “nick**”: invitas al jugador indicado a tu town. \[Recuerda que él debe aceptar con /aceptar]\&#x20

**/plot forsale “####”**: Pones un chunk (en el que estés parado en ese momento) a la venta para que tus habitantes puedan comprarlo y vivir allí.\&#x20

**/plot notforsale**: El chunk en el que estás parado dejará de estar a la venta para vivir.\&#x20

**/town claim outpost**: claimea un outpost separado de tu ciudad

#### Permisos estándar <a href="#permisos-estandar" id="permisos-estandar"></a>

**Como el TOWN está recién creado, los permisos de cada habitante serán estándar. En un inicio los habitantes tendrán los cuatro permisos principales activados en todos los chunks que formen parte de tu TOWN, sin importar su rango o si algún chunk está disponible para comprar (para vivir allí, por ejemplo). Los cuatro permisos son:**

**Build ( Construir), Destroy (Destruir), Switch (Interactuar, o sacar y poner cosas de cofres, etc) como lo puede ser con puertas, botones, mesas de cartografía, pistones, shulkers, cofres , ItemUse (Usar tiems) como esquilar ovejas, reproducir animales, tirar pociones, huevos, perlas de ender, poner lava, etc. Todos los chunks se configuran individualmente.**

Puedes chequear estos permisos con **/town**.\&#x20

Para modificarlos se pondrá:

**/Plot set perm “categoría” Build/switch/destroy/itemuse** **on/off**\&#x20

En donde dice **“categoría**” podremos **resident** , que sería residente. y en donde dice **Build/switch/destroy/itemuse** deberemos colocar solo una de las cuatro opciones, al igual que **on** **off** , solo se debe elegir una. afirmativa (**on**) o negativa (**off**).\&#x20

\
**Ejemplos:**\&#x20

**/Plot set perm resident Build on** : para que los residentes tengan permiso a construir en ese chunk.Más ejemplos aquí

**/t set perm on/off**: Para sacar o poner permisos a TODAS las categorías en TODAS las areas. Comando habilitado para la TOWNY (no es necesario ponerlo chunk por chunk) y solo válido para alcaldes.

#### **CATEGORÍAS DE PERSONAS** <a href="#categorias-de-personas" id="categorias-de-personas"></a>

**Resident:** (Residente) Personas que pertenecen a la ciudad.\&#x20

**Outsider**: (Extranjero) Persona que NO pertenece a la ciudad.\&#x20

**Ally:** (Aliados) Personas dentro de una nation. (Nation es cuando dos Towns o más se unen para hacer una alianza)\&#x20

**Friends:** (Amigos). Esta categoría se usa POR PERSONA (no como el resto) y sirve para agregar personas a tus plots. **CUIDADO** si le otorgas este permiso a un usuario, no tendrá permiso únicamente en el plot en el que estás parado. Tendrá permisos en TODAS tus plots (chunks).​
