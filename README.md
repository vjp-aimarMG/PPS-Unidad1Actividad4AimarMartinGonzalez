# PPS-Unidad1Actividad4AimarMartinGonzalez

1. Lo primero que haremos será descar **Firejail** ya que es la herramienta que he elegido para este ejercicio, para ello usaremos el comando **sudo apt install firejail**
![](/img/1.png)
2. Lo siguiente que haremos será abrir nuestro archivo de python, para ello primero tendremos que comprobar que tenemos **python3** descargar, y después con el comando **firejail python3 nombre_archivo** abriremos nuestro archivo con firejail. Hay que tener en cuenta que lo he ejecutado como usuario normal ya que como root no me funcionaba 
![](/img/2.png)
3. Una vez hemos comprobado que se ejecuta correctamente abriremos **firejail configuration** para monitorear lo que sucede, en nuestro caso lo haremos desde un terminal
![](/img/3.png)
4. Podemos observar que ya estaría monitoreando lo que hemos abierto
![](/img/4.png)
5. Podemos monitorear lo que ocupa de CPU, memoria, incluso los archivos que utiliza
![](/img/5.png)
6. Por último ejecutamos la calculadora hasta terminar el proceso y observaremos que en firejail se eliminará lo que nos salía anteriormente
![](/img/6.png)