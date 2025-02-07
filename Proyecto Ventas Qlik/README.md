
# **Dashboard de Ventas con Qlik Sense**

Este proyecto muestra un análisis interactivo de ventas basado en datos ficticios, utilizando **PostgreSQL** como base de datos y **Qlik Sense** para la visualización. Es ideal para explorar el potencial de las herramientas de BI en la toma de decisiones estratégicas.

---

## **Estructura del Proyecto**

```
dashboard-ventas-qlik/
├── data/                 
│   ├── venta.csv                   # Datos ficticios de ventas
│   ├── clientes.csv                # Información de clientes
│   └── sucursales.csv              # Información de sucursales
├── scripts/              
│   ├── crear_tablas.sql            # Script para crear tablas en PostgreSQL
│   ├── cargar_datos.sql            # Script para cargar datos ficticios
│   └── consultas_ejemplo.sql       # Consultas SQL utilizadas para el análisis
├── screenshots/          
│   ├── dashboard_principal.png     # Captura del dashboard principal
│   └── modelo_datos.png            # Diagrama del modelo de datos
├── dashboard_ventas.qvf            # Archivo del dashboard Qlik Sense
└── README.md                       # Documentación del proyecto
```

---

## **Tecnologías Utilizadas**
- **Qlik Sense**: Para la creación de dashboards interactivos y análisis de datos.
- **PostgreSQL**: Base de datos relacional para almacenar y gestionar los datos.
- **CSV**: Formato para almacenar los datos ficticios antes de cargarlos en la base de datos.

---

## **Configuración del Proyecto**

### **Requisitos Previos**
1. **Qlik Sense** instalado en tu máquina.
2. **PostgreSQL** configurado con una base de datos lista para cargar los datos.
3. Archivos CSV disponibles en la carpeta `data/`.

### **Pasos para Configurar**
1. **Crea las tablas en PostgreSQL**:
   - Usa el script `scripts/crear_tablas.sql` para crear las tablas necesarias.
2. **Carga los datos**:
   - Ejecuta el script `scripts/cargar_datos.sql` para insertar los datos ficticios.
3. **Conecta Qlik Sense a PostgreSQL**:
   - Crea una conexión en Qlik Sense utilizando las credenciales de tu base de datos.
4. **Importa el archivo `dashboard_ventas.qvf` en Qlik Sense**:
   - Accede al panel de control y sube el archivo.

---

## **Características del Dashboard**

- **Ventas por Año**: Visualización de la cantidad de ventas entre 2015 y 2020.
- **Ingresos Totales**: Muestra el ingreso acumulado del año 2020.
- **Producto Estrella**: Identifica el producto más vendido.
- **Análisis por Canal de Venta**: Participación de ventas online, telefónicas y presenciales.
- **Mapa Interactivo**: Visualiza ventas por sucursales en distintas ubicaciones.

---

## **Capturas de Pantalla**

**Vista Principal del Dashboard**  
![Dashboard Principal](screenshots/dashboard_principal.png)

**Modelo de Datos**  
![Modelo de Datos](screenshots/modelo_datos.png)

---

## **Conclusiones**

- El canal online lidera las ventas con un **44.8%** del total.
- El **producto estrella** es "Pad para Mouse Fellowes con Gel", con **42,975 unidades vendidas**.
- Las sucursales con mayor volumen de ventas están en **Buenos Aires** y **Rosario**.

---

## **Próximos Pasos**

- Agregar nuevas métricas para evaluar la rentabilidad por producto.
- Implementar segmentación por categorías de clientes.

---

## **Contacto**

- Si tienes preguntas o sugerencias, no dudes en escribirme:  
  [Santino](https://www.linkedin.com/in/santino-giampietro/)  
  ✉️ Email: santinogiampietro7@gmail.com  
