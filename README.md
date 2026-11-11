# Cálculo de números del día · Paso San Sebastián

App web (una sola página, `index.html`) para armar los números diarios del Paso San Sebastián a partir de las fotos del S.I.Ca.M. (Administración de tránsitos → Compañías, entrada y salida).

## Qué hace
1. Lee de cada foto la columna verde **A (Aceptados)**: PARTICULAR (SIN), TAA 7, TAA 27, TDC y TDP. También se pueden cargar a mano.
2. Carga manual de vehículos: autos, camiones argentinos, camiones chilenos y caminantes.
3. Colectivos de Chile y de Argentina, de entrada y de salida, con pasajeros y tripulantes de cada uno.
4. Cuadro de ingresos/egresos (pasajeros, tripulantes, vehículos) y total de personas del día.
5. Grilla para Gendarmería, que se descarga como imagen o se copia como texto.
6. Planilla estadístico mensual, que se descarga como Excel (.xlsx) o se copia como columna para pegar en el Excel mensual.

## Lectura de fotos
En esta versión las fotos se leen con una clave de API de Anthropic, que se carga en la sección "Lectura de fotos". La clave queda guardada solo en el navegador de cada compu y nunca se sube al repositorio. Sin clave, los números se cargan a mano.

Los datos del día se guardan en el navegador de cada compu.

## Instalar
Con el botón **⬇ Instalar app** (arriba de todo) se instala en la compu o en el celular (Chrome, Edge o Android). En iPhone/iPad: Safari → Compartir → "Agregar a pantalla de inicio". Instalada, se abre en su propia ventana y funciona sin conexión, salvo la lectura de fotos.
