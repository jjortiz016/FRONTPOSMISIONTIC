# FRONTPOSMISIONTIC
Proyecto POS Misión TIC 2022
Proyecto POS Misión TIC 2022

Realizar el seguimiento de las ventas requiere la construcción de unas interfaces de usuario que permitan: el ingreso a la aplicación, registro de productos, maestro de productos, registro de venta, maestro de las ventas y maestro de usuarios.

La aplicación web debe contar con los siguientes módulos:

● Gestión de ingreso al sistema de información. El sistema tendrá una interfaz gráfica para el ingreso a la aplicación (registro e inicio de sesión), la autorización de ingreso a la aplicación estaría a cargo de un tercero (Gmail) mediante “Oauth 2”; todos los usuarios que se registran entran en estado pendiente.

● Módulo administrador de productos. El sistema tendrá una interfaz gráfica para el registro de productos y otra para listar, buscar y actualizar productos, cada uno debe contar con los siguientes atributos: Identificador único (Inmutable), descripción, valor unitario y estado (disponible, no disponible).

● Módulo administrador de ventas. El sistema tendrá una interfaz gráfica para el registro de las ventas y otra para listar, buscar y actualizar las ventas realizadas (Actualizar se refiere a establecer los diferentes estados de la venta: En proceso, cancelada o entregada, o editar alguno de sus otros campos modificables). Cada venta debe contar con los siguientes atributos: Identificador único de venta (Inmutable), el valor total de la venta, identificador, cantidad y precio unitario de cada producto, fecha de venta, el documento de identificación y nombre del cliente, y, además, deberá contar con un encargado de gestionar dicha venta (vendedor).

● Gestión de usuarios. Permite ver y actualizar el rol (administrador y vendedor) y el estado del usuario (pendiente/autorizado/no autorizado)

Precisiones.

Se requiere que el proyecto cumpla con las historias de usuario presentadas en este documento, pero se da libertad para que el equipo de desarrollo pueda acordar realizar cualquier funcionalidad adicional.

No se requiere módulo de inventario, clientes o uno diferente a los que se presenta anteriormente.

No se requiere contemplar impuestos o valores adicionales en la venta.

La palabra usuario es usada en el contexto del proyecto como una persona cualquiera que se registra en su aplicativo web, esta puede ser alguien que no tiene relación con la empresa, por lo que por defecto el usuario tiene estado pendiente y no tiene rol, dicha persona solo podrá ingresar a la aplicación exitosamente cuando el administrador le cambie el estado a autorizado y le asigne un rol. El administrador tiene acceso total a la aplicación, mientras que el vendedor únicamente a las interfaces de usuario correspondientes a la de registro y maestro de ventas.

ARQUITECTURA:

API REST NODE JS + EXPRESS FRONT END REACT HTML5 CSS3
