---
date: '2023-08-25T09:53:42+02:00' # date in which the content is created - defaults to "today"
title: 'Line Segment Tracking'
draft: false # set to "true" if you want to hide the content

link: "https://github.com/cms-sw/cmssw/tree/master/RecoTracker/LSTCore/standalone" # optional URL to link the logo to

params:
    button:
        icon: "square-github"
        btnText: "Repositorio de GitHub"
        URL: "https://github.com/cms-sw/cmssw/tree/master/RecoTracker/LSTCore/standalone"
    image:
        src: "images/projects/lst.png"
        scale: 0.5


## The content is used for the description of the project
---

El algoritmo Line Segment Tracking (LST) es una propuesta novedosa para la reconstrucción de trayectorias de partículas. Aprovecha la arquitectura masivamente paralela de las GPUs para reconstruir de manera eficiente las trayectorias en condiciones de alta superposición de eventos (pile-up). Este algoritmo surgió ante el aumento esperado en la complejidad de la reconstrucción en futuros experimentos con colisionadores, así como las posibles limitaciones de los recursos computacionales basados en CPU.
