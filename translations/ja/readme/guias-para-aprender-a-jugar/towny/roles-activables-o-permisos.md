---
description: A continuación tendrás el temario de todos los tutoriales y explicaciones que verás en esta guía.
---

# Roles, activables o permisos

- **De **<mark style="color:orange;">**residentes**</mark>** en adelante**\
  &#x20;                **Gestionar categorías de personas**\
  &#x20;                **Activables y permisos para tus PLOTS**\
  &#x20;                **INVITAR A ALGUIEN A VIVIR CONTIGO: \[PLOT]**
- **Según rangos**\
  &#x20;                   **Para asistentes**\
  &#x20;                   **Para subalcaldes**\
  &#x20;                   **Para alcalde o alguacil**\
  &#x20;                   **Para constructor**

### <mark style="background-color:blue;">PARA RESIDENTES</mark> (En adelante)

**/plot claim:** Reclamas el chunk (Para ver los chunks **F3 + G**) en donde estás parado para vivir, dependiendo el precio que haya establecido el alcalde tendrás que pagar más o menos dinero. **/plot unclaim**: Dejas de ser el dueño del chunk en el que estás parado. \
**/resident**: Información sobre ti /residente “nick”: Información sobre el usuario indicado.

### <mark style="background-color:green;">GESTIONAR CATEGORÍAS DE PERSONAS EN TUS PLOTS</mark> (Desde residente en adelante)

**/resident friend list**: Ver la lista de amigos que tienes en tus plots (gente que tenga permisos en tus chunks). \
**/resident friend remove “nick”**: Eliminas de amigos a la persona indicada (ya no tendrá permisos en tus plots.) \
**/resident friend add “nick”**: Agregas a la persona indicada a tu chunk como amigo para que pueda vivir en ella. <mark style="color:red;">**CUIDADO**</mark> este comando se activará en todas tus plots.

### <mark style="background-color:green;">ACTIVABLES O PERMISOS PARA TU TOWN</mark> \[PLOT]

Los comandos de plot se activan chunk por chunk (para ver todos los bloques que abarca un chunk debes presionar **F3 + G**) ,\
Estos comandos también tienen <mark style="color:orange;">**modificables**</mark>.\
Estos pueden ser <mark style="color:orange;">**explosions**</mark> (explosiones), <mark style="color:orange;">**fire**</mark> (fuego), <mark style="color:orange;">**mobs**</mark> (mobs como ovejas, caballos, esqueletos, creepers, aldeanos, todo tipo de ser viviente) o <mark style="color:orange;">**pvp**</mark> (Poder golpearse entre usuarios dentro del plot)\
\
**/plot toggle **<mark style="color:orange;">**explosion**</mark> <mark style="color:green;">**on**</mark>**/**<mark style="color:red;">**off**</mark>: activa o desactiva las explosiones en el plot indicado\
**/plot toggle **<mark style="color:orange;">**fire**</mark> <mark style="color:green;">**on**</mark>**/**<mark style="color:red;">**off**</mark>: activa o desactiva los incendios en el plot indicado.\
**/plot toggle **<mark style="color:orange;">**mobs**</mark> <mark style="color:green;">**on**</mark>**/**<mark style="color:red;">**off**</mark>: activa o desactiva los mobs en el plot indicado.\
**/plot toggle **<mark style="color:orange;">**pvp**</mark> <mark style="color:green;">**on**</mark>**/**<mark style="color:red;">**off**</mark>: Activa o desactiva el pvp en el plot indicado.

### <mark style="background-color:green;">**INVITAR A ALGUIEN A VIVIR CONTIGO: \[PLOT]**</mark>

Una vez ya tengas plot (si eres residente) probablemente quieras vivir con alguien, en ese caso, deberás darle permisos en tu plot (debes ir plot por plot, recuerda que plot es cuando un chunk ya es para vivir en él o construir).\
Para ello, deberás añadir a la persona que quieras que viva contigo.

\
**/plot perm add “nick”** : Agregas a la persona indicada a tu Plot.\
**/plot perm gui**: Despliega un menú donde verás quienes tienen permiso (incluido el amigo que acabas de agregar), puedes gestionarlos.

{% hint style="info" %}
**Recuerda**: con **/plot perm gui** también puedes ver quienes tienen permiso en tu plot, no solo gestionar.
{% endhint %}

### <mark style="background-color:blue;">ASISTENTE</mark> (En adelante)

Podrás hacer muchas cosas, incluidas las de constructor o alguacil. \[_Apartado "Alguacil"_]

**/town invite “nick”** : Invitar al usuario indicado a formar parte del TOWN.\
**/town kick user**: Expulsar al residente indicado fuera del TOWN. \
**/town claim**: Reclamar el chunk como parte del TOWN.\
**/town unclaim**: El terreno (chunk) deja de ser parte del TOWN.\
**/t set perm **<mark style="color:green;">**on**</mark>**/**<mark style="color:red;">**off**</mark>: Para sacar o poner permisos a TODAS las <mark style="color:purple;">**categorías**</mark> en TODAS las <mark style="color:blue;">**áreas**</mark>**.** Comando habilitado para la TOWNY (no es necesario ponerlo chunk por chunk) y solo válido para\
alcaldes. \[_Apartado "Permisos estándar"_]\
**/jail “nick”**:  Metes al usuario indicado a la cárcel de tu TOWN.\
**/plot type jail** : El plot donde estás parado se convierte en la cárcel de la ciudad.\
**/plot clear** : Elimina TODOS los carteles del plot. Esto incluye los carteles que privaticen cosas como cofres.

### <mark style="background-color:blue;">SUBALCALDE</mark> (En adelante)

**/town set name “Nombre”**: Cambia el nombre de la ciudad al indicado.

### <mark style="background-color:blue;">ALCALDE</mark>

**/town delete**: Borras la TOWNY entera.

### <mark style="background-color:blue;">ALGUACIL</mark> (Police)

#### Para utilizar este rol primero debes establecer un plot como cárcel.

**/plot type jail**: El plot donde estás parado se convierte en la cárcel de la ciudad.

**/town jail ”resident”**: Metes en la jail al residente indicado.\
**/town unjail “resident”**: Liberas de la cárcel al residente indicado.\
**/town outlaw **<mark style="color:green;">**add**</mark>**/**<mark style="color:red;">**remove**</mark>\*\* “nick”\*\*:  comando que expulsa y prohibe la entrada de al user indicado a la ciudad. Este comando hace que el usuario se vuelva un Outlaw. (Se vuelve un bandido)\
**/town outlaw list**: Para ver quienes son los bandidos de la ciudad.

### \&#x20<mark style="background-color:blue;">CONSTRUCTOR</mark> (Builder)

Cómo builder puedes construir en cualquier plot, incluso si no le pertenecen.\
Los únicos lugares donde **no** puede construir es en propiedades reclamadas por otros usuarios.
