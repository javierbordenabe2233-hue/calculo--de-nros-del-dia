# Cálculo de números del día · Paso San Sebastián

App web (una sola página, `index.html`) para armar los números diarios del Paso San Sebastián a partir de las fotos del S.I.Ca.M. (Administración de tránsitos → Compañías, entrada y salida).

## Qué hace
1. Lee de cada foto la columna verde **A (Aceptados)**: PARTICULAR (SIN), TAA 7, TAA 27, TDC y TDP. También se pueden cargar a mano.
2. Carga manual de vehículos: autos, camiones argentinos, camiones chilenos y caminantes.
3. Colectivos de Chile y de Argentina, de entrada y de salida. En cada uno se cargan los pasajeros CON los tripulantes incluidos, y aparte los tripulantes; en los totales se descuentan.
4. Cuadro de ingresos/egresos (pasajeros, tripulantes, vehículos) y total de personas del día.
5. Grilla para Gendarmería, que se descarga en PDF (A4, lista para imprimir) o se copia como texto.
6. Planilla estadístico mensual, que se descarga como Excel (.xlsx) o se copia como columna para pegar en el Excel mensual.

## Lectura de imágenes
- **Capturas de pantalla** (Impr Pant, Win+Shift+S): se leen gratis, sin clave, con un lector que funciona dentro del navegador. Se pueden pegar con Ctrl+V o con el botón "Pegar captura".
- **Word (.docx)**: se puede subir un Word con las dos capturas pegadas. La 1ª imagen va a Entrada y la 2ª a Salida. Si se sube desde el recuadro de Entrada o de Salida y tiene una sola imagen, va a ese lado.
- **Fotos del monitor** (celular): necesitan una clave de API de Anthropic, que se carga en "Lectura de fotos". Si hay clave cargada, se usa para todas las imágenes. La clave queda guardada solo en el navegador de cada compu y nunca se sube al repositorio.

Los datos del día se guardan en el navegador de cada compu.

## Instalar
Con el botón **⬇ Instalar app** (arriba de todo) se instala en la compu o en el celular (Chrome, Edge o Android). En iPhone/iPad: Safari → Compartir → "Agregar a pantalla de inicio". Instalada, se abre en su propia ventana y funciona sin conexión, salvo la lectura de fotos.
