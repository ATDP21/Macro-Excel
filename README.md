# Macro-Excel
Este es el resultado de un proyecto que trataba de automatizar un proceso lento y tedioso que ejercian 3 a 4 trabajadores diariamente. 
Se destinó y es usado hoy en día en la empresa que trabaja mi hermano que fue quien me hizo la petición, me explicó los requisitos y me apoyó. 


En esta gran empresa gestora de plantas fotovoltaicas el problema venía de datos segundo a segundo de diferentes inversores (dispositivos 
electrónicos que convierten la energía continua a energía alterna de los paneles solares) que estaban dando problemas ya que estos paraban
bruscamente o reducian su producción cuando no debían. Esta salida de energía está regulada para proporcionar X Kw/s, en caso de no necesitarse
por un momento el requisito se reduce o cae a 0. Comprobando entonces la tabla en el segundo específico del parón del inversor se podía saber
si estaba justificado por regulación o fue un parón accidental del inversor, lo cual causa perdidas importantes ya que se dá en muchos inversores 
y de varias plantas muy grandes. Entonces anterior a mi programa los trabajadores debían encontrar el parón del inversor en X segundo y buscar en X 
segundo de la tabla de regulación y documentar a mano si estaba justificado el parón, de qué segundo a qué segundo ocurrió todo y en que inversor, 
toda una tortura viendo que se trataban de 49600 filas que contaba documentado un inversor y la regulación cada uno al día (se ignora la franja de 
la noche).


Gracias a esta automatización la empresa pudo asignar y ampliar las funciones de los trabajadores, por lo que pasaron de 3 a 4 personas documentando
parones justificados o injustificados a recoger además datos de irradiancia (cumplido después por mi programa), para estudiar si los parones ocurrían 
a razón de picos de radiación solar, todo con un solo clic y un fácil recorte de tablas en 15 min por un solo trabajador.

    ____________________________________________________________________________________________________________________________

Para probar la Macro hay que quitar una configuración de seguridad sobre el uso de macros viniendo de terceros, no se tarda nada, y la Macros se puede analizar, 
está documentada y limpiada, solo hay que presionar Alt + F11 estando con el Excel abierto, pondré un .txt con la Macro extraida para transparencia. Si se quiere 
probar bien además se debería borrar el ejemplo de incidencias, y darle al botón de Iniciar en la pestaña "Incidencias", tarda en cargar y se bloquea el Excel por
unos segundos, pondrá que no responde, pero a lo máximo de un par de minutos lo carga todo.


*Datos de inversores:*

<img width="1167" height="985" alt="image" src="https://github.com/user-attachments/assets/940c179d-e9ab-4090-8df4-04ae8287a1a6" />



*Datos de regulación:*

<img width="1199" height="993" alt="image" src="https://github.com/user-attachments/assets/a5644524-56ba-4e23-9a50-46e3aa11bf6a" />



*Datos de irradiancia:*

<img width="573" height="1015" alt="image" src="https://github.com/user-attachments/assets/a22c152d-04fe-400d-b2e2-3c7bd0e97d51" />



*Datos procesados por programa de incidencias de haber sido justificadas o no, la empresa necesita los dos datos, ordenados por inversores:*

<img width="1407" height="1021" alt="image" src="https://github.com/user-attachments/assets/de7f3c3b-f11c-4812-8005-adadca971133" />



