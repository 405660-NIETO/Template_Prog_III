# Template de Proyecto para Programacion III

---

## Atajos
   - [Informacion](#informacion)
   - [Guia](#Guia-de-Instalacion)

---

![Rider](/img/inicioRd.png "Creacion de un proyecto en Rider")
![Visual Studio](/img/inicioVs.png "Creacion de un proyecto en Visual Studio")

---

## Informacion

### ¿Que es un Template?

Un template literalmente es una forma de inicio precargada con contenido para la creacion de un proyecto.
Por ejemplo cuando creamos un proyecto del tipo API desde 0 tenemos templates de `Weather Forectast` completo con Class y Controller
Que luego eliminamos para crear el proyecto.

Para crear un proyecto nuevo de .NET se necesita especificar que tipo de proyecto es y seleccionar alguna especie de template para iniciar

Los templates de Api como ejemplo que usan el `Weather Forecast` son creados por Microsoft mismo para dar un ejemplo de como es el proyecto.

De la misma forma se crea el template de `Programacion III`

### ¿Para que sirve el Template?

El template sirve para **ganar tiempo** durante la creacion de un proyecto, evitando tener que descargar los mismos paquetes *nuget* de siempre y enfocando nuestra atencion en el desarrollo del modelo Controller/Service/Repository y rapido Scaffolding.

## Guia de Instalacion

`1) Ir a la carpeta donde se descargo el repositorio`

![Folder](/img/folder.png "Carpeta contenedora")

`2) Click en un lugar vacio y abrir la terminal`

![Click](/img/open.png "Abrir la terminal de windows en este directorio")

`3) Instalar el template mediante el siguiente comando`

```powershell
dotnet new --install .
```

![Command](/img/command.png "Comando de instalacion")

`Una vez instalado aparece este mensaje`

![Mensaje](/img/installed.png "Instalado")

`Verificar instalacion en la lista de templates de .NET`

![ListCmd](/img/listCom.png "Comando para ver listado")

```powershell
dotnet new --list
```

![Lista](/img/list.png "Lista de templates")

---

### Creacion de un proyecto de prueba

![Ejemplo](/img/peek.png "Proyecto de ejemplo")