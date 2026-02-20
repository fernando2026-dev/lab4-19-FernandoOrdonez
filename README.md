# lab4-19-FernandoOrdonez
trabajo4 
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("=====Ejercicio 1=====");

        //Datos de la nave
        string modelo = "NASA";
        int capacidadCarga = 3000;
        float nivelCombustible = 80.5f;
        bool motorSaltoActivo = true;

        //Mostrar los datos de la neve en ua sola linea 
        Console.WriteLine("Modelo: " + modelo +
                  " | Capacidad: " + capacidadCarga +
                  " | Combustible: " + nivelCombustible + "%" +
                  " | Motor de salto activo: " + motorSaltoActivo);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 2=====");

        //expancion de memoria 
        short sensoresActivos = 128;
        int registroProcesador;

        registroProcesador = sensoresActivos;

        double precisionTotal = registroProcesador;

        Console.WriteLine("Precisión total: " + precisionTotal);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 3=====");

        double energiaGenerada = 987.65;
        int energiaLimitada;

        energiaLimitada = (int)energiaGenerada;

        Console.WriteLine("Energia generada: " + energiaGenerada);
        Console.WriteLine("Energia limitada (entero): " + energiaLimitada);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 4=====");

        Console.WriteLine("Ingrese la distancia al planeta mas cercano");
        string entradaRadar = Console.ReadLine();

        int distancia = int.Parse(entradaRadar);
        int resultadoFinal = distancia + 100;

        Console.WriteLine("Distancia con margen de seguridad: " + resultadoFinal);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 5=====");

        string señalOxigeno = "true";
        bool oxigenoActivo = Convert.ToBoolean(señalOxigeno);

        string temperaturaCabina = "22.8";

        double temperatura = Convert.ToDouble(temperaturaCabina);

        Console.WriteLine("Estado del oxigeno: " + oxigenoActivo);
        Console.WriteLine("Temperatura de la cabina: " + temperaturaCabina);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 6=====");

        double velocidadLuz = 299792.458;

        string velocidad = velocidadLuz.ToString();
        Console.WriteLine("Velocidad sin formato: " + velocidad);

        string velocidadFormateada = velocidadLuz.ToString("N3");
        Console.WriteLine("Velocidad formateada: " + velocidadFormateada);

        Console.WriteLine();

        Console.WriteLine("=====Ejercicio 7=====");

        Console.Write("Ingrese el Precio por Galón de Litio: ");
        string precioTexto = Console.ReadLine();

        double precio = Convert.ToDouble(precioTexto);
        double impuesto = precio * 0.12;

        double total = precio + impuesto;
        int totalFinal = (int)total;

        Console.WriteLine("El costo final de suministro es: " + totalFinal);
    }
}

