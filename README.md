# **INSTRUCTIVO DE INSTALACIÓN**

## **VIRTUALBOX**

**https://www.virtualbox.org/wiki/Downloads**

![imagen 1](https://ucarecdn.com/329c3a57-404b-4ccd-afd6-b4ead5f3bfa0/page1_image1.jpg)

### Como se puede observar no se recomienda la instalación de la versión 7.0.16 por lo tanto, se instalará la versión 7.0.14

**https://download.virtualbox.org/virtualbox/7.0.14/VirtualBox-7.0.14-161095-Win.exe**

**Descargar y Ejecutar como administrador**

<br>

## **UBUNTU SERVER 22.04.4 LTS**

**Descargar imagen .ISO de UBUNTU SERVER 22.04.4 LTS**

**https://www.releases.ubuntu.com/**

![imagen 2](https://ucarecdn.com/2d35af7c-4ba9-4624-a118-e4ac7d173a34/page2_image1.jpg)

![imagen 3](https://ucarecdn.com/883a3c7f-2819-4713-9a5c-660d09136187/page2_image2.jpg)

En VirtualBox Añadir nueva máquina virtual

![imagen 4](https://ucarecdn.com/b939793f-b21c-4014-8a3f-b00b530bb0db/page3_image1.jpg)

Damos nombre a la máquina virtual **(BIGDATA)** y buscamos el archivo .iso que acabamos de descargar

![imagen 5](https://ucarecdn.com/29e5f742-f695-423c-8889-2a57bbcd36bf/page3_image1.jpg)

Definimos Contraseña y Repetir contraseña como **bigdata**

![imagen 6](https://ucarecdn.com/885af07e-d01f-4f7a-a128-406bef70614d/page4_image1.jpg)

Configuramos los recursos a asignar a la máquina virtual. **Nota:** No pasarse de lo verde (depende de cada máquina) entre más recursos se asignen más rápida será la máquina virtual.

![imagen 7](https://ucarecdn.com/1edba5cb-4731-45e7-9537-6b36cab0266b/page4_image2.jpg)

Definimos un tamaño de disco virtual, se recomienda 30 GB

![imagen 8](https://ucarecdn.com/c1b5bd32-21fb-4f1e-803e-f4e03378abaf/page5_image1.jpg)

Visualizamos el resumen con la configuración asignada y damos clic en **Terminar**

![imagen 9](https://ucarecdn.com/e415291a-fe32-4d9e-a1a8-1015472d8b64/page5_image2.jpg)

<br>

### **Inicio de la instalación Ubuntu 22.04.4**

Seleccionamos el idioma Español

![imagen 10](https://ucarecdn.com/a038340e-ec71-49f0-b64d-02df789d76fa/page6_image1.jpg)

Si en la instalación nos pide actualizar el instalador, seleccionamos la opción **“Actualizar al instalador nuevo”**

![imagen 11](https://ucarecdn.com/93c43209-e5a0-4193-836a-009369971a2c/page6_image2.jpg)

Configuramos la disposición del teclado

![imagen 12](https://ucarecdn.com/67973864-260a-4dbc-86a0-82bb56bb4b06/page7_image1.jpg)

Seleccionamos el tipo de instalación, dejamos la que viene por defecto.

![imagen 13](https://ucarecdn.com/ee93fd66-3af0-4413-ab9a-ecc2416e6de2/page7_image2.jpg)

Para la configuración de red, dejamos los valores que nos brinda el instalador

![imagen 14](https://ucarecdn.com/d8448ee0-2b47-44a5-9e23-ee00d9815d44/page8_image1.jpg)

En Proxy Address no configuramos nada

![imagen 15](https://ucarecdn.com/b207607f-b9d7-4e6c-b0f3-70ab1efc0331/page8_image2.jpg)

En Mirror address dejamos el valor por defecto

![imagen 16](https://ucarecdn.com/388f41cb-b01b-4c6b-b023-757bec340d42/page9_image1.jpg)

En la configuración de Storage dejamos los valores que nos aparecen por defecto.

![imagen 17](https://ucarecdn.com/f0b5e86c-0bb7-4922-b692-aeaf620af25f/page10_image1.jpg)

Verificamos el resumen del sistema de archivos, el sistema particiona automáticamente: 1 Mb para grub (gestor de arranque), 2Gb (/boot) archivos del kernel, 28Gb resto del sistema

Esto porque se seleccionó al inicio en la configuración de la máquina de VirtualBox un espacio de disco de 30Gb

![imagen 18](https://ucarecdn.com/a1995dc9-5f76-448f-94d8-0b6234655191/page11_image1.jpg)

Seleccionamos continuar

![imagen 19](https://ucarecdn.com/b80afe50-ed74-49b2-a7c8-81a8634a9938/page12_image1.jpg)

Configuramos el perfil de usuario<br>
**Su nombre:** Digite su nombre y apellido<br>
**Your servers name:** bigdata<br>
**Elija un nombre de usuario:** vboxuser<br>
**Contraseña y confirme la contraseña:** bigdata

![imagen 20](https://ucarecdn.com/a61da37a-fdb6-4e0d-a451-cc7ed41cd583/page13_image1.jpg)

Para Ubuntu Pro, dejamos los valores por defecto **(Skip for now)**

![imagen 21](https://ucarecdn.com/294cd97e-ebf5-41f3-be97-b8b76e6b41c0/page13_image2.jpg)

Por ahora, no instalamos el servidor OpenSSH (OpenSSH es una herramienta de conectividad para el inicio de sesión remoto que usa el protocolo SSH)

![imagen 22](https://ucarecdn.com/a21177d8-6d22-44b1-ab77-d2c9135e34eb/page14_image1.jpg)

No seleccionamos ningún paquete adicional

![imagen 23](https://ucarecdn.com/9510535d-56a8-405d-82bf-4d3dec7a803a/page15_image1.jpg)

En este momento se inicia el proceso de instalación, este proceso puede demorar unos minutos, al finalizar damos enter en Reiniciar ahora

![imagen 24](https://ucarecdn.com/814b52f2-feff-48c0-aa4b-64d1b5c27cdc/page16_image1.jpg)

![imagen 25](https://ucarecdn.com/597b74f0-92cb-47cc-9980-f602d56da096/page17_image1.jpg)

En este momento procedemos a dar enter para que aparezca el **login**

![imagen 26](https://ucarecdn.com/b6fcdf5a-f3c2-464d-889a-0cbe88de5977/page18_image1.jpg)

Ingresamos con<br>
**Usuario:** vboxuser<br>
**Password:** bigdata

![imagen 27](https://ucarecdn.com/2af68be3-85b3-4f85-9843-02fecdf67723/page19_image1.jpg)

Ahora para actualizar el sistema **digitamos los siguientes comandos** en la línea de comando:
```
sudo apt-get update
```
**cuando solicite el password for vboxuser:** bigdata

![imagen 28](https://ucarecdn.com/cdc292a1-c0a8-4c3f-b2c2-f0dfc7752c76/page20_image1.jpg)
```
sudo apt-get upgrade
```
![imagen 29](https://ucarecdn.com/5f61fc10-365c-4c32-941c-d84a82d005be/page21_image1.jpg)

Escribimos **S** y damos enter
![imagen 30](https://ucarecdn.com/8f8e68b2-0f73-4189-a469-1d4ff1487f63/page22_image1.jpg)

Seleccionamos **OK** y Enter
![imagen 31](https://ucarecdn.com/7c0ff70c-0745-48a5-8386-562088293360/page22_image2.jpg)

Para realizar actualizaciones pendientes si las hay, **digtamos el siguiente comando.**
```
sudo apt-get dist-upgrade
```
![imagen 32](https://ucarecdn.com/70162a4b-5477-4e15-9792-44621ce5ec55/page23_image1.jpg)

Si hay paquetes a actualizar se debe teclear **S** y luego **enter**, de lo contrario aparecerá la línea de comando

![imagen 33](https://ucarecdn.com/ea0de561-2294-49f6-90cb-2a71cb5a26a9/page23_image2.jpg)

<br>

### **Conexión por SSH (putty) al servidor Ubuntu**

Ingresamos en **Dispositivos** – **Red** – **Preferencias de red**

![imagen 34](https://ucarecdn.com/77e9f140-b94e-4805-900a-814ea856c028/page24_image1.jpg)

Cambiar NAT por adaptador puente y aceptar, luego reiniciar la máquina virtual para que cambie la dirección IP asignada, **se debe seleccionar la tarjeta de red que tenga conectada a internet**

![imagen 35](https://ucarecdn.com/04bd2391-7fe9-4a71-ba45-122742a54117/page25_image1.jpg)

Para reiniciar digitamos **reboot** y damos enter

![imagen 36](https://ucarecdn.com/063dff1a-b0b9-45db-afc9-55a184fa9802/page25_image2.jpg)

Luego de reiniciar, ingresamos nuevamente<br>
**Usuario:** vboxuser<br>
**Password:** bigdata

![imagen 37](https://ucarecdn.com/f19109d6-23dd-4e5a-8824-5ba0482f3ea6/page26_image1.jpg)

Tomar nota de la IP asignada a la máquina virtual, ya que con esta IP nos conectaremos de forma remota. **Nota: hay que tener en cuenta que cada vez que se reinicie la máquina la IP puede cambiar**

![imagen 38](https://ucarecdn.com/96894e66-961a-464a-816e-5d3fdbc94601/page26_image2.jpg)

Descargar putty desde https://the.earth.li/~sgtatham/putty/latest/w64/putty.exe<br>
**Ejecutamos putty.exe**<br>
Colocar la IP de la máquina virtual y dar click en open

![imagen 38](https://ucarecdn.com/eb108ca1-5f51-49dd-924f-4b18d7e1b293/page27_image1.jpg)

Click en **Accept**

![imagen 38](https://ucarecdn.com/0ceb2452-1396-4234-9466-2f0ea762f5ee/page27_image2.jpg)

Ingresamos con el usuario y password de la máquina virtual, con esto tenemos acceso remoto a la consola de la máquina virtual<br>
**Usuario:** vboxuser<br>
**Password:** bigdata

![imagen 38](https://ucarecdn.com/d8429a93-3469-4869-a6ca-62b53a8f7588/page28_image1.jpg)

![imagen 38](https://ucarecdn.com/7dce834a-04d1-4abd-bfef-4c76a5ad30f3/page28_image2.jpg)

**De esta forma tenemos conexión remota por SSH a la consola de nuestra máquina virtual Ubuntu, para copiar y pegar a la consola debemos seleccionar el texto a copiar en el documento o página de origen dar CRTL+C o click derecho y copiar y luego en la consola de putty dar click derecho donde queremos pegar el texto seleccionado.**

<br>

## **INSTALAR HADOOP**

Link de referencia: https://tecadmin.net/how-to-install-apache-hadoop-on-ubuntu-22-04/

Instalar dependencias
```
sudo apt install wget apt-transport-https gnupg2 software-properties-common
```
![imagen 39](https://ucarecdn.com/99eed6db-a44d-41ad-a76a-387867bed594/page29_image1.jpg)

Si solicita Password: **tupassword**

![imagen 40](https://ucarecdn.com/95fc6d96-615c-421f-8335-bd60c8b10de4/page30_image1.jpg)

Si solicita confirmación para la instalación, damos **S** y **enter**

![imagen 41](https://ucarecdn.com/1a13187e-a1dc-4f0b-aafd-b523120b79ee/page30_image2.jpg)

Instalar Java Development Kit
```
sudo apt update && sudo apt install openjdk-11-jdk
```
![imagen 42](https://ucarecdn.com/9edf21a1-4f72-4f1b-80d5-ec48d4d0c399/page31_image1.jpg)

Cuando pregunte si desea continuar, damos **S** y **enter**

Verificamos la versión de java
```
java -version
```
![imagen 43](https://ucarecdn.com/601f7d2f-0684-41ef-bc15-4cc6ec9b1363/page32_image1.jpg)

instalamos openssh por si todavía no está instalado completo
```
sudo apt install openssh-server openssh-client
```
![imagen 44](https://ucarecdn.com/5ba5a5bd-7a0f-4e86-bba4-2388bcde121e/page33_image1.jpg)

Ejecute el siguiente comando para crear un nuevo usuario con el nombre **"hadoop"**:
```
sudo adduser hadoop
```
**Password:** hadoop

En los siguientes campos no digitamos nada, damos enter<br>

Full Name []:<br>
Room Number []:<br>
Work Phone []:<br>
Home Phone []:<br>
Other []:<br>

Para finalizar y confirmar digitamos **Y**

![imagen 45](https://ucarecdn.com/5751261f-f3fd-4373-a3c3-741d69e08383/page34_image1.jpg)

Cambie al usuario de hadoop recién creado:
```
su - hadoop
```
**password:** hadoop

![imagen 46](https://ucarecdn.com/dba9e42e-0777-4a16-b2a8-87dc203cb054/page34_image2.jpg)

Ahora configure el acceso SSH **sin contraseña** para el usuario de hadoop recién creado. Genere primero un par de claves SSH:
```
ssh-keygen -t rsa
```
a las preguntas damos solo **enter**

![imagen 47](https://ucarecdn.com/cc498b37-096e-4375-92a4-8156b43a9fe6/page35_image1.jpg)

Copie la clave pública generada en el archivo de clave autorizada y establezca los permisos adecuados:
```
cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
```
```
chmod 640 ~/.ssh/authorized_keys
```

![imagen 48](https://ucarecdn.com/f4802275-5639-4e9f-8242-83af82920b74/page36_image1.jpg)

Ahora intente SSH en el localhost.
```
ssh localhost
```
Se le pedirá que autentique los hosts agregando claves RSA a hosts conocidos. Escriba **yes** y presione **Enter** para autenticar el localhost

![imagen 49](https://ucarecdn.com/d2f07998-6785-46ae-8976-761eddd3243c/page37_image1.jpg)

Descargamos, descomprimimos hadoop y cambiamos el nombre del directorio, la descarga puede demorar un poco en iniciar
```
wget https://dlcdn.apache.org/hadoop/common/hadoop-3.3.6/hadoop-3.3.6.tar.gz
```
```
tar xzf hadoop-3.3.6.tar.gz
```
```
mv hadoop-3.3.6 hadoop
```

![imagen 50](https://ucarecdn.com/db48bfc1-9a71-4839-b500-8465c1b3ac2a/page38_image1.jpg)

A continuación, deberá configurar Hadoop y Java Environment Variables en su sistema.

Puede encontrar la ubicación JAVA_HOME ejecutando el comando en la terminal.
```
dirname $(dirname $(readlink -f $(which java)))
```

![imagen 51](https://ucarecdn.com/84f4dc58-4711-4428-8d74-abc4b2742d27/page39_image1.jpg)

Abra el archivo ~/.bashrc en su editor de texto favorito
```
nano ~/.bashrc
```

![imagen 52](https://ucarecdn.com/7c2be38a-3db0-4682-9b8e-9843b7176a28/page39_image2.jpg)

Anexe las siguientes líneas al final del archivo.
```
export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
export HADOOP_HOME=/home/hadoop/hadoop
export HADOOP_INSTALL=$HADOOP_HOME
export HADOOP_MAPRED_HOME=$HADOOP_HOME
export HADOOP_COMMON_HOME=$HADOOP_HOME
export HADOOP_HDFS_HOME=$HADOOP_HOME
export HADOOP_YARN_HOME=$HADOOP_HOME
export HADOOP_COMMON_LIB_NATIVE_DIR=$HADOOP_HOME/lib/native
export PATH=$PATH:$HADOOP_HOME/sbin:$HADOOP_HOME/bin
export HADOOP_OPTS="-Djava.library.path=$HADOOP_HOME/lib/native"
```
copiar las líneas y dar **Crtl+O enter** y luego **Crtl+X** para salir

![imagen 53](https://ucarecdn.com/e8b6cba5-184d-4974-8109-e3eb89133cba/page40_image1.jpg)

Cargue la configuración anterior en el entorno actual.
```
source ~/.bashrc
```

![imagen 54](https://ucarecdn.com/3aa549a8-074a-489f-8406-9556002eaad2/page41_image1.jpg)

También debe configurar JAVA_HOME en el archivo hadoop-env.sh. Edite el archivo de variable de entorno de Hadoop en el editor de texto
```
nano $HADOOP_HOME/etc/hadoop/hadoop-env.sh
```

![imagen 55](https://ucarecdn.com/9e739c2d-6c71-4b0b-a7c4-73e05c5baecc/page42_image1.jpg)

Buscar **“export JAVA_HOME”** y configurar se debe quitar el **#** del inicio, debe quedar
```
export JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64
```

![imagen 56](https://ucarecdn.com/95322aa0-c41e-4e65-8641-0a0d461ad798/page43_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

Primero, deberá crear los directorios namenode y datanode dentro del directorio de inicio de usuario de Hadoop. Ejecute el siguiente comando para crear ambos directorios:
```
mkdir -p ~/hadoopdata/hdfs/{namenode,datanode}
```

![imagen 57](https://ucarecdn.com/c5938482-8875-42e6-a510-f7cac5bce350/page44_image1.jpg)

A continuación, edite el archivo **core-site.xml** y actualice con el nombre de host de su sistema
```
nano $HADOOP_HOME/etc/hadoop/core-site.xml
```

![imagen 58](https://ucarecdn.com/cbcede7b-f487-4326-8fc0-49f1641ea346/page45_image1.jpg)

Y agregamos:
```
<configuration>
    <property>
        <name>fs.defaultFS</name>
        <value>hdfs://localhost:9000</value>
    </property>
</configuration>
```

![imagen 59](https://ucarecdn.com/773c6b6e-f764-4757-8e6e-b40f5cc2f492/page46_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

A continuación, edite el archivo hdfs-site.xml
```
nano $HADOOP_HOME/etc/hadoop/hdfs-site.xml
```

![imagen 60](https://ucarecdn.com/03053e26-6293-481b-9ade-e21c37f3309a/page47_image1.jpg)

Y agregamos:
```
<configuration>
<property>
    <name>dfs.replication</name>
    <value>1</value>
</property>
<property>
    <name>dfs.name.dir</name>
    <value>file:///home/hadoop/hadoopdata/hdfs/namenode</value>
</property>
<property>
    <name>dfs.data.dir</name>
    <value>file:///home/hadoop/hadoopdata/hdfs/datanode</value>
</property>
</configuration>
```

![imagen 61](https://ucarecdn.com/59c8e966-cf72-4b16-b8e9-2c3eff148dd1/page48_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

A continuación, edite el archivo **mapred-site.xml**:
```
nano $HADOOP_HOME/etc/hadoop/mapred-site.xml
```

![imagen 62](https://ucarecdn.com/ca81163a-ea1c-4328-a58d-ddc02480b3c5/page49_image1.jpg)

Y agregamos:
```
<configuration>
    <property>
        <name>mapreduce.framework.name</name>
        <value>yarn</value>
    </property>
</configuration>
```

![imagen 63](https://ucarecdn.com/fcf34656-4135-48f9-b862-7e3f3a3f48bd/page50_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

A continuación, edite el archivo **yarn-site.xml**
```
nano $HADOOP_HOME/etc/hadoop/yarn-site.xml
```

![imagen 64](https://ucarecdn.com/199873a5-0ab7-4169-9297-2587d27f491c/page51_image1.jpg)

Y agregamos:
```
<configuration>
    <property>
        <name>yarn.nodemanager.aux-services</name>
        <value>mapreduce_shuffle</value>
    </property>
</configuration>
```

![imagen 65](https://ucarecdn.com/ab02a884-7b2a-4897-94f6-88e6cdac49b2/page52_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

Antes de iniciar el clúster de Hadoop. Deberá formatear el Namenode como usuario de hadoop.

Ejecute el siguiente comando para dar formato al nodo de nombres de Hadoop
```
hdfs namenode -format
```

![imagen 66](https://ucarecdn.com/8ad139d8-993a-4601-a575-fb09b6ddec48/page52_image2.jpg)

Una vez que el directorio namenode se formatee correctamente con el sistema de archivos hdfs, verá el mensaje "El directorio de almacenamiento /home/hadoop/hadoopdata/hdfs/namenode ha sido formateado correctamente".

![imagen 67](https://ucarecdn.com/5272e61e-f797-44be-a135-3bc04b0f4fb9/page53_image1.jpg)

A continuación, inicie el clúster de Hadoop con el siguiente comando
```
start-all.sh
```

![imagen 67](https://ucarecdn.com/1155d185-2b2b-4816-9ec8-2195832f6ed7/page54_image1.jpg)

Una vez iniciados todos los servicios, puede acceder al Hadoop en el navegador de su equipo con la dirección:

**http://IP_MaquinaVrtual:9870**

donde IP_MaquinaVirtual corresponde a la IP de su máquina virtual, en el ejemplo desarrollado en este instructivo la IP de la máquina virtual es 192.168.0.135

**http://192.168.0.135:9870**

![imagen 68](https://ucarecdn.com/4af01b83-7e5d-48b7-89ba-beaefdeaff6f/page55_image1.jpg)

Y la página de la aplicación Hadoop está disponible en http://IP_MaquinaVirtual:8088

donde IP_MaquinaVirtual corresponde a la IP de su máquina virtual, en el ejemplo desarrollado en este instructivo la IP de la máquina virtual es 192.168.0.135

http://192.168.0.135:8088

![imagen 69](https://ucarecdn.com/fa099e18-7312-4bc8-9f31-3c69398f354b/page55_image2.jpg)

<br>

## SPARK

Link de referencia: https://computingforgeeks.com/how-to-install-apache-spark-on-ubuntu-debian/

Volvemos al **usuario vboxuser** con el comando
```
su – vboxuser
```
**Password:** bigdata

![imagen 70](https://ucarecdn.com/d9903cde-5b5f-4840-ab6e-c2e874ea8e61/page56_image1.jpg)

Descargue, descomprima y mueva de carpeta Apache Spark
```
VER=3.5.1
```
```
wget https://dlcdn.apache.org/spark/spark-$VER/spark-$VER-bin-hadoop3.tgz
```

![imagen 71](https://ucarecdn.com/052cb6df-f94a-4035-9b56-e0002c8837b7/page57_image1.jpg)

```
tar xvf spark-$VER-bin-hadoop3.tgz
```

![imagen 72](https://ucarecdn.com/65bb3355-402f-4009-996e-5e241dcc1f3f/page57_image2.jpg)

```
sudo mv spark-$VER-bin-hadoop3/ /opt/spark
```

si solicita password: **bigdata**
![imagen 73](https://ucarecdn.com/85e3d6d1-ab26-4ade-8ccd-953e29f23151/page57_image3.jpg)

Abra el archivo de configuración bashrc
```
nano ~/.bashrc
```

![imagen 74](https://ucarecdn.com/6ea75f78-d0c0-4971-84ee-ee6dde43056d/page58_image1.jpg)

se agrega al final
```
export SPARK_HOME=/opt/spark
export PATH=$PATH:$SPARK_HOME/bin:$SPARK_HOME/sbin
```

![imagen 75](https://ucarecdn.com/fe99cea7-336a-4223-a878-3454ba9e3804/page58_image2.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

Active y cargue los cambios.
```
source ~/.bashrc
```

![imagen 76](https://ucarecdn.com/bc7b9907-41c6-4058-9c1a-e241e30096eb/page59_image1.jpg)

Ahora puede iniciar un servidor maestro independiente mediante el comando
```
start-master.sh
```

![imagen 77](https://ucarecdn.com/9192ca97-9dbf-4232-9f7a-93a0f2ac3748/page59_image2.jpg)

El proceso escuchará en el puerto TCP 8080.
```
sudo ss -tunelp | grep 8080
```

![imagen 78](https://ucarecdn.com/f80008b7-8604-457c-8901-bbeb4f5c1419/page59_image3.jpg)

Abra el navegador web y accede a la interfaz web de Spark utilizando la URL http://IP_MaquinaVirtual:8080

donde IP_MaquinaVirtual corresponde a la IP de su máquina virtual, en el ejemplo desarrollado en este instructivo la IP de la máquina virtual es 192.168.0.135

**http://IP_MaquinaVirtual:8080**

![imagen 79](https://ucarecdn.com/d588ef2b-bd43-4f99-b7ae-65a0cdb05918/page60_image1.jpg)

**Iniciar el proceso de trabajo de Spark**

Como puede ver, el servicio maestro de Spark se está ejecutando en spark:/ bigdata:7077. Así que puede utilizar esta dirección para iniciar el proceso de trabajador de Spark utilizando el siguiente comando:
```
start-slave.sh spark://bigdata:7077
```

![imagen 80](https://ucarecdn.com/fa41c564-998c-41fb-b02a-c7decac5e45d/page60_image2.jpg)

Ahora, vaya al panel de control de Spark y actualice la pantalla. Debería ver el proceso Spark worker

![imagen 81](https://ucarecdn.com/db3cc11d-fbb9-4ab3-b1ad-1811c9c55c78/page61_image1.jpg)

**Ingresar al spark context web UI**

Iniciamos una sesión de trabajo (job) para poder ingresar a la interfaz web de Spark context web UI, para esto utilizamos el siguiente comando
```
pyspark
```

![imagen 82](https://ucarecdn.com/eba5f772-fe82-445e-9020-f1e68124c514/page61_image2.jpg)

NOTA: PARA SALIR DE LA SESION DE SPARK LO HACEMOS MEDIANTE EL COMANDO DE TECLADO **CTRL+D**

Abra el navegador web y accede a la interfaz web de Spark context web UI utilizando la URL **http://IP_MaquinaVirtual:4040**

donde **IP_MaquinaVirtual** corresponde a la IP de su máquina virtual, en el ejemplo desarrollado en este instructivo la IP de la máquina virtual es **192.168.0.135**

**http://192.168.0.135:4040**

![imagen 83](https://ucarecdn.com/06e09779-7907-4bbe-aeb4-be9532f8d899/page62_image1.jpg)

<br>

## EJERCICIO STREAMING OPENSKY

**Instalar PIP**

Para administrar paquetes de software de Python, **instalamos PIP**, una herramienta que ayudará a instalar y administrar bibliotecas o módulos.
```
sudo apt install -y python3-pip
```
Si requiere password: **bigdata**

![imagen 84](https://ucarecdn.com/f09ac1d0-290b-40ce-a342-30a427a85161/page63_image1.jpg)

Instalamos mediante PIP la librería de Python pyspark
```
sudo pip install pyspark
```

![imagen 85](https://ucarecdn.com/4c619302-737a-45c2-98e0-d1e5790c8890/page64_image1.jpg)

**Se crea un archivo de python con extension .py** lo podemos llamar **opensky.py**, donde colocaremos el código del programa que se conectará a la página de opensky network y descargara en formato JSON la información de vuelos registrados en el instante de la consulta, esta información es en tiempo real, luego convertiremos estos datos en un dataframe de Spark y sobre este dataframe se realizarán diferentes operaciones y consultas.
```
nano opensky.py
```

![imagen 86](https://ucarecdn.com/e015065f-051f-4408-afa9-4ffc3a88fdaa/page64_image2.jpg)

Pegamos el siguiente código:
```
#Importamos librerias necesarias
import json
import requests
from pyspark.sql import SparkSession, functions as F
from pyspark.sql.types import *

# Iniciar SparkSession
spark = SparkSession.builder.appName('OpenSky').getOrCreate()
spark.conf.set("spark.max.task.size", "2048")

# Definimos TIMEOUT de la consulta a la pagina de opensky
TIMEOUT = 300 # segundos

# Definimos el esquema con el que se leeran los datos
schema = StructType([
StructField("icao24", StringType()),
StructField("callsign", StringType()),
StructField("origin_country", StringType()),
StructField("time_position", StringType()),
StructField("last_contact", StringType()),
StructField("longitude", StringType()),
StructField("latitude", StringType()),
StructField("baro_altitude", StringType()),
StructField("on_ground", BooleanType()),
StructField("velocity", StringType()),
StructField("true_track", StringType()),
StructField("vertical_rate", StringType()),
StructField("sensors", ArrayType(IntegerType())),
StructField("geo_altitude", StringType()),
StructField("squawk", StringType()),
StructField("spi", BooleanType()),
StructField("position_source", IntegerType())
])

#Nos conectamos a la pagina y obtenemos los datos de vuelos
url = 'https://opensky-network.org/api/states/all'
response = requests.get(url, timeout=TIMEOUT)
data = response.json()

#Creamos el dataframe de spark
df = spark.createDataFrame(data['states'], schema=schema)

#imprimimos el esquema
df.printSchema()

#Mostramos la primera fila del dataframe
df.show(1)

# Contar registros
print("Numero de registros",df.count())
print("\n")

# Número de vuelos
flights = df.select('icao24').distinct().count()
print("Numero de vuelos:", flights)
print("\n")

# Vuelos por país
print("Vuelos por pais\n")
df.groupby('origin_country').count().show()

# Calcular promedio altitud de vuelos por país
print("Promedio altitud de vuelos por país\n")
avg_altitude = df.groupby('origin_country').agg(F.avg('baro_altitude')).orderBy('avg(baro_altitude)',
ascending=False)

# Mostrar resultados
avg_altitude.show()

# Distinct de países
print("Paises de origen de los vuelos\n")
df.select('origin_country').distinct().show()

# Filtrar por país
print("Vuelos cuyo pais de origen es España\n")
df.filter(F.col('origin_country') == 'Spain').show()

# Promedio de altitudes
from pyspark.sql.functions import avg
print("Promedio de altitud\n")
df.select(avg('geo_altitude')).show()

# Max velocidad
print("Velocidad maxima registrada\n")
df.select(df['velocity'].cast('float').alias('velocity')).agg({'velocity': 'max'}).show()

# Consulta: Filtrar por velocidad y seleccionar columnas
print("Vuelos con velocidad mayor a 500\n")
faster = df.filter(F.col('velocity') > 500).select('icao24', 'velocity')
faster.show()
```

![imagen 87](https://ucarecdn.com/c73a87e3-71b3-48a7-b82b-514c72a356ce/page67_image1.jpg)

dar **Crtl+O enter** y luego **Crtl+X** para salir

para ejecutar el archivo ingresamos la siguiente instrucción:
```
python3 opensky.py
```

![imagen 88](https://ucarecdn.com/61101995-ea0b-4231-a048-03c42b2f6bf9/page68_image1.jpg)

Al terminar la ejecución debemos obtener resultados similares a los siguientes:

![imagen 89](https://ucarecdn.com/c03b2f3e-341f-456f-9501-48f0e2d4511a/page68_image2.jpg)

![imagen 90](https://ucarecdn.com/272a9fb1-1b43-45b8-8db7-9285590de03e/page69_image1.jpg)

![imagen 91](https://ucarecdn.com/2b078daa-8722-4245-935b-79fbfdf1261a/page70_image1.jpg)

![imagen 92](https://ucarecdn.com/763e3ae1-f373-42d3-9859-473bff7bf334/page70_image2.jpg)

Si al ejecutar aparece el siguiente error, volvemos a ejecutar la instrucción:
```
python3 opensky.py
```

![imagen 93](https://ucarecdn.com/dcac16a9-ce96-4d3d-a421-14a65fe0bde9/page71_image1.jpg)

Mientras se encuentra en ejecución el script **opensky.py** recargamos la página de la interfaz web de Spark context web UI

![imagen 94](https://ucarecdn.com/f3cbd9fa-1ef7-419f-b67b-532968ba8fef/page71_image2.jpg)


![imagen 95](https://ucarecdn.com/2d187fc9-4ca3-42f8-9f83-f8160a11877f/page72_image1.jpg)


![imagen 96](https://ucarecdn.com/5aedae6b-53da-4eb9-8dee-532bdc3ae66e/page73_image1.jpg)

De esta manera damos por finalizado el componente práctico del curso Big Data - Tarea 4

<br>

## Si te gusto la calidad de este contenido, comparte el enlace de este repositorio para que sea de ayuda para otros como lo fue para ti, saludos y éxitos.

### Enlace del repositorio: https://github.com/TuMyXx93/Instructivo-tarea4.git