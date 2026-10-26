# Fantasy Capital — beta funcional
Web/PWA estática y responsive compatible con iPhone, Android y escritorio.

## Publicar en GitHub + Vercel
1. En GitHub: New repository > `fantasy-capital` > Create repository.
2. En el repositorio: Add file > Upload files; arrastra TODOS los archivos de esta carpeta a la raíz. Haz Commit.
3. En Vercel: Add New > Project > Import Git Repository > `fantasy-capital`.
4. Framework Preset **Other**, Root Directory `./`, sin comandos Build ni variables de entorno. Deploy.
5. Prueba el enlace que te entregue Vercel. No hay una URL preasignada.
6. iPhone: Safari > Compartir > Añadir a pantalla de inicio. Android: Chrome > menú > Instalar aplicación (si aparece).

## Datos
No existe conexión automática a Mister MD. Los registros iniciales son solo una muestra parcial de vídeos del 26/10/2026. CSV compatible con columnas `nombre;posicion;valor;variacion` y valores enteros en euros. Los datos introducidos se guardan en localStorage del dispositivo (no hay sincronización entre dispositivos). La simulación de ventas no opera sobre cuentas reales.

## Próximos hitos
Fuentes de datos autorizadas, captura de precios con histórico fiable, Supabase + autenticación y sincronización multi-dispositivo, análisis deportivo y financiero, importación asistida de vídeos, iconos PNG de alta compatibilidad.
