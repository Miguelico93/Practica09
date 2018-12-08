# Practica09

## Auditoría de seguridad en WordPress

## Introducción

En esta practica vamos a utilizar una herramienta para escanear nuestra pagina de wordpress ya creada en una practica anterior con vagrant.
Para ello haremos uso de una máquina creada de ubuntu.

## Crear máquina de ubuntu con vagrant

Lo que vamos a necesitar es el box de ubuntu/bionic y crearemos el directorio donde ira almacenada la máquina.
Tenemos que crear el archivo vagrantfile indicando el nombre de la maquina que vamos a crear por lo que dentro del vagrantfile indicaremos
la siguiente configuración:

```
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/bionic64"
end
```
