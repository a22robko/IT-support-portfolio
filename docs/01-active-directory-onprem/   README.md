
# 01 – Active Directory (On-prem)

**Vad detta visar för en IT-supportroll**
- Skapa/användarhantering i ADUC (1st line vardag).
- Reset/Unlock av konton.
- Gruppmedlemskap och rättigheter.
- Verifiering på klient (`whoami`, `ipconfig`, `ping`).

**Lab-miljö**
- Windows Server 2019/2022 (AD DS, DNS, DHCP) – statisk IP `172.16.0.1`
- Klient: Windows 10/11, joinad till domänen `mydomain.com`

## Innehåll
- [Skapa användare (ADUC)](01-create-user-aduc.md)
- [Återställ lösenord (Reset Password)](02-reset-password-aduc.md)
- [Lås upp konto (Unlock Account)](03-unlock-account-aduc.md)
- [Lägg till i grupp (Member Of)](04-add-to-group-aduc.md)
- [Verifiering på klient (whoami, ipconfig, ping)](05-verify-client-domain.md)

## Resultat (kort)
- Ny användare kan logga in på domänklient.
- Reset/Unlock återställer åtkomst enligt best practice.
- Nätverks- och domänkommunikation bekräftad.
