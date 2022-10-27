> # INSTALACIÓN Y ACTUALIZACIÓN DE PIP PARA TERMUX🏴‍☠️

# AUTOR Y CREADOR:
## https://github.com/Wiich-Crack-Hack/pip-install-update

# 🏴‍☠️
### En este Repositorio les dire como instalar de manera correcta el Comandó "pip"
### Además les enseñare a usar diferentes comandos y versiones "pip"
### Es algo Básico sobre "pip" pero de mucha importancia y funcionalidad.
# 🏴‍☠️

> # TU GESTOR DE PAQUETES ES 'PIP' ? SI LO ES, ENTONCES ESTO ES PARA TI😎
# 🏴‍☠️
### SI NO LO ES NO TE PREOCUPES IGUAL TE SERVIRÁ MUCHO APRENDER UN 
### POCO SOBRE "pip" YA QUE ES INDISPENSABLE PARA EL USO Y EJECUCIÓN
### ADECUADO DE MUCHOS SCRIPTS-HERRAMIENTAS EN TERMUX-ANDROID
# 🏴‍☠️

> # 👍 INSTALAR "pip" DE MANERA CORRECTA
### CON EL SIGUIENTE COMANDO VAN A INSTALAR DE MANERA CORRECTA Y 
### ADECUADA "pip" ADEMAS DE ACTUALIZAR A LA ÚLTIMA VERSIÓN 
# 🏴‍☠️
# 💲 pip install --upgrade pip

# 🏴‍☠️

## Les tiene que aparecer la última versión que es la siguiente 
### pip 22.3 from /data/data/com.termux/files/usr/lib/python3.10/site-packages/pip (python 3.10) 
### Si les salio esa versión o una mas actual lo hicieron bien de lo contrario verifiquen de nuevo.
# 🏴‍☠️

> # ✅  MOSTRAR, VERIFICAR Y COMPROBAR "PIP" EN PANTALLA 
### Vamos a utilizar como complemento -V para mostrar, verificar y comprobar la
### versión actual de PIP esto segun la Versión que busquemos mostrar y verificar
### ya sea pip, pip2, pip3 tal cual se los muestro en el siguiente ejemplo.
## 💲pip -V 

## 💲pip2 -V

## 💲pip3 -V
# 🏴‍☠️

> # ✅ ACTUALIZACIÓN DE "PIP" UTILIZANDO "PIP"
### UNA DE LAS UNICAS Y MEJORES MANERAS PARA ACTUALIZAR "PIP" ES
### UTILIZAR EL COMANDO "PIP" EN SI MISMO APLICANDO LO SIGUIENTE < install -U pip >

## 💲pip2 install -U pip
## 💲pip3 install -U pip
# 🏴‍☠️

> # ✅ ACTUALIZAR PAQUETE A LA ÚLTIMA VERSIÓN 
### Quieres actualizar un paquete en específico con PIP a la última versión?
### Entonces debes ejecutar el siguiente comando:

# > pip install -U  «Nombre del Paquete»
### Veamos un ejemplo para actualizar el paquete Flask:

## 💲 pip install -U flask

### La función de este comando sera actualizar el paquete a la última
### versión ademas de hacerlo también con sus dependencias,
### Solamente siempre y cuando asi lo requieran sus dependencias.
# 🏴‍☠️

> # ✅ ACTUALIZAR UN PAQUETE PERO NO SUS DEPENDENCIAS...

### AHORA QUE SI LO QUE NECESITAS ES ACTUALIZAR SOLO UN PAQUETE Y NO 
### QUIERES ACTUALIZAR LAS DEPENDENCIAS, APLICAMOS EL SIGUIENTE FLAG
### O ESPECIFICACIÓN  < --no-deps >

## 💲 pip install -U --no-deps flask
# 🏴‍☠️

> # ✅ ACTUALIZAR EN GENERAL TODOS LOS PAQUETES...

### POR EL MOMENTO 'PIP' NO CUENTA CON ALGUNA OPCIÓN PARA LLEVAR A CABO
### UNA ACTUALIZACIÓN DE TODAS LAS DEPENDENCIAS EN GENERAL.

### PEROOO TENGAN EN CUENTA QUE EXISTE UNA MANERA DE ACTUALIZAR TODAS LAS
### DEPENDENCIAS DE NUESTRO PROYECTO, TERMINAL O APLICACIÓN.
### Y PARA ESO VAS A EJECUTAR EL COMANDO QUE TE DEJARE A CONTINUACIÓN...

### 💲 pip list --outdated --format=freeze | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U
# 🏴‍☠️
### YA CON LA EJECUCIÓN DE ESTE COMANDO LOGRARAN ACTUALIZAR A
### LA ÚLTIMA VERSIÓN DISPONIBLE...SOLO DEBEN TENER EN CUENTA UN DICHO
### MUY POPULAR RELACIONADO A ESTO EL CUAL ES...

> # "EL QUE MUCHO ABARCA, POCO APRIETA" 😉

#### APOYEN MI REPOSITORIO DEJANDO UNA ⭐ Y COMPARTIENDOLO TAMBIÉN.

#### LES DEJARE EL LINK O ENLACE A MI CANAL DE YOUTUBE PARA QUE VEAN ALGUNOS DE MIS VIDEOS Y QUIZAS ALGUNO LES SOLUCIONE ALGUNOS PROBLEMAS QUE TIENEN CON TERMUX... https://youtube.com/channel/UCnksqirHwe0R2-aBnYt2KMw SUSCRIBANSE A MI CANAL Y DENLE 👍 A MIS VIDEOS SIEMPRE Y CUANDO SEAN DE SU AGRADO ✅👍😉😎🏴‍☠️






