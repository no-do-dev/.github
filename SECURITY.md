# Política de seguridad · Security Policy

> **ES** · Divulgación responsable para los servicios de NO-DO.DEV.
> **EN** · Coordinated disclosure for NO-DO.DEV services. English below.

---

## Alcance

Esta política cubre los servicios en producción de NO-DO.DEV:

- **no-do.dev** y subdominios (`tracez.no-do.dev`, `grimz.no-do.dev`, APIs asociadas)
- **TRACEZ** — investigación OSINT / GEOINT
- **GRIMZ** — superficie de ataque y operación autorizada

El código de las plataformas es propietario y vive en repositorios privados. No hay demos públicas: si encuentras un fallo, será en el servicio en vivo.

## Cómo reportar

Escribe a **contacto@no-do.dev** con:

- Descripción del fallo y su impacto.
- Pasos de reproducción (PoC mínima; sin volcados masivos de datos de terceros).
- Dominio, endpoint o componente afectado.

Confirmamos recepción en **72 horas** y mantenemos el canal abierto hasta el cierre.

## Reglas (safe harbor)

Investigación de buena fe dentro de estos límites — no la trataremos como acceso no autorizado:

- **No** accedas, modifiques ni exfiltres datos que no sean tuyos; usa cuentas de prueba propias.
- **No** ejecutes DoS, fuerza bruta sostenida ni ingeniería social contra el equipo o los usuarios.
- Limita las pruebas al mínimo necesario para demostrar el fallo y para ahí.
- Danos un plazo razonable para corregir antes de cualquier publicación. Coordinamos la fecha contigo.

Estas mismas reglas son las que GRIMZ exige a sus operadores: alcance explícito y autorización por diseño. Las aplicamos también a quien nos audita.

## Fuera de alcance

Normalmente no accionables salvo que demuestres impacto real: ausencia de cabeceras best-practice, auto-XSS, reportes automáticos de escáner sin PoC, rate-limiting en formularios públicos, versiones de software sin vulnerabilidad explotable.

---

## Scope (EN)

Covers NO-DO.DEV production services: **no-do.dev** and subdomains, **TRACEZ** (OSINT/GEOINT) and **GRIMZ** (authorized offensive tooling). Platform code is proprietary and private — findings will be against the live service, not this repo.

## Reporting (EN)

Email **contacto@no-do.dev** with a description, impact, minimal reproduction steps and the affected endpoint. We acknowledge within **72 hours** and keep the thread open until resolution.

## Safe harbor (EN)

Good-faith research within these bounds is not treated as unauthorized access: don't access, alter or exfiltrate data that isn't yours (use your own test accounts); no DoS, sustained brute force or social engineering; keep testing to the minimum needed to prove the issue; give us reasonable time to fix before disclosing, on a date we coordinate with you.

These are the same rules GRIMZ enforces on its operators — explicit scope, authorization by design — applied to those who audit us.
