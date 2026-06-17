# Criterios de Aceptación y Pruebas del Sistema COOPAC

## Objetivo

Este documento describe criterios de aceptación y pruebas básicas para validar el funcionamiento principal del sistema COOPAC-CM, considerando el sitio público, simulador de créditos, panel interno, gestión de contenidos, RRHH y control de accesos.

## 1. Sitio público

### Criterios de aceptación

- El visitante debe poder ingresar al inicio sin iniciar sesión.
- El sistema debe mostrar información institucional de la cooperativa.
- El visitante debe poder acceder a secciones como quiénes somos, servicios, agencias, transparencia y noticias.
- El sistema debe mostrar anuncios vigentes en la página principal.

### Pruebas sugeridas

- Ingresar a la página principal.
- Verificar que carguen las secciones públicas.
- Revisar que las noticias publicadas sean visibles.
- Confirmar que los anuncios activos aparezcan correctamente.

## 2. Simulador de créditos

### Criterios de aceptación

- El prospecto debe poder ingresar sus datos personales.
- El sistema debe validar datos obligatorios como nombre, DNI, celular, monto, plazo y agencia.
- El sistema debe calcular una cuota estimada.
- El sistema debe generar una tabla de amortización.
- La simulación debe guardarse con estado inicial nuevo.

### Pruebas sugeridas

- Enviar el formulario con datos completos.
- Probar el formulario dejando campos vacíos.
- Verificar que se muestre la cuota calculada.
- Confirmar que el registro aparezca en el panel de simulaciones.

## 3. Dashboard de simulaciones

### Criterios de aceptación

- El asesor o administrador debe poder ver las simulaciones registradas.
- El sistema debe permitir filtrar por nombre, DNI, celular, monto, plazo, tipo, agencia, estado y fecha.
- El usuario autorizado debe poder cambiar el estado de una simulación.
- El sistema debe permitir exportar información en CSV o Excel.

### Pruebas sugeridas

- Iniciar sesión como asesor.
- Ingresar al módulo de simulaciones.
- Aplicar filtros de búsqueda.
- Cambiar el estado de una simulación.
- Exportar los registros.

## 4. Gestión de contenidos

### Criterios de aceptación

- El responsable de imagen o administrador debe poder crear anuncios.
- El sistema debe permitir subir imágenes para anuncios.
- El usuario autorizado debe poder crear noticias.
- Las noticias pueden estar en estado borrador o publicado.
- Solo las noticias publicadas deben mostrarse en el sitio público.

### Pruebas sugeridas

- Crear un anuncio nuevo.
- Editar el orden y vigencia del anuncio.
- Crear una noticia como borrador.
- Publicar una noticia.
- Verificar que la noticia publicada aparezca en la página pública.

## 5. Gestión de asesores

### Criterios de aceptación

- El usuario de RRHH o administrador debe poder registrar asesores.
- El sistema debe permitir editar información del asesor.
- El sistema debe permitir eliminar asesores cuando corresponda.
- Los asesores deben tener acceso al módulo de simulaciones.

### Pruebas sugeridas

- Iniciar sesión como RRHH.
- Crear un asesor.
- Editar sus datos.
- Verificar que el asesor pueda acceder al panel correspondiente.

## 6. Roles y permisos

### Criterios de aceptación

- El administrador debe poder asignar roles a los usuarios.
- El sistema debe restringir módulos según rol.
- Un usuario sin permiso no debe poder acceder a rutas administrativas.
- El panel debe redirigir al usuario según su rol.

### Pruebas sugeridas

- Iniciar sesión como administrador.
- Asignar rol a un usuario.
- Probar acceso con rol asesor.
- Probar acceso con rol imagen.
- Probar acceso con rol RRHH.
- Confirmar que un usuario sin permiso sea bloqueado.

## Conclusión

Los criterios de aceptación permiten comprobar que el sistema COOPAC cumple con sus funcionalidades principales. Estas pruebas ayudan a validar el correcto funcionamiento del sitio público, simulador, panel administrativo, gestión de contenidos, RRHH y seguridad por roles.
