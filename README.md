# GO--Net

Projekt w języku **Go** dotyczący pakietu `net`.

## Tematy projektu

### 1. Przekrojowe przedstawienie pakietu `net`
Pokazanie możliwości pakietu oraz jego najważniejszych funkcji.

**Zakres:**
- połączenia TCP/UDP,
- obsługa adresów IP,
- klient i serwer sieciowy,
- podstawowa komunikacja sieciowa.

---

### 2. Terminalowy chat TCP
Prosty komunikator działający w terminalu z wykorzystaniem TCP.

**Zakres:**
- serwer czatu,
- obsługa wielu klientów,
- wysyłanie i odbieranie wiadomości,
- komunikacja w czasie rzeczywistym.

---

### 3. Skaner portów
Narzędzie do skanowania portów dla wskazanego adresu IP.

**Zakres:**
- podawanie adresu IP i zakresu portów,
- wykrywanie otwartych portów,
- równoległe skanowanie portów,
- prezentacja wyników w terminalu.

---

### 4. Serwer HTTP
Podstawowy serwer HTTP napisany w Go.

**Zakres:**
- tworzenie endpointów,
- obsługa requestów HTTP,
- logowanie zapytań,
- zwracanie odpowiedzi JSON lub HTML.

---

### 5. DNS Lookup Tool
Narzędzie do pobierania informacji DNS.

**Zakres:**
- pobieranie adresu IP domeny,
- reverse DNS lookup,
- rekordy MX,
- podstawowa analiza DNS.

---

### 6. Multiplayer – Kółko i Krzyżyk
Gra dla dwóch graczy komunikujących się przez TCP.

**Zakres:**
- serwer gry,
- synchronizacja planszy,
- obsługa tur graczy,
- komunikacja klient–serwer.

---

### 7. Ogólne omówienie i pokazanie użycia (małe przykłady wielu rzeczy):
- "the basic interface provided by the [Dial](https://pkg.go.dev/net#Dial), [Listen](https://pkg.go.dev/net#Listen), and Accept functions and the associated [Conn](https://pkg.go.dev/net#Conn) and [Listener](https://pkg.go.dev/net#Listener) interfaces" - [pkg.go.dev/net](https://pkg.go.dev/net)
- connecting applications via TCP and/or UDP
- build a small http server (+ Network Polling - simulate a lot of of concurrent connections?)
- domain name resolution
- unix sockets?
