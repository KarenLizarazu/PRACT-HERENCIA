# Ejecución de un Archivo C# en Visual Studio Code

## Requisitos Previos

- Visual Studio Code
- .NET SDK
- Extensión C# Dev Kit

## Pasos para Crear y Ejecutar un Proyecto

### 1. Crear un Nuevo Proyecto

```bash
dotnet new console -n NombreDelProyecto
cd NombreDelProyecto

2. Escribir Código
Abre Program.cs y añade el siguiente código:
csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("¡Hola, Mundo!");
        }
    }
}

3. Ejecutar el Proyecto
Puedes ejecutar tu aplicación usando uno de los siguientes métodos:
Desde la terminal:
bash
dotnet run

Desde el menú de Visual Studio Code: Ejecutar > Ejecutar sin depuración.