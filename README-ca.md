Básico

Aprende Bash básico. En realidad, escriba man bash al menos hojee todo el asunto; es bastante fácil de seguir y no tan largo. Los shells alternativos pueden ser agradables, pero Bash es poderoso y siempre está disponible (aprender solo zsh, fish, etc., aunque es tentador en su propia computadora portátil, lo restringe en muchas situaciones, como usar servidores existentes).
Aprende bien al menos un editor basado en texto. El nano editor es uno de los más simples para la edición básica (abrir, editar, guardar, buscar). Sin embargo, para el usuario avanzado en una terminal de texto, no hay sustituto para Vim ( vi), el editor difícil de aprender pero venerable, rápido y con todas las funciones. Mucha gente también usa el clásico Emacs, particularmente para tareas de edición más grandes. (Por supuesto, es poco probable que cualquier desarrollador de software moderno que trabaje en un proyecto extenso use solo un editor basado en texto puro y también debe estar familiarizado con los IDE y las herramientas gráficas modernas).

Búsqueda de documentación:

Sepa cómo leer la documentación oficial man(para los curiosos, man man man enumera los números de sección, por ejemplo, 1 son comandos "regulares", 5 son archivos/convenciones y 8 son para administración). Encuentre páginas man con apropos.
Sepa que algunos comandos no son ejecutables, sino incorporados en Bash, y que puede obtener ayuda sobre ellos con helpy help -d. Puede averiguar si un comando es un ejecutable, un shell incorporado o un alias usando type command.
curl cheat.sh/commanddará una breve "hoja de trucos" con ejemplos comunes de cómo usar un comando de shell.
Obtenga información sobre la redirección de salida y entrada usando >y <y canalizaciones usando |. Know >sobrescribe el archivo de salida y lo >>agrega. Más información sobre stdout y stderr.

Aprenda sobre la expansión global de archivos con *(y tal vez ?y [... ]) y las comillas y la diferencia entre comillas "simples y dobles. '(Vea más sobre la expansión variable a continuación).

Familiarícese con la gestión de trabajos de Bash: &, ctrl-z , ctrl-c , jobs, fg, bg, kill, etc.

Conozca ssh, y los conceptos básicos de la autenticación sin contraseña, a través ssh-agentde , ssh-add, etc.

Administración básica de archivos: lsy ls -l(en particular, aprenda lo que significa cada columna ls -l), , lessy ( o incluso mejor, ), y (aprenda las diferencias y ventajas de los enlaces duros frente a los blandos), , , (para un resumen rápido del disco uso: ). Para la gestión del sistema de archivos, , , , , . Aprende qué es un inodo ( o ).headtailtail -fless +Flnln -schownchmoddudu -hs *dfmountfdiskmkfslsblkls -idf -i

Gestión básica de la red: ipo ifconfig, dig, traceroute, route.

Aprenda y utilice un sistema de gestión de control de versiones, como git.

Conozca bien las expresiones regulares y las diversas banderas para grep/ egrep. Vale la pena conocer las opciones -i, -o, -v, -A, -By .-C

Aprenda a usar apt-get, o yum( según la distribución) para buscar e instalar paquetes. Y asegúrese de tener que instalar herramientas de línea de comandos basadas en Python (algunos a continuación son más fáciles de instalar a través de ).dnfpacmanpippip
