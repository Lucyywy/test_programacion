# test_programacion$.ajax({
  url: http://localhost:8081/cursos/ concatenar el id que quieren eliminar jajjaj
  type: "DELETE",
  success: function(response) {
    // Manejar la respuesta exitosa aquí
    console.log("Eliminación exitosa", response);
  },
  error: function(error) {
    // Manejar errores aquí
    console.error("Error al eliminar", error);
  }
});
