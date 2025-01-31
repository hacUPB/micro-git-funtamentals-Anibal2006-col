# Repositorio remoto 
![alt text](download.png)  

1. **Conectar el repositorio local con el remoto**:
Agrega un archivo al repositorio (opcional, pero recomendable):  
`touch README.md`  
`echo "# Mi Proyecto" > README.md`  
2. **Agrega los archivos al área de preparación (staging)**:  
`git add .`  

3. **Confirma los cambios con un commit**:   
`git commit -m "Primer commit: estructura inicial"`

4. **Conecta el repositorio local con el remoto usando la URL copiada de GitHub**:  
`git remote add origin https://github.com/usuario/nombre-repositorio.git` 

5. **Verifica que el remoto fue agregado correctamente**:
`git remote -v`  
Esto debería mostrar las conexiones del repositorio remoto.  
6. **Subir los archivos al repositorio remoto**:    
Si es la primera vez que subes archivos y usas la rama main, cambia el nombre de la rama local (si es necesario)    
`git branch -M main`  
7. **Sube los archivos al repositorio remoto en GitHub**:
`git push -u origin main`  
`-u` establece la rama `main` como predeterminada para futuros git push.  

