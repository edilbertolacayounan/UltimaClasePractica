# UltimaClasePractica
Ultima clase practica control de verision, generar grafico

Mision, clonar el repo, en una carpeta nueva.
generar una rama "desarrollo"
de la rema desarrollo crear otra rama con tu nombre
agrega dos archivos en blanco a tu rama proyecto.py, proyecto.md
crea cambios en ambos archivos, debes agregar tus nombres, apellidos, grupo, año, fecha y hora actual.
subir los nuevos cambios


usando los comandos git log --oneline --graph --all
 --oneline → Muestra cada commit en una sola línea (más compacto).
 --graph → Dibuja un gráfico ASCII con las ramas y sus uniones.
 --all → Incluye todas las ramas, no solo la actual.
genera el grafico que represente las ramas
investiga de ser necesario.

haz una captura de pantalla al grafico de la rama y subelo a tu rama.




1. comandos y ejemplos
Abre tu proyecto en la terminal
Ubícate en la carpeta raíz de tu repositorio con:

cd ruta/de/tu/repositorio

2. Usa git log con opciones de gráfico
El comando más usado es:
git log --oneline --graph --all
- --oneline → Muestra cada commit en una sola línea (más compacto).
- --graph → Dibuja un gráfico ASCII con las ramas y sus uniones.
- --all → Incluye todas las ramas, no solo la actual.

Ejemplo de salida:

* commit1 (HEAD -> main)
| * commit2 (feature-branch)
|/
* commit3


3. Añade más detalles si lo necesitas
Si quieres ver autor y fecha además del gráfico:
bash
git log --graph --all --decorate --pretty=oneline
- --decorate → Muestra etiquetas y ramas asociadas a cada commit.
- --pretty=oneline → Mantiene el formato compacto.


4. Visualización más clara
Si el gráfico en ASCII se ve muy cargado, puedes usar:
 gitk  
  gitk --all
  
  --Abre una ventana gráfica con todas las ramas.

- tig (instalable en Linux/Mac)  
    tig --all
    Muestra un gráfico navegable en la terminal.

5. Tip extra
Si solo quieres ver cómo se bifurcan las ramas sin tanto detalle:
git log --graph --oneline --decorate


En resumen: el comando clave es git log --oneline --graph --all, y si quieres algo más visual puedes usar gitk o tig.  
