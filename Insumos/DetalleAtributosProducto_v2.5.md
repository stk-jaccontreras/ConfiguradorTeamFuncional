# DetalleAtributosProducto_v2.5

## Producto

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | CATALOGOS |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cátalogo (Subramo) |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Subramo | Alcance comercial |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Individual | Open Market |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Colectivo | Credit Related |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cátalogo (Familia Principal) |  |
| Producto |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Accidentes y enfermedades |  |
|  | Clave Técnica: | Campo de texto | Sí | Sí |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños |  |
|  | Nombre Técnico: | Campo de texto | Sí | Sí |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Vida |  |
|  | Descripción del producto: | Campo de texto | Sí | Sí |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catalogo Ramo |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Familia | Ramo |
| Clasificación del producto |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Vida | Vida |
|  | Subramo | Cátalogo (Subramo) | Sí | Sí | Subramo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Accidentes y enfermedades | Accidentes personales. |
|  | Familia Principal | Cátalogo (Familia Principal) | Sí | Sí | Accidentes y enfermedades |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Accidentes y enfermedades | Gastos médicos. |
|  | Moneda | Cátalogo | Sí | Sí | Mxn |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Automóviles. |
|  | Ramo | Condición Cátalogo (Ramo) | Selección | Sí | Regla: Buscar lo que se agrego en familia y mostrar lo que tiene el campo de Ramo, el campo será multiselección |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Responsabilidad civil y riesgos profesionales. |
|  | Alcance Comercial | Condición | No | Se llena en automatico | Alcance comercial |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Accidentes y enfermedades | Salud. |
|  | Temporalidad | Condición Cátalogo | Selección | Sí | Para mostrar la información <br>Regla: Validar el campo de Alcance Comercial y obtener los datos del campo temporalidad. Del catalogo temporalidad<br>Cuando los muestre el usuario solo podra seleccionar una opción. (radio button) <br>Regla 2: En caso de que el usuario seleccione Multianual el sistema debe presentar dos campos ( Unidad de tiempo que podra tener (meses o años) y el valor |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Crédito. |
|  | Frecuencia de pago de la prima | Condición | Multi Selección | Sí | Se debera validar el Alcance Comercial seleccionado y dependiendo de la selección deberá mostrar lo que se encuentra en el catalogo de Frecuencia de Pago. El usuario debera seleccionar uno o todos, incluir una opción para cualquiera del Alcance Comercial para poder seleccionar todos y deseleccionar todos. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Crédito a la vivienda. |
|  | Recargos |  |  | Sí | Solo se mostrará cuando el Alcance Comercial es: Open Market <br>Por cada una se las frecuencias de pago seleccionadas, de bera dejar ingresar el % de Recargo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Garantía financiera. |
|  | Conductos de Cobro | Catalogo | Multi Selección | Sí | Mostrar el catalogo Conductos de cobro (Multiselección ) <br>Agregar un checkbox con leyenda de MSI (Meses sin Intereres)  en caso de que seleccione la opcion TDC. No debe de incluir cuantos meses sin intereses aplicaran. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Riesgos catastróficos. |
| Documentos del producto |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Muestra el catalogo en multiselección | Catalogo | Multiselección | Sí | Agregar una opcion de seleccionar todos o deseleccionarlos |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Monedas |  |
| Alcance del producto / Elegibilidad |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Pesos | Mxn |
|  | Edad minima | Campo de texto (númerico) | Sí | Sí | Validación hasta el 100 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Dolares | USD |
|  | Edad máxima | Campo de texto (númerico) | Sí | Opcional | Validación hasta el 100 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Temporalidad |  |
|  | Tipo de Oferta | Catálogo (Tipo de Oferta) | Selección | Si | Nueva |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Alcance comercial | Temporalidad |
|  | Género | Condición | Multiselección | Si | Presentar Opciones Masculino / Femenino |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Horas |
|  | Requiere Cúmulo | Condición | Selección | Si | si se selecciona Checkbox, se habilita nuevo campo para ingresar monto de cúmulo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Días |
|  | Contratante | Condición | Multiselección | Si | Presentar Opciones Persona Física / Persona Moral |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Mensual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Anual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Multianual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Meses |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Anual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Multi-anual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Ligado a vigencia de crédito |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Frecuencia de Pago |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Alcance comercial | Frecuencia |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Semanal |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Decena |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Catorcenal |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Quincenal |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Mensual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Semestral |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Trimestral |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Open Market | Anual |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Prima Recurrente |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Credit Related | Prima Única |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Conductos de cobro |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cargo a Cheques |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | TC Santander |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | TC Otros Bancos |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Tarjeta de débito |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Efectivo Ventanilla |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cargo Crédito |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Domiciliación |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Amex |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Documentos |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Tipo de documento | Documento |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Solicitud |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Carátula |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Condiciones Generales |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Welcome Kit |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Aviso de Privacidad |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | FUI |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Producto | Medios Electrónicos |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Identificación |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Comprobante Domicilio |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Conductos de cobro |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Nueva |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Renovación |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Retención |  |

## Planes

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | CATALOGOS | Catálogo (Planes) |  |  |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo | Notas adicionles |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Clave y Nombre del Plan | Tipo de Suma Asegurada | Suma Asegurada Desde | Suma Asegurada Hasta |  |  |  |  | Tipo de Suma Asegurada |
| Busqueda y Gestion de planes | Plan | Catálogo (Planes) | Multiselección | Si | VMA01 - PLAN VIDA MULTIANUAL | Se debe poder buscar (busqueda por autocompletar)  y seleccionar el plan (asigno) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 6401 - VIDA RECOMPENSA | Monto Fijo |  |  |  |  |  |  | Monto Fijo |
| Planes asignados: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA01 - PLAN VIDA MULTIANUAL | Rango | 300000 | 1000000 |  |  |  |  | Rango |
|  | Nombre | Campo texto (Catalogo) | No | Se llena en automatico | Mostrar  una tabla con los valores del catálogo de Plan seleccionado en el campo "Plan" |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA02 - VIDA MULTIANUAL JUPITER | Ninguno |  |  |  |  |  |  | Ninguno |
|  | Moneda | Campo texto (Catalogo) | No | Se llena en automatico | Mostrar el tipo de moneda de la suma asegurada. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA13 - PLAN VIDA MULTIANUAL | Monto Fijo |  |  |  |  |  |  |  |
|  | Tipo de Suma Asegurada | Campo texto (Catalogo) | No |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Suma asegurada | Campo texto | Si | Si | Esta sección de valores escalonados solo se muestra cuando el tipo de plan que se quiere asignar = "Rango", en caso contrario no se muestra nada. <br><br>Regla: Para tipo de suma asegurada Rango: El valor ingresado debe estar entre el rango de los campos del catálogo "Plan" campos suma asegurada Desde y Suma asegura Hasta y se permitira ingresar mas de un valor.<br>Para el tipo de suma asegurada Monto fijo: Debe ingresar el monto de la Suma Asegurada.<br>Para el tipo de Suma asegura Ninguno: No solicita monto de Suma asegurada | Se debe poder ingresar varios valores (al menos 1) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7001 - CLASICO | Ninguno |  |  |  |  |  |  |  |
|  | Iconos de acción por plan |  |  |  |  | Icono de palomita Icono basura, Icono E |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7003 - TRES EN UNO | Ninguno |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7005 - TRES EN UNO CON ASISTENCIA EN VIAJE | Monto Fijo |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | PRE001 - CLASICO | Rango | 15000 | 800000 |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | PRE002 - TRES EN UNO | Monto Fijo |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Monedas |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Descripción | Divisas |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Pesos | Mxn |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Dolares | USD |  |  |  |  |  |  |  |

## Coberturas & Asistencias

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | CATALOGOS |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Coberturas) |
| Búsqueda y Selección de Plan para Coberturas/Asistencia | Plan | Campo texto | Selección | Si | Mostrar los valores selecionados en el campo Planes asignados al producto (Tabla) y permitir selecionarlos |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 6401 - VIDA RECOMPENSA |
| Asignar Cobertura al Plan | Cobertura | Catálogo (Coberturas) | Selección | Si | 6401 - VIDA RECOMPENSA | Se debe poder seleccionar la cobertura del catálogo, (Recuperar dle catálogo los campos: Clave, Nombre, Tipo, Unidad, Limite. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA01 - PLAN VIDA MULTIANUAL |
|  | Asignar al plan | Boton | Selección | Si | Al selecionar el boton de Asignar, se debe mostrar el valor selecionado en la tabla "Coberturas asignadas al plan" Columnas: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA02 - VIDA MULTIANUAL JUPITER |
| Tabla: Coberturas asignadas al plan | Clave | Campo texto | No | Se llena en automatico | Valores de la Cobertura seleccionada |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA13 - PLAN VIDA MULTIANUAL |
|  | Nombre Cobertura/ Asistencia | Campo texto | No | Se llena en automatico | Valores de la Cobertura seleccionada |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | VMA14 - PLAN VIDA MULTIANUAL |
|  | Tipo | Campo texto | No | Se llena en automatico | Valores de la Cobertura seleccionada |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7001 - CLASICO |
|  | Unidad | Campo texto | No | Se llena en automatico | Valores de la Cobertura seleccionada |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7003 - TRES EN UNO |
|  | Límite | Campo texto | No | Se llena en automatico | Valores de la Cobertura seleccionada |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | PRE001 - CLASICO |
|  | LUC | Check | Selección | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7005 - TRES EN UNO CON ASISTENCIA EN VIAJE |
|  | Estatus | Campo texto | No | Se llena en automatico | Estado de la cobertura (Asignado o Desasignado) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | PRE001 - CLASICO |
|  | Detalles | Boton | No | No | Al selecionar el boton, se debe mostrar una subsección con los atributos numerados del 1 al 5: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Subcobertura | Boton | No | No | Al selecionar el boton, se debe mostrar la tabla de Subcoberturas: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | 1- Catálogo Tipo limite Cobertura | Campo texto | Selección | Si | Fija |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | PRE002 - TRES EN UNO |
|  | 2- Condición | Campo texto | Selección | Si | Valores: Fija Oblig./ Opcional |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | 3- Deducible/ Co-Aseguro | Campo texto | Si | Si | Valores:  Coaseguro, Deducible, Franquicia<br>Para Coaseguro y Deducible habilitar dos campos uno para capturar %  y otro para capturar Monto<br>Para Franquicia poner un check. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Tipo limite Coberturas) |
|  | 4- Edades Cobertura | Campo texto | Si |  | Poner un Chek preguntando si aplica Edad Minima y Edad Maxima, <br>Si aplica habilitar los campos de  edad Minima y edad Maxima. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Fija |
|  | 5- Extensible | Catálogo (Parentesco) | Si | No | Conyuge | Check Extencibe<br>Si se seleciona check de Extencible, HAbilitar el catálogo de Parentesco |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Flex |
|  | Acciones | Boton | Si | Si | Valores Asignado / Desasignado |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Min |
| Subcoberturas / Coberturas Adicionales |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Max |
| Tabla: SubCoberturas | Tabla Subcoberturas |  |  |  | Muestra la tabla generada de las subcobertursas generadas en "Agrega nuevas coberturas al plan"<br>Campos de la tabla: Nombre SubCobertura, Clave Cobertura Madre, Limite, Eventos, Periodo, Regla de Indemnización, Acciones<br>La columna Acciones: podra permitir borrar la Subcobertura generada. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Conyuge |
|  | Nueva Subcobertura |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Agregar Nueva Subcobertura al Plan | Nombre Subcobertura | Campo texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Límite (Moneda) | Campo texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Fija |
|  | Eventos Max | Campo texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Opcional |
|  | Periodo | Campo texto | Selección | Si | Valores: Por año de Poliza, Por Evento, Semestral, Mensual |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Regla de Indemnización / Descripción | Campo texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Guardar Subcobertura | Boton | Si | Si | Genera tabla con los valores Capturados, Columnas de la tabla: ID SubCobertura, Nombre SubCobertura, Clave Cobertura Madre, Limite, Eventos, Periodo, Acciones. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Parentesco) |
| Exclusiones del Plan | Exclusiones Disponibles en Catálogo Institucional | Catálogo Exclusiones Institucional | Selección | Si | Deportes de alto riesgo o extremos |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Hijos |
|  | Asignar Exclusión | Boton | Selección | Si | Al seleccionar el boton de Exclusión, debe mostrar los campos en la tabla de  Exclusiones Asignadas al Plan Activo, con los campos:  Calve, Nombre de exclusión, Descripción Oficial, Deducible Aplicable ($ o %) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Padres |
| Tabla Exclusiones Asignadas al Plan Activo | Clave | Campo texto | No | Se llena en automatico |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Nombre de exclusión | Campo texto | No | Se llena en automatico |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Exclusiones) |
|  | Descripción Oficial | Campo texto | No | Se llena en automatico |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Deportes de alto riesgo o extremos |
|  | Deducible Aplicable ($ o %) |  |  |  | Valores:  No Aplica, Monto, %<br>Habilitar dos campos uno para capturar %  y otro para capturar Monto<br>Para No aplica poner un check. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Enfermedades preexistentes no declaradas |
|  | Acciones | Boton | Si | Si | Valores Asignado / Desasignado |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Dolo o mala fe del asegurado |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Suicidio en los dos primeros años |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Epidemias o pandemias no declaradas |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Accidentes bajo influjo de alcohol o drogas |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Contaminación nuclear o radiactividad |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Riesgos laborales no declarados |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Actos de guerra, rebelión o terrorismo |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Cúmulo | Numérico (monto/moneda), abierto, editable | Sí | Sí | Monto máximo de suma asegurada compartido entre productos con la misma cobertura (ej. Vida hasta $10,000,000); checkbox aplica/no aplica |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Edad mínima / máxima (por cobertura) | Numérico, abierto, editable | Sí | Sí (mínima); condicional (máxima) | Ambas aplican en EMISIÓN; en RENOVACIÓN solo aplica la máxima (la mínima ya no aplica, la póliza ya está en cartera) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Eventos al año (por cobertura) | Numérico o catálogo 'sin límite' | Sí | Sí | Puede ser un número o 'sin límite de eventos' (se agota hasta consumir la suma asegurada) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Periodo de carencia (por cobertura) | Numérico (días), abierto | Sí | Sí (valor 0 si no aplica) | Se mueve de nivel producto a nivel cobertura; 0 = no bloqueante |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Periodo de espera (por cobertura) | Numérico (días), abierto | Sí | Sí (valor 0 si no aplica) | Se mueve de nivel producto a nivel cobertura; 0 = no bloqueante |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Deducible / Coaseguro (por cobertura) | Selección aplica/no aplica + monto o % | Sí | Sí | Confirma estructura ya presente en esta hoja — sin cambio |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Tipo de límite de cobertura | Catálogo | Sí | Sí | Agregar valor 'Mínima' al catálogo existente (Fija/Máxima/Flex) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Tarifa de cobertura (renombrar 'costo') | Catálogo o abierto (cuota al millar o cuota fija) | Sí | Sí | Monto o % de la suma asegurada base; terminología correcta es 'tarifa' o 'cuota', no 'costo' (ese término es de Asistencias) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Costo de asistencia | Numérico, abierto | Sí | Condicional (algunas asistencias no llevan monto, ej. dental → 'incluida/amparada') | Periodicidad del monto (mes/día/año) aún sin definir |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Suma asegurada (formato) | Monto, % o texto libre/leyenda | Sí | Sí | Puede ser monto fijo, % de suma base, o leyenda ad hoc (ej. Gadget: 'reembolso' o 'reparación') — minoritario en el catálogo actual |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Clave de cobertura | Abierto, ligado a catálogo | No | Sí | Debe corresponder a la clave de ramo contable (catálogo pendiente de que el cliente lo comparta) |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Subcobertura: solo mención de paso en la sesión más reciente ('50% de esa cobertura en esta subcobertura'), sin definición formal — sigue como lo que ya trae esta hoja, sin cambios ni cierre. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Exclusiones: no se tocaron en ninguna de las 4 sesiones nuevas — sin cambio frente a lo que ya trae esta hoja. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

## ModeloNegocio

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogos |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Modelo de Negocio y Distribución de Riesgo |  |  | Seleccion |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Reaseguradores) |
| Directo | Directo | Check | Seleccion | No | Operación Directa — 100% Retención Propia |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Assurant |
| Re-Aseguro | Parámetros del Contrato de Reaseguro |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Swiss Re |
|  | Reasegurador | Catalogo (Reaseguradores) | Seleccion | Si | Assurant |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Tipo de reasegurador | Catalogo (Tipo de Reaseguradores) | Seleccion | Si | Extranjero |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Tipo de Reasegurador) |
|  | País de origen | Catalogo (Paises) | Seleccion | Si | Estados Unidos |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Nacional |
|  | Registro RGRE (CNSF) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Extranjero |
|  | Calificación crediticia | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Intragrupo |
|  | Modalidad de contrato | Catálogo Modalidad de contrato) | Seleccion | Si | Cuota_Parte |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Pais Origen reaseguro) |
|  | Porcentaje de cesión (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Estados Unidos |
|  | Capacidad de contrato ($) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Mexico |
|  | Comisión de reaseguro (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Participación utilidades (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Base de Cobertura) |
|  | Base de cobertura | Catalogo (Reaseguradores) | Seleccion | Si | RISK_ATTACHING |  |  |  |  |  |  |  |  |  |  |  |  |  |  | RISK_ATTACHING |
|  | Número de contrato / Slip | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Co-Aseguro | Parámetros de Co-Aseguro |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | LOSSES_OCCURRING |
|  | Nombre del socio comercial | Catálogo (Socio Comercial) | Seleccion | Si | GNP Seguros |  |  |  |  |  |  |  |  |  |  |  |  |  |  | CLAIMS_MADE |
|  | Número de Convenio | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Rol de Zurich Santander | Campo Texto | Seleccion | Si | Valores: Lider o Seguidor |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | ¿Esquema bajo el que se negoció la oferta? | Check |  |  | Si se selecciona Esquema bajo el que se negocio la oferta se habilitan los siguientes compos: % Coaseguro compañía (Zurich Santander) y Comisión del coaseguro (%) |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Modalidad de Contrato) |
|  | % Coaseguro compañía (Zurich Santander) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cuota_Parte |
|  | Comisión del coaseguro (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Excedente |
|  | Funciones de Coaseguro | Campo Texto | Si | No |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Facultativo |
| RE&CO |  |  |  |  | Operación combinada de cesión proporcional y coaseguro bilateral |  |  |  |  |  |  |  |  |  |  |  |  |  |  | XL_RISK (Exceso de pérdida) |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | STOP_LOSS |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Socio Comercial) |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | GNP Seguros |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Axa Seguros |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Seguros Monterrey |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Qualitas |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Mapfre Mexico |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Chubb Seguros |
|  | Nota para negocio: el detalle del reasegurador (nombre del socio, pais, modalidad de contrato, comision) se confirmo en sesion que queda FUERA del Configurador -se gestiona en un modulo aparte, porque estos contratos se renegocian cada ano-. El deducible y el coaseguro a nivel cobertura SI quedan dentro del Configurador. Pendiente cerrar el detalle final con el area de Reaseguro. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

## Tarifas

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |  |  |  |  |  |  |  |  | Catálogo (Tipo Directriz Tarifas) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Modalidad de tarifa | Catálogo | Sí | Sí | Definida / Por algoritmo (excluyente) |  |  |  |  |  |  |  |  |  | Unica |
|  | Directriz de tarifa definida | Catálogo (Tipo Directriz Tarifas) | Multiselección | Sí | Unica |  |  |  |  |  |  |  |  |  | Edad / Rango |
|  | Archivo de tarifa | Archivo | Sí | Condicional (Modalidad=Definida) | Carga de archivo de tarifa |  |  |  |  |  |  |  |  |  | Género |
|  | Extraprima (% o al millar) | Numérico | Sí | Condicional | Definido en módulo Administrador |  |  |  |  |  |  |  |  |  | Hábito |
|  | Variables del algoritmo | Abierto | Sí | Condicional (Modalidad=Algoritmo) | Campos requeridos en cotización |  |  |  |  |  |  |  |  |  | Suma Asegurada |
|  | Fórmula del algoritmo | Abierto | Sí | Condicional | Condicionantes: suma, resta, multiplicación, división |  |  |  |  |  |  |  |  |  | Cobertura |
|  | Inputs de cada variable | Abierto | Sí | Condicional | — |  |  |  |  |  |  |  |  |  | Plazo |
|  | Valores de Rescate | Archivo/layout | Sí | Condicional (oferta=Ahorro) | Por plazo meta y vigencia |  |  |  |  |  |  |  |  |  |  |
|  | Cargos por Rescate | Archivo/layout | Sí | Condicional (oferta=Ahorro) | Por plazo meta y vigencia |  |  |  |  |  |  |  |  |  |  |
|  | Fondo — Perfil | Catálogo, no editable tras creación | Sí | Condicional (Ahorro) | — |  |  |  |  |  |  |  |  |  |  |
|  | Fondo — Nombre/Tipo de Renta/Moneda/Distribución/Fee/Comisión fee/Tasa proyectada | Abierto/Catálogo, editable tras creación | Sí | Condicional (Ahorro) | — |  |  |  |  |  |  |  |  |  |  |
|  | Recargo por pago fraccionado | % por forma de pago | Sí | Sí | No modifica la prima neta del seguro |  |  |  |  |  |  |  |  |  |  |
|  | Derecho de póliza | Monto (no %) | Sí | Sí | Puede ser cero; se define a nivel producto |  |  |  |  |  |  |  |  |  |  |
|  | Alcance de cambio de tarifa | Catálogo | Sí | Sí (al actualizar) | Solo nuevas emisiones / también cartera vigente |  |  |  |  |  |  |  |  |  |  |
|  | Versión de tarifa | Sistema | No | — | Se genera automático, no la captura el usuario |  |  |  |  |  |  |  |  |  |  |
|  | Estado activo/inactivo | Sistema | No | — | Baja lógica, no eliminación física |  |  |  |  |  |  |  |  |  |  |
|  | PREGUNTAS PARA NEGOCIO |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Seccion de costos de producto -- Propuesta, pendiente de verificar |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla |  |  |  |  |  |  |  |  |  |  |
|  | Comision a banco | Campo numerico (%) | Si | Si | Propuesta del equipo de analisis; pendiente de confirmar en la siguiente sesion de revision con Producto/Actuaria |  |  |  |  |  |  |  |  |  |  |
|  | Nota para negocio: derecho de poliza, gastos de implementacion y gastos de administracion/adquisicion ya estan cubiertos arriba, dentro de Tarifas. Falta confirmar si conviene agruparlos en una seccion propia de costos de producto, junto con comision a banco. Otros conceptos de rentabilidad (prima cedida, reserva, comisiones de reaseguro, BAI, TAX, NPV) no tienen ninguna definicion todavia -pendiente de una sesion dedicada con Finanzas y Actuaria. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

## Suscripción 

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogos |  |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Selección de Plan para Reglas de Suscripción | Seleccione el plan | Campo texto | Selección | Si | Mostrar los valores selecionados en Planes, tabla Planes, asignados al producto (Tabla) y permitir selecionarlos |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Elegir Plan |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Resumen de Ramos, Subramo y Familias de Productos | Familia Principal | Campo texto | No | Se llena en automatico | Se llena con lo que se tenga seleccionado en Producto -> Familia principal |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Ramos Seleccionados | Campo texto | No | Se llena en automatico | Se llena con lo que se tenga seleccionado en Producto ->Ramos Seleccionados |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Subramo | Campo texto | No | Se llena en automatico | Se llena con lo que se tenga seleccionado en Producto -> Subramo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Familias de Productos | Catálogo (Familias Productos) | No | Si | A partir de la Familia Principal, se busca en el catálogo de Familias Productos para mostrar las opciones correspondientes |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Configurar la regla | Seleccionar la regla | Catálogo (Reglas) | Selección | Si | Opción 1 - Validación IMC<br><br>Opción 2 - Ocupaciones de Riesgo |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Seleccionar |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Si seleccionó Opción 1 -  Validación IMC | Buscar validacion IMC (existente) | Catálogo (IMC) | Selección | No | ValidacionIMC_Unica | Muestra el catálogo completo, Campos: Desde Hasta, Tipo_Riesgo, ExtraPrima, no editables |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Mostrar el resultado: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Monedas |  |  |  |  |  |
|  | Solo se muestra el resultado |  |  |  | Opcion 1- Validación IMC - Asignar | Ejemplo: | #VALUE! |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Descripción | Divisas |  |  |  |  |
|  | Opcion Asignar |  |  |  | Se asigna al producto/plan |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Pesos | Mxn |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Dolares | USD |  |  |  |  |
| Si seleccionó Opción 2 - Ocupaciones de Riesgo | Buscar Ocupaciones de Riesgo | Catálogo (Ocipaciones Riesgos) | Selección | No | Actor | Muestra el catálogo completo, Campos: OCUPACION, ACEPTACIÓN |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Mostrar el resultado: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Solo se muestra el resultado |  |  |  | Opcion 2 - Ocupaciones de Riesgo - Asignar | Ejemplo: | #VALUE! |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Opcion Asignar |  |  |  | Se asigna al producto/plan |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Validación IMC |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Grados de IMC |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ID | Nombre de la validación | Desde | Hasta | Tipo_Riesgo | ExtraPrima |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 | ValidacionIMC_Unica | 0 | 15 | Rechazo | 0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 | ValidacionIMC_Unica | 15.001 | 17 | ExtPrima | 50 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 | ValidacionIMC_Unica | 17.001 | 20 | Normal | 0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 | ValidacionIMC_Unica | 20.001 | 25 | Normal | 0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ValidacionIMC_Unica | 25.001 | 27 | Normal | 0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ValidacionIMC_Unica | 27.001 | 32 | Normal | 0 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ValidacionIMC_Unica | 32.001 | 36 | ExtPrima | 25 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ValidacionIMC_Unica | 36.001 | 40 | ExtPrima | 50 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | ValidacionIMC_Unica | 40.001 | 100 | Rechazo | 0 |
| Mostrar el resultado: |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Solo se muestra el resultado |  |  |  | Opcion 1 - Asignar |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Opcion Asignar |  |  |  | Se asigna al producto/plan |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Ocupaciones |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | CONTROL | OCUPACION | ACEPTACIÓN |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 1 | Abarrotero (Propietario/empleado) | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 2 | Abogado (ejercicio de su profesión) | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 3 | Actor | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 4 | Actuario (ejercicio de su profesión) | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 5 | Adiestrador (Animales domésticos) | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 6 | Afilador | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 7 | Afinador de Pianos | OK |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 8 | Agente de transito | RECHAZO |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 9 | Agente judicial | RECHAZO |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | 10 | Agente PGR, PGJ | RECHAZO |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catalogo Familia Productos |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Familia | Familia Producto |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Vida | Vida |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Salud | Salud |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Fraude |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Hogar |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | PYME |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Daños | Pertenencias/Contenidos |  |  |  |  |

## Renovación

|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Tipo de Devolución por cancelación) |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Devolución BS |
| Políticas de Renovación del Producto | Permite renovación automática | Check | Selección | Si | Si selecciona Permite renovación automática habilitar el campo Edad máxima de renovación (años) |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Devolución ZS |
|  | Suma asegurada indexada | Check | Selección | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | A petición del cliente |
|  | Factor indexación SA (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Factor indexación prima (%) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | % Descuento por renovación | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Tipo Endoso) |
|  | Aviso de Renovación (días) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Modificación de Suma Asegurada |
|  | Edad máxima de renovación (años) | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Inclusión / Exclusión de Coberturas |
|  | ¿Aplica Cancelación PND (Prima No Devengada)? | Check | Selección | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cambio de Contratante / Asegurado |
|  | % de sanción por cancelación | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cambio de Forma de Pago |
|  | Días de devengamiento | Campo Texto | Si | Si |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Corrección de Datos |
|  | Tipo de devolución | Catálogo | Selección | Si | Devolución BS |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cancelación / Rescisión |
| Endosos del Producto |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Buscador de Producto Base | Campo texto | Selección | Si | Buscar y autocompletar la búsqueda de Productos y permitir selecionarlos |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Tipo de Endoso habilitado | Catálogo (Tipo Endoso) | Selección | Si | Modificación de Suma Asegurada |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Catálogo (Calculo Prima Endoso) |
|  | Regla de Cálculo de prima de endoso | Catálogo (Calculo Prima Endoso) |  |  | Prorrateo comercial a mes completo |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Prorrateo comercial a mes completo |
|  | Acciones | Boton | Si | Si | Valores Asignar |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Prorrateo por días de vigencia restante |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Sin costo (Endoso Administrativo) |
| Tabla: Endosos del Producto |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  | Cobro de prima fija por emisión de endoso |
|  | Tipo de Endoso | Campo texto | No | Se llena en automatico | Se llena con el tipo de Endoso |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Afecta Prima | Campo texto | No | Se llena en automatico | Se llena con lo que se haya seleccionado en regla de cálculo de prima de endoso |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Documento Emitido | Campo texto | No | Se llena en automatico |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Tiempo Máximo Gestión | Campo texto | No | Se llena en automatico |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Estatus | Botón | No | Se llena en automatico | Valores Habilitado / Deshabilitado |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Aviso de renovación | Catálogo (canal) + numérico (días previos) | Sí | Sí | Se configura por canal y por número de días previos a la renovación |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Actualización de tarifas/planes/parámetros al renovar | Regla de comportamiento (no es un campo de captura) | — | — | Se actualizan a los vigentes al momento de renovar, no a los de la emisión original |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | Regreso a menú Oferta al terminar captura | Regla de flujo de pantalla | — | — | — |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| Nota para negocio | Los campos 'Edad maxima de renovacion', '% de sancion por cancelacion', 'Dias de devengamiento' y 'Tipo de devolucion' estan propuestos por el equipo de analisis a partir de este mismo documento de trabajo. Pendiente de definir con Producto y Cobranza si aplican y bajo que regla. |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |

## Siniestros

|  | ESTATUS DE ALCANCE |
| --- | --- |
|  | El Configurador solo GOBIERNA, como fuente que Siniestros consume: el catalogo de Coberturas y de Sublimites (cuya aprobacion es responsabilidad de Siniestros, no de Producto). |
|  | No completar esta hoja con funcionalidad de ejecución de siniestros. |

## Contabilidad

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |
| --- | --- | --- | --- | --- | --- |
|  | Ramo Contable | Campo de Texto | Selección | Si |  |
|  | Accidentes personales | Campo de Texto | Selección | Si |  |
|  | Acciones | Boton | Si | Si | Valores Asignar |
|  | Cuentas Concentradoras | Campo de Texto | Selección | Si |  |
|  | Acciones | Boton | Si | Si | Valores Agregar |
|  | Guías Contables | Campo de Texto | Selección | Si |  |
|  | Acciones | Boton | Si | Si | Valores Agregar |
|  | Guías Contables | Campo de Texto | Selección | Si |  |

## Cobranza

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |
| --- | --- | --- | --- | --- | --- |
|  | Forma de pago habilitadas | Campo de Texto | No | Se llena en automático | Se llenan con lo seleccionado en Producto - >Frecuencia de pago de la prima |
|  | Conductos de cobro habilitadas | Campo de Texto | No | Se llena en automático | Se llenan con lo seleccionado en Producto - >Conductos de cobro |
| Tabla: Periodos de gracia, espera y carencia |  |  |  |  |  |
|  | Periodo de Gracia | Campo de Texto | Si | SI |  |
|  | Periodo de Espera | Campo de Texto | Si | SI |  |
|  | Periodo de Carencia | Campo de Texto | Si | SI |  |

## Compliance (PLD)

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |
| --- | --- | --- | --- | --- | --- |
| Matriz de campos requeridos — Contratante, Asegurado y Beneficiario |  |  |  |  |  |
| Contratante | Cotizar todos | Checkbox | No | No | Al seleccionar la opción, se habilitan o deshabilitan todos los campos de la sección Cotizar |
|  | Emitir todos | Checkbox | No | No | Al seleccionar la opción, se habilitan o deshabilitan todos los campos de la sección Emitir |
|  | BUC | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Nombre | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | RFC | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Domicilio | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Situación Fiscal | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | País | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Nacionalidad | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Teléfono | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Correo electrónico | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
| Asegurado | Cotizar todos | Checkbox | No | No | Al seleccionar la opción, se habilitan o deshabilitan todos los campos de la sección Cotizar |
|  | Emitir todos | Checkbox | No | No | Al seleccionar la opción, se habilitan o deshabilitan todos los campos de la sección Emitir |
|  | Nombre | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | RFC | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Domicilio | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Correo electrónico | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | País | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Nacionalidad | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Ocupación | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Suma Asegurada | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
|  | Fecha de Nacimiento | Checkbox | No | No | Al seleccionar el checkbox de la columna correspondiente (Cotizar y/o Emitir) se habilita / deshabilita el atributo para el Contratante |
| Beneficiario | Requerido todos | Checkbox | No | No | Al seleccionar la opción, se habilitan o deshabilitan todos los campos de la sección |
|  | Nombre | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Apellido Paterno | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Apellido Materno | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Porcentaje | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Parentesco | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Domicilio | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
|  | Teléfono | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para el Beneficiario |
| Figuras del Seguro (Participantes en la Póliza) | Tipo de contratante habilitado | Checkbox - Multiselección | No | Si | Presentar las figuras Persona Física, Persona Moral y Persona Física con Actividad Empresarial |
|  | Asegurados adicionales | Listado | No | Si | Presentar las opciones "No - Solo titular" y "Si - múltiples asegurados (mismo contrato)" |
|  | Máximo de asegurados | Campo de Texto | No | Se llena en automático | Se habilita este campo para elegir el número de asegurados solo si el campo "Asegurados iniciales" selecciona la opción "Si - múltiples asegurados" |
|  | Máximo de Beneficiarios | Campo de Texto | Si | No |  |
|  | Regla de Beneficiarios | Listado | No | No | Presentar las opciones "Porcentaje sumando 100%" y "Beneficiario irrevocable (sin distribución porcentual)" |
| Listas restrictivas y normatividad | Requiere validación de Black List previo a emitir (bandera de producto) | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para requerir validación |
|  | Solicitar documentación adicional por umbral de PLD | Checkbox | No | No | Al seleccionar el checkbox se habilita / deshabilita el atributo para solicitar documentación |
|  | Umbral de prima (USD) para documentacion PLD | Campo numerico | Si | Si | Valor de trabajo propuesto: 2,500 USD -pendiente de confirmacion explicita de Compliance/Legal- |
|  | Requiere cuestionario FUI | Derivado (automatico) | No | - | Se activa cuando la prima supera el umbral anterior |
|  | Valida figuras del seguro | Indicador | No | - | Contratante / Asegurado / Beneficiario pasan por esta validacion; sin mas detalle de campos todavia |

## Comercial

| Gestión de campañas | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |
| --- | --- | --- | --- | --- | --- | --- |
| Búsqueda y Selección de Productos | Buscador de productos Asociados | Listado | No | Si | Mostrar los valores del catálogo de productos y permitir selecionarlos |  |
| Búsqueda de campañas | Filtro de campaña | Campo de texto | Si | No | Filtrar el nombre de las campañas a partir del valor ingresado |  |
| Estado | Campo Texto (Catálogo Estado Campañas) | Selección | No | No | Contiene los estados de las campañas y permite seleccionar uno para filtrarlas. Al realizar la búsqueda, extrae Código, Nombre de Campaña, Vigencia, Descuento, Meta Pólizas, Productos Asociados, Canales y Estado |  |
| Catálogo de Campañas Configuradas | Código | Campo de Texto | No | Se llena en automático | Se llena con el contenido del código de la campaña configurada |  |
|  | Nombre de Campaña | Campo de Texto | No | Se llena en automático | Se llena con el contenido del nombre de la campaña configurada |  |
|  | Vigencia | Campo de Texto | No | Se llena en automático | Se llena con el contenido de la vigencia de la campaña configurada |  |
|  | Descuento | Campo de Texto | No | Se llena en automático | Se llena con el contenido del descuento de la campaña configurada |  |
|  | Meta Pólizas | Campo de Texto | No | Se llena en automático | Se llena con el contenido de la meta pólizas de la campaña configurada |  |
|  | Productos Asociados | Campo de Texto | No | Se llena en automático | Se llena con los productos asociados a la campaña configurada |  |
|  | Canales | Campo de Texto | No | Se llena en automático | Se llena con los planes asociados a la campaña configurada |  |
|  | Estado | Campo de Texto | No | Se llena en automático | Se llena con el estado de la campaña configurada |  |
|  | Acciones |  |  |  | Valores Editar / Eliminar |  |
| Pendientes | Se necesita sesión con área comercial |  |  |  |  |  |
|  | ¿Cuál es la relación campaña con producto? |  |  |  |  |  |

## Revisión & Aprobación

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |
| --- | --- | --- | --- | --- | --- | --- |
| Resumen Ejecutivo del Producto |  |  |  |  |  |  |
| Matriz de Firmas y Vo.Bo. por Área | Área Funcional |  |  |  |  |  |
|  | Firmante Responsable | Campo texto | No | Se llena en automatico | Autorizador del Area, dato optenido de la matriz de autorizaciones |  |
|  | Estado | Campo texto | No | Se llena en automatico | Valor tomado del Ciclo de Vida y Transición de Estados |  |
|  | Fecha | Campo texto | No | Se llena en automatico | Fecha en la que se genero la autorización |  |
|  | Acción | Boton | No | Si | Cambia el estatus de Pendiet |  |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |
|  | Área Funcional (valores del catálogo) | Catálogo | — | — | Analista Producto, Owner Producto, Actuarial, Suscripción, Comercial, Cobranza, Reaseguro, Contabilidad, Legal, Compliance, Siniestros, Emisión | Gobernado por la Matriz de Roles y Permisos del proyecto. |
|  | Firmante — 'Publicar producto' | — | — | — | Único Accountable: Owner Producto (Director de producto); el resto de áreas solo se informan | Gobernado por la Matriz de Roles y Permisos del proyecto. |
|  | Acción (aprobar/rechazar/editar) | Botón | — | Sí | El aprobador puede regresar al Analista o editar directamente los campos faltantes por urgencia |  |

## Validación CNSF

|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo |  |
| --- | --- | --- | --- | --- | --- | --- |
| Nota Técnica Actuarial | Folio interno de Nota Técnica | Campo texto | Si | Si |  |  |
|  | Fecha de emisión de la nota | Fecha | Si | Si |  |  |
|  | Actuario responsable | Campo texto | Si | Si |  |  |
|  | Cédula profesional del actuario | Campo texto | Si | Si |  |  |
|  | URL o archivo PDF de la nota | Campo texto | Si | Si |  |  |
|  | Condiciones generales | Campo texto | Si | Si |  |  |
| Registros Regulatorios Oficiales | Oficio de Aprobación CNSF | Campo texto | Si | Si |  |  |
|  | Fecha de oficio CNSF | Fecha | Si | Si |  |  |
|  | Registro CONDUSEF (RECAS / RESBA) | Campo texto | Si | Si |  |  |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |
|  | Vigencia del folio CNSF | — | — | — | El folio de registro CNSF puede cambiar en vida del producto por observaciones regulatorias; no se reescribe el histórico |  |
|  | Bloqueo de publicación sin registro CNSF | — | — | — | No se puede publicar una versión si las condiciones generales no tienen registro/sello aprobado por CNSF |  |
|  | Cláusulas obligatorias CUSF | — | — | — | Las condiciones generales incluyen cláusulas obligatorias de la CUSF, no editables por el Analista de producto |  |
|  | El alcance exacto y la denominacion de RECAS/CONDUSEF siguen pendientes de confirmar con el area Juridica/Cumplimiento. No tratar este registro como definitivo todavia. |  |  |  |  |  |
|  | Campo | Tipo de campo | Editable? | Obligatorio | Valores del catalogo / Regla | Fuente |
|  | Vigencia del folio CNSF | Fecha | Sí | Sí | El folio de registro tiene una vigencia propia que debe capturarse, además de la fecha en que se hizo el registro |  |
|  | NOTA — vínculo con el módulo de Plantillas (no existe hoja propia todavía) |  |  |  |  |  |

## Reglas_Cotizador

| 1.- Endpoint: |  |  | 2.-REQUEST |  |  | ESTANDAR |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| /configurador/calcularCotizacion/v1 |  |  | Id Producto | 1 |  | idProducto | idCotizador | versionRegla | Lógica |
|  |  |  | Id Cotizador | COT_VIDA_MULTIANUAL |  | 1 | COT_VIDA_MULTIANUAL | v1 | Reglas Vida Multianual |
|  |  |  | Versión Regla | v1 |  | 1 | COT_VIDA_INDIVIDUAL | v1 | Reglas Vida Individual |
|  |  |  | Producto | Vida Individual Multianual |  | 2 | COT_AUTO | v1 | Reglas Auto |
|  |  |  | Tipo movimiento | Emisión |  |  |  |  |  |
|  |  |  | Fecha cotización | 2026-10-09 00:00:00 |  |  |  |  |  |
|  |  |  | Fecha nacimiento | 27/06/2002 |  |  |  |  |  |
|  |  |  | Edad | 24 |  |  |  |  |  |
| Ejemplo en Json |  |  | Estatura | 1.67 |  |  |  |  |  |
|  |  |  | Peso | 48 |  |  |  |  |  |
| { |  |  | IMC | 17.21 |  |  |  |  |  |
| "idProducto": "1", |  |  | Ocupación | Actor |  |  |  |  |  |
| "idCotizador": "COT_VIDA_MULTIANUAL", |  |  | Plazo | 3 años |  |  |  |  |  |
| "versionRegla": "v1", |  |  | Suma asegurada | 4000000 |  |  |  |  |  |
| "parametros": { |  |  | Cobertura | Fallecimiento |  |  |  |  |  |
| "edad": 24, |  |  |  |  |  |  |  |  |  |
| "sumaAsegurada": 4000000.00, |  |  | 3.-REGLA DE NEGOCIO |  |  |  |  |  |  |
| "plazo": 3, |  |  | Entrada evaluada | Resultado |  |  |  |  |  |
| "ocupacion": "ACTOR", |  |  | Condición | Valor de ejemplo |  |  |  |  |  |
| "imc": 17.21, |  |  | Producto | Vida Individual Multianual |  |  |  |  |  |
| "cobertura": "FALLECIMIENTO" |  |  | Edad | 24 años |  |  |  |  |  |
| } |  |  | Plazo | 3 años |  |  |  |  |  |
| } |  |  | Cobertura | Fallecimiento |  |  |  |  |  |
|  |  |  | Tarifa resultante | 4.65 ‰ |  |  |  |  |  |
|  |  |  | Prima calculada | 18600 |  |  |  |  |  |
|  |  |  | 4.-RESPONSE |  |  |  |  |  |  |
|  |  |  | Tarifa aplicada | 4.65 ‰ |  |  |  |  |  |
|  |  |  | Prima | $18,600.00. |  |  |  |  |  |
|  |  |  | Resultado | Cotización calculada |  |  |  |  |  |
|  | El ejemplo numérico (edad 24, plazo 3 años, tarifa 4.65‰, prima $18,600) no tiene respaldo en ningún entregable ni en la bitácora — no se pudo confirmar ni contradecir su origen. |  |  |  |  |  |  |  |  |
|  | No se encontró en esta sesión ninguna mención de 'idCotizador', 'versionRegla' ni del patrón COT_VIDA_MULTIANUAL/COT_VIDA_INDIVIDUAL/COT_AUTO — sigue sin confirmarse si ese patrón, tal como lo trae esta hoja, es el diseño vigente o quedó superado por el enfoque de metadatos JSON. |  |  |  |  |  |  |  |  |
|  | Recomendación: llevar el hallazgo del contrato JSON dinámico a `E04_Diseno_Tecnico` y `E05_Catalogo_de_APIs` como posible ADR — no evaluado todavía contra esos entregables en esta operación. |  |  |  |  |  |  |  |  |

## Diccionario_Entrada

| Parámetro | Nombre técnico | Tipo | Longitud | Ejemplo | Origen |
| --- | --- | --- | --- | --- | --- |
| Tipo movimiento | tipoMovimiento | String | 20 | Emisión | Catálogo |
| Fecha cotización | fechaCotizacion | Date | 10 | 2026-10-09 00:00:00 | Sistema |
| Fecha nacimiento | fechaNacimiento | Date | 10 | 27/06/2002 | Usuario |
| Edad | edad | Integer | 3 | 24 | Calculado |
| Estatura | estatura | Decimal | 4,2 | 1.67 | Usuario |
| Peso | peso | Decimal | 5,2 | 48 | Usuario |
| IMC | imc | Decimal | 5,2 | 17.21 | Calculado |
| Ocupación | ocupacion | String/ID | 50 | Actor | Catálogo |
| Plazo | plazoSeguro | Integer | 2 | 3 | Selección |
| Suma asegurada | sumaAsegurada | Decimal | 15,2 | 4000000 | Selección |
| Cobertura | cobertura | String/ID | 50 | Fallecimiento | Catálogo |
|  | Solo 'edad' y 'sumaAsegurada' tienen contraparte parcial en el Diccionario de Datos del proyecto (edad_minima/maxima_contratacion, suma_asegurada numerica). El resto de parametros (imc, ocupacion, plazoSeguro, cobertura, fechaCotizacion, fechaNacimiento, estatura, peso, tipoMovimiento) no estan modelados todavia como atributos propios con tipo/longitud. |  |  |  |  |
|  | IMC y Ocupación aparecen únicamente como valores de ejemplo del catálogo 'variable_riesgo' (ENT tarifario), no como atributos de entrada de cotización con tipo/longitud propios. |  |  |  |  |
