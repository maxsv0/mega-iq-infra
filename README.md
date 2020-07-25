# Web Infrastructure of www.mega-iq.com

Key components of Mega-IQ web infrastructure are:
* Router instance that handles incoming traffic
* Instances running local UI (for every locale)
* Database instance
* Mega-IQ API
 
All incoming traffic is handled by a router instance.

Based on the domain name requests would be sent to a different instance. A list of supported URL's is below.

| URL| Locale | Proxy Destination |
| -----|:------:| ----|
| [www.mega-iq.com](https://www.mega-iq.com) | EN | Front-End instance ```iq-ui-en``` |
| [es.mega-iq.com](https://es.mega-iq.com) | ES | Front-End instance ```iq-ui-es``` |
| [de.mega-iq.com](https://de.mega-iq.com) | DE | Front-End instance ```iq-ui-de``` |
| [ru.mega-iq.com](https://ru.mega-iq.com) | RU | Front-End instance ```iq-ui-ru``` |
| [www.mega-iq.com/api/v1](https://www.mega-iq.com/api/v1) | EN | Public API |
| [es.mega-iq.com/api/v1](https://es.mega-iq.com/api/v1) | ES | Public API |
| [de.mega-iq.com/api/v1](https://de.mega-iq.com/api/v1) | DE | Public API |
| [ru.mega-iq.com/api/v1](https://ru.mega-iq.com/api/v1) | RU | Public API |
| [img.mega-iq.com](https://img.mega-iq.com) | all | storage.googleapis.com |

HTTP traffic is redirected to HTTPS
