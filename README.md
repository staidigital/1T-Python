# Oppsummering: Python-programmering for Matematikk 1T

I Matematikk 1T brukes Python til å utføre enkle matematiske operasjoner og løse problemer ved hjelp av programmering. Her er en oversikt over det viktigste du må kunne:

---

## 1. **Matteoperasjoner**
Python støtter alle grunnleggende matematiske operasjoner:

```python
# Grunnleggende operasjoner
a = 10
b = 3
print(a + b)  # Addisjon
print(a - b)  # Subtraksjon
print(a * b)  # Multiplikasjon
print(a / b)  # Divisjon
print(a // b) # Heltallsdivisjon
print(a % b)  # Modulo (rest etter divisjon)
print(a ** b) # Potens
```

---

## 2. **Variabler**
Variabler brukes til å lagre verdier:

```python
# Definere variabler
x = 5
y = 2
z = x + y
print(z)  # Skriver ut 7
```

---

## 3. **Input fra bruker**
For å hente data fra brukeren bruker vi `input()`:

```python
# Input og konvertering til tall
tall = int(input("Skriv inn et tall: "))
print("Du skrev:", tall)
```

---

## 4. **Utskrift med `print()`**
Bruk `print()` for å vise informasjon til brukeren:

```python
# Utskrift av tekst og variabler
navn = "Ola"
print("Hei,", navn)
```

---

## 5. **If-setninger**
For å lage valg i programmet brukes `if`, `elif` og `else`:

```python
# If-eksempel
tall = int(input("Skriv inn et tall: "))
if tall > 0:
    print("Tallet er positivt")
elif tall == 0:
    print("Tallet er null")
else:
    print("Tallet er negativt")
```

---

## 6. **For-løkker**
`for`-løkker brukes til å gjenta kode et bestemt antall ganger:

```python
# For-løkke eksempel
for i in range(1, 6):
    print("Tallet er:", i)  # Skriver ut tall fra 1 til 5
```

---

## 7. **While-løkker**
`while`-løkker brukes til å gjenta kode så lenge en betingelse er sann:

```python
# While-løkke eksempel
teller = 1
while teller <= 5:
    print("Teller er:", teller)
    teller += 1  # Øker teller med 1
```

---

## 8. **Funksjoner**
Funksjoner brukes til å gjenbruke kode. De kan returnere verdier ved hjelp av `return`:

```python
# Funksjonsdefinisjon og bruk
def areal_rektangel(lengde, bredde):
    return lengde * bredde

# Kaller funksjonen
areal = areal_rektangel(5, 3)
print("Arealet er:", areal)
```

---

Med disse grunnleggende ferdighetene kan du løse mange oppgaver i Matematikk 1T ved hjelp av Python. Øv deg på å bruke de ulike delene i praktiske programmer!
