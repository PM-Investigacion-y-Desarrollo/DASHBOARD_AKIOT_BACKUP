# DASHBOARD AKIOT BACKUP
Respaldo oficial (JSON) de los dashboards de AKIOT Professional. 📊 Este repositorio almacena la configuración JSON de los cuadros de mando principales y sus componentes para las industrias clave: Farmacéutica (FARMA), Petróleo y Gas (OIL AND GAS), Clima (WEATHER), y Agro y Alimentación (AGRO Y FOOD). El objetivo es asegurar una recuperación rápida y completa de las visualizaciones ante cualquier eventualidad, garantizando la continuidad operativa y el monitoreo geográfico de dispositivos (mapas) por tipo de cliente.

**Importante**: Este repositorio solo almacena el template del dashboard (la estructura y diseño). El dashboard no funcionará correctamente si se eliminan o modifican los siguientes elementos en ThinkBoard: Activos, Dispositivos, Atributos (de cliente o servidor), Cadenas de Reglas, Integraciones o Usuarios.

## Instructivo: Restaurar Dashboard en ThinkBoard desde JSON

Este proceso te permite recrear un dashboard completo (diseño, widgets, configuración) usando el archivo JSON de respaldo.

**Prerrequisito Clave**: Antes de importar, asegúrate de que todos los Activos, Dispositivos, Atributos, y Cadenas de Reglas a los que hace referencia el dashboard ya existen en tu instancia de ThinkBoard. Si no existen, el dashboard se importará, pero los widgets mostrarán errores de datos.

**Paso 1**: En paneles hacer click en +

<img width="700" height="544" alt="Clipboard_09-30-2025_01" src="https://github.com/user-attachments/assets/32e0a7f0-4088-415c-b1a9-2b19cb06733b" />

**Paso 2**: Importar nuevo panel

<img width="400" height="213" alt="image" src="https://github.com/user-attachments/assets/c3ede4e0-dfe6-4acf-9b61-5352f37c2e2d" />

**Paso 3**: Navegar fichero

<img width="602" height="397" alt="image" src="https://github.com/user-attachments/assets/93a47925-385b-4eb0-90ba-0eca8078892c" />

**Paso 4**: Elegir archivo JSON

<img width="600" height="536" alt="image" src="https://github.com/user-attachments/assets/38879fa7-0b49-47d8-91bf-f387c5f31f66" />

**Paso 5**: Finalmente importar y probar el dashboard. Si los activos, dispositivos, etc no son modificados entonces el dashboard funciona correctamente.

**Importante**: Lo unico que no se conseva del dashboard importado son los grupos.


