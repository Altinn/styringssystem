---
name: Generelle henvendelser til team Styringssystem
about: Meld inn saker du mener team Styringssystem skal behandle
title: ''
labels: ''
assignees: ''

---

Her kan du melde inn forslag til saker de mener team Styringssystem skal håndtere. Dersom det viser seg at vi ikke skal jobbe videre med denne saken vil vi videreformidle denne i samråd med kontaktperson for å finne rette team som skal være utførende.

For at vi skal kunne behandle denne saken er vi avhengig av at du legger inn en del informasjon i denne issuen:

### Beskrivelse
- Gi en beskrivelse av hva saken gjelder

_______________________________________________________________________________________________________________

## Kilde
_______________________________________________________________________________________________________________

## Kontaktperson
Oppgi navn på hvem vi kan kontakte
_______________________________________________________________________________________________________________

## Hvilke team/person kommer saken fra
_______________________________________________________________________________________________________________

## Ønske out-put på endringen
_______________________________________________________________________________________________________________

## Ønsket dato for utførsel av endringen
____________________

name: Bug Report
description: Opprett en bug-rapport.
title: "[Bug]: "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Takk for at du rapporterer en bug!
  - type: input
    id: contact
    attributes:
      label: Kontaktinformasjon
      description: Hvordan kan vi kontakte deg hvis vi trenger mer informasjon?
      placeholder: eks. email@example.com
  - type: textarea
    id: what-happened
    attributes:
      label: Hva skjedde?
      description: Beskriv hva som skjedde og hva du forventet skulle skje.
      placeholder: Fortell oss hva du ser!
      validations:
        required: true
  - type: date
    id: date
    attributes:
      label: Dato
      description: Velg datoen da problemet oppstod.
      validations:
        required: true
