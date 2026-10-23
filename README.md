<div align="center">

<img src="https://raw.githubusercontent.com/angel04-gifd/porcinotech-app/main/logo.png" alt="Logo de PorcinoTech" width="140" />

# PorcinoTech 🐖🌾

**Administra tu granja porcina desde el celular: cerdos, corrales, alimento y partos, todo en un solo lugar y en tiempo real.**

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)

[📥 **Descargar la app (APK)**](../../releases/latest)

</div>

---

## 📥 Instalar en tu teléfono

1. Entra a [**Releases**](../../releases/latest) y descarga **`PorcinoTech.apk`** (sección *Assets*).
2. Ábrelo en tu teléfono Android. Si te lo pide, permite **"Instalar apps desconocidas"** para el navegador o administrador de archivos que usaste.
3. Si aparece el aviso de **Play Protect**, elige **Instalar de todos modos** (la app no está en Play Store, por eso no está verificada).
4. Abre **PorcinoTech**, toca **Crear una cuenta** y elige: **crear tu granja** (administrador) o **unirte con un código** (operador).

> 📶 Necesitas conexión a internet: los usuarios de una misma granja comparten los datos en tiempo real.
> 🤖 Solo Android: en iPhone no se puede instalar un APK.

## 🚜 ¿Qué puedes hacer?

- 🐽 **Cerdos:** registro, edición y archivo, con arete único y control de peso.
- 🏚️ **Corrales:** capacidad, estado y etapa productiva de cada uno.
- 🌽 **Alimentación automática:** la ración diaria se calcula sola según los cerdos y la etapa de cada corral, y el stock se descuenta al registrar consumos.
- 🍼 **Inseminaciones y partos:** próximos partos, gestaciones fallidas y partos reales.
- 📈 **Panel de inicio:** gráfica de consumo y ☀️ clima en vivo con alerta de estrés por calor.
- 🏡 **Varias granjas:** cada una con sus datos separados; cambias entre ellas con un toque.
- 🔑 **Cuenta segura:** registro con correo y recuperación de contraseña con un código, sin salir de la app.
- ☁️ **Todo en la nube:** si desinstalas la app, inicias sesión y recuperas tus datos.
- 🔄 **Tiempo real:** los cambios de un compañero se ven al instante en la misma granja.

## 🧑‍🌾 Cuentas y granjas

- **Crear una granja** → eres **administrador**. Puedes tener varias y cambiar entre ellas con el botón de la granja en la barra superior.
- **Unirte con un código** → eres **operador**. El administrador ve el código en **Perfil > Mi granja** y te lo comparte.
- **Datos separados:** cada granja solo ve sus propios cerdos, corrales, alimentos, consumos y partos.

### 🔒 ¿Qué puede hacer cada rol?

| Acción | Administrador | Operador |
|---|:---:|:---:|
| Cerdos: ver, registrar, editar | ✅ | ✅ |
| Cerdos: eliminar | ✅ | ❌ |
| Corrales: ver y cambiar estado | ✅ | ✅ |
| Corrales: crear, editar datos, eliminar | ✅ | ❌ |
| Alimentos: ver y registrar consumo | ✅ | ✅ |
| Alimentos: crear, editar stock, eliminar | ✅ | ❌ |
| Inseminaciones y partos: registrar | ✅ | ✅ |
| Partos: eliminar | ✅ | ❌ |
| Ver el código de granja e invitar operadores | ✅ | ❌ |

## 🌽 ¿Cómo se calcula la ración?

Cada corral tiene una etapa (**Pre-inicio, Inicio, Desarrollo, Engorda, Gestación, Lactancia**) con una ración sugerida:

`cerdos activos del corral × ración de su etapa`

Al registrar un consumo, se resta del stock y no se permiten consumos mayores que la existencia.

## 💬 ¿Problemas o dudas?

Abre una observación en la pestaña [**Issues**](../../issues/new) de este repositorio: cuéntanos qué pasó y en qué pantalla.

---

<div align="center">

Proyecto de la materia **Desarrollo Móvil Integral** · Universidad Tecnológica del Valle del Mezquital (UTVM) 🎓

Hecho con 🌱 por [Angel Jovani Benitez Mezquite](https://github.com/angel04-gifd)

</div>
