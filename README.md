# Ejercicio

1. Mostrar Información Básica con Props
Crea un componente Tarjeta que reciba como props el nombre y la descripción de un artículo, y muéstralos dentro de una tarjeta.
2. Pasar Props con Números
Crea un componente Producto que reciba el nombre y precio de un producto como props y muestre la información en un formato legible.
3. Controlar el Tipo de Prop
Crea un componente Avatar que reciba como prop la URL de una imagen de perfil y el tamaño de la imagen (en píxeles). Asegúrate de que el tamaño sea de tipo Number.
4. Pasar Objetos como Props
Crea un componente Usuario que reciba como prop un objeto con la información de un usuario (nombre, apellido, edad) y muéstrelo en un formato de tarjeta.
5. Renderizado Condicional con Props
Crea un componente EstadoPedido que reciba como prop el estado de un pedido (por ejemplo, "enviado", "pendiente", "cancelado") y muestre un mensaje diferente dependiendo del estado.
DEBEN USAR Bootstrap Y subirlos a un repositorio

  name: 'Tarjeta',
  props: {
    nombre: String,
    descripcion: String
  }