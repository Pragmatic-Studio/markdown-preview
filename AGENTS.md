Este proyecto se adhiere a las siguientes reglas y principios de desarrollo para mantener la consistencia y la calidad del código. Por favor, tenlos en cuenta al sugerir o generar código.

1. Stack Tecnológico
Evitar bibliotecas y frameworks externos: El código debe ser 100% nativo. No se deben utilizar librerías de terceros como jQuery, Bootstrap o React.

Tecnologías permitidas: Usa únicamente HTML5, CSS3 y JavaScript (ES6+) para la lógica de la aplicación.

2. Organización del Proyecto
El código debe estar bien estructurado en las siguientes carpetas para facilitar la navegación y el mantenimiento:

src/: Contiene el código fuente principal.

js/: Para todos los archivos de JavaScript.

css/: Para todas las hojas de estilo.

assets/: Para recursos como imágenes, fuentes y videos.

index.html: Archivo principal en la raíz del proyecto.

3. Principios de Código
SOLID: En la medida de lo posible, el código JavaScript debe seguir los principios de SOLID para un diseño modular y de fácil mantenimiento.

S (Single Responsibility Principle): Cada módulo o función debe tener una única responsabilidad.

O (Open/Closed Principle): Las entidades deben estar abiertas para extensión, pero cerradas para modificación.

L (Liskov Substitution Principle): Los objetos de un subtipo deben poder ser sustituidos por objetos de su supertipo sin alterar la corrección del programa.

I (Interface Segregation Principle): Los clientes no deben ser forzados a depender de interfaces que no utilizan.

D (Dependency Inversion Principle): Los módulos de alto nivel no deben depender de módulos de bajo nivel. Ambos deben depender de abstracciones.

Comentarios y Documentación: Agrega comentarios claros y concisos en las partes más complejas del código para explicar la lógica.

Convenciones de Nombres: Usa nombres de variables y funciones descriptivos y coherentes. Prefiere camelCase para JavaScript y kebab-case para clases de CSS.

