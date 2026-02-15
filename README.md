# Formularz logowania – Tailwind CSS

Prosty formularz logowania stworzony w HTML z wykorzystaniem **Tailwind CSS (CDN)**. Projekt zawiera responsywny widok z podstawowymi polami: adres e-mail, hasło oraz linkami do odzyskiwania hasła i rejestracji.

---

## Opis projektu

Strona przedstawia minimalistyczny formularz logowania:

- Pole **Adres e-mail**
- Pole **Hasło**
- Link **„Zapomniałeś hasła?”**
- Przycisk **„Zaloguj się”**
- Link do **rejestracji**

Stylizacja została wykonana przy użyciu Tailwind CSS w wersji przeglądarkowej (CDN).

---

## Technologie

- HTML5
- Tailwind CSS (CDN: `@tailwindcss/browser@4`)

---

## Struktura projektu

Projekt składa się z jednego pliku:

```
formularz.html
```

Kod zawiera:

- Responsywny viewport
- Centralnie wyśrodkowany formularz (flexbox)
- Stylizowane pola formularza
- Prosty efekt hover
- Podstawową walidację HTML (`required`, `type="email"`)

---

## Uruchomienie projektu

1. Sklonuj repozytorium:

```bash
git clone https://github.com/Mikolaj65624/Formularz-logowania-tailwind.git
```

2. Otwórz plik `formularz.html` w przeglądarce.

Nie jest wymagana żadna instalacja zależności ani serwer.

---

## Uwagi

Obecnie formularz nie wysyła danych do serwera (`action="#"`).  
Aby dodać funkcjonalność logowania, należy podpiąć backend oraz odpowiednią obsługę formularza.
