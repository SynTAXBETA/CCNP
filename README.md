Markup :  # Heading 1 #

IP Routing este procesul de forwardare al pachetelor. Pachetul este primit de router, este decapsulat, inspectat, decis ce se face cu el, incapsulat si apoi trimis pe interfata potrivita sau dupa caz la next-hopul potrivit
IP Routing == trimite pachete de la Sursa la Destinatie

Pasul 1: Pachetul este creat de catre end-host.
Pasul 2: End-hostul decide daca IP-ul destinatie este in aceasi retea (LAN) cu el insusi in functie de IP/Subnet mask
Pasul 3: Daca este local, trimite direct:
Pasul 3.1 Gaseste mac-ul destinatie in functie de tabela ARP pe care o are deja sau trimite un ARP request
Pasul 3.2: Incapsuleaza pachetul intr-un data-link frame, cu destinatia L2 luata din tabela ARP
Pasul 4: Daca nu este local, trimite la default gateway:
Pasul 4.1: Gaseste adresa MAC a default gateway in tabela ARP pe care o are deja sau trimite un ARP request. 
Pasul 4.2: Incapsuleaza pachetul intr-un data-link frame, cu destinatia L2 luata din tabela ARP

* TEST
* TEST2
  * SUB ITEM

# Large text

## Second large

### Third large

