---
theme: default
layout: center
class: text-center
highlighter: shiki
lineNumbers: false
info: Presentación Ejecutiva PICS
drawings:
  persist: false
transition: slide-up
title: Sistema de Mapeo Dinámico Vial
mdc: true
---

# Sistema de Mapeo Dinámico Vial

<div class="mt-10 text-xl text-gray-300">
  Transformando la infraestructura urbana con <span class="text-[#00aaff] font-bold">Inteligencia Artificial</span>
</div>

<!-- <div class="absolute bottom-10 left-0 right-0 text-sm text-gray-500 bg-black/50 py-2 backdrop-blur-sm">
  Presentación
</div> -->

<style>
h1 {
  background-color: #00aaff;
  background-image: linear-gradient(45deg, #00aaff 10%, #0055aa 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  font-size: 4.5rem;
  font-weight: 900;
  text-shadow: 0px 4px 20px rgba(0,0,0,0.8);
}
</style>

---
layout: default
---

# El desafío actual en la gestión pública

El mantenimiento de la red vial enfrenta limitaciones históricas que cuestan tiempo y recursos.

<div class="grid grid-cols-2 gap-8 mt-10">
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-time class="inline-block mr-2 text-[#00aaff]"/> Relevamientos Lentos</h3>
    <p class="text-gray-400 text-sm">Las inspecciones manuales son costosas, requieren mucho personal y tardan meses en cubrir todo el municipio.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-warning-alt class="inline-block mr-2 text-[#00aaff]"/> Subjetividad</h3>
    <p class="text-gray-400 text-sm">La catalogación del daño depende del criterio del inspector. No hay métricas estandarizadas.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-map class="inline-block mr-2 text-[#00aaff]"/> Falta de Datos Georreferenciados</h3>
    <p class="text-gray-400 text-sm">La toma de decisiones presupuestarias se hace "a ciegas", sin un mapa actualizado en tiempo real.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-network-4 class="inline-block mr-2 text-[#00aaff]"/> Desconexión</h3>
    <p class="text-gray-400 text-sm">Falta de herramientas integradas que conecten la calle directamente con el escritorio del Secretario de Obras Públicas.</p>
  </div>
</div>

---
layout: default
---

# Comparativa de Procesos: Tradicional vs. Dinámico

¿Cómo transformamos un proceso manual costoso en una solución automática eficiente?

<div class="grid grid-cols-2 gap-6 mt-4">
  <div class="p-4 border border-slate-700/40 rounded-xl bg-slate-900/20 backdrop-blur-sm" v-click>
    <h3 class="text-slate-400 text-lg font-bold mb-2.5 flex items-center gap-2">
      <carbon-warning-alt class="text-xl text-slate-400"/> Relevamiento Tradicional
    </h3>
    <ul class="space-y-1.5 text-xs text-gray-400">
      <li><strong>Planillas Manuales:</strong> Inspectores a pie o en vehículo anotando datos a mano.</li>
      <li><strong>Criterio Subjetivo:</strong> La gravedad del bache depende de la opinión de cada inspector.</li>
      <li><strong>Lento e Ineficiente:</strong> Semanas de trabajo administrativo para digitalizar y analizar.</li>
      <li><strong>Costoso y Estático:</strong> Red desactualizada; la red vial se degrada más rápido de lo que se mide.</li>
    </ul>
  </div>

  <div class="p-4 border border-[#00aaff]/35 rounded-xl bg-[#0d1527]/40 backdrop-blur-sm shadow-[0_4px_20px_rgba(0,170,255,0.05)]" v-click>
    <h3 class="text-[#00aaff] text-lg font-bold mb-2.5 flex items-center gap-2">
      <carbon-checkmark class="text-xl text-[#00aaff]"/> Relevamiento Dinámico
    </h3>
    <ul class="space-y-1.5 text-xs text-gray-300">
      <li><strong>Mapeo Pasivo:</strong> Celular en parabrisas de vehículos en ruta habitual (camión de basura, patrullas).</li>
      <li><strong>Objetividad con IA:</strong> Visión computacional estandariza severidades sin error humano.</li>
      <li><strong>Procesamiento Cloud:</strong> Alertas y reportes consolidados automáticamente en el día.</li>
      <li><strong>Costo de Hardware $0:</strong> Aprovecha recursos existentes de forma continua y escalable.</li>
    </ul>
  </div>
</div>

<div class="mt-5 text-center text-xs text-gray-400" v-click>
  <span class="text-[#00aaff] font-bold">Métrica de Impacto:</span> Reducción del <strong>90%</strong> en tiempos de relevamiento de toda la infraestructura vial municipal.
</div>

---
layout: default
---

# La solución: ¿Qué es el sistema de mapeo dinámico del estado vial?

<div class="mb-8 text-gray-300">
  Una plataforma integral que automatiza el relevamiento de calles utilizando cámaras de smartphones en vehículos municipales, procesando todo con IA en la nube.
</div>

<div class="grid grid-cols-3 gap-6 text-center mt-12">
  <div class="p-6 pics-card" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-video/></div>
    <h3 class="font-bold mb-2 text-[#00aaff]">Captura Móvil</h3>
    <p class="text-xs text-gray-400">App web que registra video y telemetría de coordenadas desde cualquier vehículo, optimizada para zonas sin señal.</p>
  </div>
  
  <div class="p-6 pics-card" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-machine-learning-model/></div>
    <h3 class="font-bold mb-2 text-[#00aaff]">Análisis IA</h3>
    <p class="text-xs text-gray-400">Detecta baches y grietas automáticamente. Unifica daños cercanos mediante criterios geoespaciales.</p>
  </div>

  <div class="p-6 pics-card" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-dashboard/></div>
    <h3 class="font-bold mb-2 text-[#00aaff]">Gestión y Reportes</h3>
    <p class="text-xs text-gray-400">Dashboard interactivo con mapas y reportes generados por un asistente virtual inteligente.</p>
  </div>
</div>

---
layout: default
---

# PozoCam: Los ojos del Sistema

<div class="grid grid-cols-2 gap-8 mt-6">
<div class="flex flex-col justify-center">
<p class="text-sm text-gray-400 mb-4 leading-tight">
  La recolección no requiere hardware costoso. Operamos sobre los parabrisas con celulares de los empleados municipales.
</p>
<ul class="space-y-3 text-sm text-gray-300 leading-snug">
<li v-click>
  <strong class="text-[#00aaff] block mb-0.5">Resiliencia Offline:</strong>
  Guarda todo localmente y sube los datos solo al recuperar la conexión estable.
</li>
<li v-click>
  <strong class="text-[#00aaff] block mb-0.5">Subida Multipartes:</strong>
  Si se corta internet a la mitad, no se pierde el video; el sistema retoma exactamente desde el último fragmento.
</li>
<li v-click>
  <strong class="text-[#00aaff] block mb-0.5">Telemetría Exacta:</strong>
  Sincronización geoespacial para ubicar con precisión dónde se encuentra cada anomalía.
</li>
</ul>
</div>

<div class="flex items-center justify-center" v-click>
  <img src="./assets/pozocam_app.jpg" alt="PozoCam App UI" class="rounded-xl border border-white/5 shadow-[0_4px_20px_rgba(0,170,255,0.1)] hover:border-[#00aaff]/40 transition-all duration-300 max-h-80 object-contain" />
</div>
</div>

---
layout: default
---

# Inteligencia Artificial de Frontera

No solo vemos la calle, **la entendemos**. Nuestro motor de visión computacional garantiza precisión y seguridad ciudadana.

<div class="grid grid-cols-2 gap-8 mt-8">
  <div>
    <h3 class="text-xl font-bold mb-4 border-b border-white/10 pb-2 text-[#00aaff]">Detección Precisa</h3>
    <ul class="space-y-3 text-sm text-gray-400">
      <li v-click><span class="text-[#00aaff] font-bold">Tres categorías clave:</span> Baches, Grietas y Calles de Tierra.</li>
      <li v-click><span class="text-[#00aaff] font-bold">Cero Duplicados:</span> El sistema agrupa capturas sucesivas de un mismo daño en un recorrido, consolidando la alerta y conservando solo la imagen con mayor nitidez.</li>
      <li v-click><span class="text-[#00aaff] font-bold">Filtro Inteligente:</span> Ignora automáticamente el cielo, árboles o aves para concentrarse exclusivamente en la calzada.</li>
    </ul>
  </div>
  
  <div v-click>
    <div class="bg-[#080d1a]/55 border border-[#00aaff]/40 backdrop-blur-md p-6 rounded-xl shadow-[0_4px_20px_rgba(0,0,0,0.4)] hover:border-[#00aaff]/80 hover:shadow-[0_0_20px_rgba(0,170,255,0.15)] transition-all duration-300">
      <div class="text-3xl mb-2"><carbon-security class="text-[#00aaff]"/></div>
      <h3 class="text-xl font-bold text-[#00aaff] mb-2">Privacidad por Diseño</h3>
      <p class="text-sm text-gray-400">
        Cumplimos con las normativas de protección de datos. Antes de que cualquier imagen se almacene en el servidor municipal, el sistema <strong>difumina automáticamente rostros de peatones y patentes de vehículos</strong>.
      </p>
    </div>
  </div>
</div>

---
layout: default
---

# Dashboard Municipal y Asistente Virtual

Pasamos de tener un "mapa lleno de puntos" a tener un **mapa de decisión estratégica**.

<div class="grid grid-cols-2 gap-8 mt-4">
  <ul class="space-y-3 text-xs text-gray-300 leading-snug">
    <li v-click>
      <strong class="text-[#00aaff] text-sm block mb-0.5">Priorización con Sentido Social (OSM)</strong>
      Cruza automáticamente los daños detectados con paradas de colectivo, escuelas y hospitales (OpenStreetMap).
      <br><span class="text-gray-400"><strong>Diferencial:</strong> Repara primero los daños de mayor rentabilidad y uso social.</span>
    </li>
    <li v-click>
      <strong class="text-[#00aaff] text-sm block mb-0.5">Control Humano (Human-in-the-Loop)</strong>
      Los inspectores validan o descartan falsos positivos generados por la IA.
      <br><span class="text-gray-400"><strong>Diferencial:</strong> Mantiene el criterio experto y reentrena al modelo continuamente.</span>
    </li>
    <li v-click>
      <strong class="text-[#00aaff] text-sm block mb-0.5">Automatización de Reportes e Informes</strong>
      El Asistente Virtual (LLM) redacta informes técnicos con vocabulario formal de obra pública.
      <br><span class="text-gray-400"><strong>Diferencial:</strong> Ahorra tiempo de oficina; reportes de bacheo listos en minutos.</span>
    </li>
  </ul>

  <div class="flex items-center justify-center" v-click>
    <img src="./assets/dashboard_general.png" alt="Panel de Inspección y Auditoría" class="rounded-xl border border-white/5 shadow-[0_4px_20px_rgba(0,170,255,0.1)] hover:border-[#00aaff]/40 transition-all duration-300 max-h-80 object-contain" />
  </div>
</div>

---
layout: default
---

# Centro de Control Inteligente
<div class="text-gray-400 text-sm mb-4">Visión consolidada del estado de la infraestructura vial del Municipio de Moreno.</div>

<div class="w-full flex justify-center items-center h-[75%]">
  <img src="./assets/inspeccion_deteccion.png" alt="Dashboard PICS Moreno" class="rounded-xl border border-[#00aaff]/40 shadow-[0_4px_30px_rgba(0,170,255,0.2)] hover:border-[#00aaff] transition-all duration-300 max-h-full object-contain" />
</div>

---
layout: center
class: text-center
---

# Ciclo de valor

<div class="flex justify-center items-center mt-10 gap-4">
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#0d1527]/60 backdrop-blur-sm border border-[#00aaff]/60 flex items-center justify-center text-2xl mb-2 shadow-[0_0_15px_rgba(0,170,255,0.15)] hover:border-[#00aaff] hover:shadow-[0_0_20px_rgba(0,170,255,0.3)] hover:-translate-y-[2px] transition-all duration-300"><carbon-car/></div>
    <span class="text-xs font-bold text-[#00aaff]">1. Captura Móvil</span>
  </div>
  <div class="w-12 h-0.5 bg-gradient-to-r from-[#00aaff] to-white/5" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#0d1527]/30 border border-white/5 flex items-center justify-center text-2xl mb-2 transition-all duration-300"><carbon-cloud-upload/></div>
    <span class="text-xs font-bold text-gray-400">2. Subida Segura</span>
  </div>
  <div class="w-12 h-0.5 bg-white/5" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#0d1527]/30 border border-white/5 flex items-center justify-center text-2xl mb-2 transition-all duration-300"><carbon-settings/></div>
    <span class="text-xs font-bold text-gray-400">3. Análisis y Privacidad</span>
  </div>
  <div class="w-12 h-0.5 bg-gradient-to-r from-white/5 to-[#00aaff]" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#0d1527]/60 backdrop-blur-sm border border-[#00aaff]/60 flex items-center justify-center text-2xl mb-2 shadow-[0_0_15px_rgba(0,170,255,0.15)] hover:border-[#00aaff] hover:shadow-[0_0_20px_rgba(0,170,255,0.3)] hover:-translate-y-[2px] transition-all duration-300"><carbon-report/></div>
    <span class="text-xs font-bold text-[#00aaff]">4. Reporte y Acción</span>
  </div>
</div>

<div class="mt-16 text-gray-400 text-sm max-w-2xl mx-auto text-center" v-click>
  Un proceso integrado que transforma el recorrido diario de un vehículo municipal en <strong>reportes técnicos formales y mapas de priorización social</strong>, listos para la planificación y ejecución inmediata de obras de bacheo.
</div>

---
layout: default
---

# ¿Por qué elegir el Sistema de Mapeo Dinámico del Estado Vial ?

<div class="grid grid-cols-2 gap-6 mt-5">
  <div class="pics-card" v-click>
    <h3 class="text-[#00aaff] text-lg font-bold mb-1.5 flex items-center gap-2">
      <carbon-report class="text-xl"/> Automatización de Reportes
    </h3>
    <p class="text-gray-400 text-xs">El asistente de IA redacta informes técnicos de obras de bacheo en minutos, reduciendo drásticamente la carga de trabajo y el tiempo administrativo de la oficina.</p>
  </div>
  <div class="pics-card" v-click>
    <h3 class="text-[#00aaff] text-lg font-bold mb-1.5 flex items-center gap-2">
      <carbon-wallet class="text-xl"/> Costos Reducidos
    </h3>
    <p class="text-gray-400 text-xs">No requiere vehículos equipados ni hardware costoso. Utiliza smartphones estándar montados en la flota municipal existente (recolectores, patrullas).</p>
  </div>
  <div class="pics-card" v-click>
    <h3 class="text-[#00aaff] text-lg font-bold mb-1.5 flex items-center gap-2">
      <carbon-map class="text-xl"/> Priorización Social
    </h3>
    <p class="text-gray-400 text-xs">Cruce automático con OpenStreetMap para priorizar reparaciones a menos de 50m de escuelas y hospitales, optimizando la asignación con criterio de rentabilidad social.</p>
  </div>
  <div class="pics-card" v-click>
    <h3 class="text-[#00aaff] text-lg font-bold mb-1.5 flex items-center gap-2">
      <carbon-analytics class="text-xl"/> Transparencia de Gestión
    </h3>
    <p class="text-gray-400 text-xs">Evidencia objetiva georreferenciada con registro fotográfico e histórico. Permite auditar y rendir cuentas de las obras públicas de forma abierta al ciudadano.</p>
  </div>
</div>

---
layout: center
class: text-center
---

<h1 class="text-5xl font-black mb-4">Proyecto Integrador de Ciencias de Datos - 11285<br><span class="text-[#00aaff]">Universidad Nacional de Luján</span></h1>

<div class="mt-8">
  <div class="text-xl mb-4">¿Preguntas?</div>
  <p class="text-gray-500 text-sm">Kelechian, Leonardo</p>
  <p class="text-gray-500 text-sm">Coyra, Federico</p>
</div>

<div class="mt-12 text-[#00aaff] text-4xl animate-bounce">
  <carbon-arrow-down/>
</div>