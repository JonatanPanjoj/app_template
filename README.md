# Instrucciones

### Clonar el repositorio original:
Esto clonará solo la última versión del repositorio, sin el historial completo. 
```
git clone --depth 1 https://github.com/tu-usuario/tu-repositorio.git  
```  
### Eliminar la referencia al repositorio original:
Esto quitará la conexión con el repositorio original. Ahora, si ejecutas git remote -v, no deberías ver ninguna URL asociada.
```  
cd tu-repositorio
git remote remove origin
```   


### Crear un nuevo repositorio en tu plataforma (por ejemplo, en GitHub).

Ve a GitHub
Crea un nuevo repositorio vacío.
Asocia tu repositorio clonado con el nuevo repositorio en línea: Esto establecerá una nueva conexión remota con tu nuevo repositorio.
``` 
git remote add origin https://github.com/tu-usuario/tu-nuevo-repositorio.git
``` 


### Sube tu código al nuevo repositorio:

``` 
git push -u origin master
Esto enviará tu código al nuevo repositorio en línea.
``` 

Ahora, tendrás un repositorio clonado que no apunta al repositorio original, y puedes usarlo como una plantilla.


# Dependencies
google_fonts,
go_router,
flutter_riverpod,
easy_localization,

## Assets
``` 
  assets:
    - assets/img/
    - assets/translations/
``` 
