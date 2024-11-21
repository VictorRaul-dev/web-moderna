# La Web Moderna

## Autor
- **Nombre completo:** Victor Raul Cercado Lopez  
- **Nombre del curso:** Desarrollo Web Moderna  
- **Email:** vicraul.vrcl@gmail.com  
- **Fecha de creación del proyecto:** 20 de noviembre de 2024  

## Sobre el Proyecto
En “La Web Moderna” podrás leer los conceptos clave que todo Desarrollador de Software debe saber para crear aplicaciones web.

## eslintrc
El archivo `.eslintrc.json` configura las reglas y estilo de código que se deben seguir para mantener la calidad del código. Aquí explico cada línea:

```json
{
  "env": {
    "browser": true, // Define que el entorno es un navegador, habilitando variables como 'window' y 'document'.
    "es2021": true // Permite características de ECMAScript 2021.
  },
  "extends": ["eslint:recommended"], // Usa las reglas recomendadas por ESLint como base.
  "parserOptions": {
    "ecmaVersion": "latest", // Utiliza la última versión disponible del estándar ECMAScript.
    "sourceType": "module" // Habilita el uso de módulos ES6 (import/export).
  },
  "rules": {
    "indent": ["error", 2], // Obliga a usar una indentación de 2 espacios. Genera un error si no se cumple.
    "linebreak-style": ["error", "unix"], // Requiere que los saltos de línea sigan el estilo Unix ('\n').
    "quotes": ["error", "single"], // Obliga a usar comillas simples ('') en lugar de dobles ("").
    "semi": ["error", "always"], // Obliga a usar punto y coma (;) al final de cada línea.
    "no-unused-vars": "warn", // Muestra una advertencia si hay variables declaradas pero no utilizadas.
    "no-console": "warn" // Muestra una advertencia si se usa 'console.log' o cualquier función de consola.
  }
}
```
## Despliegue

- [Ver Sitio Web](https://victorraul-dev.github.io/web-moderna/)
