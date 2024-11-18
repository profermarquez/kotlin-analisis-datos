#  Instalación del Kotlin Kernel en jupyter notebook
# Fuente del Dataframe
https://github.com/Kotlin/dataframe/blob/master/examples/notebooks/netflix/netflix_titles.csv

# Crear un entorno virtual y activarlo
virtualenv env
/env/Scripts/activate


# instalar rust compiles, java compile y kotlin compiler
- https://www.rust-lang.org/tools/install
- https://www.oracle.com/java/technologies/downloads/#jdk23-windows
- kotlin-compiler-2.0.21.zip de https://github.com/JetBrains/kotlin/releases/tag/v2.0.21



# Configurar todos los path de los compiladores instalados
set PATH=%USERPROFILE%\.cargo\bin;%PATH%
set PATH=E:\java\bin;%PATH%
set PATH=E:\kotlinc\bin;%PATH%

# verificar las versiones
javac --version
kotlinc -version 
cargo -V

# instalar jupyter-notebook y el kernel de kotlin
pip install notebook
pip install kotlin-jupyter-kernel

# Interoperabilidad de kotlin y java
Ambos lenguajes se ejecutan en la JVM (Java Virtual Machine), lo que significa que Kotlin compila a bytecode, igual que Java, además puedes usar herramientas como javac, jar o cualquier entorno Java para ejecutar o empaquetar aplicaciones Kotlin.




