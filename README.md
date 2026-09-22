# Playr Web

Sitio estático de soporte para la app Playr (público a propósito -- no
contiene código fuente de la app, solo páginas que usan la anon key de
Supabase igual que la app móvil).

- `/reset-password/` -- completa el restablecimiento de contraseña
  directo en el navegador (sin depender de tener la app instalada), con
  opción de abrir en la app si se prefiere. Ver el correo de
  "Restablecer contraseña" en el repo principal (`playr/supabase/
  email-templates/reset-password.html`) para el enlace exacto que se
  manda.
- `/legal/` -- Términos y Condiciones + Política de Privacidad públicos
  (requisito de Google Play para usuarios sin la app instalada). Migrada
  desde un artefacto de claude.ai -- esta página en GitHub Pages es ahora
  la fuente canónica; actualízala junto con `playr/LEGAL.md` y
  `legal_documents` en la base cada vez que se publique una versión
  nueva (mismo contenido en los 3 lugares).

Pensado para crecer con más sub-páginas de soporte web más adelante (ej.
acceso de dueños de cancha a sus reservas desde un navegador).
