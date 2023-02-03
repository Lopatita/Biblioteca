# Structura unei biblioteci_Lopatita Iosif-Otniel_Examen Baze de date spatiale
![uml diagram](https://github.com/Lopatita/Biblioteca/blob/main/proiect%20biblioteca.drawio.png)

#enunt
Realizarea unei baze de date pentru administrarea unei biblioteci cu scopul de a stoca si administra carti, articole, edituri si autorii acestora, impreuna cu descrierea fizica si cuvantu cheie si locatia prin care se poate identifica o carte si un articol.

Entitati:
  - Carte:
          - ID_carte
          - Titlu
          - An
          - Cota
          - ID_editura
          - ID_descriere fizica
          - ID_locatie
   - Autor: 
          - ID_autor 
          - Nume 
          - Pseudonim
          - Observatii
          - ID_carte
          
   - Articol:
          - ID_articol
          - Titlu
          - Publicat in
          - ID_cuvant cheie
          - ID_autor
          
   - Editura:
          - ID_editura
          - Nume
          - Director general
          - Adresa web
          
   - Descriere fizica:
          - ID_descriere fizica
          - Numar de pagini
          - Dimensiuni
          - Foto
         
   - Locatie:
          - ID_locatie integer
          - Denumire
          - Adresa
          
   - Cuvant cheie:
          - ID_cuvant cheie
          - Cuvant
          - ID_carte
          
    ![uml diagram](https://github.com/Lopatita/Biblioteca/blob/main/Model%20conceptual.png)
