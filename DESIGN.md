---
name: Diegocom.dev
description: Profilo personale e lavori AppSec
colors:
  paper: "#f7f6f2"
  ink: "#151c2b"
  white: "#faf9f6"
  text-on-paper: "#4d5563"
  text-on-ink: "#c5cddd"
  rule-on-paper: "#cbd0d8"
  rule-on-ink: "#3e4960"
  action: "#c3d5ff"
  selected-record: "#e9eef7"
typography:
  display:
    fontFamily: "Manrope, system-ui, sans-serif"
    fontSize: "clamp(3.5rem, 7.6vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.98
    letterSpacing: "-.04em"
  body:
    fontFamily: "Manrope, system-ui, sans-serif"
    fontWeight: 400
    lineHeight: 1.65
rounded:
  action: "2px"
spacing:
  page-gutter: "clamp(1.25rem, 4vw, 3rem)"
  page-width: "75rem"
components:
  email-action:
    backgroundColor: "{colors.action}"
    textColor: "{colors.ink}"
    rounded: "{rounded.action}"
    padding: "0.625rem 0.875rem"
    height: "2.75rem"
---

## Overview

La homepage riprende l’apertura della prima bozza. Il nome in grande introduce il ruolo, una descrizione del lavoro e i contatti. L’esperienza AppSec segue in una sola sezione, con i casi leggibili direttamente. Ricerca, progetti e AI per le PMI completano il profilo.

## Colors

L’apertura e i contatti usano un fondo blu inchiostro. Il resto della pagina usa un fondo carta. L’azzurro distingue il link email e il punto nel nome. Una tinta chiara aiuta a individuare il caso aperto tramite un collegamento diretto.

## Typography

Manrope è il carattere della pagina, incluso nel repo. Scala e peso distinguono il nome, le intestazioni e i contenuti. I settori e le date usano dimensioni più discrete.

## Layout

Su desktop il testo è a sinistra e il disegno a destra. Fino a 52 rem l’apertura mostra solo il testo. Fino a 40 rem le righe di esperienza si impilano in una sola colonna. Ogni caso ha titolo, settore e contributo nello stesso blocco.

## Elevation & Depth

Superfici piatte, spaziatura e filetti separano i contenuti.

## Components

- Il monogramma e il disegno di traiettorie riprendono gli asset della prima bozza nella palette attuale. La didascalia spiega l’incrocio tra sicurezza applicativa e AI.
- I casi AppSec sono visibili nella sezione Esperienza AppSec e hanno ancore individuali. Certificazioni e contatto seguono i casi.
- FUT Scoreboard è presentato come progetto condiviso con il contributo di Diego al passato.
- I link nativi usano etichette visibili e focus distinguibile.
