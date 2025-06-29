# M2AE7 - ABP7

1. Se creo la carpeta y se inicio repositorio Git
```bash
git init
```
2. Verificar el estado del repositorio
```bash
git status
```

3. Crear archivo contenidos.txt con contenido inicial
```bash
echo "Módulo : Orientación al perfil y metodología del curso" > contenidos.txt
echo "Módulo : Fundamentos de Desarrollo Web" >> contenidos.txt
echo "Módulo : Lenguaje de Consultas a una Base de Datos" >> contenidos.txt
```

4. Verificar contenido del archivo
```bash
cat contenidos.txt
```

5. Ver tamaño y permisos
```bash
ls -lh contenidos.txt
ls -l contenidos.txt
```

6. Añadir archivo al repositorio
```bash
git add contenidos.txt
```

7. Hacer primer commit
```bash
git commit -m "Primera versión del temario subida a repositorio"
```

8. Agregar nueva línea al final
```bash
echo "Módulo 4: Desarrollo de aplicaciones web dinámicas" >> contenidos.txt
```

9. Verificar cambios pendientes
```bash
git status
git diff
```

10. Agregar y hacer nuevo commit
```bash
git add contenidos.txt
git commit -m "Versión actualizada del contenido"
```

11. Ver registro de cambios
```bash
git log --oneline
```

12. Validar estado final
```bash
git status
```
13. Se realiza

14. Se sube imagenes de como se realizo

![Paso 1](img/001.png)
![Paso 2](img/002.png)
![Paso 3](img/003.png)