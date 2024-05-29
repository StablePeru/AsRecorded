
# AsRecordedAPP

## Descripción

**AsRecordedAPP** es una aplicación de gestión de diálogos y toma de datos que facilita la organización y edición de información en hojas de Excel. Esta aplicación está construida utilizando PyQt5 para la interfaz gráfica de usuario y Pandas para la manipulación de datos en Excel.

## Características

- Cargar y visualizar hojas de Excel.
- Filtrar y buscar personajes y diálogos.
- Marcar intervenciones como completas.
- Editar y guardar cambios directamente en el archivo de Excel.
- Navegación fácil entre diferentes tomas y personajes.

## Estructura del Proyecto

```plaintext
AsRecordedAPP/
├── datahandler/
│   ├── __init__.py
│   ├── data_handler.py
│   ├── data_validator.py
│   ├── excel_handler.py
│   └── exceptions.py
├── gui/
│   ├── __init__.py
│   ├── main_window.py
│   ├── main_widget.py
│   ├── gidoia_widget.py
│   ├── character_filter_dialog.py
│   ├── custom_widgets.py
│   └── utils.py
├── resources/
│   └── main.css
├── PreparacionExcel/
│   ├── Excel/
│   │   └── Excel de ejemplo
│   ├── scripts/
│   │   ├── CrearTxt.py  # Crea un txt adecuado para el programa con el word de referencia
│   │   └── PandasGuion.py  # Crea el xlsx usando el txt de referencia
│   ├── Txt/
│   │   └── Txt de ejemplo  # Recomendado como plantilla para trabajar con el programa
│   └── Word/
│       └── Word de ejemplo  # Específico del programa usado en la empresa
├── main.py
└── README.md
```

## Instalación

1. Clona este repositorio:

    ```sh
    git clone https://github.com/StablePeru/AsRecorded.git
    cd AsRecordedAPP/AsRecordedAPP_1.2
    ```

2. Crea y activa un entorno virtual (opcional pero recomendado):

    ```sh
    python -m venv venv
    source venv/bin/activate  # En Windows: .\venv\Scripts ctivate
    ```

3. Instala las dependencias:

    ```sh
    pip install -r requirements.txt
    ```

## Uso

1. Ejecuta la aplicación:

    ```sh
    python main.py
    ```

2. Usa la interfaz para cargar y editar archivos de Excel, navegar entre tomas y personajes, y marcar intervenciones como completas.

## Contribuir

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del proyecto.
2. Crea una nueva rama (`git checkout -b feature/nueva-caracteristica`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añadir nueva característica'`).
4. Haz push a la rama (`git push origin feature/nueva-caracteristica`).
5. Abre un Pull Request.

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).

## Contacto

Para cualquier pregunta o sugerencia, por favor contacta a stableperu@gmail.com.
