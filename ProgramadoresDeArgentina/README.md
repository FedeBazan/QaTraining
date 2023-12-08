<table>
  <tr>
    <th>Reporte n°1</th>
    <th></th>
  </tr>
  <tr>
    <td>ID</td>
    <td>TS0001</td>
  </tr>
  <tr>
    <td>Titulo</td>
    <td>Envio de datos no validos para los campo (Case-1)s</td>
  </tr>
  <tr>
    <td>Descripcion</td>
    <td>La seccion de "Contactos" señala un 200 de codigo de proceso exitoso frente a datos que no corresponden a los campos del formulario</td>
  </tr>
  <tr>
    <td>Entorno de ambiente</td>
    <td><ul>
     <li>Navegador: Chrome Version 120.0.6099.71 (Official Build) (64-bit)</li>
     <li>OS: Windows 10 Version 22H2</li>
    </ul> </td>
  </tr>
 <tr>
    <td>Tipo de Bug</td>
    <td><b>Funcional</b></td>
  </tr>
<tr>
    <td>Criticidad</td>
    <td>Critica</td>
  </tr>
  <tr>
    <td>Prioridad</td>
    <td>Alta</td>
  </tr>
  <tr>
    <td>Datos de Entrada</td>
    <td>Usuario: testodrina@gmail.com
        Comentario : Random string is ulala awonka gumba </td>
  </tr>
  <tr>
    <td>Pasos</td>
    <td><ul>
     <li> 1-Visitar la web: https://programadoresargentina.com </li>
     <li> 2-Visualizar el link "Contacto" en el navegador y hacer click (se puede hacer Scroll hacia abajo para posicionarce en la seccion "Contacto")</li>
     <li> 3-Rellenar el formulario con los "Datos de Entrada"</li>
     <li> 4-Visualizar la habilitacion del boton enviar</li>
     <li> 5-Limpiar los campos de "Correo Electronico" y "Mensaje"</li>
     <li> 6-Click en Enviar</li>
    </ul></td>
  </tr>
  <tr>
    <td>Resultado Esperado</td>
    <td>Se debe volver a bloquear el boton Enviar o no permitir el envio por datos invalidos en los campos.</td>
  </tr>
  <tr>
    <td>Resultado Obtenido</td>
    <td>El formulario arroja un mensaje de ejecucion exito y el API retorna un coigo 200</td>
  </tr>
  <tr>
    <td>Estado</td>
    <td>En Espera</td>
  </tr>
  <tr>
    <td>Img o Vid</td>
    <td>




https://github.com/FedeBazan/QaTraining/assets/48597230/4415d44b-bd63-4c11-9d35-49025d971323





</td>
  </tr>
 <tr>
    <td>Comentario</td>
    <td>otros casos similares ocurre al ejecutar los Steeps hasta el 3, con solo rellenar con un string que cumpla el formato de email en el campo correo electronico y salirse del campo con el correo colocado es posible correr otros tipos de defectos ya que en mensaje es solo rellenar los caracteres minimos para habilitar el boton de "Enviar"</td>
  </tr>
</table>
<!-- ------------------------------------------------------------------------------------------------------------------- -->

<!--
<table>
  <tr>
    <th>Reporte n°XXXX</th>
    <th></th>
  </tr>
  <tr>
    <td>ID</td>
    <td>GR99-002</td>
  </tr>
  <tr>
    <td>Titulo</td>
    <td></td>
  </tr>
  <tr>
    <td>Descripcion</td>
    <td></td>
  </tr>
  <tr>
    <td>Precondiciones</td>
    <td> </td>
  </tr>
 <tr>
    <td>Tipo de Bug</td>
    <td><b>REPASAR</b></td>
  </tr>
<tr>
    <td>Criticidad</td>
    <td></td>
  </tr>
  <tr>
    <td>Prioridad</td>
    <td></td>
  </tr>
  <tr>
    <td>Datos de Entrada</td>
    <td></td>
  </tr>
  <tr>
    <td>Pasos</td>
    <td></td>
  </tr>
  <tr>
    <td>Resultado Esperado</td>
    <td></td>
  </tr>
  <tr>
    <td>Resultado Obtenido</td>
    <td></td>
  </tr>
  <tr>
    <td>Estado</td>
    <td></td>
  </tr>
  <tr>
    <td>Img o Vid</td>
    <td></td>
  </tr>
  <tr>
    <td>Mejora</td>
    <td>Se debe guardar el estado del usuario, revisar trabajo de conexion entre web y bd. </td>
  </tr>
</table>-->
