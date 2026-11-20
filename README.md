# Verificador de Redirecciones HTTP 301/302 y Cadenas de Saltos

[![Verificador Redirecciones](https://img.shields.io/badge/TAVARDT-Redirect%20301-5b3cf5.svg)](https://tools.tavardt.com/es/verificador-redirecciones-301/)
[![Jurisdiccion](https://img.shields.io/badge/Jurisdiccion-Espana-00C853.svg)](https://ag.tavardt.com/es/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de cadenas de redireccion, deteccion de bucles infinitos y conservacion de PageRank en Espana.

Desarrollado y mantenido por la division de ingenieria web y optimizacion de rastreo de **[TAVARDT Espana](https://ag.tavardt.com/es/)**.

---

## Capacidades de Auditoria de Redirecciones HTTP

* **Rastreo Completo de Cadenas de Saltos**: Inspeccion de codigos HTTP (301, 302, 307, 308) y tiempos de transicion.
* **Deteccion de Bucles Infinitos**: Identificacion de rutas circulares que provocan fallos de carga en navegadores y buscadores.
* **Conservacion de Autoridad y PageRank**: Alertas contra cadenas excesivas que consumen presupuesto de rastreo y diluyen autoridad.
* **Control de Seguridad de Protocolo**: Deteccion de degradaciones temporales a HTTP inseguro.
* **Puntuacion de Eficiencia de Redireccion**: Indice cuantitativo de 0 a 100 con pasos de subsanacion tecnica.

---

## Instalacion y Ejecucion

Requiere Python 3.8 o superior sin dependencias externas.

```bash
git clone https://github.com/TAVARDT-Espana/redirect-301-tracker-es.git
cd redirect-301-tracker-es
python redirect_tracker.py https://empresa.es
```

Para generar salida estructurada JSON:

```bash
python redirect_tracker.py https://empresa.es --json
```

---

## Diagnostico Completo en la Web

Para revision profunda de cadenas de redireccion:

* **[Verificador de Redirecciones 301 Oficial](https://tools.tavardt.com/es/verificador-redirecciones-301/)**
* **[Portal Corporativo TAVARDT Espana](https://ag.tavardt.com/es/)**

---

## Consultoria en Migraciones y SEO Tecnico

Para migraciones seguras y conservacion de trafico bajo directrices de Estandares W3C y Directrices IETF RFC 9110, consulte al equipo de **[TAVARDT Espana](https://ag.tavardt.com/es/contacto/)**.
