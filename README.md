# API REST de Administración de Usuarios

Esta API REST permite administrar usuarios y proporciona varios endpoints para realizar operaciones relacionadas con ellos.

## Endpoints

### Listar todos los usuarios

Obtiene una lista de todos los usuarios registrados.

- **Método:** GET
- **Ruta:** `/`
- **Respuesta exitosa (Código 200):**
  ```json
  [
    {
      "id": "2a543f41-c73e-4849-b6cf-a02dec6481dc",
      "cedula_identidad": "123456789",
      "nombre": "Usuario 1",
      "primer_apellido": "Apellido 1",
      "segundo_apellido": "Apellido 2",
      "fecha_nacimiento": "2000-01-01"
    },
    {
      "id": "f71ef553-86c4-4a0a-ad25-112008de7d0b",
      "cedula_identidad": "987654321",
      "nombre": "Usuario 2",
      "primer_apellido": "Apellido 3",
      "segundo_apellido": "Apellido 4",
      "fecha_nacimiento": "1995-05-10"
    }
    // ... otros usuarios
  ]
```

