# Macro-Excel
Este es el resultado de un proyecto que trataba de automatizar un proceso lento y tedioso que ejercian 3 a 4 trabajadores diariamente. 
Se destinó y es usado hoy en día en la empresa que trabaja mi hermano que fue quien me hizo la petición, me explicó los requisitos y me apoyó. 


En esta gran empresa gestora de plantas fotovotaicas el problema venía de datos segundo a segundo de diferentes inversores (dispositivos 
electrónicos que convierten la energía continua a energía alterna de los paneles solares) que estaban dando problemas ya que estos paraban
bruscamente o reducian su producción cuando no debían. Esta salida de energía está regulada para proporcionar X Kw, en caso de no necesitarse
por un momento el requisito se reduce o cae a 0. Comprobando entonces la tabla en el segundo específico del parón del inversor se podía saber
si estaba justificado por regulación o fue un parón accidental del inversor, lo cual causa perdidas importantes ya que se dá en muchos inversores 
y de una planta muy grande. Entonces anterior a mi programa los trabajadores debían encontrar el parón del inversor en X segundo y buscar en X 
segundo de la tabla de regulación y documentar si estaba justificado el parón, de qué segundo a qué segundo ocurrió todo y en que inversor, 
toda una tortura viendo que se trataban de 49600 filas que contaba documentado un inversor y la regulación cada uno al día (se ignora la 
franja de la noche).


Gracias a esta automatización la empresa pudo asignar y ampliar las funciones de los trabajadores, por lo que pasaron de 3 a 4 personas documentando
parones justificados o injustificados a recoger además datos de irradiancia, para estudiar si los parones ocurrian a razón de picos de radiación solar, 
todo con un solo clic y un recorte de tablas en 15 min por un solo trabajador.
