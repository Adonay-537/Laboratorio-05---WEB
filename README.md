# Laboratorio-05---WEB

¿Por qué React se comporta como si fuera HTML puro?
Aunque estemos escribiendo JSX (que parece HTML), React no lo interpreta directamente como tal. JSX es una sintaxis que se transforma en funciones de JavaScript que crean elementos virtuales. React usa el Virtual DOM, una representación en memoria de la estructura del HTML, para calcular los cambios antes de aplicarlos al DOM real. Por eso, aunque parece HTML, lo que realmente estás haciendo es construir interfaces con JavaScript que terminan renderizándose como HTML estándar en el navegador.

¿Qué significa className en React? ¿las props tienen un limite? ¿Quién define las props?
Un class name es la forma correcta de asignar clases CSS en React. Internamente, React traduce eso al atributo class cuando genera el HTML final.Con respecto a las props, no hay un límite técnico en la cantidad de props que puedes pasar a un componente. Se puede enviar tantos como quieras. Pero desde el punto de vista de buenas prácticas, es mejor mantenerlos organizados y no abusar. Por ultimo las props son definidas por el componente padre.
