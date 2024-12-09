# Proba-IT-2024-Template

### Acest template public poate fi folosit pentru a vă crea repository-ul pentru proba tehnică. El permite și crearea automată de issue-uri, în concordanță cu task-urile probei:
* Homepage
* Profile
* Register & Login
* Add Recipes Page
* Recipes Page & Search

### Pentru a crea un repo privat și pentru a rula workflow-ul pentru issue-uri, se vor urma pașii de mai jos:
* Repository privat:
    * În colțul din dreapta-sus, apasă pe butonul „Use this template”, apoi pe cel de „Create a new repository” pentru a crea un repository în contul tău de GitHub.
* Adaugă token-ul tău de GitHub la Repository Secrets:
    * În repo-ul tău, mergi la secțiunea de „Settings”.
    * Selectează „Secrets and variables” > „Actions” > „New repository secret”.
    * Creează un secret nou, cu numele „TOKEN”, și introdu token-ul de acces personal. Mai multe detalii [aici](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic).
* Rulează workflow-ul:
    * Mergi la secțiunea „Actions” din repository-ul tău.
    * Selectează „Initialise Repo” > „Run workflow”.
    * După ce workflow-ul va termina de rulat, la secțiunea de „Issues” vor apărea cele 5 issue-uri menționate mai sus.
Metoda de rulare:
Pentru a rula aplicația web, există câteva metode simple și eficiente care asigură o experiență fluidă utilizatorului. În primul rând, aplicația poate fi rulată direct ca un site static. Acest lucru implică descărcarea sau clonarea fișierelor sursă din repository și deschiderea fișierului principal homepage_nelogat.html într-un browser web modern.

În primul rând, utilizatorul trebuie să se asigure că are toate fișierele aplicației descărcate. Acestea includ fișierele HTML, CSS, JavaScript și imaginile utilizate în pagină. Pentru majoritatea utilizatorilor, aceasta este cea mai rapidă și intuitivă metodă de rulare a aplicației.
În cazul în care se dorește testarea aplicației într-un mediu care simulează un server web, există mai multe opțiuni disponibile.  Structura aplicației reflectă o organizare clară și intuitivă, cu elemente distribuite armonios pe pagină. Aceasta include un meniu de navigare în partea superioară, cu acces rapid la secțiunile "Recipes" și "Add Recipe". Sub meniu, utilizatorii pot găsi un câmp de căutare, însoțit de butoane pentru filtrare și sortare, poziționate sub bara de căutare pentru o accesibilitate optimă. În zona centrală a paginii sunt afișate carduri care prezintă rețete, fiecare incluzând detalii precum numele rețetei, numărul de rating-uri și autorul. Acest design asigură o interfață prietenoasă și ușor de utilizat.
Pentru o experiență optimă, este recomandată utilizarea unui browser modern, precum Google Chrome, Firefox, Edge sau Safari. În cazul în care utilizatorul întâmpină probleme legate de afișarea imaginilor sau stilurilor CSS, se recomandă verificarea structurii fișierelor pentru a confirma că toate resursele necesare sunt disponibile și în același director cu fișierul index.html.
În concluzie, rularea aplicației web dezvoltate este un proces intuitiv, fie că utilizatorul alege să o deschidă direct în browser, fie să o ruleze pe un server local. Structura clară a aplicației și distribuția elementelor sale facilitează navigarea și utilizarea, oferind o experiență plăcută atât pentru utilizatori, cât și pentru dezvoltatori
