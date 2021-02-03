# Web Infrastructure of [Mega-IQ Test IQ](https://www.mega-iq.com)

Key components of Mega-IQ web infrastructure are:
* Router instance that handles incoming traffic
* Instances running local UI (for every locale)
* Database instance
* Mega-IQ API
 
All incoming traffic is handled by a router instance.

Based on the domain name requests would be sent to a different instance. A list of supported URL's is below.

| URL| Locale | Proxy Destination |
| -----|:------:| ----|
| [Mega-IQ test IQ online](https://www.mega-iq.com) | EN | Front-End instance ```iq-ui-en``` |
| [Mega-IQ test coeficiente intelectual](https://es.mega-iq.com) | ES | Front-End instance ```iq-ui-es``` |
| [Mega-IQ test iq online](https://de.mega-iq.com) | DE | Front-End instance ```iq-ui-de``` |
| [Мега-IQ тест онлайн](https://ru.mega-iq.com) | RU | Front-End instance ```iq-ui-ru``` |
| [www.mega-iq.com/api/v1](https://www.mega-iq.com/api/v1) | EN | Public API |
| [es.mega-iq.com/api/v1](https://es.mega-iq.com/api/v1) | ES | Public API |
| [de.mega-iq.com/api/v1](https://de.mega-iq.com/api/v1) | DE | Public API |
| [ru.mega-iq.com/api/v1](https://ru.mega-iq.com/api/v1) | RU | Public API |

HTTP traffic is redirected to HTTPS
