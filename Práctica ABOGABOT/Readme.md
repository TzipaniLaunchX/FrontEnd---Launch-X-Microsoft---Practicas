# `Práctica ABOGABOT`
_____________________________________________________________________________________________
## `Descripción del caso` 
- Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a traves de una página web llenando un formulario.

- Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción.

- Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal.

- El administrador del sitio recbe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legal en formato word para empezar el proceso.

- El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos.

- El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso.

- Al usuario le llegan correos de notificación para saber el avance de su proceso.

- La página debe de ser responsive para poderla ver desde el celular.

- La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.

## `Toma de requerimientos`
- Creación de una página web responsive (Web/Movil)
- Roles: `Usuario`, `Administrador` y `Sistema`.
- Inicio de sesión de `Usuario` y `Administrador`.

### `Usuario`
- Inicio de sesión/Creación de cuenta
  - Se requiere Nombre completo e e-mail.
- Formulario con los datos del cliente y de la demanda. 
- Procesamiento de pago
  - Metodo de pago [Tarjeta de crédito/débito, transferencia bancaria, Depósito en punto de venta]
- Seguimiento de la/s demanda/s.
- Recepción de notificaciones de actualización de la demanda vía e-mail.

### `Administrador` 
- Notificación de nueva demanda en el sistema e e-mail con cada nueva demanda.
- Recepción de un documento Word (.doc) generado por el sistema, con la información de la demanda proporcionada por el cliente.
- Recepción de pago [Cuenta bancaria, Wallet, etc.]
- Dashboard con balance de ingresos
  - Sección para ver información de cada depósito recibido.
  - Código de asignación para rastrear que pago corresponde a que demanda.
- Opción para añadir comentarios de actualización del proceso de demanda.

### `Sistema`
- Generación de documento Word (.doc) con la información proporcionada por el cliente en el formulario.
- Diseño en color azul marino y blanco (se aceptan otros).


## `Buyer persona`

![Buyer Persona](https://user-images.githubusercontent.com/114957103/201801225-6c458aea-91f4-4756-bb0c-f6a0b5db4c08.png)

## `Público objetivo`
![Target Audience](https://user-images.githubusercontent.com/114957103/201803322-d10dc370-4de1-477f-a51b-5ec7a7a31d69.jpg)
Este diagrama fue creado en [miro] (https://miro.com/app/board/uXjVPEM4_Ik=/?share_link_id=587411906097)

