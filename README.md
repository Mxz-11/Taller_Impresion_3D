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

# Contactarnos
Max: alu.167442@usj.es
Jorge: alu.139992@usj.es


# UltiMaker Cura Installation Guide

UltiMaker Cura is a free and easy-to-use 3D printing software, trusted by millions of users. It allows you to finely adjust your 3D models with over 400 settings to achieve the best slicing and printing results.

## Workshop Files

### First Print
[Thingiverse Link](https://www.thingiverse.com/thing:327753)

### Printing with Supports
[Thingiverse Link](https://www.thingiverse.com/thing:1376811)

## Index

- [System Requirements](#system-requirements)
- [Installation on Windows](#installation-on-windows)
- [Installation on macOS](#installation-on-macos)
- [Installation on Linux](#installation-on-linux)

## System Requirements

Before starting the installation, ensure that your system meets the minimum requirements.

### Graphics Card
- OpenGL 2 compatible; OpenGL 4.1 recommended for 3D layer view.

### Screen Resolution
- 1024 x 768 pixels.

### Processor
- Intel Core 2 or AMD Athlon 64.

### RAM
- 550 MB available.

## Installation on Windows

### 1. Download
Visit the official [UltiMaker Cura website](https://ultimaker.com/software/ultimaker-cura/) and download the Windows installer.

### 2. Run the Installer
Once downloaded, locate the file in your downloads folder and double-click to run it.

### 3. Installation Wizard
- **License Agreement**: Read and accept the terms of the license agreement to proceed.
- **Installation Location**: Choose the folder where you want to install the program or use the default location.
- **Additional Components**: Select if you want to install add-ons or additional configurations based on your needs.

### 4. Completion
After the installation is complete, you can launch UltiMaker Cura from the desktop shortcut or the Start menu.

## Installation on macOS

### 1. Download
- Visit the official [UltiMaker Cura website](https://ultimaker.com/software/ultimaker-cura/).
- In the downloads section, you will find different versions of the macOS installer:
  - **MacOS-x64.dmg**: For Macs with Intel processors.
  - **MacOS-ARM64.dmg**: For Macs with Apple Silicon processors (M1, M2, and later).
- Select the file corresponding to your Mac's architecture and download it.

### 2. Mount the Disk Image
Once the download is complete, locate the `.dmg` file in your downloads folder and double-click to mount the disk image.

### 3. Installation
- A window displaying the disk image contents will open.
- Drag the UltiMaker Cura icon to the Applications folder to copy the software to your system.

### 4. Initial Launch
- Navigate to the Applications folder and double-click the UltiMaker Cura icon to start the program.
- The first time you run the software, macOS may display a warning indicating that the application was downloaded from the internet. Click **Open** to continue.

## Installation on Linux

### 1. Download
Visit the official [UltiMaker Cura website](https://ultimaker.com/software/ultimaker-cura/) and download the `.AppImage` file corresponding to the latest version.

### 2. Grant Execution Permissions
- Open a terminal and navigate to the directory where you downloaded the file.
- Grant execution permissions to the file using the following command:
  ```bash
  chmod +x UltiMaker-Cura-<version>.AppImage
  ```
- Replace `<version>` with the specific version of the downloaded file.

### 3. Run the Software
- In the same terminal, execute the file with:
  ```bash
  ./UltiMaker-Cura-<version>.AppImage
  ```
- If you encounter issues running the `.AppImage`, ensure you have the necessary dependencies installed, such as `fuse` and `libnss3`:
  ```bash
  sudo apt update
  sudo apt install fuse libnss3
  ```

## Contact Us
- **Max**: [alu.167442@usj.es](mailto:alu.167442@usj.es)
- **Jorge**: [alu.139992@usj.es](mailto:alu.139992@usj.es)

