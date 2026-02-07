# 💰 Alke Wallet - Módulo 2

## 📋 Descripción
Alke Wallet es una aplicación web de billetera digital que permite a los usuarios gestionar sus finanzas de manera segura y eficiente. Este proyecto forma parte del Módulo 2 del programa de desarrollo y proporciona funcionalidades esenciales para el manejo de dinero electrónico.

## ✨ Características

- **Inicio de Sesión Seguro**: Sistema de autenticación de usuarios
- **Panel de Control**: Menú principal con acceso a todas las funcionalidades
- **Depósitos**: Permite añadir fondos a la cuenta
- **Envío de Dinero**: Transferencias entre usuarios de forma rápida
- **Historial de Transacciones**: Visualización completa de movimientos financieros
- **Interfaz Responsive**: Diseño adaptable a dispositivos móviles y escritorio

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura de las páginas web
- **CSS3**: Estilos personalizados
- **Bootstrap 5.3.0**: Framework CSS para diseño responsive
- **JavaScript**: Lógica del lado del cliente
- **jQuery 3.7.0**: Biblioteca para manipulación del DOM
- **Font Awesome 6.4.0**: Iconos para mejorar la interfaz

## 📁 Estructura del Proyecto

```
alke_wallet_modulo2/
│
├── index.html              # Página principal (redirección a login)
├── login.html             # Página de inicio de sesión
├── menu.html              # Panel de control principal
├── deposit.html           # Página para realizar depósitos
├── sendmoney.html         # Página para enviar dinero
├── transactions.html      # Historial de transacciones
│
├── css/
│   └── styles.css        # Estilos personalizados
│
└── js/
    └── script.js         # Scripts JavaScript
```

## 🚀 Instalación

1. Clona este repositorio:
```bash
git clone https://github.com/tu-usuario/alke_wallet_modulo2.git
```

2. Navega al directorio del proyecto:
```bash
cd alke_wallet_modulo2
```

3. Abre el archivo `index.html` en tu navegador web preferido o utiliza un servidor local:
```bash
# Con Python 3
python -m http.server 8000

# Con Node.js (http-server)
npx http-server
```

## 💻 Uso

1. Al abrir la aplicación, serás redirigido automáticamente a la página de inicio de sesión
2. Ingresa tus credenciales (usuario y contraseña)
3. Una vez autenticado, accederás al menú principal
4. Desde el menú puedes:
   - Realizar depósitos a tu cuenta
   - Enviar dinero a otros usuarios
   - Consultar el historial de transacciones

## 🎯 Funcionalidades Principales

### Login
- Validación de credenciales
- Redirección automática al menú principal

### Depósitos
- Formulario para añadir fondos
- Validación de montos
- Confirmación de transacción

### Envío de Dinero
- Selección de destinatario
- Ingreso de monto a transferir
- Verificación de saldo disponible

### Transacciones
- Listado de todas las operaciones realizadas
- Filtros por fecha y tipo de transacción
- Visualización de detalles

## 🤝 Contribución

Las contribuciones son bienvenidas. Para cambios importantes:

1. Haz un Fork del proyecto
2. Crea una rama para tu característica (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## 📝 Notas de Desarrollo

- Asegúrate de tener conexión a internet para cargar las bibliotecas CDN (Bootstrap, jQuery, Font Awesome)
- El proyecto utiliza redirección automática desde `index.html` hacia `login.html`
- Los estilos personalizados se encuentran en `css/styles.css`
- La lógica JavaScript está centralizada en `js/script.js`

## 📄 Licencia

Este proyecto es parte de un ejercicio académico del Módulo 2.

## 👥 Autor

Desarrollado como parte del programa de formación en desarrollo web.

---

**Alke Wallet** - Gestiona tu dinero de forma digital y segura 💳