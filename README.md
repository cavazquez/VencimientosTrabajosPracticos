# Calculadora de Vencimiento de Exámenes

Una herramienta web simple para calcular las fechas de vencimiento de las materias aprobadas, incluyendo períodos regulares y complementarios.

## 🚀 Características

- Calcula automáticamente las fechas de vencimiento según el año y cuatrimestre de aprobación
- Soporta los tres períodos académicos: Verano, 1er Cuatrimestre y 2do Cuatrimestre
- Muestra tanto la fecha de vencimiento regular como la fecha complementaria
- Indica visualmente si la materia ya ha vencido
- Interfaz intuitiva y responsiva
- Incluye tests unitarios para validar el funcionamiento

## 🛠️ Tecnologías Utilizadas

- HTML5
- JavaScript (ES6+)
- [Tailwind CSS](https://tailwindcss.com/) para los estilos
- Sin dependencias externas (solo CDN de Tailwind)

## 📅 Cálculo de Vencimientos

El sistema calcula los vencimientos de la siguiente manera:

- **1er Cuatrimestre/Verano**:
  - Vencimiento: Febrero/Marzo del año + 4
  - Complementaria: Abril del año + 4

- **2do Cuatrimestre**:
  - Vencimiento: Julio/Agosto del año + 4
  - Complementaria: Septiembre del año + 4

## 🚀 Cómo Usar

1. Ingresa el año en que aprobaste la materia
2. Selecciona el cuatrimestre o verano correspondiente
3. Haz clic en "Calcular vencimiento"
4. Verás las fechas de vencimiento y si la materia ya venció

## 📝 Notas Importantes

- Las fechas de vencimiento están sujetas a la aprobación del Consejo Directivo de cada año
- Se recomienda verificar la información en el Departamento de Alumnos (Pabellón 2)
- Esta herramienta es de carácter informativo y no reemplaza la información oficial de la facultad

## 🧪 Tests

El código incluye pruebas unitarias que validan el correcto funcionamiento del cálculo de fechas. Los tests se ejecutan automáticamente al cargar la página y los resultados se muestran en la consola del navegador.

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

---
