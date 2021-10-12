# Validación de Formularios

Validación de Formularios sin uso de librerías. Envío con fetch y FormSubmit.   

Definición de componentes y lógica 

	1- Crear hook personalizado (useForm.js) para encapsular la lógica 
	2- Crear componente principal (ComponentForm.js) para crear el formulario 

Programación de eventos  

	1- Función handleChange 
	2- Función HandleBlur 

Programación de validaciones  

	1- Uso de expreciones reguladoras: 

            - regexName = /^[A-Za-zÑñÁáÉéÍíÓóÚúÜü\s]+$/; 
            - regexEmail = /^(\w+[/./-]?){1,}@[a-z]+[/.]\w{2,}$/; 
            - regexComments = /^.{1,255}$/; 

Envío de datos AJAX y API FormSubmit  

	1- Función handleSubmit 
	2- Re-utilización del herper (helpHttp.js) ‘Mini librería para peticiones fetch’ 
	3- Utilizar el servicio de FORMSUBMIT   https://formsubmit.co/ 
	4- Re-utilización de componentes (Loader.js y Message.js) 

### `npm run start`
