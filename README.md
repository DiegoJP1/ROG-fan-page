# ROG-fan-page
proyecto-3 
hecho con localhost -> asus -> 
CREATE TABLE `usuarios` (
  `id` int(11) NOT NULL,
  `correo` varchar(255) NOT NULL,
  `nombre` varchar(100) NOT NULL,
  `genero` enum('Masculino','Femenino','Otro') NOT NULL,
  `avatar` varchar(255) DEFAULT NULL,
  `contrasena` varchar(100) NOT NULL,
  `rol` varchar(20) DEFAULT 'usuario'
) 
aviso:proyecto incompleto 
