# Register Form (Form)

Projekt formularza rejestracji z walidacją w HTML, CSS i Javascript.

## Opis

Formularz składa się z sześciu pól o różnych typach inputa. Wprowadzone zostały specjalne atrybuty HTML do walidacji poszczególnych pól, takie jak `required`, `minlength`, `maxlength`, `pattern`. W tym ostatnim przypadku zastosowanie znajdują `wyrażenia regularne RegExp`. W przypadku dwóch pól hasła są one porównywane przez skrypt pod kątem tego, czy wpisane hasła są takie same. Prawidłowe wysłanie formularza jest komunikowane użytkownikowi zmianą koloru obramowania inputów (z czerwonego na zielony) oraz komunikatem o sukcesie u dołu formularza.

Projekt używa nadto `Flexboxa`, `pseudoklas CSS`, a także `Google Font`.

## Zastosowanie i plany rozwoju

Uniwersalne zastosowanie, przy czym przed wdrożeniem do konkretnego projektu należy opracować `Media Queries`.

Preview dostępne [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/register-form/)
