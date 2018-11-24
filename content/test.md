---
title: "Hem"

views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa

    byline:
        region: after-main
        template: anax/v2/block/default
        sort: 3
        data:
            meta:
                type: single
                route: block/byline

---
Testsida
=========================



Detta innehåll är skrivet i markdown och du hittar innehållet i filen `content/test.md`.


Lekstuga med tre kolumner.
