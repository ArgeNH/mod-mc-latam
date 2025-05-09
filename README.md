# 🎮 Minecraft Resources Colombia

## 📝 Descripción
Este repositorio contiene una colección de mods y plugins para Minecraft desarrollados en Colombia, enfocados en mejorar la experiencia de juego y agregar contenido único inspirado en la cultura colombiana.

## 👨‍💻 Desarrollador
- **Nombre:** Arge Niño
- **GitHub:** [@ArgeNH](https://github.com/ArgeNH)
- **Sitio Web:** [argenh.dev](https://argenh.dev)


## 🚀 Características
- Mods y plugins optimizados para servidores colombianos
- Integración con sistemas de economía local
- Contenido cultural colombiano
- Soporte multilingüe (Español/Inglés)

## 🛠️ Requisitos
- Minecraft Java Edition
- Java 17 o superior
- Forge/Fabric (dependiendo del mod)

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Por favor, lee nuestras guías de contribución antes de enviar un pull request.

## 📄 Licencia
Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 📞 Contacto
- LinkedIn: [in/argenino](https://linkedin.com/in/argenino)
- Twitter: [@arge_nino](https://twitter.com/arge_nino)
- Instagram: [@arge.nino](https://instagram.com/arge.nino)

## 🌱 Flujo de ramas y convención de nombres

Para mantener el orden y facilitar la colaboración, sigue este flujo y convención para la creación de ramas:

### Ramas principales

- **main**: Rama principal, contiene el código listo para producción.
- **NH-develop**: Rama de desarrollo principal. Aquí se integran las nuevas características antes de pasar a main.

### Ramas secundarias (feature, fix, hotfix, etc.)

Crea ramas a partir de `NH-developer` usando la siguiente sintaxis:

- **NH-feature/[nombre-descriptivo]**: Para nuevas funcionalidades.
  - Ejemplo: NH-feature/sistema-economia
- **NH-fix/[nombre-descriptivo]**: Para corrección de errores.
  - Ejemplo: NH-fix/corrige-bug-economia
- **NH-hotfix/[nombre-descriptivo]**: Para correcciones urgentes en producción.
  - Ejemplo: NH-hotfix/arreglo-crash-servidor
- **NH-docs/[nombre-descriptivo]**: Para cambios en la documentación.
  - Ejemplo: NH-docs/actualiza-readme

### Flujo de trabajo recomendado

1. Crea tu rama a partir de `NH-developer`:
   ```bash
   git switch NH-developer
   git pull
   git switch -c NH-feature/mi-nueva-funcionalidad
   ```
2. Realiza tus cambios y haz commits descriptivos.
3. Haz push de tu rama:
   ```bash
   git push origin NH-feature/mi-nueva-funcionalidad
   ```
4. Abre un Pull Request hacia `NH-developer`.
5. Espera revisión y mergea cuando esté aprobado.

---
⭐️ Desarrollado con ❤️ en Colombia
