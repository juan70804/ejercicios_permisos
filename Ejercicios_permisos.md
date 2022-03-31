
# Ejercicios de los permisos de Linux

## 1 - Te encuentras navegando por los archivos **home** de tu computadora y mediante el comando **ls -lh** visualizas los permisos que tienen algunos archivos que de encuentran en el directorio de descargas

 ```bash
-rwx------ 1 juanc juanc 837K mar 27 03:32 informefinal.txt
-rwx------ 1 juanc juanc 934K mar 27 03:32 proteasa.pdb
```

### Despues de visualizar las autorizaciones se te ocurre modificar el fichero de informefinal.txt ¿Es posible realizar alguna modificación?

### **Respuesta**

```bash
Si es posible, ya que presentamos permisos de lectura, escritura y ejecución como propietario, es por ello que podemos realizar modificaciones en los dos ficheros mostrados anteriormente.
```

## 2 - Imagina que logras ingresar al escritorio de Roberto con el usuario Paulo (que no forma parte del grupo Solaria) y visualizas lo siguiente con el comando ls -l 

 ```bash
-rwxr-x--- 1 Roberto Solaria 536K feb 19 00:00 primerparcial.md
```

### Supongamos que deseas mover primerparcial.md a un dispositivo USB como usuario Paulo ¿Puedes hacerlo de acuerdo con las autorizaciones proporcionadas?

### **Respuesta**

```bash
No, el usuario Paulo pertenece a la categoría "otros", que no tiene ningún permiso en el fichero indicado. Es por ello que no podrá mover el archivo propuesto.
```

### Sistema binario 
# ![imagen1](imagenes/sistemabinario.png "Sistema binario")






