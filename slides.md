---
theme: default
background: ./assets/portada.png
class: text-center
highlighter: shiki
lineNumbers: false
info: Presentación Ejecutiva PICS
drawings:
  persist: false
transition: slide-up
title: PICS - Sistema de Mapeo Dinámico Vial
mdc: true
---

# PICS
## Sistema de Mapeo Dinámico del Estado Vial

<div class="mt-10 text-xl text-gray-300">
  Transformando la infraestructura urbana con <span class="text-[#00aaff] font-bold">Inteligencia Artificial</span>
</div>

<div class="absolute bottom-10 left-0 right-0 text-sm text-gray-500 bg-black/50 py-2 backdrop-blur-sm">
  Municipio de Moreno | Presentación Ejecutiva
</div>

<style>
h1 {
  background-color: #00aaff;
  background-image: linear-gradient(45deg, #00aaff 10%, #0055aa 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  font-size: 5rem;
  font-weight: 900;
  text-shadow: 0px 4px 20px rgba(0,0,0,0.8);
}
h2 {
  text-shadow: 0px 2px 10px rgba(0,0,0,0.8);
}
</style>

---
layout: default
class: bg-black text-white
---

# El desafío actual en la gestión pública

El mantenimiento de la red vial enfrenta limitaciones históricas que cuestan tiempo y recursos.

<div class="grid grid-cols-2 gap-8 mt-10">
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-time class="inline-block mr-2"/> Relevamientos Lentos</h3>
    <p class="text-gray-400 text-sm">Las inspecciones manuales son costosas, requieren mucho personal y tardan meses en cubrir todo el municipio.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-warning-alt class="inline-block mr-2"/> Subjetividad</h3>
    <p class="text-gray-400 text-sm">La catalogación del daño depende del criterio del inspector. No hay métricas estandarizadas.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-map class="inline-block mr-2"/> Falta de Datos Georreferenciados</h3>
    <p class="text-gray-400 text-sm">La toma de decisiones presupuestarias se hace "a ciegas", sin un mapa actualizado en tiempo real.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl mb-2"><carbon-network-4 class="inline-block mr-2"/> Desconexión</h3>
    <p class="text-gray-400 text-sm">Falta de herramientas integradas que conecten la calle directamente con el escritorio del Secretario de Obras Públicas.</p>
  </div>
</div>

---
layout: default
class: bg-[#050505] text-white
---

# La solución: 
# ¿Qué es el sistema de mapeo dinámico del estado vial?

<div class="mb-8 text-gray-300">
  Una plataforma integral que automatiza el relevamiento de calles utilizando cámaras de smartphones en vehículos municipales, procesando todo con IA en la nube.
</div>

<div class="grid grid-cols-3 gap-6 text-center mt-12">
  <div class="p-6 border border-[#222] rounded-xl bg-gradient-to-b from-[#111] to-black shadow-[0_0_15px_rgba(0,170,255,0.1)]" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-video/></div>
    <h3 class="font-bold mb-2">Captura Móvil</h3>
    <p class="text-xs text-gray-400">App web que graba video y GPS desde cualquier vehículo, preparada para zonas sin señal.</p>
  </div>
  
  <div class="p-6 border border-[#222] rounded-xl bg-gradient-to-b from-[#111] to-black shadow-[0_0_15px_rgba(0,170,255,0.1)]" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-machine-learning-model/></div>
    <h3 class="font-bold mb-2">Análisis IA</h3>
    <p class="text-xs text-gray-400">Detecta baches y grietas automáticamente. Unifica daños cercanos para evitar alertas duplicadas.</p>
  </div>

  <div class="p-6 border border-[#222] rounded-xl bg-gradient-to-b from-[#111] to-black shadow-[0_0_15px_rgba(0,170,255,0.1)]" v-click>
    <div class="text-[#00aaff] text-4xl mb-4"><carbon-dashboard/></div>
    <h3 class="font-bold mb-2">Gestión y Reportes</h3>
    <p class="text-xs text-gray-400">Dashboard interactivo con mapas y reportes generados por un asistente virtual inteligente.</p>
  </div>
</div>

---
layout: image-right
image: https://images.unsplash.com/photo-1517404215738-15263e9f9178?q=80&w=2070&auto=format&fit=crop
class: bg-black text-white
---

# PozoCam: Los ojos del Sistema

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
    Sincronización de GPS para ubicar exactamente en qué metro cuadrado está el bache.
  </li>
</ul>

---
layout: default
class: bg-[#050505] text-white
---

# Inteligencia Artificial de Frontera

No solo vemos la calle, **la entendemos**. Nuestro motor de visión computacional garantiza precisión y seguridad ciudadana.

<div class="grid grid-cols-2 gap-8 mt-8">
  <div>
    <h3 class="text-xl font-bold mb-4 border-b border-[#333] pb-2 text-white">Detección Precisa</h3>
    <ul class="space-y-3 text-sm text-gray-400">
      <li v-click><span class="text-[#00aaff] font-bold">Tres categorías clave:</span> Baches, Grietas y Calles de Tierra.</li>
      <li v-click><span class="text-[#00aaff] font-bold">Cero Duplicados:</span> La IA sabe si un auto pasó dos veces por el mismo pozo. Actualiza la foto con la mejor calidad en vez de duplicar alertas.</li>
      <li v-click><span class="text-[#00aaff] font-bold">Filtro Inteligente:</span> Ignora automáticamente el cielo, árboles o aves para concentrarse solo en la calzada.</li>
    </ul>
  </div>
  
  <div v-click>
    <div class="bg-[#111] p-6 rounded-xl border border-[#00aaff] shadow-[0_0_20px_rgba(0,170,255,0.2)]">
      <div class="text-3xl mb-2"><carbon-security class="text-[#00aaff]"/></div>
      <h3 class="text-xl font-bold text-white mb-2">Privacidad por Diseño</h3>
      <p class="text-sm text-gray-400">
        Cumplimos con las normativas de protección de datos. Antes de que cualquier imagen llegue al servidor municipal, una segunda IA <strong>difumina automáticamente rostros de peatones y patentes de vehículos</strong>.
      </p>
    </div>
  </div>
</div>

---
layout: default
class: bg-black text-white
---

# Dashboard Municipal y Asistente Virtual

Pasamos de tener un "mapa lleno de puntos" a tener un **mapa de decisión estratégica**.

<div class="grid grid-cols-2 gap-8 mt-6">
  <ul class="space-y-4 text-sm text-gray-300">
    <li v-click>
      <strong class="text-[#00aaff] text-base block mb-1">Mapa Interactivo</strong>
      Visualice todo el municipio y seleccione cualquier calle para inspeccionar la calzada.
    </li>
    <li v-click>
      <strong class="text-[#00aaff] text-base block mb-1">Auditoría Human-in-the-Loop</strong>
      Los inspectores revisan las alertas generadas por la IA, descartando falsos positivos. Sirviendo estas para reentrenar el modelo para que no vuelva a equivocarse.
    </li>
    <li v-click>
      <strong class="text-[#00aaff] text-base block mb-1">Reportes Ejecutivos por IA</strong>
      Un modelo de lenguaje privado redacta informes técnicos formales listos para licitaciones u órdenes de trabajo, priorizando obras cerca de escuelas u hospitales.
    </li>
  </ul>

  <div class="flex items-center justify-center" v-click>
    <img src="./assets/inspeccion_d40.png" alt="Panel de Inspección y Auditoría" class="rounded-xl border border-[#222] shadow-[0_0_20px_rgba(0,170,255,0.2)] max-h-80 object-contain" />
  </div>
</div>

---
layout: default
class: bg-[#050505] text-white
---

# Centro de Control Inteligente
<div class="text-gray-400 text-sm mb-4">Visión consolidada del estado de la infraestructura vial del Municipio de Moreno.</div>

<div class="w-full flex justify-center items-center h-[75%]">
  <img src="./assets/dashboard_general.jpg" alt="Dashboard PICS Moreno" class="rounded-xl border-2 border-[#00aaff] shadow-[0_0_30px_rgba(0,170,255,0.4)] max-h-full object-contain" />
</div>

---
layout: center
class: bg-black text-white text-center
---

# Ciclo de valor

<div class="flex justify-center items-center mt-10 gap-4">
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#111] border-2 border-[#00aaff] flex items-center justify-center text-2xl mb-2 shadow-[0_0_15px_rgba(0,170,255,0.4)]"><carbon-car/></div>
    <span class="text-xs font-bold text-gray-300">1. Captura Móvil</span>
  </div>
  <div class="w-12 h-1 bg-gradient-to-r from-[#00aaff] to-[#333]" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#111] border-2 border-[#333] flex items-center justify-center text-2xl mb-2"><carbon-cloud-upload/></div>
    <span class="text-xs font-bold text-gray-300">2. Subida Segura</span>
  </div>
  <div class="w-12 h-1 bg-gradient-to-r from-[#333] to-[#333]" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#111] border-2 border-[#333] flex items-center justify-center text-2xl mb-2"><carbon-settings/></div>
    <span class="text-xs font-bold text-gray-300">3. Análisis y Privacidad</span>
  </div>
  <div class="w-12 h-1 bg-gradient-to-r from-[#333] to-[#00aaff]" v-click></div>
  <div class="flex flex-col items-center" v-click>
    <div class="w-16 h-16 rounded-full bg-[#111] border-2 border-[#00aaff] flex items-center justify-center text-2xl mb-2 shadow-[0_0_15px_rgba(0,170,255,0.4)]"><carbon-report/></div>
    <span class="text-xs font-bold text-gray-300">4. Reporte y Acción</span>
  </div>
</div>

<div class="mt-16 text-gray-400 text-sm max-w-2xl mx-auto" v-click>
  Un proceso totalmente desatendido. El inspector graba, el sistema procesa, consolida, prioriza y entrega soluciones listas para la toma de decisiones.
</div>

---
layout: default
class: bg-[#050505] text-white
---

# ¿Por qué elegir el Sistema de mapeo dinámico del estado vial ?

<div class="grid grid-cols-2 gap-8 mt-12">
  <div v-click>
    <h3 class="text-[#00aaff] text-xl font-bold mb-2">Escalabilidad Cloud</h3>
    <p class="text-gray-400 text-sm">Arquitectura desplegada en Google Cloud. Auto-escalable: Si no hay videos subiéndose, los servidores de IA se apagan para ahorrar presupuesto municipal.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl font-bold mb-2">Costos Reducidos</h3>
    <p class="text-gray-400 text-sm">No requiere hardware especializado (Hardware o vehículos costosos). Utiliza la flota actual del municipio y cámaras celulares.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl font-bold mb-2">Mejora Continua</h3>
    <p class="text-gray-400 text-sm">El sistema no queda obsoleto. Con cada auditoría, la IA se podrá reentrenar automáticamente para mejorar.</p>
  </div>
  <div v-click>
    <h3 class="text-[#00aaff] text-xl font-bold mb-2">Transparencia de Gestión</h3>
    <p class="text-gray-400 text-sm">Datos objetivos y respaldados con fotografías y GPS para justificar presupuestos de obras públicas frente a los ciudadanos.</p>
  </div>
</div>

---
layout: center
class: bg-black text-white text-center
---

<h1 class="text-5xl font-black mb-4">Proyecto Integrador de Ciencias de Datos - 11285<br><span class="text-[#00aaff]">Universidad Nacional de Luján.</span></h1>

<div class="mt-8">
  <div class="text-xl mb-4">¿Preguntas?</div>
  <p class="text-gray-500 text-sm">Kelechian, Leonardo</p>
  <p class="text-gray-500 text-sm">Coyra, Federico</p>
</div>

<div class="mt-12 text-[#00aaff] text-4xl animate-bounce">
  <carbon-arrow-down/>
</div>