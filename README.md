# practica1_253239

Parte 2
¿Hubo algún error? No
¿Alguna advertencia? No
¿Algo en la consola que avisara? Nada

Parte 3 
¿Cuál comando revisa y cuál ejecuta?
npx tsc --noEmit revisa los tipos pero no corre nada
node multas.ts ejecuta el código tal cual sin revisar tipos sin corregir errores

parte 6
PS C:\Users\luise\OneDrive\Documentos\practica1_253239\multas> npx tsc --noEmit
multas.ts:31:15 - error TS2345: Argument of type 'string' is not assignable to parameter of type 'Prestamo'.
31 calcularMulta("no soy un prestamo");

PS C:\Users\luise\OneDrive\Documentos\practica1_253239\multas> npx tsc --noEmit
multas.ts:31:22 - error TS2339: Property 'fechaDevolucion' does not exist on type 'Prestamo'.
31 console.log(prestamo.fechaDevolucion);

PS C:\Users\luise\OneDrive\Documentos\practica1_253239\multas> npx tsc --noEmit
multas.ts:31:59 - error TS2322: Type '"perdido"' is not assignable to type 'EstadoPrestamo'.
31 const otroPrestamo: Prestamo = { multa: 100, ejemplar: 5, estado: 'perdido' };
                                                             ~~~~~~
  multas.ts:6:3
    6   estado: EstadoPrestamo;
        ~~~~~~
    The expected type comes from property 'estado' which is declared here on type 'Prestamo'


Found 1 error in multas.ts:31
