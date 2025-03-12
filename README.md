# Guía de instalación de UltiMaker Cura

UltiMaker Cura es un software gratuito y fácil de usar para la impresión 3D, confiado por millones de usuarios. Permite ajustar finamente tus modelos 3D con más de 400 configuraciones para obtener los mejores resultados de corte e impresión.

## Archivos para el taller

**Primera impresión**: https://www.thingiverse.com/thing:327753

**Impresión con soportes**: https://www.thingiverse.com/thing:1376811

## Índice

- [Requisitos del sistema](#requisitos-del-sistema)
- [Instalación en Windows](#instalación-en-windows)
- [Instalación en macOS](#instalación-en-macos)
- [Instalación en Linux](#instalación-en-linux)

## Requisitos del sistema

Antes de comenzar la instalación, asegúrate de que tu sistema cumple con los requisitos mínimos.

**Tarjeta gráfica**: Compatible con OpenGL 2; se recomienda OpenGL 4.1 para la vista en 3D de las capas.​

**Resolución de pantalla**: 1024 x 768 píxeles.​

**Procesador**: Intel Core 2 o AMD Athlon 64.​

**Memoria RAM**: 550 MB disponibles.

## Instalación en Windows

1. **Descarga**: Visita la página oficial de UltiMaker Cura y descarga el instalador para Windows.​ (https://ultimaker.com/es/software/ultimaker-cura/)

2. **Ejecución del instalador**: Una vez descargado, localiza el archivo en tu carpeta de descargas y haz doble clic para ejecutarlo.​

3. **Asistente de instalación**:

    Acuerdo de licencia: Lee y acepta los términos del acuerdo de licencia para continuar.​
    Ubicación de instalación: Elige la carpeta donde deseas instalar el programa o utiliza la ubicación predeterminada.​
    Componentes adicionales: Selecciona si deseas instalar complementos o configuraciones adicionales según tus necesidades.​

4. **Finalización**: Tras completar la instalación, puedes iniciar UltiMaker Cura desde el acceso directo en el escritorio o desde el menú Inicio.

## Instalación en macOS

1. **Descarga**:

    Accede a la página oficial de UltiMaker Cura.​ (https://ultimaker.com/es/software/ultimaker-cura/)
    En la sección de descargas, encontrarás diferentes versiones del instalador para macOS:​
        MacOS-x64.dmg: Para Macs con procesadores Intel.
        MacOS-ARM64.dmg: Para Macs con procesadores Apple Silicon (M1, M2 y posteriores).
    Selecciona el archivo que corresponda a la arquitectura de tu Mac y descárgalo.​

2. **Montaje de la imagen**:

    Una vez completada la descarga, localiza el archivo .dmg en tu carpeta de descargas y haz doble clic para montar la imagen de disco.​

3. **Instalación**:

    Se abrirá una ventana que mostrará el contenido de la imagen de disco.​
    Arrastra el icono de UltiMaker Cura a la carpeta Aplicaciones para copiar el software a tu sistema.​

4. **Ejecución inicial**:

    Navega a la carpeta Aplicaciones y haz doble clic en el icono de UltiMaker Cura para iniciar el programa.​
    La primera vez que ejecutes el software, macOS puede mostrar una advertencia indicando que la aplicación se descargó de internet. Haz clic en "Abrir" para continuar.​

## Instalación en Linux

1. **Descarga**:

   Visita la página oficial de UltiMaker Cura (https://ultimaker.com/es/software/ultimaker-cura/) y descarga el archivo .AppImage correspondiente a la versión más reciente.
   
3. **Asigna permisos de ejecución**:

   Abre una terminal y navega hasta el directorio donde descargaste el archivo.​
   Otorga permisos de ejecución al archivo con el siguiente comando:
     ```bash
     chmod +x UltiMaker-Cura-<versión>.AppImage
     ```
    Reemplaza <versión> con la versión específica del archivo descargado.
     
4. **Ejecución**:

   En la misma terminal, ejecuta el archivo con:
   ```bash
   ./UltiMaker-Cura-<versión>.AppImage
   ```

   Si encuentras problemas al ejecutar el .AppImage, asegúrate de tener instaladas las dependencias necesarias, como fuse y libnss3.

   ```bash
   sudo apt update
   sudo apt install fuse libnss3
   ```

   
