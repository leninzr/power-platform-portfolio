### 🏷️ Estándares de Nomenclatura y Buenas Prácticas

Para garantizar la mantenibilidad, escalabilidad y una transferencia de conocimiento limpia en proyectos en equipo, se aplica estrictamente el siguiente estándar de prefijos para los elementos de la solución:

| Elemento / Control | Prefijo | Ejemplo de Uso | Descripción / Buenas Prácticas |
| :--- | :---: | :--- | :--- |
| **Canvas App** | `app_` | `app_ControlInventario` | Nombre general de la aplicación en PascalCase. |
| **Screen** | `scr_` | `scr_DashboardPrincipal` | Pantallas principales de la interfaz. |
| **Container (Fijo/Flexible)** | `con_` | `con_FormularioResponsivo` | Contenedores para agrupar elementos y estructurar layouts responsivos. |
| **Button** | `btn_` | `btn_GuardarRegistro` | Botones de acción ejecutable. |
| **Gallery** | `gal_` | `gal_ListaTickets` | Contenedores de datos conectados a orígenes dinámicos. |
| **Text Input** | `txt_` | `txt_BusquedaCliente` | Campos de entrada de texto por parte del usuario. |
| **Dropdown / Combo** | `cmb_` | `cmb_FiltrarEstatus` | Controles de selección múltiple o simple. |
| **Label** | `lbl_` | `lbl_TituloFormulario` | Textos estáticos o dinámicos informativos. |
| **Form** | `frm_` | `frm_DetalleSolicitud` | Formularios nativos de edición o visualización. |
| **Image** | `img_` | `img_FotoPerfilUsuario` | Control para mostrar imágenes locales o URLs dinámicas. |
| **Icon / Shape** | `ico_` | `ico_DescargarReporte` | Íconos nativos y formas geométricas de la interfaz. |
| **Toggle / Switch** | `tgl_` | `tgl_ActivarNotificaciones` | Interruptores binarios (Verdadero/Falso). |
| **Checkbox** | `chk_` | `chk_AceptarTerminos` | Casillas de selección múltiple independiente. |
| **Timer** | `tmr_` | `tmr_CierreSesionAutomatica` | Temporizadores para ejecutar código después de un intervalo. |
| **Global Variable** | `gbl_` | `gbl_UsuarioActual` | Variables definidas con `Set()` accesibles en toda la app. |
| **Context Variable** | `ctx_` | `ctx_EsModoEdicion` | Variables locales definidas con `UpdateContext()`. |
| **Collection** | `col_` | `col_CarritoProductos` | Tablas en memoria local creadas con `ClearCollect()`. |
