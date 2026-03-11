+++
date = '2026-03-09T23:01:30+01:00'
draft = false
title = 'Contact'
h1 = 'Contact'
description = "Les propositions de l'association Origami en QRGA, Caylus et Saint Antonin"
layout = 'nu'
+++

{{/* layouts/contact/contact.html ou shortcode contact_page.html */}}

<!-- ═══════════════════════════════════════════════════
     SECTION HERO — "Tu n'es pas seul"
═══════════════════════════════════════════════════ -->
<section class="relative overflow-hidden min-h-[80vh] flex items-center bg-mycolor-950">

  <!-- Texture de fond subtile -->
  <div class="absolute inset-0 opacity-10"
       style="background-image: radial-gradient(circle at 20% 50%, var(--mycolor-400) 0%, transparent 50%), radial-gradient(circle at 80% 20%, var(--mycolor-300) 0%, transparent 40%);">
  </div>

  <!-- Grille décorative -->
  <div class="absolute inset-0 opacity-5"
       style="background-image: linear-gradient(var(--mycolor-400) 1px, transparent 1px), linear-gradient(90deg, var(--mycolor-400) 1px, transparent 1px); background-size: 48px 48px;">
  </div>

  <div class="relative z-10 max-w-4xl mx-auto px-6 py-20 text-center">

    <!-- Accroche principale -->
    <p class="text-mycolor-300 uppercase tracking-[0.3em] text-sm font-medium mb-6"
       data-aos="fade-down" data-aos-duration="600">
      Atelier & entraide
    </p>

    <h1 class="text-4xl sm:text-5xl xl:text-6xl font-bold text-white leading-tight mb-8"
        data-aos="fade-up" data-aos-duration="700" data-aos-delay="100">
      Ton projet bloqué ?<br>
      <span class="text-mycolor-300">Tu n'es pas seul.</span>
    </h1>

    <p class="text-lg sm:text-xl text-mycolor-100/80 max-w-2xl mx-auto leading-relaxed mb-10"
       data-aos="fade-up" data-aos-duration="700" data-aos-delay="200">
      Électronique, programmation, Arduino, Raspberry Pi, machine à inventer, appareil à réparer…
      Quelle que soit l'étape où tu es coincé, on peut réfléchir ensemble et trouver une piste.
    </p>

    <a href="#contact-form"
       class="inline-block bg-mycolor-400 hover:bg-mycolor-300 text-myblack font-semibold px-8 py-4 rounded-full transition-all duration-300 hover:scale-105 hover:shadow-lg"
       data-aos="zoom-in" data-aos-delay="350">
      Parler de mon projet →
    </a>

  </div>
</section>


<!-- ═══════════════════════════════════════════════════
     SECTION — Ce qu'on peut faire ensemble
═══════════════════════════════════════════════════ -->
<section class="bg-white py-16 px-6">
  <div class="max-w-5xl mx-auto">

    <h2 class="text-2xl sm:text-3xl font-bold text-myblack text-center mb-4"
        data-aos="fade-up">
      Ce qu'on peut faire ensemble
    </h2>
    <p class="text-center text-gray-500 mb-12 max-w-xl mx-auto"
       data-aos="fade-up" data-aos-delay="100">
      Pas de jugement sur le niveau. L'idée, c'est d'avancer — à deux ou à plusieurs.
    </p>

    <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6">

      <!-- Carte 1 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="0">
        <div class="text-3xl mb-4">⚡</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Électronique & circuits</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Schémas, soudure, composants introuvables, bugs mystérieux sur ta carte…
          On décortique ça ensemble.
        </p>
      </div>

      <!-- Carte 2 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="80">
        <div class="text-3xl mb-4">💻</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Code & programmation</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Arduino, Python, scripts, automatisations… Si ton code ne fait pas ce que tu veux,
          on cherche pourquoi.
        </p>
      </div>

      <!-- Carte 3 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="160">
        <div class="text-3xl mb-4">🔧</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Réparer plutôt que jeter</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Donner une seconde vie à un appareil, c'est souvent possible.
          Et c'est toujours plus satisfaisant qu'un remplacement.
        </p>
      </div>

      <!-- Carte 4 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="0">
        <div class="text-3xl mb-4">🤖</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Inventer une machine</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Tu as une idée en tête mais tu ne sais pas par où commencer ?
          On transforme l'idée en plan d'action concret.
        </p>
      </div>

      <!-- Carte 5 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="80">
        <div class="text-3xl mb-4">🍓</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Raspberry Pi & SBC</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Domotique, médiacentre, serveur maison, caméra de surveillance… 
          On configure et on dépanne.
        </p>
      </div>

      <!-- Carte 6 -->
      <div class="border border-mycolor-200 rounded-2xl p-6 hover:shadow-md hover:-translate-y-1 transition-all duration-300"
           data-aos="fade-up" data-aos-delay="160">
        <div class="text-3xl mb-4">🌱</div>
        <h3 class="font-bold text-myblack text-lg mb-2">Projets utiles & altruistes</h3>
        <p class="text-gray-600 text-sm leading-relaxed">
          Une idée qui peut servir à d'autres, à la communauté, à la planète ?
          C'est exactement le genre de projet qu'on aime accompagner.
        </p>
      </div>

    </div>
  </div>
</section>


<!-- ═══════════════════════════════════════════════════
     BANDEAU CITATION — L'esprit du lieu
═══════════════════════════════════════════════════ -->
<section class="bg-mycolor-100 py-14 px-6 text-center"
         data-aos="fade-in">
  <blockquote class="max-w-3xl mx-auto">
    <p class="text-xl sm:text-2xl font-medium text-myblack italic leading-relaxed mb-4">
      « La technique, ça s'apprend mieux à deux. Et une bonne question posée au bon moment,
      ça vaut des heures de galère en solo. »
    </p>
    <cite class="text-mycolor-500 text-sm not-italic">— L'état d'esprit de l'atelier</cite>
  </blockquote>
</section>


<!-- ═══════════════════════════════════════════════════
     SECTION FORMULAIRE DE CONTACT
═══════════════════════════════════════════════════ -->
<section id="contact-form" class="bg-white py-16 px-6">
  <div class="max-w-2xl mx-auto">

    <h2 class="text-2xl sm:text-3xl font-bold text-myblack text-center mb-3"
        data-aos="fade-up">
      Raconte-moi ton projet
    </h2>
    <p class="text-center text-gray-500 mb-10"
       data-aos="fade-up" data-aos-delay="100">
      Pas besoin d'avoir tout ficelé. Un brouillon d'idée suffit pour commencer.
    </p>

    <!-- Formulaire — adapter à ton backend / Netlify Forms / Formspree -->
    <form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field"
          action="/contact/merci"     
          class="space-y-6"
          data-aos="fade-up" data-aos-delay="150">
      <input type="hidden" name="form-name" value="contact">
<input name="bot-field" style="display:none">
      <div>
        <label class="block text-sm font-medium text-myblack mb-1" for="name">Ton prénom</label>
        <input id="name" name="name" type="text" required
               placeholder="Marie, Thomas…"
               class="w-full border border-mycolor-200 rounded-xl px-4 py-3 text-myblack placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-mycolor-300 transition">
      </div>

      <div>
        <label class="block text-sm font-medium text-myblack mb-1" for="email">Ton e-mail</label>
        <input id="email" name="email" type="email" required
               placeholder="pour qu'on puisse te répondre"
               class="w-full border border-mycolor-200 rounded-xl px-4 py-3 text-myblack placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-mycolor-300 transition">
      </div>

      <div>
        <label class="block text-sm font-medium text-myblack mb-1" for="type">Type de projet</label>
        <select id="type" name="type"
                class="w-full border border-mycolor-200 rounded-xl px-4 py-3 text-myblack focus:outline-none focus:ring-2 focus:ring-mycolor-300 transition bg-white">
          <option value="">— Choisis une catégorie —</option>
          <option value="electronique">Électronique / circuits</option>
          <option value="code">Code / programmation</option>
          <option value="arduino">Arduino / microcontrôleurs</option>
          <option value="raspberry">Raspberry Pi / Linux embarqué</option>
          <option value="reparation">Réparation</option>
          <option value="machine">Inventer une machine</option>
          <option value="autre">Autre / je ne sais pas encore</option>
        </select>
      </div>

      <div>
        <label class="block text-sm font-medium text-myblack mb-1" for="message">Décris ton projet ou ton problème</label>
        <textarea id="message" name="message" rows="5" required
                  placeholder="Où tu en es, ce qui bloque, ce que tu veux faire… Pas besoin que ce soit parfait."
                  class="w-full border border-mycolor-200 rounded-xl px-4 py-3 text-myblack placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-mycolor-300 transition resize-none"></textarea>
      </div>

      <div class="pt-2">
        <button type="submit"
                class="w-full bg-mycolor-400 hover:bg-mycolor-300 text-myblack font-semibold py-4 rounded-full transition-all duration-300 hover:scale-[1.02] hover:shadow-md">
          Envoyer mon message →
        </button>
      </div>

    </form>

  </div>
</section>


<!-- ═══════════════════════════════════════════════════
     SECTION RASSURANTE — Pas de pression
═══════════════════════════════════════════════════ -->
<section class="bg-mycolor-50 py-12 px-6"
         data-aos="fade-up">
  <div class="max-w-3xl mx-auto grid grid-cols-1 sm:grid-cols-3 gap-8 text-center">

    <div>
      <p class="text-3xl mb-3">🤝</p>
      <h3 class="font-bold text-myblack mb-1">Aucun jugement</h3>
      <p class="text-gray-500 text-sm">Peu importe ton niveau. On a tous débuté quelque part.</p>
    </div>

    <div>
      <p class="text-3xl mb-3">💬</p>
      <h3 class="font-bold text-myblack mb-1">Réponse humaine</h3>
      <p class="text-gray-500 text-sm">Pas de réponse automatique. On lit, on réfléchit, on répond vraiment.</p>
    </div>

    <div>
      <p class="text-3xl mb-3">🎯</p>
      <h3 class="font-bold text-myblack mb-1">Envie d'avancer</h3>
      <p class="text-gray-500 text-sm">L'objectif : que tu repars avec une piste concrète, pas juste des encouragements.</p>
    </div>

  </div>
</section>

{{< contact >}}