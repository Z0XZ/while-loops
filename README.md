# While-løkker i Python

## Forklaring

En `while`-løkke i Python utfører en handling så lenge en bestemt betingelse er sann. Når betingelsen blir usann, avsluttes løkken. Det er viktig å være forsiktig så man ikke skaper en uendelig løkke, hvor betingelsen alltid er sann.

## Eksempel

**Enkel While-løkke**:

```Python
teller = 0
while teller < 5:
    print(teller)
    teller += 1
print("Løkken er ferdig!")
```

Dette vil printe tallene 0 til 4.

## Oppgaver

Gjør oppgavene som står i .py-filene.

Til oppgave 3 trenger du litt tilleggsinformasjon:

Om man skal trekke tilfeldige tall i Python kan man gjøre dette ved å bruke random-biblioteket.
Da må man først importere biblioteket, og deretter kalle på en funksjon som heter randint slik:

```Python
import random

tilfeldig = random.randint(1,50) #Trekker et tilfeldig tall mellom 1 og 50 og lagrer det i variabelen.
```

Oppgave 4 kan du vente med til du er ferdig med oppgavene om conditionals, så blir det litt enklere å gjøre oppgaven.
