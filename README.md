# skuf-rules

Personal routing rules for client-side split routing.

## Policy

DIRECT:
- Russian critical services
- public services
- banks
- payments
- marketplaces
- operators
- Yandex
- VK / Mail.ru / OK

PROXY:
- everything else

## FoXray Rule Set

Use:

    name: skuf-direct-ru
    type: domain
    url: https://raw.githubusercontent.com/baudbreach/skuf-rules/main/dist/skuf-direct-ru.dat

## Source list

The source domain list is stored here:

    source/skuf-direct-ru
