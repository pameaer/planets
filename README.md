# Proyecto Final Bioinformática 2024

Este repositorio contiene el proyecto final de Bioinformática 2024 de Pamela Enriquez.

## Instrucciones para Generar una Filogenia

Para generar una filogenia utilizando IQ-TREE, utiliza el siguiente script en Git Bash desde el directorio `DATA/iqtree-2.0.6-Windows`:

```bash
./iqtree2.exe -s SecuenciasAlineadas.aln-fasta -B 1000

```bash
# Aquí va tu script o comandos
./iqtree2.exe -s SecuenciasAlineadas.aln-fasta -B 1000

### 3. Guardar y Salir del Editor

Guarda los cambios en el archivo `README.md` y luego cierra el editor de texto. En `nano`, por ejemplo, puedes presionar `Ctrl + O` para guardar y `Ctrl + X` para salir.

### 4. Añadir y Hacer Commit de los Cambios

Después de editar el archivo `README.md`, vuelve a Git Bash y añade los cambios al área de staging y realiza un commit para guardarlos en tu repositorio local:

```bash
git add README.md
git commit -m "Agrega script y documentación al README.md"

