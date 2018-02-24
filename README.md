[![Build Status](https://travis-ci.org/edigonzales/ccc-web-service.svg?branch=master)](https://travis-ci.org/edigonzales/ccc-web-service)

# ccc-web-service - a prototype

Spielwiese für CCC-Server mit Spring Boot und STOMP.

## TODO

* CccMessage-Modell: Was gehört rein, was nicht?
* Logik für Client unsubscribe/disconnect Event.
* Der Client-Typ wird überhaupt nicht geprüft, dh. die ready-Meldung geht raus wenn zwei unterschiedliche Typen sich angemeldet haben. Das muss aber nicht "app" und "gis" sein, sondern irgend etwas.
* Tests (siehe Ursprungsbeispiel)